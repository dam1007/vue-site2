<template>
  <HeaderSection />
  <SliderSection />
  <ContentsSection />
  <ImageSection />
  <ImgtextSection />
  <YoutubeSection />
  <ReviewSection />
  <FooterSection />
</template>

<script>
  import HeaderSection from './components/HeaderSection.vue'
  import SliderSection from './components/SliderSection.vue'
  import ContentsSection from './components/ContentsSection.vue'
  import ImageSection from './components/ImageSection.vue'
  import ImgtextSection from './components/ImgtextSection.vue'
  import YoutubeSection from './components/YoutubeSection.vue'
  import ReviewSection from './components/ReviewSection.vue'
  import FooterSection from './components/FooterSection.vue'

  export default {
    name: 'App',
    components: {
      HeaderSection,
      SliderSection,
      ContentsSection,
      ImageSection,
      ImgtextSection,
      YoutubeSection,
      ReviewSection,
      FooterSection,
    }
  }
</script>

<style>
  @import "./App.css";
</style>
