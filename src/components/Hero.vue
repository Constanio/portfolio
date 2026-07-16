<template>
  <section id="home" class="relative pt-24 pb-16 md:pt-32 md:pb-24 overflow-hidden bg-gradient-to-br from-slate-50 to-blue-50 dark:from-slate-950 dark:to-slate-900 transition-colors duration-500">
    <!-- Background patterns/effects -->
    <div class="absolute inset-0 z-0">
      <div class="absolute top-0 left-0 w-64 h-64 bg-amber-100 dark:bg-amber-900/20 rounded-full -translate-x-1/2 -translate-y-1/2 blur-3xl opacity-60"></div>
      <div class="absolute bottom-0 right-0 w-96 h-96 bg-teal-100 dark:bg-teal-900/20 rounded-full translate-x-1/3 translate-y-1/3 blur-3xl opacity-40"></div>
      <div class="absolute top-1/2 left-1/4 w-32 h-32 bg-indigo-100 dark:bg-indigo-900/20 rounded-full blur-2xl animate-pulse opacity-50"></div>
    </div>

    <div class="container mx-auto px-6 relative z-10">
      <div class="flex flex-col md:flex-row items-center">
        <!-- Text content -->
        <div class="md:w-1/2 mb-12 md:mb-0 order-2 md:order-1 text-left">
          <!-- Badge/Chip -->
          <div class="inline-flex items-center px-4 py-2 bg-gradient-to-r from-amber-100 to-orange-100 dark:from-amber-900/30 dark:to-orange-900/30 text-amber-800 dark:text-amber-400 rounded-full mb-6 border border-amber-200 dark:border-amber-800/50 max-w-full">
            <span class="flex-shrink-0 w-2 h-2 bg-amber-500 rounded-full mr-2 animate-pulse"></span>
            <span class="text-xs sm:text-sm font-medium truncate">Développeur Full-Stack disponible</span>
          </div>

          <!-- Main title -->
          <h1 class="text-4xl md:text-6xl font-bold mb-6 break-words">
            <span class="block text-slate-800 dark:text-white mb-2">Rakotoarison</span>
            <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-600 to-teal-600 dark:from-indigo-400 dark:to-teal-400">
              Emerson Constanio
            </span>
          </h1>

          <!-- Subtitle -->
          <div class="relative mb-8">
            <div class="absolute -left-4 top-0 h-full w-1 bg-gradient-to-b from-indigo-400 to-teal-400 rounded-full"></div>
            <p class="text-xl md:text-2xl text-slate-700 dark:text-slate-300 pl-4 leading-relaxed">
              Je crée des <span class="font-semibold text-indigo-600 dark:text-indigo-400">applications web modernes</span> 
              avec Vue.js, .NET, Go et des architectures robustes
            </p>
          </div>

          <!-- CTA Buttons -->
          <div class="flex flex-col sm:flex-row gap-4 mb-10">
            <a 
              href="#contact" 
              class="group relative overflow-hidden bg-gradient-to-r from-indigo-600 to-teal-600 text-white px-8 py-4 text-lg font-semibold rounded-xl shadow-lg hover:shadow-xl transition-all duration-300 hover:-translate-y-1"
            >
              <span class="relative z-10">Me contacter</span>
              <div class="absolute inset-0 bg-gradient-to-r from-indigo-700 to-teal-700 opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
            </a>
            
            <a 
              href="#projects" 
              class="group bg-white dark:bg-slate-800 px-8 py-4 text-lg font-semibold rounded-xl border-2 border-indigo-600 text-indigo-600 dark:text-indigo-400 hover:bg-indigo-50 dark:hover:bg-slate-700 transition-all duration-300 hover:-translate-y-1 shadow-md"
            >
              <span class="flex items-center justify-center">
                Voir mes projets
                <svg class="w-5 h-5 ml-2 transform group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6" />
                </svg>
              </span>
            </a>
          </div>

          <!-- Social links & Contact -->
          <div class="space-y-4">
            <div class="flex flex-col sm:flex-row sm:items-center gap-4 sm:gap-6">
              <a 
                href="https://github.com/Constanio" 
                target="_blank"
                class="group flex items-center space-x-3 text-slate-700 dark:text-slate-300 hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors duration-300"
              >
                <div class="flex-shrink-0 w-12 h-12 rounded-xl bg-white dark:bg-slate-800 shadow-md group-hover:bg-indigo-50 dark:group-hover:bg-slate-700 flex items-center justify-center transition-all duration-300 group-hover:scale-110 border border-slate-200 dark:border-slate-700">
                  <svg class="w-6 h-6 group-hover:text-indigo-600 dark:group-hover:text-indigo-400" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                    <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd" />
                  </svg>
                </div>
                <div class="min-w-0">
                  <div class="font-medium text-slate-700 dark:text-slate-300">GitHub</div>
                  <div class="text-sm text-slate-500 dark:text-slate-400 truncate">@Constanio</div>
                </div>
              </a>

              <a 
                href="https://www.linkedin.com/in/rakotoarison-emerson-constanio-31295426a/" 
                target="_blank"
                rel="noopener noreferrer"
                class="group flex items-center space-x-3 text-slate-700 dark:text-slate-300 hover:text-blue-600 dark:hover:text-blue-400 transition-colors duration-300"
              >
                <div class="flex-shrink-0 w-12 h-12 rounded-xl bg-white dark:bg-slate-800 shadow-md group-hover:bg-blue-50 dark:group-hover:bg-slate-700 flex items-center justify-center transition-all duration-300 group-hover:scale-110 border border-slate-200 dark:border-slate-700">
                  <svg class="w-6 h-6 group-hover:text-blue-600 dark:group-hover:text-blue-400" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                    <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                  </svg>
                </div>
                <div class="min-w-0">
                  <div class="font-medium text-slate-700 dark:text-slate-300">LinkedIn</div>
                  <div class="text-sm text-slate-500 dark:text-slate-400 truncate">Rakotoarison Emerson</div>
                </div>
              </a>
              
              <a 
                href="mailto:emersonconstanio2@gmail.com" 
                class="group flex items-center space-x-3 text-slate-700 dark:text-slate-300 hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors duration-300"
              >
                <div class="flex-shrink-0 w-12 h-12 rounded-xl bg-white dark:bg-slate-800 shadow-md group-hover:bg-indigo-50 dark:group-hover:bg-slate-700 flex items-center justify-center transition-all duration-300 group-hover:scale-110 border border-slate-200 dark:border-slate-700">
                  <svg class="w-6 h-6 group-hover:text-indigo-600 dark:group-hover:text-indigo-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                  </svg>
                </div>
                <div class="min-w-0">
                  <div class="font-medium text-slate-700 dark:text-slate-300">Email</div>
                  <div class="text-sm text-slate-500 dark:text-slate-400 truncate">emersonconstanio2@gmail.com</div>
                </div>
              </a>
            </div>
            
            <div class="flex items-center text-sm text-slate-600 dark:text-slate-400 bg-white/70 dark:bg-slate-800/70 backdrop-blur-sm rounded-lg p-3 border border-slate-200 dark:border-slate-700">
              <svg class="w-4 h-4 mr-2 text-indigo-500 dark:text-indigo-400" fill="currentColor" viewBox="0 0 24 24">
                <path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5a2.5 2.5 0 010-5 2.5 2.5 0 010 5z"/>
              </svg>
              <span>Basé à Madagascar • Disponible pour missions freelance & CDI</span>
            </div>
          </div>
        </div>

        <!-- Photo/Avatar section -->
        <div class="md:w-1/2 flex justify-center order-1 md:order-2 mb-12 md:mb-0">
          <div class="relative">
            <!-- Main avatar container -->
            <div class="relative z-10">
              <div class="relative w-64 h-64 sm:w-72 sm:h-72 md:w-96 md:h-96">
                <!-- Outer glow ring -->
                <div class="absolute inset-0 bg-gradient-to-r from-indigo-400 to-teal-400 rounded-full animate-spin-slow opacity-20 blur-xl"></div>
                
                <!-- Main avatar circle with gradient border -->
                <div class="absolute inset-3 sm:inset-4 bg-gradient-to-r from-indigo-500 to-teal-500 rounded-full p-1 border-4 border-white/20 shadow-2xl">
                  <!-- Inner circle avec PHOTO -->
                  <div class="w-full h-full bg-gradient-to-br from-blue-50 to-indigo-50 dark:from-slate-800 dark:to-slate-900 rounded-full flex items-center justify-center overflow-hidden">
                    <!-- Votre photo de profil -->
                    <div class="relative w-full h-full">
                      <!-- Photo principale -->
                      <img 
                        src="../assets/sans.png" 
                        alt="Rakotoarison Emerson Constanio"
                        class="w-full h-full object-cover"
                      />
                      <!-- Overlay effect -->
                      <div class="absolute inset-0 bg-gradient-to-t from-indigo-500/10 to-transparent rounded-full"></div>
                    </div>
                  </div>
                </div>
                
                <!-- Floating elements around avatar -->
                <div class="absolute -top-2 -right-2 sm:-top-4 sm:-right-4 w-12 h-12 sm:w-16 sm:h-16 bg-gradient-to-r from-amber-100 to-orange-100 dark:from-amber-900 dark:to-orange-900 rounded-2xl shadow-2xl flex items-center justify-center animate-float-slow border-2 border-amber-200 dark:border-amber-800">
                  <div class="text-amber-800 dark:text-amber-200 font-bold text-[10px] sm:text-sm">Vue.js</div>
                </div>
                
                <div class="absolute -bottom-4 -left-2 sm:-bottom-6 sm:-left-4 w-14 h-14 sm:w-20 sm:h-20 bg-gradient-to-r from-teal-100 to-emerald-100 dark:from-teal-900 dark:to-emerald-900 rounded-2xl shadow-2xl flex items-center justify-center animate-float-slow delay-300 border-2 border-teal-200 dark:border-teal-800">
                  <div class="text-teal-800 dark:text-teal-200 font-bold text-[10px] sm:text-sm">.NET</div>
                </div>
                
                <div class="absolute top-1/2 -right-4 sm:-right-8 w-10 h-10 sm:w-14 sm:h-14 bg-gradient-to-r from-indigo-100 to-purple-100 dark:from-indigo-900 dark:to-purple-900 rounded-2xl shadow-2xl flex items-center justify-center animate-float delay-500 border-2 border-indigo-200 dark:border-indigo-800">
                  <div class="text-indigo-800 dark:text-indigo-200 font-bold text-[8px] sm:text-xs">Go</div>
                </div>
              </div>
            </div>
            
            <!-- Availability badge with animation -->
            <div class="absolute -bottom-4 right-4 sm:-bottom-6 sm:right-8 z-20">
              <div class="relative">
                <div class="bg-gradient-to-r from-emerald-50 to-teal-50 dark:from-emerald-950 dark:to-teal-950 px-4 py-2 sm:px-6 sm:py-3 rounded-xl shadow-2xl hover:shadow-3xl transition-all duration-300 hover:-translate-y-1 border-2 border-emerald-200 dark:border-emerald-800">
                  <div class="flex items-center space-x-2">
                    <div class="relative">
                      <div class="w-2 h-2 sm:w-3 sm:h-3 bg-emerald-500 rounded-full animate-ping absolute opacity-75"></div>
                      <div class="w-2 h-2 sm:w-3 sm:h-3 bg-emerald-500 rounded-full relative"></div>
                    </div>
                    <div>
                      <div class="text-[10px] sm:text-xs text-slate-600 dark:text-slate-400">Disponible pour</div>
                      <div class="text-xs sm:text-base font-bold text-emerald-700 dark:text-emerald-400">Nouveaux projets</div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>

      <!-- Tech stack indicators -->
      <div class="mt-20 pt-8 border-t border-slate-200/50 dark:border-slate-800">
        <div class="flex flex-col md:flex-row items-center justify-between">
          <div class="text-sm text-slate-600 dark:text-slate-400 mb-4 md:mb-0 font-medium">
            Stack technique principale
          </div>
          <div class="flex flex-wrap gap-3">
            <div v-for="tech in techStack" :key="tech"
                 class="px-4 py-2 bg-white/90 dark:bg-slate-800/90 backdrop-blur-sm rounded-lg shadow-sm hover:shadow-md hover:-translate-y-1 transition-all duration-300 border border-slate-100 dark:border-slate-700">
              <div class="flex items-center space-x-2">
                <div class="w-2 h-2 rounded-full bg-gradient-to-r from-indigo-500 to-teal-500"></div>
                <span class="font-medium text-slate-800 dark:text-slate-200">{{ tech }}</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const techStack = ['Vue.js', 'Nuxt.js', 'React.js', 'ASP.NET', 'Golang', 'PostgreSQL', 'Docker', 'Tailwind CSS']
</script>

<style scoped>
@keyframes gradient {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

.animate-gradient {
  background-size: 200% 200%;
  animation: gradient 3s ease infinite;
}

@keyframes spin-slow {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

.animate-spin-slow {
  animation: spin-slow 20s linear infinite;
}

@keyframes float-slow {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-15px); }
}

.animate-float-slow {
  animation: float-slow 5s ease-in-out infinite;
}

@keyframes fade-in {
  from { opacity: 0; transform: translateY(10px); }
  to { opacity: 1; transform: translateY(0); }
}

.animate-fade-in {
  animation: fade-in 0.8s ease-out;
}
</style>