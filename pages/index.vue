<template>
  <div>
    <NavBar/>
    <Slider/>
    <ProfilSection/>
    <StrukturSection/>
    <ProgramSection/>
    <RegistrasiSection/>
    <!-- <Login/> -->
    <!-- <NewsSection/> -->
    <Footer/>

  </div>
</template>

<script>
  import Navbar from '~/components/organisms/Navbar.vue'
  import Slider from '~/components/organisms/Slider.vue'
  import ProfilSection from '~/components/mollecules/ProfilSection.vue'
  import StrukturSection from'~/components/mollecules/StrukturSection.vue'
  import ProgramSection from'~/components/mollecules/ProgramSection.vue'
  import RegistrasiSection from'~/components/organisms/RegistrasiSection.vue'
  import NewsSection from '~/components/organisms/NewsSection.vue'
 /*  import Login from '~/components/atoms/Login.vue' */
  import Footer from '~/components/organisms/Footer.vue'
  
 
export default {
  components: {
    NavBar: Navbar,
    Slider: Slider,
    ProfilSection: ProfilSection,
    StrukturSection: StrukturSection,
    ProgramSection: ProgramSection,
    RegistrasiSection: RegistrasiSection,
    // Login: Login,
    Footer: Footer,

    // NewsSection: NewsSection,
  }
}
</script>

<style>



</style>










