<template>  
    <header-section></header-section>
    <router-view></router-view>
    <later-section></later-section>
    <footer-section></footer-section>
</template>

<script>
import HeaderSection from '../components/fontend/Header.vue'
import FooterSection from '../components/fontend/Footer.vue';
import LaterSection from '../components/fontend/Newsletter.vue'
export default {
  components : {
    HeaderSection, 
    LaterSection,
    FooterSection
},
  name: "Master",
};
</script>

<style></style>
