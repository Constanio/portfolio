<template>
  <section id="about" class="py-20 bg-gradient-to-b from-blue-50 to-indigo-50/30">
    <div class="container mx-auto px-6">
      <!-- Section Header -->
      <div class="text-center mb-16">
        <div class="inline-block mb-4">
          <span class="text-indigo-600 font-semibold text-sm uppercase tracking-wider">Introduction</span>
          <div class="h-1 w-12 bg-gradient-to-r from-indigo-500 to-teal-500 mx-auto mt-2 rounded-full"></div>
        </div>
        <h2 class="text-4xl md:text-5xl font-bold text-slate-800 mb-6">
          À propos de <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-600 to-teal-600">moi</span>
        </h2>
        <p class="text-xl text-slate-700 max-w-2xl mx-auto leading-relaxed">
          Développeur full-stack passionné par la création d'applications web modernes et performantes.
        </p>
      </div>

      <!-- Main Content -->
      <div class="max-w-6xl mx-auto">
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
          <!-- Profile Card -->
          <div class="lg:col-span-2 space-y-8">
            <!-- Main Description -->
            <div class="bg-gradient-to-br from-white to-blue-50 rounded-2xl shadow-lg p-8 border border-blue-100">
              <div class="flex items-start mb-6">
                <div class="w-16 h-16 bg-gradient-to-br from-indigo-100 to-teal-100 rounded-xl flex items-center justify-center mr-6 border border-indigo-200">
                  <span class="text-2xl text-indigo-600">👨‍💻</span>
                </div>
                <div>
                  <h3 class="text-2xl font-bold text-slate-800 mb-3">Mon parcours</h3>
                  <p class="text-slate-700 leading-relaxed">
                    Développeur motivé et en début de carrière, passionné par la création d'applications 
                    web et logicielles. Je maîtrise les technologies modernes pour développer des solutions 
                    fonctionnelles et efficaces. Toujours enthousiaste à l'idée d'apprendre et de contribuer 
                    à des projets innovants.
                  </p>
                </div>
              </div>
              
              <!-- Key Attributes -->
              <div class="grid grid-cols-2 md:grid-cols-4 gap-4 mt-8 pt-8 border-t border-blue-100">
                <div class="text-center p-4 bg-gradient-to-b from-indigo-50 to-white rounded-xl border border-indigo-100">
                  <div class="text-2xl font-bold text-indigo-600 mb-2">2+</div>
                  <div class="text-sm text-slate-600">Années d'expérience</div>
                </div>
                <div class="text-center p-4 bg-gradient-to-b from-teal-50 to-white rounded-xl border border-teal-100">
                  <div class="text-2xl font-bold text-teal-600 mb-2">10+</div>
                  <div class="text-sm text-slate-600">Projets réalisés</div>
                </div>
                <div class="text-center p-4 bg-gradient-to-b from-amber-50 to-white rounded-xl border border-amber-100">
                  <div class="text-2xl font-bold text-amber-600 mb-2">5+</div>
                  <div class="text-sm text-slate-600">Technologies</div>
                </div>
                <div class="text-center p-4 bg-gradient-to-b from-purple-50 to-white rounded-xl border border-purple-100">
                  <div class="text-2xl font-bold text-purple-600 mb-2">3</div>
                  <div class="text-sm text-slate-600">Langues parlées</div>
                </div>
              </div>
            </div>

            <!-- Contact Information -->
            <div class="bg-gradient-to-br from-white to-blue-50 rounded-2xl shadow-lg p-8 border border-blue-100">
              <h3 class="text-2xl font-bold text-slate-800 mb-6">Contact</h3>
              <div class="space-y-6">
                <a href="tel:0340831979" class="flex items-center p-4 rounded-xl border border-blue-100 hover:border-indigo-300 hover:shadow-md transition-all duration-300 group bg-white/50">
                  <div class="w-12 h-12 rounded-lg bg-gradient-to-br from-indigo-50 to-blue-50 flex items-center justify-center mr-4 group-hover:bg-indigo-100 transition-colors border border-indigo-100">
                    <span class="text-indigo-600 text-xl">📱</span>
                  </div>
                  <div class="flex-1">
                    <div class="font-medium text-slate-700">Téléphone</div>
                    <div class="text-slate-900 text-lg font-semibold group-hover:text-indigo-600 transition-colors">0340831979</div>
                  </div>
                </a>

                <a href="mailto:emersonconstanio2@gmail.com" class="flex items-center p-4 rounded-xl border border-blue-100 hover:border-indigo-300 hover:shadow-md transition-all duration-300 group bg-white/50">
                  <div class="w-12 h-12 rounded-lg bg-gradient-to-br from-teal-50 to-cyan-50 flex items-center justify-center mr-4 group-hover:bg-teal-100 transition-colors border border-teal-100">
                    <span class="text-teal-600 text-xl">✉️</span>
                  </div>
                  <div class="flex-1">
                    <div class="font-medium text-slate-700">Email</div>
                    <div class="text-slate-900 text-lg font-semibold group-hover:text-teal-600 transition-colors">emersonconstanio2@gmail.com</div>
                  </div>
                </a>

                <a href="https://github.com/RakotoarisoEConstanio_" target="_blank" class="flex items-center p-4 rounded-xl border border-blue-100 hover:border-indigo-300 hover:shadow-md transition-all duration-300 group bg-white/50">
                  <div class="w-12 h-12 rounded-lg bg-gradient-to-br from-slate-50 to-gray-50 flex items-center justify-center mr-4 group-hover:bg-slate-100 transition-colors border border-slate-100">
                    <svg class="w-6 h-6 text-slate-700 group-hover:text-indigo-600" fill="currentColor" viewBox="0 0 24 24">
                      <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <div class="flex-1">
                    <div class="font-medium text-slate-700">GitHub</div>
                    <div class="text-slate-900 text-lg font-semibold group-hover:text-indigo-600 transition-colors">RakotoarisoEConstanio_</div>
                  </div>
                </a>
              </div>
            </div>
          </div>

          <!-- Languages & Quick Facts -->
          <div class="space-y-8">
            <!-- Languages Card -->
            <div class="bg-gradient-to-br from-white to-indigo-50 rounded-2xl shadow-lg p-8 border border-indigo-100">
              <h3 class="text-2xl font-bold text-slate-800 mb-6 flex items-center">
                <svg class="w-6 h-6 mr-2 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5h12M9 3v2m1.048 9.5A18.022 18.022 0 016.412 9m6.088 9h7M11 21l5-10 5 10M12.751 5C11.783 10.77 8.07 15.61 3 18.129" />
                </svg>
                Langues
              </h3>
              <div class="space-y-6">
                <div v-for="(language, index) in languages" :key="index" class="space-y-2">
                  <div class="flex justify-between items-center">
                    <span class="font-medium text-slate-800">{{ language.name }}</span>
                    <span class="px-3 py-1 bg-gradient-to-r from-indigo-100 to-teal-100 text-indigo-700 rounded-full text-sm font-semibold border border-indigo-200">
                      {{ language.level }}
                    </span>
                  </div>
                  <div class="h-2 bg-slate-200 rounded-full overflow-hidden">
                    <div 
                      class="h-full bg-gradient-to-r from-indigo-500 to-teal-500 rounded-full transition-all duration-1000"
                      :style="{ width: language.percentage }"
                    ></div>
                  </div>
                </div>
              </div>
            </div>

            <!-- Availability Card -->
            <div class="bg-gradient-to-br from-indigo-600 to-teal-600 rounded-2xl shadow-xl p-8 text-white relative overflow-hidden">
              <div class="absolute top-0 right-0 w-24 h-24 bg-white/10 rounded-full -translate-y-8 translate-x-8"></div>
              <div class="relative z-10">
                <div class="flex items-center mb-6">
                  <div class="w-12 h-12 bg-white/20 rounded-xl flex items-center justify-center mr-4 backdrop-blur-sm">
                    <span class="text-xl">💼</span>
                  </div>
                  <div>
                    <h3 class="text-2xl font-bold">Disponibilité</h3>
                    <p class="text-white/90 text-sm">Statut actuel</p>
                  </div>
                </div>
                
                <div class="flex items-center mb-4">
                  <div class="relative mr-3">
                    <div class="w-3 h-3 bg-emerald-300 rounded-full animate-ping absolute opacity-75"></div>
                    <div class="w-3 h-3 bg-emerald-300 rounded-full relative"></div>
                  </div>
                  <div class="font-semibold">Disponible pour de nouvelles opportunités</div>
                </div>
                
                <p class="text-white/80 text-sm mb-6">
                  Ouvert aux projets freelance, CDD ou CDI dans le développement web full-stack.
                </p>
                
                <a 
                  href="#contact" 
                  class="block w-full text-center py-3 px-6 bg-white text-indigo-600 font-semibold rounded-lg hover:bg-slate-100 transition-colors duration-300 shadow-md"
                >
                  Me contacter
                </a>
              </div>
            </div>

            <!-- Personal Traits -->
            <div class="bg-gradient-to-br from-white to-amber-50 rounded-2xl shadow-lg p-8 border border-amber-100">
              <h3 class="text-2xl font-bold text-slate-800 mb-6 flex items-center">
                <svg class="w-6 h-6 mr-2 text-amber-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
                Qualités
              </h3>
              <div class="space-y-4">
                <div class="flex items-center p-3 rounded-lg bg-gradient-to-r from-amber-50 to-orange-50 border border-amber-100">
                  <div class="w-10 h-10 rounded-lg bg-gradient-to-br from-amber-100 to-orange-100 flex items-center justify-center mr-4 border border-amber-200">
                    <span class="text-amber-600 text-lg">🎯</span>
                  </div>
                  <div>
                    <div class="font-medium text-slate-800">Passionné</div>
                    <div class="text-sm text-slate-600">Toujours en apprentissage</div>
                  </div>
                </div>
                <div class="flex items-center p-3 rounded-lg bg-gradient-to-r from-teal-50 to-emerald-50 border border-teal-100">
                  <div class="w-10 h-10 rounded-lg bg-gradient-to-br from-teal-100 to-emerald-100 flex items-center justify-center mr-4 border border-teal-200">
                    <span class="text-teal-600 text-lg">⚡</span>
                  </div>
                  <div>
                    <div class="font-medium text-slate-800">Rapide d'exécution</div>
                    <div class="text-sm text-slate-600">Délais respectés</div>
                  </div>
                </div>
                <div class="flex items-center p-3 rounded-lg bg-gradient-to-r from-indigo-50 to-purple-50 border border-indigo-100">
                  <div class="w-10 h-10 rounded-lg bg-gradient-to-br from-indigo-100 to-purple-100 flex items-center justify-center mr-4 border border-indigo-200">
                    <span class="text-indigo-600 text-lg">🤝</span>
                  </div>
                  <div>
                    <div class="font-medium text-slate-800">Collaboratif</div>
                    <div class="text-sm text-slate-600">Excellent travail d'équipe</div>
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
const languages = [
  { name: 'Malagasy', level: 'Natif', percentage: '100%' },
  { name: 'Français', level: 'Courant', percentage: '90%' },
  { name: 'Anglais', level: 'Intermédiaire', percentage: '70%' }
]
</script>

<style scoped>
/* Animations minimales et élégantes */
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

section {
  animation: fadeIn 0.6s ease-out;
}

/* Effet de survol amélioré */
.bg-gradient-to-br {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.bg-gradient-to-br:hover {
  transform: translateY(-4px);
}
</style>