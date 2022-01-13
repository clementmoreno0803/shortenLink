<template>
  <div class="container">
    <navbar></navbar>
    <presentation></presentation>
    <div class="advance_link"></div>
    <mapAdress></mapAdress>
    <detail></detail>
  </div>
  <boostLink></boostLink>
  <footerSection></footerSection>
</template>

<script>
import mapAdress from "./components/map.vue";
import navbar from "./components/nav.vue";
import presentation from "./components/pres.vue";
import detail from "./components/details.vue";
import boostLink from "./components/boost.vue";
import footerSection from "./components/footerSection.vue";

export default {
  name: "App",
  components: {
    mapAdress,
    navbar,
    presentation,
    detail,
    boostLink,
    footerSection,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@500;700&display=swap");
:root {
  --primary: rgb(42, 207, 207);
  --secondary: white;
  --footer: hsl(260, 8%, 14%);
}
#app {
  display: flex;
  justify-content: center;
  box-sizing: border-box;
  flex-direction: column;
  align-items: center;
}
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container {
  width: 75%;
}
.titre {
  width: 50%;
}
h1 {
  font-family: "Poppins";
  font-size: 4rem;
  margin: 0;
  line-height: 1.2;
}

h2 {
  font-family: "Poppins";
  font-size: 1.175rem;
  font-weight: 500;
  opacity: 0.4;
  margin-bottom: 30px;
}
h3 {
  font-family: "Poppins";
  font-size: 1rem;
  opacity: 0.4;
  font-weight: 500;
}
h4 {
  font-family: "Poppins";
  font-size: 1.425rem;
  font-weight: 700;
  margin: 0;
}
h5 {
  font-family: "Poppins";
  font-size: 0.775rem;
  font-weight: 500;
  opacity: 0.4;
  text-align: left;
}

.advance_link {
  background: hsl(0, 0%, 95%);
  width: 100%;
  position: absolute;
  left: 0;
  height: calc(100% + 150px);
  z-index: -1;
}
</style>
