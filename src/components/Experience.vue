<template>
  <section id="experience" class="py-16 bg-gradient-to-b from-indigo-50/30 to-blue-50 dark:from-slate-900 dark:to-slate-950 transition-colors duration-500">
    <div class="container mx-auto px-6">
      <!-- Section Header -->
      <div class="text-center mb-12">
        <div class="inline-block mb-4">
          <span class="text-indigo-600 dark:text-indigo-400 font-semibold text-sm uppercase tracking-wider">Mon parcours</span>
          <div class="h-1 w-12 bg-gradient-to-r from-indigo-500 to-teal-500 mx-auto mt-2 rounded-full"></div>
        </div>
        <h2 class="text-4xl md:text-5xl font-bold text-slate-800 dark:text-white mb-4">
          Expériences <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-600 to-teal-600 dark:from-indigo-400 dark:to-teal-400">professionnelles</span>
        </h2>
        <p class="text-slate-700 dark:text-slate-300 max-w-2xl mx-auto">
          Stages et missions en développement logiciel
        </p>
      </div>

      <!-- Experiences Container -->
      <div class="max-w-4xl mx-auto">
        <!-- Experience 1 -->
        <div class="relative mb-12">
          <div class="flex items-start gap-0 md:gap-8">
            <!-- Timeline Icon -->
            <div class="hidden md:block flex-shrink-0">
              <div class="w-14 h-14 rounded-full bg-gradient-to-r from-indigo-500 to-teal-500 flex items-center justify-center shadow-lg border-2 border-white dark:border-slate-800">
                <svg class="w-7 h-7 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                </svg>
              </div>
            </div>

            <!-- Content -->
            <div class="flex-1">
              <!-- Experience Header -->
              <div class="flex flex-col sm:flex-row sm:items-center justify-between mb-6 gap-4">
                <div>
                  <div class="inline-flex items-center px-4 py-2 bg-gradient-to-r from-indigo-100 to-teal-100 dark:from-indigo-900/30 dark:to-teal-900/30 text-indigo-700 dark:text-indigo-300 rounded-full text-sm font-semibold mb-3 border border-indigo-200 dark:border-indigo-800/50">
                    <span class="w-2 h-2 bg-indigo-500 rounded-full mr-2"></span>
                    Stage
                  </div>
                  <h3 class="text-2xl font-bold text-slate-800 dark:text-white">Développeur Logiciel</h3>
                </div>
                <div class="flex-shrink-0">
                  <div class="flex items-center text-slate-700 dark:text-slate-300 bg-gradient-to-r from-indigo-50 to-blue-50 dark:from-slate-800 dark:to-slate-900 px-4 py-2 rounded-lg border border-indigo-100 dark:border-slate-700 text-sm sm:text-base">
                    <svg class="w-5 h-5 mr-2 text-indigo-600 dark:text-indigo-400 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                    </svg>
                    <span class="font-medium">SOAVOANIO, Sambava</span>
                  </div>
                </div>
              </div>

              <!-- Project Description -->
              <div class="bg-gradient-to-br from-white to-indigo-50 dark:from-slate-800 dark:to-slate-900 rounded-xl shadow-lg p-6 mb-6 border-l-4 border-indigo-500 border border-indigo-100 dark:border-slate-700">
                <div class="flex flex-col xs:flex-row items-start">
                  <div class="flex-shrink-0 w-12 h-12 rounded-lg bg-gradient-to-r from-indigo-100 to-purple-100 dark:from-indigo-900/30 dark:to-purple-900/30 flex items-center justify-center mb-4 sm:mb-0 sm:mr-4 border border-indigo-200 dark:border-indigo-800/50">
                    <span class="text-indigo-600 dark:text-indigo-400 text-xl">🏥</span>
                  </div>
                  <div>
                    <h4 class="font-semibold text-slate-800 dark:text-white mb-2">Application de gestion médico-social</h4>
                    <p class="text-slate-700 dark:text-slate-300 text-sm sm:text-base">
                      Conception et réalisation d'une application complète pour la gestion médico-social, 
                      incluant la gestion des patients, des rendez-vous et des données médicales.
                    </p>
                  </div>
                </div>
              </div>

              <!-- Technologies -->
              <div class="mb-6">
                <h4 class="font-semibold text-slate-800 dark:text-white mb-3 flex items-center">
                  <svg class="w-5 h-5 mr-2 text-indigo-600 dark:text-indigo-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                  </svg>
                  Technologies utilisées
                </h4>
                <div class="flex flex-wrap gap-2 sm:gap-3">
                  <span class="px-3 py-1.5 sm:px-4 sm:py-2 bg-gradient-to-r from-indigo-50 to-blue-50 dark:from-slate-800 dark:to-slate-700 text-indigo-700 dark:text-indigo-300 rounded-lg text-sm font-medium flex items-center border border-indigo-100 dark:border-slate-600 hover:border-indigo-300 dark:hover:border-indigo-500 transition-colors">
                    <span class="w-1.5 h-1.5 sm:w-2 sm:h-2 bg-indigo-500 rounded-full mr-2"></span>
                    C#
                  </span>
                  <span class="px-3 py-1.5 sm:px-4 sm:py-2 bg-gradient-to-r from-indigo-50 to-purple-50 dark:from-slate-800 dark:to-slate-700 text-purple-700 dark:text-purple-300 rounded-lg text-sm font-medium flex items-center border border-purple-100 dark:border-slate-600 hover:border-purple-300 dark:hover:border-purple-500 transition-colors">
                    <span class="w-1.5 h-1.5 sm:w-2 sm:h-2 bg-purple-500 rounded-full mr-2"></span>
                    .NET
                  </span>
                  <span class="px-3 py-1.5 sm:px-4 sm:py-2 bg-gradient-to-r from-blue-50 to-cyan-50 dark:from-slate-800 dark:to-slate-700 text-blue-700 dark:text-blue-300 rounded-lg text-sm font-medium flex items-center border border-blue-100 dark:border-slate-600 hover:border-blue-300 dark:hover:border-blue-500 transition-colors">
                    <span class="w-1.5 h-1.5 sm:w-2 sm:h-2 bg-blue-500 rounded-full mr-2"></span>
                    WinForms
                  </span>
                </div>
              </div>

              <!-- Key Responsibilities -->
              <div class="bg-gradient-to-br from-slate-50 to-gray-50 dark:from-slate-800 dark:to-slate-900 rounded-xl p-6 border border-slate-200 dark:border-slate-700">
                <h4 class="font-semibold text-slate-800 dark:text-white mb-4 flex items-center">
                  <svg class="w-5 h-5 mr-2 text-teal-600 dark:text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                  </svg>
                  Responsabilités
                </h4>
                <ul class="space-y-3">
                  <li class="flex items-start">
                    <svg class="w-5 h-5 text-emerald-500 mr-3 mt-0.5 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                    </svg>
                    <span class="text-slate-700 dark:text-slate-300 text-sm sm:text-base">Développement de fonctionnalités en C# et .NET</span>
                  </li>
                  <li class="flex items-start">
                    <svg class="w-5 h-5 text-emerald-500 mr-3 mt-0.5 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                    </svg>
                    <span class="text-slate-700 dark:text-slate-300 text-sm sm:text-base">Maintenance et optimisation de l'application existante</span>
                  </li>
                  <li class="flex items-start">
                    <svg class="w-5 h-5 text-emerald-500 mr-3 mt-0.5 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                    </svg>
                    <span class="text-slate-700 dark:text-slate-300 text-sm sm:text-base">Tests et débogage des fonctionnalités</span>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>

        <!-- Experience 2 -->
        <div class="relative">
          <div class="flex items-start gap-0 md:gap-8">
            <!-- Timeline Icon -->
            <div class="hidden md:block flex-shrink-0">
              <div class="w-14 h-14 rounded-full bg-gradient-to-r from-teal-500 to-emerald-500 flex items-center justify-center shadow-lg border-2 border-white dark:border-slate-800">
                <svg class="w-7 h-7 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z" />
                </svg>
              </div>
            </div>

            <!-- Content -->
            <div class="flex-1">
              <!-- Experience Header -->
              <div class="flex flex-col sm:flex-row sm:items-center justify-between mb-6 gap-4">
                <div>
                  <div class="inline-flex items-center px-4 py-2 bg-gradient-to-r from-teal-100 to-emerald-100 dark:from-teal-900/30 dark:to-emerald-900/30 text-teal-700 dark:text-teal-300 rounded-full text-sm font-semibold mb-3 border border-teal-200 dark:border-teal-800/50">
                    <span class="w-2 h-2 bg-teal-500 rounded-full mr-2"></span>
                    Stage
                  </div>
                  <h3 class="text-2xl font-bold text-slate-800 dark:text-white">Développeur Web Full-Stack</h3>
                </div>
                <div class="flex-shrink-0">
                  <div class="flex items-center text-slate-700 dark:text-slate-300 bg-gradient-to-r from-teal-50 to-emerald-50 dark:from-slate-800 dark:to-slate-900 px-4 py-2 rounded-lg border border-teal-100 dark:border-slate-700 text-sm sm:text-base">
                    <svg class="w-5 h-5 mr-2 text-teal-600 dark:text-teal-400 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                    </svg>
                    <span class="font-medium">SYMRISE Madagascar</span>
                  </div>
                </div>
              </div>

              <!-- Project Description -->
              <div class="bg-gradient-to-br from-white to-teal-50 dark:from-slate-800 dark:to-slate-900 rounded-xl shadow-lg p-6 mb-6 border-l-4 border-teal-500 border border-teal-100 dark:border-slate-700">
                <div class="flex flex-col xs:flex-row items-start">
                  <div class="flex-shrink-0 w-12 h-12 rounded-lg bg-gradient-to-r from-teal-100 to-emerald-100 dark:from-teal-900/30 dark:to-emerald-900/30 flex items-center justify-center mb-4 sm:mb-0 sm:mr-4 border border-teal-200 dark:border-teal-800/50">
                    <span class="text-teal-600 dark:text-teal-400 text-xl">🌱</span>
                  </div>
                  <div>
                    <h4 class="font-semibold text-slate-800 dark:text-white mb-2">Application de gestion de production</h4>
                    <p class="text-slate-700 dark:text-slate-300 text-sm sm:text-base">
                      Développement d'une application web pour la gestion de production de produits finis 
                      (vanille, gingembre), incluant le suivi des stocks, la traçabilité et la gestion qualité.
                    </p>
                  </div>
                </div>
              </div>

              <!-- Technologies -->
              <div class="mb-6">
                <h4 class="font-semibold text-slate-800 dark:text-white mb-3 flex items-center">
                  <svg class="w-5 h-5 mr-2 text-teal-600 dark:text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                  </svg>
                  Technologies utilisées
                </h4>
                <div class="flex flex-wrap gap-2 sm:gap-3">
                  <span class="px-3 py-1.5 sm:px-4 sm:py-2 bg-gradient-to-r from-indigo-50 to-purple-50 dark:from-slate-800 dark:to-slate-700 text-indigo-700 dark:text-indigo-300 rounded-lg text-sm font-medium flex items-center border border-indigo-100 dark:border-slate-600 hover:border-indigo-300 dark:hover:border-indigo-500 transition-colors">
                    <span class="w-1.5 h-1.5 sm:w-2 sm:h-2 bg-indigo-500 rounded-full mr-2"></span>
                    Vue.js
                  </span>
                  <span class="px-3 py-1.5 sm:px-4 sm:py-2 bg-gradient-to-r from-teal-50 to-emerald-50 dark:from-slate-800 dark:to-slate-700 text-teal-700 dark:text-teal-300 rounded-lg text-sm font-medium flex items-center border border-teal-100 dark:border-slate-600 hover:border-teal-300 dark:hover:border-teal-500 transition-colors">
                    <span class="w-1.5 h-1.5 sm:w-2 sm:h-2 bg-teal-500 rounded-full mr-2"></span>
                    Go
                  </span>
                  <span class="px-3 py-1.5 sm:px-4 sm:py-2 bg-gradient-to-r from-cyan-50 to-blue-50 dark:from-slate-800 dark:to-slate-700 text-cyan-700 dark:text-cyan-300 rounded-lg text-sm font-medium flex items-center border border-cyan-100 dark:border-slate-600 hover:border-cyan-300 dark:hover:border-cyan-500 transition-colors">
                    <span class="w-1.5 h-1.5 sm:w-2 sm:h-2 bg-cyan-500 rounded-full mr-2"></span>
                    Fiber
                  </span>
                  <span class="px-3 py-1.5 sm:px-4 sm:py-2 bg-gradient-to-r from-amber-50 to-orange-50 dark:from-slate-800 dark:to-slate-700 text-amber-700 dark:text-amber-300 rounded-lg text-sm font-medium flex items-center border border-amber-100 dark:border-slate-600 hover:border-amber-300 dark:hover:border-amber-500 transition-colors">
                    <span class="w-1.5 h-1.5 sm:w-2 sm:h-2 bg-amber-500 rounded-full mr-2"></span>
                    REST API
                  </span>
                </div>
              </div>

              <!-- Key Responsibilities -->
              <div class="bg-gradient-to-br from-slate-50 to-gray-50 dark:from-slate-800 dark:to-slate-900 rounded-xl p-6 border border-slate-200 dark:border-slate-700">
                <h4 class="font-semibold text-slate-800 dark:text-white mb-4 flex items-center">
                  <svg class="w-5 h-5 mr-2 text-teal-600 dark:text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                  </svg>
                  Responsabilités
                </h4>
                <ul class="space-y-3">
                  <li class="flex items-start">
                    <svg class="w-5 h-5 text-emerald-500 mr-3 mt-0.5 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                    </svg>
                    <span class="text-slate-700 dark:text-slate-300 text-sm sm:text-base">Développement frontend avec Vue.js</span>
                  </li>
                  <li class="flex items-start">
                    <svg class="w-5 h-5 text-emerald-500 mr-3 mt-0.5 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                    </svg>
                    <span class="text-slate-700 dark:text-slate-300 text-sm sm:text-base">Création d'API REST avec Go</span>
                  </li>
                  <li class="flex items-start">
                    <svg class="w-5 h-5 text-emerald-500 mr-3 mt-0.5 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                    </svg>
                    <span class="text-slate-700 dark:text-slate-300 text-sm sm:text-base">Gestion de base de données et optimisation</span>
                  </li>
                  <li class="flex items-start">
                    <svg class="w-5 h-5 text-emerald-500 mr-3 mt-0.5 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                    </svg>
                    <span class="text-slate-700 dark:text-slate-300 text-sm sm:text-base">Tests et déploiement de l'application</span>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Summary Section -->
      <div class="mt-16 pt-8 border-t border-indigo-200 dark:border-slate-800">
        <div class="max-w-4xl mx-auto">
          <div class="bg-gradient-to-r from-indigo-50/80 to-teal-50/80 dark:from-slate-900/80 dark:to-slate-800/80 rounded-2xl p-8 border border-indigo-100 dark:border-slate-700 backdrop-blur-sm shadow-inner">
            <div class="grid grid-cols-1 md:grid-cols-5 gap-8 items-center">
              <div class="md:col-span-2 text-center md:text-left">
                <h3 class="text-2xl font-bold text-slate-800 dark:text-white mb-2">Expérience pratique</h3>
                <p class="text-slate-700 dark:text-slate-300 text-sm">
                  Développement d'applications réelles dans des environnements professionnels
                </p>
              </div>
              <div class="md:col-span-3">
                <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
                  <div class="text-center p-4 bg-white/60 dark:bg-slate-800/60 rounded-xl shadow-sm border border-indigo-100 dark:border-slate-700 hover:bg-white dark:hover:bg-slate-800 transition-colors">
                    <div class="text-3xl font-bold text-indigo-600 dark:text-indigo-400">2</div>
                    <div class="text-xs font-semibold text-slate-600 dark:text-slate-400 uppercase tracking-wider">Stages</div>
                  </div>
                  <div class="text-center p-4 bg-white/60 dark:bg-slate-800/60 rounded-xl shadow-sm border border-teal-100 dark:border-slate-700 hover:bg-white dark:hover:bg-slate-800 transition-colors">
                    <div class="text-3xl font-bold text-teal-600 dark:text-teal-400">4+</div>
                    <div class="text-xs font-semibold text-slate-600 dark:text-slate-400 uppercase tracking-wider">Techs</div>
                  </div>
                  <div class="text-center p-4 bg-white/60 dark:bg-slate-800/60 rounded-xl shadow-sm border border-amber-100 dark:border-slate-700 hover:bg-white dark:hover:bg-slate-800 transition-colors">
                    <div class="text-3xl font-bold text-amber-600 dark:text-amber-400">2</div>
                    <div class="text-xs font-semibold text-slate-600 dark:text-slate-400 uppercase tracking-wider">Apps</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
// Pas de logique particulière nécessaire
</script>

<style scoped>
/* Animation douce pour l'apparition */
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

/* Effet de survol pour les cartes */
.bg-gradient-to-br {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.bg-gradient-to-br:hover {
  transform: translateY(-4px);
}
</style>