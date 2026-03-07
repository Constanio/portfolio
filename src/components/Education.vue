<template>
  <section id="education" class="py-16 bg-gradient-to-b from-teal-50/30 to-blue-50 dark:from-slate-950 dark:to-slate-900 transition-colors duration-500">
    <div class="container mx-auto px-6">
      <!-- Section Header -->
      <div class="text-center mb-12">
        <div class="inline-block mb-4">
          <span class="text-teal-600 dark:text-teal-400 font-semibold text-sm uppercase tracking-wider">Parcours académique</span>
          <div class="h-1 w-12 bg-gradient-to-r from-indigo-500 to-teal-500 mx-auto mt-2 rounded-full"></div>
        </div>
        <h2 class="text-4xl md:text-5xl font-bold text-slate-800 dark:text-white mb-4">
          Mes <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-600 to-teal-600 dark:from-indigo-400 dark:to-teal-400">formations</span>
        </h2>
        <p class="text-slate-700 dark:text-slate-300 max-w-2xl mx-auto">
          Mon parcours académique en développement web et ingénierie géospatiale
        </p>
      </div>

      <!-- Timeline Container -->
      <div class="max-w-4xl mx-auto">
        <!-- Timeline Item 1 - M1 -->
        <div class="relative mb-12">
          <div class="flex flex-col md:flex-row gap-8 items-start">
            <!-- Date Badge -->
            <div class="md:w-1/4">
              <div class="bg-gradient-to-r from-indigo-600 to-teal-600 text-white px-6 py-3 rounded-xl shadow-lg inline-block border border-indigo-500">
                <div class="font-bold text-lg">2024 - 2025</div>
                <div class="text-sm opacity-90">1 an</div>
              </div>
            </div>

            <!-- Content Card -->
            <div class="md:w-3/4">
              <div class="bg-gradient-to-br from-white to-indigo-50 dark:from-slate-800 dark:to-slate-900 rounded-xl shadow-lg p-8 border-l-4 border-indigo-500 hover:shadow-xl transition-all duration-300 border border-indigo-100 dark:border-slate-700">
                <!-- Degree Level Badge -->
                <div class="inline-flex items-center px-4 py-2 bg-gradient-to-r from-indigo-100 to-teal-100 dark:from-indigo-900/30 dark:to-teal-900/30 text-indigo-700 dark:text-indigo-300 rounded-full text-sm font-semibold mb-4 border border-indigo-200 dark:border-indigo-800/50">
                  <span class="w-2 h-2 bg-indigo-500 rounded-full mr-2"></span>
                  Master 1
                </div>

                <h3 class="text-2xl font-bold text-slate-800 dark:text-white mb-3">
                  Ingénierie Géospatiale et Technologie d'Information
                </h3>
                
                <div class="flex items-center text-slate-600 dark:text-slate-400 mb-4">
                  <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-indigo-100 to-teal-100 dark:from-indigo-900/30 dark:to-teal-900/30 flex items-center justify-center mr-3 border border-indigo-200 dark:border-indigo-800/50">
                    <svg class="w-4 h-4 text-indigo-600 dark:text-indigo-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
                    </svg>
                  </div>
                  <span class="font-medium">EMIT, Fianarantsoa</span>
                </div>

                <p class="text-slate-700 dark:text-slate-300 mb-4">
                  Spécialisation en technologies géospatiales et systèmes d'information, 
                  avec une approche orientée développement d'applications.
                </p>

                <!-- Skills Tags -->
                <div class="flex flex-wrap gap-2">
                  <span class="px-3 py-1 bg-gradient-to-r from-indigo-50 to-indigo-100 dark:from-slate-700 dark:to-slate-800 text-indigo-700 dark:text-indigo-300 rounded-full text-sm border border-indigo-200 dark:border-slate-600">
                    Géomatique
                  </span>
                  <span class="px-3 py-1 bg-gradient-to-r from-teal-50 to-teal-100 dark:from-slate-700 dark:to-slate-800 text-teal-700 dark:text-teal-300 rounded-full text-sm border border-teal-200 dark:border-slate-600">
                    SIG
                  </span>
                  <span class="px-3 py-1 bg-gradient-to-r from-purple-50 to-purple-100 dark:from-slate-700 dark:to-slate-800 text-purple-700 dark:text-purple-300 rounded-full text-sm border border-purple-200 dark:border-slate-600">
                    Analyse spatiale
                  </span>
                </div>
              </div>
            </div>
          </div>

          <!-- Timeline connector for mobile -->
          <div class="md:hidden absolute left-6 top-0 bottom-0 w-0.5 bg-gradient-to-b from-indigo-300 to-teal-300 dark:from-indigo-900 dark:to-teal-900 -z-10"></div>
        </div>

        <!-- Timeline Item 2 - L3 -->
        <div class="relative mb-12">
          <div class="flex flex-col md:flex-row gap-8 items-start">
            <!-- Date Badge -->
            <div class="md:w-1/4 md:text-right">
              <div class="bg-gradient-to-r from-teal-600 to-emerald-600 text-white px-6 py-3 rounded-xl shadow-lg inline-block border border-teal-500">
                <div class="font-bold text-lg">2023 - 2024</div>
                <div class="text-sm opacity-90">1 an</div>
              </div>
            </div>

            <!-- Content Card -->
            <div class="md:w-3/4">
              <div class="bg-gradient-to-br from-white to-teal-50 dark:from-slate-800 dark:to-slate-900 rounded-xl shadow-lg p-8 border-l-4 border-teal-500 hover:shadow-xl transition-all duration-300 border border-teal-100 dark:border-slate-700">
                <!-- Degree Level Badge -->
                <div class="inline-flex items-center px-4 py-2 bg-gradient-to-r from-teal-100 to-emerald-100 dark:from-teal-900/30 dark:to-emerald-900/30 text-teal-700 dark:text-teal-300 rounded-full text-sm font-semibold mb-4 border border-teal-200 dark:border-teal-800/50">
                  <span class="w-2 h-2 bg-teal-500 rounded-full mr-2"></span>
                  Licence 3
                </div>

                <h3 class="text-2xl font-bold text-slate-800 dark:text-white mb-3">
                  Développement d'Applications Internet et Intranet
                </h3>
                
                <div class="flex items-center text-slate-600 dark:text-slate-400 mb-4">
                  <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-teal-100 to-emerald-100 dark:from-teal-900/30 dark:to-emerald-900/30 flex items-center justify-center mr-3 border border-teal-200 dark:border-teal-800/50">
                    <svg class="w-4 h-4 text-teal-600 dark:text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
                    </svg>
                  </div>
                  <span class="font-medium">EMIT, Fianarantsoa</span>
                </div>

                <p class="text-slate-700 dark:text-slate-300 mb-4">
                  Approfondissement des compétences en développement web full-stack, 
                  architecture d'applications et gestion de bases de données.
                </p>

                <!-- Skills Tags -->
                <div class="flex flex-wrap gap-2">
                  <span class="px-3 py-1 bg-gradient-to-r from-indigo-50 to-indigo-100 dark:from-slate-700 dark:to-slate-800 text-indigo-700 dark:text-indigo-300 rounded-full text-sm border border-indigo-200 dark:border-slate-600">
                    Vue.js
                  </span>
                  <span class="px-3 py-1 bg-gradient-to-r from-blue-50 to-blue-100 dark:from-slate-700 dark:to-slate-800 text-blue-700 dark:text-blue-300 rounded-full text-sm border border-blue-200 dark:border-slate-600">
                    .NET
                  </span>
                  <span class="px-3 py-1 bg-gradient-to-r from-teal-50 to-teal-100 dark:from-slate-700 dark:to-slate-800 text-teal-700 dark:text-teal-300 rounded-full text-sm border border-teal-200 dark:border-slate-600">
                    PostgreSQL
                  </span>
                </div>
              </div>
            </div>
          </div>

          <!-- Timeline connector for mobile -->
          <div class="md:hidden absolute left-6 top-0 bottom-0 w-0.5 bg-gradient-to-b from-teal-300 to-emerald-300 dark:from-teal-900 dark:to-emerald-900 -z-10"></div>
        </div>

        <!-- Timeline Item 3 - L2 -->
        <div class="relative mb-12">
          <div class="flex flex-col md:flex-row gap-8 items-start">
            <!-- Date Badge -->
            <div class="md:w-1/4">
              <div class="bg-gradient-to-r from-blue-600 to-indigo-600 text-white px-6 py-3 rounded-xl shadow-lg inline-block border border-blue-500">
                <div class="font-bold text-lg">2022 - 2023</div>
                <div class="text-sm opacity-90">1 an</div>
              </div>
            </div>

            <!-- Content Card -->
            <div class="md:w-3/4">
              <div class="bg-gradient-to-br from-white to-blue-50 dark:from-slate-800 dark:to-slate-900 rounded-xl shadow-lg p-8 border-l-4 border-blue-500 hover:shadow-xl transition-all duration-300 border border-blue-100 dark:border-slate-700">
                <!-- Degree Level Badge -->
                <div class="inline-flex items-center px-4 py-2 bg-gradient-to-r from-blue-100 to-indigo-100 dark:from-blue-900/30 dark:to-indigo-900/30 text-blue-700 dark:text-blue-300 rounded-full text-sm font-semibold mb-4 border border-blue-200 dark:border-blue-800/50">
                  <span class="w-2 h-2 bg-blue-500 rounded-full mr-2"></span>
                  Licence 2
                </div>

                <h3 class="text-2xl font-bold text-slate-800 dark:text-white mb-3">
                  Développement d'Applications Internet et Intranet
                </h3>
                
                <div class="flex items-center text-slate-600 dark:text-slate-400 mb-4">
                  <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-blue-100 to-indigo-100 dark:from-blue-900/30 dark:to-indigo-900/30 flex items-center justify-center mr-3 border border-blue-200 dark:border-blue-800/50">
                    <svg class="w-4 h-4 text-blue-600 dark:text-blue-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
                    </svg>
                  </div>
                  <span class="font-medium">EMIT, Fianarantsoa</span>
                </div>

                <p class="text-slate-700 dark:text-slate-300 mb-4">
                  Acquisition des bases du développement web, des langages de programmation 
                  et des principes de conception d'applications.
                </p>

                <!-- Skills Tags -->
                <div class="flex flex-wrap gap-2">
                  <span class="px-3 py-1 bg-gradient-to-r from-amber-50 to-amber-100 dark:from-slate-700 dark:to-slate-800 text-amber-700 dark:text-amber-300 rounded-full text-sm border border-amber-200 dark:border-slate-600">
                    JavaScript
                  </span>
                  <span class="px-3 py-1 bg-gradient-to-r from-purple-50 to-purple-100 dark:from-slate-700 dark:to-slate-800 text-purple-700 dark:text-purple-300 rounded-full text-sm border border-purple-200 dark:border-slate-600">
                    PHP
                  </span>
                  <span class="px-3 py-1 bg-gradient-to-r from-teal-50 to-teal-100 dark:from-slate-700 dark:to-slate-800 text-teal-700 dark:text-teal-300 rounded-full text-sm border border-teal-200 dark:border-slate-600">
                    MySQL
                  </span>
                </div>
              </div>
            </div>
          </div>

          <!-- Timeline connector for mobile -->
          <div class="md:hidden absolute left-6 top-0 bottom-0 w-0.5 bg-gradient-to-b from-blue-300 to-indigo-300 dark:from-blue-900 dark:to-indigo-900 -z-10"></div>
        </div>

        <!-- Timeline Item 4 - L1 -->
        <div class="relative">
          <div class="flex flex-col md:flex-row gap-8 items-start">
            <!-- Date Badge -->
            <div class="md:w-1/4 md:text-right">
              <div class="bg-gradient-to-r from-purple-600 to-pink-600 text-white px-6 py-3 rounded-xl shadow-lg inline-block border border-purple-500">
                <div class="font-bold text-lg">2021 - 2022</div>
                <div class="text-sm opacity-90">1 an</div>
              </div>
            </div>

            <!-- Content Card -->
            <div class="md:w-3/4">
              <div class="bg-gradient-to-br from-white to-purple-50 dark:from-slate-800 dark:to-slate-900 rounded-xl shadow-lg p-8 border-l-4 border-purple-500 hover:shadow-xl transition-all duration-300 border border-purple-100 dark:border-slate-700">
                <!-- Degree Level Badge -->
                <div class="inline-flex items-center px-4 py-2 bg-gradient-to-r from-purple-100 to-pink-100 dark:from-purple-900/30 dark:to-pink-900/30 text-purple-700 dark:text-purple-300 rounded-full text-sm font-semibold mb-4 border border-purple-200 dark:border-purple-800/50">
                  <span class="w-2 h-2 bg-purple-500 rounded-full mr-2"></span>
                  Licence 1
                </div>

                <h3 class="text-2xl font-bold text-slate-800 dark:text-white mb-3">
                  Développement d'Applications Internet et Intranet
                </h3>
                
                <div class="flex items-center text-slate-600 dark:text-slate-400 mb-4">
                  <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-purple-100 to-pink-100 dark:from-purple-900/30 dark:to-pink-900/30 flex items-center justify-center mr-3 border border-purple-200 dark:border-purple-800/50">
                    <svg class="w-4 h-4 text-purple-600 dark:text-purple-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
                    </svg>
                  </div>
                  <span class="font-medium">EMIT, Fianarantsoa</span>
                </div>

                <p class="text-slate-700 dark:text-slate-300 mb-4">
                  Introduction au développement web, initiation aux langages de programmation 
                  et découverte des technologies internet.
                </p>

                <!-- Skills Tags -->
                <div class="flex flex-wrap gap-2">
                  <span class="px-3 py-1 bg-gradient-to-r from-orange-50 to-orange-100 dark:from-slate-700 dark:to-slate-800 text-orange-700 dark:text-orange-300 rounded-full text-sm border border-orange-200 dark:border-slate-600">
                    HTML/CSS
                  </span>
                  <span class="px-3 py-1 bg-gradient-to-r from-cyan-50 to-cyan-100 dark:from-slate-700 dark:to-slate-800 text-cyan-700 dark:text-cyan-300 rounded-full text-sm border border-cyan-200 dark:border-slate-600">
                    Algorithmique
                  </span>
                  <span class="px-3 py-1 bg-gradient-to-r from-teal-50 to-teal-100 dark:from-slate-700 dark:to-slate-800 text-teal-700 dark:text-teal-300 rounded-full text-sm border border-teal-200 dark:border-slate-600">
                    Bases de données
                  </span>
                </div>
              </div>
            </div>
          </div>

          <!-- Timeline connector for mobile -->
          <div class="md:hidden absolute left-6 top-0 bottom-0 w-0.5 bg-gradient-to-b from-purple-300 to-pink-300 dark:from-purple-900 dark:to-pink-900 -z-10"></div>
        </div>
      </div>

      <!-- Graduation Summary -->
      <div class="mt-16 pt-8 border-t border-indigo-200 dark:border-slate-800">
        <div class="max-w-4xl mx-auto">
          <div class="bg-gradient-to-r from-indigo-50/80 to-teal-50/80 dark:from-slate-900 dark:to-slate-800 rounded-2xl p-6 sm:p-8 border border-indigo-100 dark:border-slate-700 backdrop-blur-sm">
            <div class="flex flex-col lg:flex-row items-center justify-between gap-8">
              <div class="text-center lg:text-left">
                <h3 class="text-2xl font-bold text-slate-800 dark:text-white mb-2">Parcours continu</h3>
                <p class="text-slate-700 dark:text-slate-300">
                  4 années d'études spécialisées en développement web et technologies de l'information
                </p>
              </div>
              <div class="w-full lg:w-auto">
                <div class="grid grid-cols-1 sm:grid-cols-3 gap-4 sm:gap-6">
                  <div class="text-center p-4 bg-white dark:bg-slate-800 rounded-xl shadow-sm border border-indigo-100 dark:border-slate-700">
                    <div class="text-3xl font-bold text-indigo-600 dark:text-indigo-400">4</div>
                    <div class="text-sm text-slate-600 dark:text-slate-400">Diplômes</div>
                  </div>
                  <div class="text-center p-4 bg-white dark:bg-slate-800 rounded-xl shadow-sm border border-teal-100 dark:border-slate-700">
                    <div class="text-3xl font-bold text-teal-600 dark:text-teal-400">1</div>
                    <div class="text-sm text-slate-600 dark:text-slate-400">Université</div>
                  </div>
                  <div class="text-center p-4 bg-white dark:bg-slate-800 rounded-xl shadow-sm border border-amber-100 dark:border-slate-700">
                    <div class="text-3xl font-bold text-amber-600 dark:text-amber-400">100%</div>
                    <div class="text-sm text-slate-600 dark:text-slate-400">Taux de réussite</div>
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
// Pas de logique particulière nécessaire pour ce composant
</script>

<style scoped>
/* Animation douce pour l'apparition */
section > * {
  animation: fadeInUp 0.6s ease-out;
}

@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Style pour les cartes au survol */
.bg-gradient-to-br {
  transition: all 0.3s ease;
}

.bg-gradient-to-br:hover {
  transform: translateY(-4px);
}
</style>