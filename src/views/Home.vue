<template>
    <PageLayout>
        <Hero :projectName="projectName" :projectLogo="projectLogo" :projectDescription="projectDescription"
            :projectStack="projectStack" :whatsNewText="projectWhatsNewText" :whatsNewLink="'https://laravuetail.com/'"
            :projectGitRepoLink="projectGitRepoLink">
        </Hero>
        <WatchVideo :projectDemoLink="projectDemoLink" :projectDemoVideo="projectDemoVideo"></WatchVideo>
        <WhatIsThis></WhatIsThis>
    </PageLayout>
</template>
<script setup>
import Hero from '../components/HomePage/Hero.vue';
import WatchVideo from '../components/HomePage/WatchVideo.vue';
import WhatIsThis from '../components/HomePage/WhatIsThis.vue';
import PageLayout from '../components/PageLayout/PageLayout.vue';
</script>
<script>
export default {
    data() {
        return {
            projectName: import.meta.env.VITE_PROJECT_NAME,
            projectLogo: import.meta.env.VITE_PROJECT_LOGO,
            projectDescription: import.meta.env.VITE_PROJECT_DESCRIPTION,
            projectGitRepoLink: import.meta.env.VITE_PROJECT_GIT_REPO_LINK,
            projectStack: import.meta.env.VITE_PROJECT_STACK,
            projectDemoLink: import.meta.env.VITE_PROJECT_DEMO_LINK,
            projectDemoVideo: import.meta.env.VITE_PROJECT_DEMO_VIDEO,
            projectWhatsNewText: import.meta.env.VITE_PROJECT_WHATS_NEW_TEXT,
        }
    },
}
</script>