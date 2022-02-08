<template>
  <!-- <header class="header-container container">
    <nav class="navigation">
      <p class="text-portifolio">Portfólio</p>
      <ul class="ul-nav">
        <li class="li-nav"><a href="#sobre">Sobre mim</a></li>
        <li class="li-nav"><a href="#">Projetos</a></li>
        <li class="li-nav"><a href="#">Serviços</a></li>
        <li class="li-nav"><a href="#">Minhas skills</a></li>
      </ul>
    </nav>
  </header> -->
  <Nav />
  <SobreMimVue />
  <Projetos />
  <Servicos />
  <Skills />
  <Footer />
</template>

<script>
import Nav from "../components/Nav.vue";
import SobreMimVue from "src/pages/SobreMim.vue";
import Projetos from "src/pages/Projetos.vue";
import Servicos from "src/pages/Servicos.vue";
import Skills from "src/pages/Skills.vue";
import Footer from "src/components/Footer.vue";
export default {
  components: { Nav, SobreMimVue, Projetos, Servicos, Skills, Footer },
};
</script>

<style scoped>
.header-container {
  width: 100%;
}
.navigation {
  width: 100%;
  padding: 34px 0;
  display: flex;
  justify-content: space-between;
}

.text-portifolio {
  color: var(--branco);

  margin: 0;

  font-family: var(--dm-sans);
  font-size: 1.62rem;
  font-weight: 700;
  font-style: normal;

  line-height: 2.11rem;
}

.ul-nav {
  display: flex;
  align-items: center;
  gap: 2.81rem;
}

.li-nav {
  list-style: none;
}

.li-nav a {
  color: var(--branco);

  font-family: var(--dm-sans);
  font-size: 1.12rem;
  font-weight: 400;

  line-height: 1.46rem;

  text-decoration: none;
}

.li-nav a:hover {
  border-bottom: 2px solid var(--verde);
}

@media screen and (max-width: 1000px) {
  .header-container {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .navigation {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
  }
}
</style>
