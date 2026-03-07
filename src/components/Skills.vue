<template>
  <section id="skills" class="py-16 bg-gradient-to-b from-teal-50/30 to-blue-50 dark:from-slate-950 dark:to-slate-900 transition-colors duration-500">
    <div class="container mx-auto px-6">
      <!-- Section Header -->
      <div class="text-center mb-12">
        <div class="inline-block mb-4">
          <span class="text-indigo-600 dark:text-indigo-400 font-semibold text-sm uppercase tracking-wider">Mes expertises</span>
          <div class="h-1 w-12 bg-gradient-to-r from-indigo-500 to-teal-500 mx-auto mt-2 rounded-full"></div>
        </div>
        <h2 class="text-4xl md:text-5xl font-bold text-slate-800 dark:text-white mb-4">
          Compétences <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-600 to-teal-600 dark:from-indigo-400 dark:to-teal-400">techniques</span>
        </h2>
        <p class="text-slate-700 dark:text-slate-300 max-w-2xl mx-auto">
          Technologies et outils que j'utilise pour développer des applications modernes
        </p>
      </div>

      <!-- Skills Grid -->
      <div class="max-w-6xl mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <!-- Programming Languages -->
          <div class="bg-gradient-to-br from-white to-indigo-50 dark:from-slate-800 dark:to-slate-900 rounded-2xl shadow-lg p-8 hover:shadow-xl transition-all duration-300 border border-indigo-100 dark:border-slate-700">
            <div class="flex items-center mb-8">
              <div class="w-12 h-12 rounded-lg bg-gradient-to-r from-indigo-100 to-purple-100 dark:from-indigo-900/30 dark:to-purple-900/30 flex items-center justify-center mr-4 border border-indigo-200 dark:border-indigo-800/50">
                <svg class="w-6 h-6 text-indigo-600 dark:text-indigo-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4" />
                </svg>
              </div>
              <h3 class="text-2xl font-bold text-slate-800 dark:text-white">Langages</h3>
            </div>
            
            <div class="space-y-6">
              <div v-for="(language, index) in languages" :key="index" class="flex items-center justify-between group p-3 rounded-lg hover:bg-indigo-50/50 dark:hover:bg-slate-700/50 transition-colors">
                <div class="flex items-center">
                  <div class="w-10 h-10 rounded-lg bg-gradient-to-br from-indigo-50 to-purple-50 dark:from-indigo-900/20 dark:to-purple-900/20 flex items-center justify-center mr-4 border border-indigo-200 dark:border-indigo-800/50 group-hover:border-indigo-300 dark:group-hover:border-indigo-500 transition-colors">
                    <span class="text-indigo-600 dark:text-indigo-400 font-medium group-hover:text-indigo-700 dark:group-hover:text-indigo-300">{{ language.icon }}</span>
                  </div>
                  <span class="font-medium text-slate-800 dark:text-slate-200">{{ language.name }}</span>
                </div>
                <div class="text-right">
                  <div class="text-xs text-slate-500 dark:text-slate-400 mb-1">Niveau</div>
                  <div class="flex space-x-1">
                    <div v-for="i in 5" :key="i" 
                         class="w-2 h-2 rounded-full transition-all duration-300"
                         :class="i <= language.level ? 'bg-gradient-to-r from-indigo-500 to-purple-500' : 'bg-slate-300 dark:bg-slate-700'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Databases -->
          <div class="bg-gradient-to-br from-white to-teal-50 dark:from-slate-800 dark:to-slate-900 rounded-2xl shadow-lg p-8 hover:shadow-xl transition-all duration-300 border border-teal-100 dark:border-slate-700">
            <div class="flex items-center mb-8">
              <div class="w-12 h-12 rounded-lg bg-gradient-to-r from-teal-100 to-emerald-100 dark:from-teal-900/30 dark:to-emerald-900/30 flex items-center justify-center mr-4 border border-teal-200 dark:border-teal-800/50">
                <svg class="w-6 h-6 text-teal-600 dark:text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4m0 5c0 2.21-3.582 4-8 4s-8-1.79-8-4" />
                </svg>
              </div>
              <h3 class="text-2xl font-bold text-slate-800 dark:text-white">Bases de données</h3>
            </div>
            
            <div class="space-y-6">
              <div v-for="(database, index) in databases" :key="index" class="group p-4 rounded-lg hover:bg-teal-50/50 dark:hover:bg-slate-700/50 transition-colors">
                <div class="flex items-center justify-between mb-3">
                  <div class="flex items-center">
                    <div class="w-10 h-10 rounded-lg bg-gradient-to-br from-teal-50 to-emerald-50 dark:from-teal-900/20 dark:to-emerald-900/20 flex items-center justify-center mr-4 border border-teal-200 dark:border-teal-800/50 group-hover:border-teal-300 dark:group-hover:border-teal-500 transition-colors">
                      <span class="text-teal-600 dark:text-teal-400 font-medium group-hover:text-teal-700 dark:group-hover:text-teal-300">DB</span>
                    </div>
                    <div>
                      <span class="font-medium text-slate-800 dark:text-slate-200 block">{{ database.name }}</span>
                      <span class="text-xs text-slate-500 dark:text-slate-400">{{ database.type }}</span>
                    </div>
                  </div>
                  <span class="px-3 py-1 bg-gradient-to-r from-teal-100 to-emerald-100 dark:from-teal-900/50 dark:to-emerald-900/50 text-teal-700 dark:text-teal-300 rounded-full text-sm font-medium border border-teal-200 dark:border-teal-800">
                    {{ database.experience }}
                  </span>
                </div>
                <div class="h-2 bg-slate-200 dark:bg-slate-700 rounded-full overflow-hidden">
                  <div 
                    class="h-full bg-gradient-to-r from-teal-500 to-emerald-500 rounded-full transition-all duration-1000"
                    :style="{ width: database.experience }"
                  ></div>
                </div>
              </div>
            </div>
          </div>

          <!-- Frameworks & Tools -->
          <div class="bg-gradient-to-br from-white to-amber-50 dark:from-slate-800 dark:to-slate-900 rounded-2xl shadow-lg p-8 hover:shadow-xl transition-all duration-300 border border-amber-100 dark:border-slate-700">
            <div class="flex items-center mb-8">
              <div class="w-12 h-12 rounded-lg bg-gradient-to-r from-amber-100 to-orange-100 dark:from-amber-900/30 dark:to-orange-900/30 flex items-center justify-center mr-4 border border-amber-200 dark:border-amber-800/50">
                <svg class="w-6 h-6 text-amber-600 dark:text-amber-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4" />
                </svg>
              </div>
              <h3 class="text-2xl font-bold text-slate-800 dark:text-white">Frameworks & Outils</h3>
            </div>
            
            <div class="grid grid-cols-2 gap-4">
              <div v-for="(framework, index) in frameworks" :key="index" 
                   class="bg-gradient-to-br from-slate-50 to-white dark:from-slate-700 dark:to-slate-800 rounded-lg p-4 hover:bg-gradient-to-br hover:from-indigo-50 hover:to-purple-50 dark:hover:from-indigo-900/30 dark:hover:to-purple-900/30 hover:border-indigo-200 dark:hover:border-indigo-500 border border-slate-200 dark:border-slate-600 transition-all duration-300 group">
                <div class="flex items-center">
                  <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-white to-slate-50 dark:from-slate-800 dark:to-slate-900 flex items-center justify-center mr-3 border border-slate-300 dark:border-slate-600 group-hover:border-indigo-300 dark:group-hover:border-indigo-500 transition-colors">
                    <span class="text-slate-600 dark:text-slate-400 group-hover:text-indigo-600 dark:group-hover:text-indigo-400 text-sm font-medium">{{ framework.icon }}</span>
                  </div>
                  <div>
                    <div class="font-medium text-slate-800 dark:text-slate-200 group-hover:text-indigo-700 dark:group-hover:text-indigo-300">{{ framework.name }}</div>
                    <div class="text-xs text-slate-500 dark:text-slate-400 group-hover:text-indigo-500 dark:group-hover:text-indigo-400">{{ framework.category }}</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Additional Skills -->
        <div class="mt-12 bg-gradient-to-r from-indigo-50/80 to-teal-50/80 dark:from-slate-800 dark:to-slate-900 rounded-2xl p-8 border border-indigo-100 dark:border-slate-700 backdrop-blur-sm">
          <div class="flex flex-col md:flex-row items-center justify-between">
            <div class="mb-6 md:mb-0">
              <h3 class="text-2xl font-bold text-slate-800 dark:text-white mb-2">Autres compétences</h3>
              <p class="text-slate-700 dark:text-slate-300">Outils et méthodes complémentaires</p>
            </div>
            <div class="flex flex-wrap gap-3">
              <span class="px-4 py-2 bg-gradient-to-br from-white to-slate-50 dark:from-slate-800 dark:to-slate-700 text-slate-800 dark:text-slate-200 rounded-lg font-medium shadow-sm border border-slate-200 dark:border-slate-600 hover:border-indigo-300 dark:hover:border-indigo-500 hover:bg-white dark:hover:bg-slate-600 transition-colors">
                Git & GitHub
              </span>
              <span class="px-4 py-2 bg-gradient-to-br from-white to-blue-50 dark:from-slate-800 dark:to-slate-700 text-blue-800 dark:text-blue-300 rounded-lg font-medium shadow-sm border border-blue-200 dark:border-slate-600 hover:border-blue-300 dark:hover:border-blue-500 hover:bg-white dark:hover:bg-slate-600 transition-colors">
                Docker
              </span>
              <span class="px-4 py-2 bg-gradient-to-br from-white to-teal-50 dark:from-slate-800 dark:to-slate-700 text-teal-800 dark:text-teal-300 rounded-lg font-medium shadow-sm border border-teal-200 dark:border-slate-600 hover:border-teal-300 dark:hover:border-teal-500 hover:bg-white dark:hover:bg-slate-600 transition-colors">
                REST API
              </span>
              <span class="px-4 py-2 bg-gradient-to-br from-white to-amber-50 dark:from-slate-800 dark:to-slate-700 text-amber-800 dark:text-amber-300 rounded-lg font-medium shadow-sm border border-amber-200 dark:border-slate-600 hover:border-amber-300 dark:hover:border-amber-500 hover:bg-white dark:hover:bg-slate-600 transition-colors">
                Agile/Scrum
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const languages = [
  { name: 'JavaScript', level: 4, icon: 'JS' },
  { name: 'Golang', level: 4, icon: 'GO' },
  { name: 'Java', level: 3, icon: 'JA' },
  { name: '.NET', level: 4, icon: '.NET' },
  { name: 'PHP', level: 4, icon: 'PHP' }
]

const databases = [
  { name: 'MySQL', type: 'Relationnel', experience: '90%' },
  { name: 'PostgreSQL', type: 'Relationnel', experience: '85%' },
  { name: 'MongoDB', type: 'NoSQL', experience: '40%' }
]

const frameworks = [
  { name: 'Vue.js', category: 'Frontend', icon: 'Vue' },
  { name: 'React Native', category: 'Mobile', icon: 'RN' },
  { name: 'ASP.NET', category: 'Backend', icon: 'ASP' },
  { name: 'Spring Boot', category: 'Backend', icon: 'SB' },
  { name: 'Fiber', category: 'Backend', icon: 'FB' },
  { name: 'Laravel', category: 'Backend', icon: 'LV' }
]
</script>

<style scoped>
/* Animations */
section {
  animation: fadeIn 0.6s ease-out;
}

@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

/* Animation pour les barres de progression */
@keyframes slideIn {
  from {
    width: 0;
  }
}

.h-2 > div {
  animation: slideIn 1s ease-out;
}

/* Effet de survol pour les cartes */
.bg-gradient-to-br {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.bg-gradient-to-br:hover {
  transform: translateY(-4px);
}
</style>