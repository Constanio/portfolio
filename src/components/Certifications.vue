<template>
  <section id="certifications" class="py-16 bg-gradient-to-b from-indigo-50/30 to-blue-50">
    <div class="container mx-auto px-6">
      <!-- Section Header -->
      <div class="text-center mb-12">
        <div class="inline-block mb-4">
          <span class="text-indigo-600 font-semibold text-sm uppercase tracking-wider">Reconnaissances</span>
          <div class="h-1 w-12 bg-gradient-to-r from-indigo-500 to-teal-500 mx-auto mt-2 rounded-full"></div>
        </div>
        <h2 class="text-4xl md:text-5xl font-bold text-slate-800 mb-4">
          Mes <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-600 to-teal-600">certifications</span>
        </h2>
        <p class="text-slate-700 max-w-2xl mx-auto">
          Certifications et formations validant mes compétences techniques
        </p>
      </div>

      <!-- Certifications Grid -->
      <div class="max-w-4xl mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
          <!-- C# Certification -->
          <div class="bg-gradient-to-br from-white to-indigo-50 rounded-2xl shadow-lg p-6 hover:shadow-xl transition-all duration-300 border-l-4 border-indigo-500 border border-indigo-100">
            <div class="flex items-start mb-4">
              <div class="w-12 h-12 rounded-lg bg-gradient-to-r from-indigo-100 to-purple-100 flex items-center justify-center mr-4 border border-indigo-200">
                <span class="text-indigo-600 font-bold text-xl">C#</span>
              </div>
              <div>
                <h3 class="text-xl font-bold text-slate-800 mb-1">Résolution de problèmes en C#</h3>
                <div class="flex items-center">
                  <svg class="w-4 h-4 text-indigo-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                  </svg>
                  <p class="text-slate-600 text-sm">Coding Games</p>
                </div>
              </div>
            </div>
            
            <p class="text-slate-700 mb-4">
              Certification obtenue en résolvant des problèmes algorithmiques complexes en C#
            </p>
            
            <div class="flex items-center justify-between pt-4 border-t border-indigo-100">
              <div class="flex items-center">
                <svg class="w-5 h-5 text-emerald-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
                <span class="text-sm font-medium text-slate-700">Validé</span>
              </div>
              <span class="text-sm text-slate-500 bg-gradient-to-r from-slate-50 to-white px-3 py-1 rounded-lg border border-slate-200">2024</span>
            </div>
          </div>

          <!-- Golang Certification -->
          <div class="bg-gradient-to-br from-white to-teal-50 rounded-2xl shadow-lg p-6 hover:shadow-xl transition-all duration-300 border-l-4 border-teal-500 border border-teal-100">
            <div class="flex items-start mb-4">
              <div class="w-12 h-12 rounded-lg bg-gradient-to-r from-teal-100 to-emerald-100 flex items-center justify-center mr-4 border border-teal-200">
                <span class="text-teal-600 font-bold text-xl">Go</span>
              </div>
              <div>
                <h3 class="text-xl font-bold text-slate-800 mb-1">Résolution de problèmes en Go</h3>
                <div class="flex items-center">
                  <svg class="w-4 h-4 text-teal-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                  </svg>
                  <p class="text-slate-600 text-sm">Coding Games</p>
                </div>
              </div>
            </div>
            
            <p class="text-slate-700 mb-4">
              Certification en résolution de problèmes algorithmiques avec le langage Go
            </p>
            
            <div class="flex items-center justify-between pt-4 border-t border-teal-100">
              <div class="flex items-center">
                <svg class="w-5 h-5 text-emerald-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
                <span class="text-sm font-medium text-slate-700">Validé</span>
              </div>
              <span class="text-sm text-slate-500 bg-gradient-to-r from-slate-50 to-white px-3 py-1 rounded-lg border border-slate-200">2024</span>
            </div>
          </div>

          <!-- Power BI Certification -->
          <div class="md:col-span-2">
            <div class="bg-gradient-to-br from-white to-indigo-50 rounded-2xl shadow-lg p-6 hover:shadow-xl transition-all duration-300 border-l-4 border-purple-500 border border-indigo-100">
              <div class="flex flex-col md:flex-row md:items-center justify-between mb-6">
                <div class="flex items-start mb-4 md:mb-0">
                  <div class="w-12 h-12 rounded-lg bg-gradient-to-r from-purple-100 to-pink-100 flex items-center justify-center mr-4 border border-purple-200">
                    <svg class="w-6 h-6 text-purple-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
                    </svg>
                  </div>
                  <div>
                    <h3 class="text-xl font-bold text-slate-800 mb-1">Business Intelligence avec Power BI</h3>
                    <div class="flex items-center">
                      <svg class="w-4 h-4 text-purple-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
                      </svg>
                      <p class="text-slate-600 text-sm">IDEA ACADEMY</p>
                    </div>
                  </div>
                </div>
                <div class="flex items-center px-4 py-2 bg-gradient-to-r from-emerald-100 to-green-100 text-emerald-700 rounded-lg border border-emerald-200">
                  <svg class="w-5 h-5 text-emerald-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                  </svg>
                  <span class="text-sm font-medium">Certificat de formation</span>
                </div>
              </div>
              
              <p class="text-slate-700 mb-6">
                Formation complète en Business Intelligence avec maîtrise de l'outil Power BI pour 
                l'analyse de données, la création de rapports interactifs et de tableaux de bord.
              </p>
              
              <div class="flex flex-col md:flex-row md:items-center justify-between pt-4 border-t border-indigo-100">
                <div class="flex flex-wrap gap-2 mb-4 md:mb-0">
                  <span class="px-3 py-1.5 bg-gradient-to-r from-purple-50 to-purple-100 text-purple-700 rounded-lg text-sm font-medium border border-purple-200">
                    Power BI
                  </span>
                  <span class="px-3 py-1.5 bg-gradient-to-r from-indigo-50 to-indigo-100 text-indigo-700 rounded-lg text-sm font-medium border border-indigo-200">
                    Analyse de données
                  </span>
                  <span class="px-3 py-1.5 bg-gradient-to-r from-teal-50 to-teal-100 text-teal-700 rounded-lg text-sm font-medium border border-teal-200">
                    Visualisation
                  </span>
                  <span class="px-3 py-1.5 bg-gradient-to-r from-amber-50 to-amber-100 text-amber-700 rounded-lg text-sm font-medium border border-amber-200">
                    Tableaux de bord
                  </span>
                </div>
                <span class="text-sm text-slate-500 bg-gradient-to-r from-slate-50 to-white px-3 py-1 rounded-lg border border-slate-200">2024</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Skills Summary -->
        <div class="mt-12 pt-8 border-t border-indigo-200">
          <div class="text-center">
            <h3 class="text-2xl font-bold text-slate-800 mb-6">Compétences certifiées</h3>
            <div class="flex flex-col md:flex-row items-center justify-center gap-8">
              <div class="flex items-center p-4 rounded-xl bg-gradient-to-r from-indigo-50 to-purple-50 border border-indigo-200">
                <div class="w-3 h-3 bg-indigo-500 rounded-full mr-3"></div>
                <span class="font-medium text-slate-800">Résolution algorithmique</span>
              </div>
              <div class="flex items-center p-4 rounded-xl bg-gradient-to-r from-teal-50 to-emerald-50 border border-teal-200">
                <div class="w-3 h-3 bg-teal-500 rounded-full mr-3"></div>
                <span class="font-medium text-slate-800">Développement backend</span>
              </div>
              <div class="flex items-center p-4 rounded-xl bg-gradient-to-r from-purple-50 to-pink-50 border border-purple-200">
                <div class="w-3 h-3 bg-purple-500 rounded-full mr-3"></div>
                <span class="font-medium text-slate-800">Analyse de données</span>
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
/* Animation simple pour l'apparition */
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