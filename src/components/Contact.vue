<template>
  <section id="contact" class="py-16 bg-gradient-to-b from-blue-50 to-indigo-50/30 dark:from-slate-950 dark:to-slate-900 transition-colors duration-500">
    <div class="container mx-auto px-6">
      <!-- Section Header -->
      <div class="text-center mb-12">
        <div class="inline-block mb-4">
          <span class="text-indigo-600 dark:text-indigo-400 font-semibold text-sm uppercase tracking-wider">Prenez contact</span>
          <div class="h-1 w-12 bg-gradient-to-r from-indigo-500 to-teal-500 mx-auto mt-2 rounded-full"></div>
        </div>
        <h2 class="text-4xl md:text-5xl font-bold text-slate-800 dark:text-white mb-4">
          Contactez<span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-600 to-teal-600 dark:from-indigo-400 dark:to-teal-400">-moi</span>
        </h2>
        <p class="text-slate-700 dark:text-slate-300 max-w-2xl mx-auto">
          Ouvert aux opportunités de stage, CDD ou CDI en développement web full-stack
        </p>
      </div>

      <!-- Contact Container -->
      <div class="max-w-4xl mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          <!-- Contact Information -->
          <div>
            <div class="bg-gradient-to-br from-white to-indigo-50 dark:from-slate-800 dark:to-slate-900 rounded-2xl shadow-lg p-8 mb-8 border border-indigo-100 dark:border-slate-700">
              <h3 class="text-2xl font-bold text-slate-800 dark:text-white mb-6 flex items-center">
                <svg class="w-6 h-6 text-indigo-600 dark:text-indigo-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                </svg>
                Informations de contact
              </h3>
              
              <div class="space-y-6">
                <!-- Phone -->
                <a href="tel:0340831979" class="flex items-center p-4 rounded-xl border border-indigo-100 dark:border-slate-700 hover:border-indigo-300 dark:hover:border-indigo-500 hover:shadow-md transition-all duration-300 group bg-white/50 dark:bg-slate-800/50">
                  <div class="flex-shrink-0 w-12 h-12 rounded-lg bg-gradient-to-r from-indigo-50 to-purple-50 dark:from-indigo-900/30 dark:to-purple-900/30 flex items-center justify-center mr-4 group-hover:bg-indigo-100 dark:group-hover:bg-indigo-900 transition-colors border border-indigo-200 dark:border-indigo-800/50">
                    <svg class="w-6 h-6 text-indigo-600 dark:text-indigo-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                    </svg>
                  </div>
                  <div class="flex-1">
                    <div class="font-medium text-slate-700 dark:text-slate-300">Téléphone</div>
                    <div class="text-slate-900 dark:text-white text-lg font-semibold group-hover:text-indigo-600 dark:group-hover:text-indigo-400 transition-colors">0340831979</div>
                  </div>
                </a>

                <!-- Email -->
                <a href="mailto:emersonconstanio2@gmail.com" class="flex items-center p-4 rounded-xl border border-indigo-100 dark:border-slate-700 hover:border-indigo-300 dark:hover:border-indigo-500 hover:shadow-md transition-all duration-300 group bg-white/50 dark:bg-slate-800/50 overflow-hidden">
                  <div class="flex-shrink-0 w-12 h-12 rounded-lg bg-gradient-to-r from-teal-50 to-emerald-50 dark:from-teal-900/30 dark:to-emerald-900/30 flex items-center justify-center mr-4 group-hover:bg-teal-100 dark:group-hover:bg-teal-900 transition-colors border border-teal-200 dark:border-teal-800/50">
                    <svg class="w-6 h-6 text-teal-600 dark:text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                    </svg>
                  </div>
                  <div class="flex-1 min-w-0">
                    <div class="font-medium text-slate-700 dark:text-slate-300">Email</div>
                    <div class="text-slate-900 dark:text-white text-base sm:text-lg font-semibold group-hover:text-teal-600 dark:group-hover:text-teal-400 transition-colors break-all sm:break-normal">emersonconstanio2@gmail.com</div>
                  </div>
                </a>

                <!-- GitHub -->
                <a href="https://github.com/Constanio" target="_blank" class="flex items-center p-4 rounded-xl border border-indigo-100 dark:border-slate-700 hover:border-indigo-300 dark:hover:border-indigo-500 hover:shadow-md transition-all duration-300 group bg-white/50 dark:bg-slate-800/50 overflow-hidden">
                  <div class="flex-shrink-0 w-12 h-12 rounded-lg bg-gradient-to-r from-slate-50 to-gray-50 dark:from-slate-800 dark:to-slate-700 flex items-center justify-center mr-4 group-hover:bg-slate-100 dark:group-hover:bg-slate-600 transition-colors border border-slate-200 dark:border-slate-700">
                    <svg class="w-6 h-6 text-slate-600 dark:text-slate-400 group-hover:text-indigo-600 dark:group-hover:text-indigo-400" fill="currentColor" viewBox="0 0 24 24">
                      <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <div class="flex-1 min-w-0">
                    <div class="font-medium text-slate-700 dark:text-slate-300">GitHub</div>
                    <div class="text-slate-900 dark:text-white text-base sm:text-lg font-semibold group-hover:text-indigo-600 dark:group-hover:text-indigo-400 transition-colors truncate">Constanio</div>
                  </div>
                </a>

                <!-- LinkedIn -->
                <a href="https://www.linkedin.com/in/rakotoarison-emerson-constanio-31295426a/" target="_blank" rel="noopener noreferrer" class="flex items-center p-4 rounded-xl border border-indigo-100 dark:border-slate-700 hover:border-blue-300 dark:hover:border-blue-500 hover:shadow-md transition-all duration-300 group bg-white/50 dark:bg-slate-800/50 overflow-hidden">
                  <div class="flex-shrink-0 w-12 h-12 rounded-lg bg-gradient-to-r from-blue-50 to-sky-50 dark:from-blue-900/30 dark:to-sky-900/30 flex items-center justify-center mr-4 group-hover:bg-blue-100 dark:group-hover:bg-blue-900 transition-colors border border-blue-200 dark:border-blue-800/50">
                    <svg class="w-6 h-6 text-blue-600 dark:text-blue-400" fill="currentColor" viewBox="0 0 24 24">
                      <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                    </svg>
                  </div>
                  <div class="flex-1 min-w-0">
                    <div class="font-medium text-slate-700 dark:text-slate-300">LinkedIn</div>
                    <div class="text-slate-900 dark:text-white text-base sm:text-lg font-semibold group-hover:text-blue-600 dark:group-hover:text-blue-400 transition-colors truncate">Rakotoarison Emerson</div>
                  </div>
                </a>
              </div>
            </div>

            <!-- Availability Status -->
            <div class="bg-gradient-to-r from-indigo-600 to-teal-600 rounded-2xl shadow-xl p-8 text-white relative overflow-hidden">
              <div class="absolute top-0 right-0 w-24 h-24 bg-white/10 rounded-full -translate-y-8 translate-x-8"></div>
              <div class="relative z-10">
                <div class="flex items-center mb-4">
                  <div class="relative mr-4">
                    <div class="w-3 h-3 bg-emerald-300 rounded-full animate-ping absolute opacity-75"></div>
                    <div class="w-3 h-3 bg-emerald-300 rounded-full relative"></div>
                  </div>
                  <div class="font-semibold text-lg">Actuellement disponible</div>
                </div>
                <p class="text-white/90 mb-4">
                  Je suis ouvert aux discussions concernant des projets freelance, 
                  des opportunités de stage, CDD ou CDI.
                </p>
                <div class="flex items-center text-sm text-white/80">
                  <svg class="w-4 h-4 mr-2" fill="currentColor" viewBox="0 0 24 24">
                    <path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5a2.5 2.5 0 010-5 2.5 2.5 0 010 5z"/>
                  </svg>
                  <span>Basé à Madagascar, disponible pour travail remote</span>
                </div>
              </div>
            </div>
          </div>

          <!-- Contact Form -->
          <div>
            <div class="bg-gradient-to-br from-white to-indigo-50 dark:from-slate-800 dark:to-slate-900 rounded-2xl shadow-lg p-8 border border-indigo-100 dark:border-slate-700">
              <h3 class="text-2xl font-bold text-slate-800 dark:text-white mb-6 flex items-center">
                <svg class="w-6 h-6 text-indigo-600 dark:text-indigo-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 10h.01M12 10h.01M16 10h.01M9 16H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-5l-5 5v-5z" />
                </svg>
                Envoyez-moi un message
              </h3>
              
              <form 
                @submit.prevent="handleSubmit" 
                name="contact" 
                method="POST" 
                data-netlify="true" 
                class="space-y-6"
              >
                <input type="hidden" name="form-name" value="contact" />
                <!-- Name -->
                <div>
                  <label for="name" class="block text-slate-800 dark:text-slate-200 font-medium mb-2 flex items-center">
                    <svg class="w-4 h-4 mr-2 text-indigo-600 dark:text-indigo-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" />
                    </svg>
                    Nom complet <span class="text-red-500 ml-1">*</span>
                  </label>
                  <input 
                    id="name"
                    v-model="form.name"
                    type="text" 
                    required
                    class="w-full px-4 py-3 border border-indigo-200 dark:border-slate-700 rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-transparent transition-all bg-white/50 dark:bg-slate-800 dark:text-white"
                    placeholder="Votre nom"
                  >
                </div>

                <!-- Email -->
                <div>
                  <label for="email" class="block text-slate-800 dark:text-slate-200 font-medium mb-2 flex items-center">
                    <svg class="w-4 h-4 mr-2 text-teal-600 dark:text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                    </svg>
                    Adresse email <span class="text-red-500 ml-1">*</span>
                  </label>
                  <input 
                    id="email"
                    v-model="form.email"
                    type="email" 
                    required
                    class="w-full px-4 py-3 border border-indigo-200 dark:border-slate-700 rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-transparent transition-all bg-white/50 dark:bg-slate-800 dark:text-white"
                    placeholder="votre@email.com"
                  >
                </div>

                <!-- Subject -->
                <div>
                  <label for="subject" class="block text-slate-800 dark:text-slate-200 font-medium mb-2 flex items-center">
                    <svg class="w-4 h-4 mr-2 text-amber-600 dark:text-amber-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 7h.01M7 3h5c.512 0 1.024.195 1.414.586l7 7a2 2 0 010 2.828l-7 7a2 2 0 01-2.828 0l-7-7A1.994 1.994 0 013 12V7a4 4 0 014-4z" />
                    </svg>
                    Sujet
                  </label>
                  <input 
                    id="subject"
                    v-model="form.subject"
                    type="text" 
                    class="w-full px-4 py-3 border border-indigo-200 dark:border-slate-700 rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-transparent transition-all bg-white/50 dark:bg-slate-800 dark:text-white"
                    placeholder="Objet de votre message"
                  >
                </div>

                <!-- Message -->
                <div>
                  <label for="message" class="block text-slate-800 dark:text-slate-200 font-medium mb-2 flex items-center">
                    <svg class="w-4 h-4 mr-2 text-purple-600 dark:text-purple-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z" />
                    </svg>
                    Message <span class="text-red-500 ml-1">*</span>
                  </label>
                  <textarea 
                    id="message"
                    v-model="form.message"
                    rows="4"
                    required
                    class="w-full px-4 py-3 border border-indigo-200 dark:border-slate-700 rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-transparent transition-all resize-none bg-white/50 dark:bg-slate-800 dark:text-white"
                    placeholder="Décrivez votre projet ou votre demande..."
                  ></textarea>
                </div>

                <!-- Submit Button -->
                <button 
                  type="submit" 
                  :disabled="isSubmitting"
                  class="w-full py-3 px-6 bg-gradient-to-r from-indigo-600 to-teal-600 text-white font-semibold rounded-lg hover:from-indigo-700 hover:to-teal-700 transition-all duration-300 disabled:opacity-50 disabled:cursor-not-allowed shadow-md hover:shadow-lg flex items-center justify-center"
                >
                  <span v-if="!isSubmitting" class="flex items-center">
                    Envoyer le message
                    <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8" />
                    </svg>
                  </span>
                  <span v-else class="flex items-center justify-center">
                    <svg class="animate-spin h-5 w-5 mr-3 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24">
                      <circle class="opacity-25" cx="12" cy="12" r="10" stroke="currentColor" stroke-width="4"></circle>
                      <path class="opacity-75" fill="currentColor" d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4zm2 5.291A7.962 7.962 0 014 12H0c0 3.042 1.135 5.824 3 7.938l3-2.647z"></path>
                    </svg>
                    Envoi en cours...
                  </span>
                </button>

                <!-- Success Message -->
                <div v-if="submitSuccess" class="p-4 bg-gradient-to-r from-emerald-50 to-green-50 dark:from-emerald-900/30 dark:to-green-900/30 border border-emerald-200 dark:border-emerald-800 rounded-lg">
                  <div class="flex items-center">
                    <svg class="w-5 h-5 text-emerald-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                    </svg>
                    <div>
                      <div class="font-medium text-emerald-800 dark:text-emerald-400">Message envoyé avec succès !</div>
                      <div class="text-emerald-700 dark:text-emerald-500 text-sm">Je vous répondrai dans les plus brefs délais.</div>
                    </div>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { ref, reactive } from 'vue'

// Form state
const form = reactive({
  name: '',
  email: '',
  subject: '',
  message: ''
})

const isSubmitting = ref(false)
const submitSuccess = ref(false)

const handleSubmit = async () => {
  isSubmitting.value = true
  
  // Simuler l'envoi du formulaire
  await new Promise(resolve => setTimeout(resolve, 1500))
  
  // Réinitialiser le formulaire
  form.name = ''
  form.email = ''
  form.subject = ''
  form.message = ''
  
  isSubmitting.value = false
  submitSuccess.value = true
  
  // Masquer le message de succès après 5 secondes
  setTimeout(() => {
    submitSuccess.value = false
  }, 5000)
}
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

/* Style pour les champs de formulaire au focus */
input:focus, textarea:focus {
  box-shadow: 0 0 0 3px rgba(99, 102, 241, 0.1);
}
</style>