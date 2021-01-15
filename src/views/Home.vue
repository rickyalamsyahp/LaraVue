<template>
  <div class="home">
    <HeaderSalsa/>
    <HeroSalsa/>
    <WomanSalsa/>
    <InstaSalsa/>
    <PartnerSalsa/>
    <FooterSalsa/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderSalsa from '@/components/HeaderSalsa.vue'
import HeroSalsa from '@/components/HeroSalsa.vue'
import WomanSalsa from '@/components/WomanSalsa.vue'
import InstaSalsa from '@/components/InstaSalsa.vue'
import PartnerSalsa from '@/components/PartnerSalsa.vue'
import FooterSalsa from '@/components/FooterSalsa.vue'





export default {
  name: 'Home',
  components: {
   HeaderSalsa,
   HeroSalsa,
   WomanSalsa,
   InstaSalsa,
   PartnerSalsa,
   FooterSalsa,
  }
}
</script>
