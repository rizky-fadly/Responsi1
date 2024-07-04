<template>
  <>
  <div>
    <AboutSection />
    <HeroSection />
    <ContactSection/>
    <ProjectSection />
  </div>
</template>

<script>
import HeroSection from '~/components/HeroSection.vue';
import AboutSection from '~/components/AboutSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';

export default {
  components: {
    AboutSection,
    HeroSection,
    ContactSection,
    ProjectsSection,
  }
}
</script>./Index.vue