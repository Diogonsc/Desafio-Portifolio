<template>
  <section class="projetos-container container-geral">
    <h2>Projetos</h2>
    <Cards />
  </section>
</template>

<script>
import Cards from "../components/Cards.vue";
export default {
  components: { Cards },
};
</script>

<style scoped>
.projetos-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 8rem 0 0 0;
}
.projetos-container > h2 {
  color: var(--branco);
  margin: 0 0 30px 0;
  font-family: var(--dm-sans);
  font-size: 2rem;
  font-weight: 700;
  font-style: normal;
  line-height: 2.6rem;
}

@media screen and (max-width: 1000px) {
  /* .container-geral {
    padding: 0;
  } */
}
</style>
