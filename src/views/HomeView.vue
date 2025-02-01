<template>
  <!-- MainHeader section-->
  <MainHeader></MainHeader>

  <!-- Sticky Header -->
  <StickyHeader></StickyHeader>

  <!-- Main Slider -->
  <MainSlider></MainSlider>

  <!-- FeaturesSection -->
  <FeaturesSection></FeaturesSection>

  <!-- AboutSection -->
  <AboutSection></AboutSection>

  <!-- ServicesSection -->
  <ServicesSection></ServicesSection>

  <!-- ProjectsSection -->
  <ProjectsSection></ProjectsSection>

  <!-- Image Banner -->
  <ImageBanner></ImageBanner>

  <!-- TestimonialsSection -->
  <TestimonialsSection></TestimonialsSection>

  <!-- Blog -->
  <BlogSection></BlogSection>

  <!-- Contact -->
  <ContactSection></ContactSection>

  <!-- Brands -->
  <BrandsSection></BrandsSection>

  <!-- FooterSection -->
  <FooterSection></FooterSection>

  <!-- CopyRightSection -->
  <CopyRightSection></CopyRightSection>

</template>

<script>
// @ is an alias to /src
import MainHeader from '@/components/Common/MainHeader.vue';
import StickyHeader from '@/components/Common/StickyHeader.vue';
import MainSlider from '@/components/Common/MainSlider.vue';
import FeaturesSection from '@/components/Common/FeaturesSection.vue';
import AboutSection from '@/components/Common/AboutSection.vue';
import ServicesSection from '@/components/Common/ServicesSection.vue';
import ProjectsSection from '@/components/Common/ProjectsSection.vue';
import ImageBanner from '@/components/Common/ImageBanner.vue';
import TestimonialsSection from '@/components/Common/TestimonialsSection.vue';
import BlogSection from '@/components/Common/BlogSection.vue';
import ContactSection from '@/components/Common/ContactSection.vue';
import BrandsSection from '@/components/Common/BrandsSection.vue';
import FooterSection from '@/components/Common/FooterSection.vue';
import CopyRightSection from '@/components/Common/CopyRightSection.vue';

export default {
  name: 'HomeView',
  components: {
    MainHeader,
    StickyHeader,
    MainSlider,
    FeaturesSection,
    AboutSection,
    ServicesSection,
    ProjectsSection,
    ImageBanner,
    TestimonialsSection,
    BlogSection,
    ContactSection,
    BrandsSection,
    FooterSection,
    CopyRightSection
  }
}
</script>
