<template>
  <div class="home">
    <Navbar />
    <Best />
    <Welmart />
    <Beco />
    <Food />
    <Dylan />
    <Contact />
    <Address />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import Best from "@/components/Best.vue";
import Welmart from "@/components/Welmart.vue";
import Beco from "@/components/Beco.vue";
import Food from "@/components/Food.vue";
import Dylan from "@/components/Dylan.vue";
import Contact from "@/components/Contact.vue";
import Address from "@/components/Address.vue";

export default {
  name: "Home",
  components: {
    Navbar,
    Best,
    Welmart,
    Beco,
    Food,
    Dylan,
    Contact,
    Address,
  },
};
</script>
<style lang="scss" scoped>
.home {
  position: relative;
}
</style>
