<template>
  <div>
    <HeroNav />
    <HomeServices />
    <HomeAbout />
    <HomeProcess />
    <HomePortfolio />
    <HomeTestimonials />
    <HomeCTA />
  </div>
</template>

<script>
import HeroNav from "../components/HeroNav";
import HomeServices from "../components/HomeServices";
import HomeAbout from "../components/HomeAbout";
import HomeProcess from "../components/HomeProcess";
import HomePortfolio from "../components/HomePortfolio";
import HomeTestimonials from "../components/HomeTestimonials";
import HomeCTA from "../components/HomeCTA";
export default {
  name: 'IndexPage',
  components: {HomeCTA, HomeTestimonials, HomePortfolio, HomeProcess, HomeAbout, HeroNav, HomeServices}
}
</script>
