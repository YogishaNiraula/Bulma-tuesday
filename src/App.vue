<template>
  <navbar />
  <levelitem
    >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
    <br />jxiklsa;xaIKNXAXSOLMASX;LSAMN'AXOUBCVHYXSAL/L/
  </levelitem>
  <gridImg />
  <email
    >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
    tempor incididunt ut labore et dolore magna aliqua.</email
  >
  <bottom />
</template>

<script>
import navbar from "./components/navbar.vue";
import levelitem from "./components/levelitem.vue";
import gridImg from "./components/gridImg.vue";
import email from "./components/email.vue";
import bottom from "./components/bottom.vue";
export default {
  name: "App",
  components: {
    navbar,
    levelitem,
    gridImg,
    email,
    bottom,
  },
};
</script>
