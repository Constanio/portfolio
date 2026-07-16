<template>
  <header class="fixed w-full z-50 transition-all duration-300" :class="isScrolled ? 'bg-white/95 dark:bg-slate-900/95 backdrop-blur-md shadow-lg py-3' : 'bg-gradient-to-r from-indigo-50/95 to-blue-50/95 dark:from-slate-950/95 dark:to-slate-900/95 backdrop-blur-md py-5'">
    <nav class="container mx-auto px-6">
      <div class="flex justify-between items-center">
        <!-- Logo -->
        <a
          href="#home"
          class="font-bold transition-all duration-300 leading-tight"
          :class="isScrolled ? 'text-indigo-600' : 'text-slate-800 dark:text-white'"
        >
          <span
            class="block text-base sm:text-xl md:text-2xl truncate max-w-[150px] sm:max-w-none"
            :class="isScrolled ? 'text-slate-800 dark:text-white' : 'text-slate-900 dark:text-white'"
            title="Rakotoarison"
          >
            Rakotoarison
          </span>
          <span
            class="block text-sm sm:text-lg md:text-xl text-transparent bg-clip-text bg-gradient-to-r from-indigo-600 to-teal-600 truncate max-w-[150px] sm:max-w-none"
            title="Emerson Constanio"
          >
            Emerson Constanio
          </span>
        </a>

        <!-- Desktop Navigation -->
        <div class="hidden md:flex items-center space-x-8">
          <ul class="flex space-x-8">
            <li v-for="item in navItems" :key="item.id">
              <a 
                :href="item.href" 
                class="font-medium transition-all duration-300 relative group"
                :class="isScrolled ? 'text-slate-700 dark:text-slate-300 hover:text-indigo-600' : 'text-slate-800 dark:text-slate-200 hover:text-indigo-600'"
              >
                {{ item.label }}
                <span class="absolute -bottom-1 left-0 w-0 h-0.5 bg-gradient-to-r from-indigo-500 to-teal-500 group-hover:w-full transition-all duration-300"></span>
              </a>
            </li>
          </ul>
          
          <!-- Dark Mode Toggle Desktop -->
          <button 
            @click="toggleDarkMode"
            class="p-2 rounded-lg bg-slate-100 dark:bg-slate-800 text-slate-600 dark:text-amber-400 hover:bg-slate-200 dark:hover:bg-slate-700 transition-all duration-300 border border-slate-200 dark:border-slate-700 shadow-sm"
            aria-label="Toggle Dark Mode"
          >
            <svg v-if="!isDark" class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.354 15.354A9 9 0 018.646 3.646 9.003 9.003 0 0012 21a9.003 9.003 0 008.354-5.646z" />
            </svg>
            <svg v-else class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 3v1m0 16v1m9-9h-1M4 9h-1m15.364-6.364l-.707.707M6.343 17.657l-.707.707M16.95 16.95l.707.707M7.636 7.636l.707-.707M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
            </svg>
          </button>
        </div>

        <!-- Mobile Menu Button & Dark Mode Toggle -->
        <div class="md:hidden flex items-center space-x-3">
          <!-- Dark Mode Toggle Mobile -->
          <button 
            @click="toggleDarkMode"
            class="p-2 rounded-lg bg-slate-100 dark:bg-slate-800 text-slate-600 dark:text-amber-400 hover:bg-slate-200 dark:hover:bg-slate-700 transition-all duration-300 border border-slate-200 dark:border-slate-700"
            aria-label="Toggle Dark Mode"
          >
            <svg v-if="!isDark" class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.354 15.354A9 9 0 018.646 3.646 9.003 9.003 0 0012 21a9.003 9.003 0 008.354-5.646z" />
            </svg>
            <svg v-else class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 3v1m0 16v1m9-9h-1M4 9h-1m15.364-6.364l-.707.707M6.343 17.657l-.707.707M16.95 16.95l.707.707M7.636 7.636l.707-.707M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
            </svg>
          </button>

          <button 
            @click="toggleMobileMenu"
            class="p-2 rounded-lg bg-gradient-to-r from-indigo-50 to-blue-50 dark:from-slate-800 dark:to-slate-700 text-indigo-600 dark:text-indigo-400 hover:from-indigo-100 hover:to-blue-100 transition-colors duration-300"
          >
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path v-if="!mobileMenuOpen" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
              <path v-else stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
            </svg>
          </button>
        </div>
      </div>

      <!-- Mobile Navigation -->
      <div 
        v-if="mobileMenuOpen"
        class="md:hidden mt-4 py-4 px-4 bg-white dark:bg-slate-900 rounded-xl shadow-xl border border-indigo-100 dark:border-slate-800 animate-slideDown"
      >
        <ul class="space-y-3">
          <li v-for="item in navItems" :key="item.id">
            <a 
              :href="item.href" 
              @click="closeMobileMenu"
              class="block py-3 px-4 rounded-lg text-slate-700 dark:text-slate-200 hover:bg-gradient-to-r hover:from-indigo-50 hover:to-blue-50 dark:hover:from-slate-800 dark:hover:to-slate-700 hover:text-indigo-600 dark:hover:text-indigo-400 transition-all duration-300"
            >
              {{ item.label }}
            </a>
          </li>
        </ul>
        
        <!-- Contact Info Mobile -->
        <div class="mt-6 pt-6 border-t border-slate-100 dark:border-slate-700">
          <div class="flex items-center justify-center space-x-4">
            <a 
              href="https://github.com/Constanio" 
              target="_blank"
              class="p-2 rounded-lg bg-gradient-to-r from-slate-50 to-gray-50 dark:from-slate-800 dark:to-slate-700 text-slate-700 dark:text-slate-200 hover:from-indigo-50 hover:to-purple-50 dark:hover:from-indigo-900/40 dark:hover:to-purple-900/40 hover:text-indigo-600 dark:hover:text-indigo-400 transition-all duration-300"
              title="GitHub"
            >
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd" />
              </svg>
            </a>
            <a 
              href="https://www.linkedin.com/in/rakotoarison-emerson-constanio-31295426a/" 
              target="_blank"
              rel="noopener noreferrer"
              class="p-2 rounded-lg bg-gradient-to-r from-slate-50 to-gray-50 dark:from-slate-800 dark:to-slate-700 text-slate-700 dark:text-slate-200 hover:from-blue-50 hover:to-sky-50 dark:hover:from-blue-900/40 dark:hover:to-sky-900/40 hover:text-blue-600 dark:hover:text-blue-400 transition-all duration-300"
              title="LinkedIn"
            >
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
              </svg>
            </a>
            <a 
              href="mailto:emersonconstanio2@gmail.com" 
              class="p-2 rounded-lg bg-gradient-to-r from-slate-50 to-gray-50 dark:from-slate-800 dark:to-slate-700 text-slate-700 dark:text-slate-200 hover:from-teal-50 hover:to-emerald-50 dark:hover:from-teal-900/40 dark:hover:to-emerald-900/40 hover:text-teal-600 dark:hover:text-teal-400 transition-all duration-300"
              title="Email"
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
const isDark = ref(false)

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

const toggleDarkMode = () => {
  isDark.value = !isDark.value
  if (isDark.value) {
    document.documentElement.classList.add('dark')
    localStorage.setItem('theme', 'dark')
  } else {
    document.documentElement.classList.remove('dark')
    localStorage.setItem('theme', 'light')
  }
}

onMounted(() => {
  window.addEventListener('scroll', handleScroll)
  
  // Initialize theme
  const savedTheme = localStorage.getItem('theme')
  const prefersDark = window.matchMedia('(prefers-color-scheme: dark)').matches
  
  if (savedTheme === 'dark' || (!savedTheme && prefersDark)) {
    isDark.value = true
    document.documentElement.classList.add('dark')
  } else {
    isDark.value = false
    document.documentElement.classList.remove('dark')
  }
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