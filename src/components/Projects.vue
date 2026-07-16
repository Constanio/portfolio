<template>
  <section id="projects" class="py-16 bg-gradient-to-b from-blue-50 to-indigo-50/30 dark:from-slate-900 dark:to-slate-950 transition-colors duration-500">
    <div class="container mx-auto px-6">
      <!-- Section Header -->
      <div class="text-center mb-12">
        <div class="inline-block mb-4">
          <span class="text-indigo-600 dark:text-indigo-400 font-semibold text-sm uppercase tracking-wider">Mes réalisations</span>
          <div class="h-1 w-12 bg-gradient-to-r from-indigo-500 to-teal-500 mx-auto mt-2 rounded-full"></div>
        </div>
        <h2 class="text-4xl md:text-5xl font-bold text-slate-800 dark:text-white mb-4">
          Projets <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-600 to-teal-600 dark:from-indigo-400 dark:to-teal-400">personnels</span>
        </h2>
        <p class="text-slate-700 dark:text-slate-300 max-w-2xl mx-auto">
          Applications web complètes développées avec des technologies modernes
        </p>
      </div>

      <!-- Projects Grid -->
      <div class="max-w-6xl mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
          <ProjectCard 
            v-for="project in projects"
            :key="project.id"
            :title="project.title"
            :description="project.description"
            :technologies="project.technologies"
            :category="project.category"
            :demoLink="project.demoLink"
            :githubLink="project.githubLink"
          />
        </div>

        <!-- View More Projects -->
        <div class="mt-12 text-center">
          <a 
            href="https://github.com/Constanio" 
            target="_blank"
            class="inline-flex items-center px-6 py-3 bg-gradient-to-r from-white to-blue-50 dark:from-slate-800 dark:to-slate-700 text-indigo-700 dark:text-indigo-300 rounded-lg border-2 border-indigo-300 dark:border-indigo-800 hover:bg-gradient-to-r hover:from-indigo-50 hover:to-purple-50 dark:hover:from-indigo-900/30 dark:hover:to-purple-900/30 hover:border-indigo-400 dark:hover:border-indigo-600 transition-all duration-300 font-medium shadow-sm"
          >
            Voir plus sur GitHub
            <svg class="w-5 h-5 ml-2 text-indigo-600 dark:text-indigo-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14" />
            </svg>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import ProjectCard from './ProjectCard.vue'

const projects = [
  {
    id: 1,
    title: 'SIRH Flow',
    description: 'Système d\'information RH full-stack : interface de gestion moderne et API backend.',
    technologies: ['Vue.js', 'Go', 'Tailwind CSS'],
    category: 'Application Web',
    demoLink: 'https://sirhexamplefront.netlify.app/',
    githubLink: 'https://github.com/Constanio/SIRH_example_front',
  },
  {
    id: 2,
    title: 'Business Operations Dashboard',
    description: 'Application web dédiée à la gestion des opérations commerciales, permettant de suivre et analyser les activités en temps réel.',
    technologies: ['Vue.js', 'Go', 'PostgreSQL'],
    category: 'Application Web',
    demoLink: 'https://flowerp12.netlify.app/',
    githubLink: 'https://github.com/Constanio/front_flowerp',
  },
  {
    id: 3,
    title: 'BuildTrack',
    description: 'Plateforme de suivi de projets de construction : tableau de bord Vue et API .NET.',
    technologies: ['Vue.js', 'C#', 'ASP.NET'],
    category: 'Gestion',
    demoLink: '',
    githubLink: '',
  },
  {
    id: 4,
    title: 'KYC Golang',
    description: 'Backend pour automatiser et sécuriser la vérification d\'identité des utilisateurs (Know Your Customer).',
    technologies: ['Go'],
    category: 'Application Web',
    demoLink: '',
    githubLink: 'https://github.com/Constanio/KYC_golang',
  },
  {
    id: 5,
    title: 'Vavaka Katolika',
    description: 'Application mobile Flutter dédiée au contenu et à la pratique catholique.',
    technologies: ['Flutter', 'Dart'],
    category: 'Mobile',
    demoLink: '',
    githubLink: 'https://github.com/Constanio/vavaka-katolika',
  },
  {
    id: 6,
    title: 'Flutter Maïeutique',
    description: 'Application mobile Flutter autour de la méthode maïeutique et de l\'accompagnement pédagogique.',
    technologies: ['Flutter', 'Dart'],
    category: 'Mobile',
    demoLink: '',
    githubLink: 'https://github.com/Constanio/flutter_maieutique',
  },
  {
    id: 7,
    title: 'BI AutoML',
    description: 'Projet de Business Intelligence et AutoML : analyse de données et modèles prédictifs avec Jupyter Notebook.',
    technologies: ['Python', 'Jupyter', 'AutoML'],
    category: 'Business Intelligence',
    demoLink: '',
    githubLink: 'https://github.com/Constanio/BI_autoML',
  },
]
</script>

<style scoped>
/* Animation simple d'apparition */
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
</style>