<template>
  <section class="servicos-container">
    <h2>Serviços</h2>
    <div class="q-pa-md row items-start q-gutter-md cards">
      <div class="servicos-cards">
        <img src="../assets/img/code.png" alt="tag code" />
        <h3>Criação de sites</h3>
      </div>
      <div class="servicos-cards">
        <img src="../assets/img/figma.png" alt="tag code" />
        <h3>UI Designer</h3>
      </div>
      <div class="servicos-cards">
        <img src="../assets/img/smartphone.png" alt="tag code" />
        <h3>Sites responsivos</h3>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  components: {},
};
</script>

<style lang="css" scoped>
.servicos-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 8rem 0 0 0;
}
.servicos-container > h2 {
  color: var(--branco);
  margin: 0 0 30px 0;
  font-family: var(--dm-sans);
  font-size: 2rem;
  font-weight: 700;
  font-style: normal;
  line-height: 2.6rem;
}

.cards {
  display: flex;
  justify-content: center;
  align-items: center;
}

.servicos-cards {
  width: 21.87rem;
  height: 15rem;
  margin-bottom: 17px;
  background-color: var(--cinza-400);
  border-bottom: 4px solid var(--verde);
}

.servicos-cards img,
h3 {
  padding: 30px 0 0 30px;
}

.servicos-cards h3 {
  width: 11.87rem;
  color: var(--cinza);
  font-family: var(--dm-sans);
  font-size: 2rem;
  font-weight: 500;
  font-style: normal;
  line-height: 2.6rem;
  margin: 0;
}
</style>
