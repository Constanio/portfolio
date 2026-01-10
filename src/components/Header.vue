<template>
  <header class="fixed w-full z-50 transition-all duration-300" :class="isScrolled ? 'bg-white/95 backdrop-blur-md shadow-lg py-3' : 'bg-gradient-to-r from-indigo-50/95 to-blue-50/95 backdrop-blur-md py-5'">
    <nav class="container mx-auto px-6">
      <div class="flex justify-between items-center">
        <!-- Logo -->
        <div class="text-2xl font-bold transition-all duration-300" :class="isScrolled ? 'text-indigo-600' : 'text-slate-800'">
          <span :class="isScrolled ? 'text-slate-800' : 'text-slate-900'">Rakotoarison</span>
          <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-600 to-teal-600"> Emerson</span>
        </div>

        <!-- Desktop Navigation -->
        <ul class="hidden md:flex space-x-8">
          <li v-for="item in navItems" :key="item.id">
            <a 
              :href="item.href" 
              class="font-medium transition-all duration-300 relative group"
              :class="isScrolled ? 'text-slate-700 hover:text-indigo-600' : 'text-slate-800 hover:text-indigo-600'"
            >
              {{ item.label }}
              <span class="absolute -bottom-1 left-0 w-0 h-0.5 bg-gradient-to-r from-indigo-500 to-teal-500 group-hover:w-full transition-all duration-300"></span>
            </a>
          </li>
        </ul>

        <!-- Mobile Menu Button -->
        <button 
          @click="toggleMobileMenu"
          class="md:hidden p-2 rounded-lg bg-gradient-to-r from-indigo-50 to-blue-50 text-indigo-600 hover:from-indigo-100 hover:to-blue-100 transition-colors duration-300"
        >
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path v-if="!mobileMenuOpen" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
            <path v-else stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
          </svg>
        </button>
      </div>

      <!-- Mobile Navigation -->
      <div 
        v-if="mobileMenuOpen"
        class="md:hidden mt-4 py-4 px-4 bg-white rounded-xl shadow-xl border border-indigo-100 animate-slideDown"
      >
        <ul class="space-y-3">
          <li v-for="item in navItems" :key="item.id">
            <a 
              :href="item.href" 
              @click="closeMobileMenu"
              class="block py-3 px-4 rounded-lg text-slate-700 hover:bg-gradient-to-r hover:from-indigo-50 hover:to-blue-50 hover:text-indigo-600 transition-all duration-300"
            >
              {{ item.label }}
            </a>
          </li>
        </ul>
        
        <!-- Contact Info Mobile -->
        <div class="mt-6 pt-6 border-t border-slate-100">
          <div class="flex items-center justify-center space-x-4">
            <a 
              href="https://github.com/RakotoarisoEConstanio_" 
              target="_blank"
              class="p-2 rounded-lg bg-gradient-to-r from-slate-50 to-gray-50 text-slate-700 hover:from-indigo-50 hover:to-purple-50 hover:text-indigo-600 transition-all duration-300"
            >
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd" />
              </svg>
            </a>
            <a 
              href="mailto:emersonconstanio2@gmail.com" 
              class="p-2 rounded-lg bg-gradient-to-r from-slate-50 to-gray-50 text-slate-700 hover:from-teal-50 hover:to-emerald-50 hover:text-teal-600 transition-all duration-300"
            >
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
              </svg>
            </a>
          </div>
        </div>
      </div>
    </nav>
  </header>
</template>

<script setup>
import { ref, onMounted, onUnmounted } from 'vue'

const isScrolled = ref(false)
const mobileMenuOpen = ref(false)

const navItems = [
  { id: 1, label: 'Accueil', href: '#home' },
  { id: 2, label: 'À propos', href: '#about' },
  { id: 3, label: 'Formations', href: '#education' },
  { id: 4, label: 'Expériences', href: '#experience' },
  { id: 5, label: 'Compétences', href: '#skills' },
  { id: 6, label: 'Projets', href: '#projects' },
  { id: 7, label: 'Contact', href: '#contact' },
]

const handleScroll = () => {
  isScrolled.value = window.scrollY > 20
}

const toggleMobileMenu = () => {
  mobileMenuOpen.value = !mobileMenuOpen.value
}

const closeMobileMenu = () => {
  mobileMenuOpen.value = false
}

onMounted(() => {
  window.addEventListener('scroll', handleScroll)
})

onUnmounted(() => {
  window.removeEventListener('scroll', handleScroll)
})
</script>

<style scoped>
/* Animations */
@keyframes slideDown {
  from {
    opacity: 0;
    transform: translateY(-10px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.animate-slideDown {
  animation: slideDown 0.3s ease-out;
}

/* Effet de verre */
.backdrop-blur-md {
  backdrop-filter: blur(12px);
}
</style>