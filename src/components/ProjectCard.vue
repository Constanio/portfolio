<template>
  <div class="group bg-gradient-to-br from-white to-slate-50 dark:from-slate-800 dark:to-slate-900 rounded-2xl shadow-lg overflow-hidden hover:shadow-2xl transition-all duration-300 border border-slate-200 dark:border-slate-700 hover:border-indigo-300 dark:hover:border-indigo-500 relative">
    <!-- Color accent based on category -->
    <div class="absolute top-0 left-0 w-2 h-full" :class="getCategoryColor(category)"></div>
    
    <!-- Project Header with Icon -->
    <div class="p-6 pb-4">
      <div class="flex items-start justify-between mb-4">
        <div class="w-12 h-12 rounded-lg bg-gradient-to-br from-indigo-50 to-purple-50 dark:from-indigo-900/30 dark:to-purple-900/30 flex items-center justify-center border border-indigo-100 dark:border-indigo-800/50">
          <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-600 to-purple-600 dark:from-indigo-400 dark:to-purple-400 text-lg font-bold">
            {{ getProjectInitials(title) }}
          </span>
        </div>
        <span class="px-3 py-1 bg-gradient-to-r from-slate-100 to-slate-50 dark:from-slate-700 dark:to-slate-800 text-slate-700 dark:text-slate-300 rounded-full text-xs font-medium border border-slate-300 dark:border-slate-600">
          {{ category }}
        </span>
      </div>

      <!-- Project Title -->
      <h3 class="text-xl font-bold text-slate-800 dark:text-white mb-3 group-hover:text-indigo-700 dark:group-hover:text-indigo-400 transition-colors">
        {{ title }}
      </h3>

      <!-- Project Description -->
      <p class="text-slate-700 dark:text-slate-300 mb-6 leading-relaxed">
        {{ description }}
      </p>
    </div>

    <!-- Technologies Tags -->
    <div class="px-6 pb-6">
      <div class="flex flex-wrap gap-2 mb-6">
        <span 
          v-for="(tech, index) in technologies" 
          :key="tech"
          class="px-3 py-1.5 bg-gradient-to-br from-slate-50 to-white dark:from-slate-700 dark:to-slate-800 text-slate-700 dark:text-slate-300 rounded-lg text-sm font-medium border border-slate-300 dark:border-slate-600 hover:bg-gradient-to-br hover:from-indigo-50 hover:to-purple-50 dark:hover:from-indigo-900/30 dark:hover:to-purple-900/30 hover:text-indigo-700 dark:hover:text-indigo-300 hover:border-indigo-300 dark:hover:border-indigo-500 transition-all duration-300 cursor-default"
          :style="{
            animationDelay: `${index * 100}ms`,
            animation: 'fadeInUp 0.6s ease-out forwards'
          }"
        >
          {{ tech }}
        </span>
      </div>

      <!-- Action Button -->
      <div class="flex items-center justify-between">
        <button 
          @click="handleViewProject"
          class="flex-1 py-3 px-4 bg-gradient-to-r from-indigo-600 to-teal-600 text-white font-medium rounded-lg hover:from-indigo-700 hover:to-teal-700 transition-all duration-300 flex items-center justify-center group/btn shadow-md hover:shadow-lg"
        >
          <span>Voir le projet</span>
          <svg class="w-4 h-4 ml-2 transform group-hover/btn:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
          </svg>
        </button>
        
        <!-- GitHub Link -->
        <a 
          v-if="githubLink"
          :href="githubLink"
          target="_blank"
          class="ml-3 p-3 bg-gradient-to-br from-slate-50 to-white dark:from-slate-700 dark:to-slate-800 text-slate-600 dark:text-slate-400 rounded-lg border border-slate-300 dark:border-slate-600 hover:bg-gradient-to-br hover:from-indigo-50 hover:to-purple-50 dark:hover:from-indigo-900/30 dark:hover:to-purple-900/30 hover:text-indigo-600 dark:hover:text-indigo-400 hover:border-indigo-300 dark:hover:border-indigo-500 transition-all duration-300"
          title="Code source"
        >
          <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
            <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd" />
          </svg>
        </a>
      </div>
    </div>

    <!-- Hover Effect Gradient -->
    <div class="absolute inset-0 bg-gradient-to-r from-indigo-500/0 to-teal-500/0 group-hover:from-indigo-500/5 group-hover:to-teal-500/5 transition-all duration-500 pointer-events-none rounded-2xl"></div>
  </div>
</template>

<script setup>
import { defineProps } from 'vue'

const props = defineProps({
  title: String,
  description: String,
  technologies: Array,
  category: {
    type: String,
    default: 'Application Web'
  },
  demoLink: {
    type: String,
    default: '#'
  },
  githubLink: {
    type: String,
    default: ''
  }
})

const getProjectInitials = (title) => {
  return title
    .split(' ')
    .map(word => word[0])
    .join('')
    .toUpperCase()
    .slice(0, 2)
}

const getCategoryColor = (category) => {
  const colors = {
    'Application Web': 'bg-gradient-to-b from-indigo-500 to-purple-500',
    'E-commerce': 'bg-gradient-to-b from-teal-500 to-emerald-500',
    'Santé': 'bg-gradient-to-b from-emerald-500 to-green-500',
    'Gestion': 'bg-gradient-to-b from-blue-500 to-cyan-500'
  }
  return colors[category] || 'bg-gradient-to-b from-indigo-500 to-purple-500'
}

const handleViewProject = () => {
  const url = props.demoLink && props.demoLink !== '#' ? props.demoLink : props.githubLink
  if (!url) return
  window.open(url, '_blank', 'noopener,noreferrer')
}
</script>

<style scoped>
/* Animations */
.group {
  animation: slideUp 0.6s ease-out;
  opacity: 0;
  animation-fill-mode: forwards;
}

@keyframes slideUp {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(10px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Effet de survol amélioré */
.bg-gradient-to-br {
  transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
}

.group:hover {
  transform: translateY(-8px);
}
</style>