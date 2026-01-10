<template>
  <footer class="bg-gradient-to-r from-slate-800 to-slate-900 text-white py-12">
    <div class="container mx-auto px-6">
      <!-- Main Footer Content -->
      <div class="flex flex-col lg:flex-row justify-between items-center gap-8 mb-8">
        <!-- Brand & Description -->
        <div class="text-center lg:text-left max-w-md">
          <div class="text-3xl font-bold mb-4">
            <span class="text-white">Rakotoarison</span>
            <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-400 to-teal-400"> Emerson</span>
          </div>
          <p class="text-slate-300 mb-6 leading-relaxed">
            Développeur Full-Stack passionné par la création d'applications web modernes et performantes.
            Spécialisé en Vue.js, .NET et Go.
          </p>
          
          <!-- Quick Contact -->
          <div class="flex flex-col sm:flex-row gap-4 mb-6">
            <a 
              href="mailto:emersonconstanio2@gmail.com" 
              class="inline-flex items-center justify-center px-4 py-2 bg-gradient-to-r from-indigo-600/20 to-teal-600/20 text-indigo-300 hover:text-white rounded-lg border border-indigo-800 hover:border-indigo-600 transition-all duration-300 group"
            >
              <svg class="w-4 h-4 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
              </svg>
              emersonconstanio2@gmail.com
            </a>
            <a 
              href="tel:0340831979" 
              class="inline-flex items-center justify-center px-4 py-2 bg-gradient-to-r from-teal-600/20 to-emerald-600/20 text-teal-300 hover:text-white rounded-lg border border-teal-800 hover:border-teal-600 transition-all duration-300 group"
            >
              <svg class="w-4 h-4 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
              </svg>
              0340831979
            </a>
          </div>
        </div>

        <!-- Quick Links & Social -->
        <div class="flex flex-col sm:flex-row gap-8">
          <!-- Navigation Links -->
          <div>
            <h3 class="font-bold text-lg mb-4 text-white">Navigation</h3>
            <ul class="space-y-2">
              <li v-for="item in quickLinks" :key="item.id">
                <a 
                  :href="item.href" 
                  class="text-slate-300 hover:text-white transition-colors duration-300 flex items-center group"
                >
                  <svg class="w-3 h-3 mr-2 text-indigo-400 opacity-0 group-hover:opacity-100 transition-opacity duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6" />
                  </svg>
                  {{ item.label }}
                </a>
              </li>
            </ul>
          </div>

          <!-- Social Links -->
          <div>
            <h3 class="font-bold text-lg mb-4 text-white">Réseaux</h3>
            <div class="flex space-x-4">
              <a 
                href="https://github.com/RakotoarisoEConstanio_" 
                target="_blank"
                class="w-12 h-12 rounded-full bg-gradient-to-r from-slate-700 to-slate-800 flex items-center justify-center text-slate-300 hover:text-white hover:from-indigo-600 hover:to-purple-600 transition-all duration-300 border border-slate-700 hover:border-indigo-500 group"
                title="GitHub"
              >
                <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                  <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd" />
                </svg>
              </a>
              <a 
                href="mailto:emersonconstanio2@gmail.com" 
                class="w-12 h-12 rounded-full bg-gradient-to-r from-slate-700 to-slate-800 flex items-center justify-center text-slate-300 hover:text-white hover:from-teal-600 hover:to-emerald-600 transition-all duration-300 border border-slate-700 hover:border-teal-500 group"
                title="Email"
              >
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                </svg>
              </a>
            </div>
          </div>
        </div>
      </div>

      <!-- Divider -->
      <div class="h-px bg-gradient-to-r from-transparent via-slate-700 to-transparent my-8"></div>

      <!-- Copyright -->
      <div class="flex flex-col md:flex-row justify-between items-center text-slate-400 text-sm">
        <div class="mb-4 md:mb-0">
          <p>&copy; {{ currentYear }} Rakotoarison Emerson Constanio. Tous droits réservés.</p>
        </div>
        <div class="flex items-center">
          <svg class="w-4 h-4 mr-2 text-indigo-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" />
          </svg>
          <p>Développé avec Vue.js, Vite et Tailwind CSS</p>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup>
const currentYear = new Date().getFullYear()

const quickLinks = [
  { id: 1, label: 'Accueil', href: '#home' },
  { id: 2, label: 'À propos', href: '#about' },
  { id: 3, label: 'Compétences', href: '#skills' },
  { id: 4, label: 'Projets', href: '#projects' },
  { id: 5, label: 'Contact', href: '#contact' },
]
</script>

<style scoped>
/* Animation pour l'apparition du footer */
footer {
  animation: fadeIn 0.8s ease-out;
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Effet de survol pour les liens */
a {
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}
</style>