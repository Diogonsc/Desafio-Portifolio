<template>
  <div class="q-pa-md row items-start q-gutter-md container-geral cards">
    <div class="projeto-cards cards" v-for="n in 6" :key="n">
      <q-card class="projeto-img">
        <a href="">
          <img src="https://cdn.quasar.dev/img/mountains.jpg" />
        </a>

        <q-card-section class="projeto-title">
          <div class="text-h6 title-h6">{{ title }}</div>
          <div class="text-subtitle2 subtitle-h6">{{ subtitle }}</div>
        </q-card-section>

        <q-card-section class="q-pt-none">
          {{ lorem }}
        </q-card-section>
      </q-card>
    </div>
  </div>
</template>

<script>
export default {
  setup() {
    return {
      title: "Título do projeto",
      subtitle: "Tecnologias: HTML, CSS e JS.",
    };
  },
};
</script>

<style lang="css" scoped>
.my-card {
  width: 100%;
  max-width: 250px;
}
.cards {
  display: flex;
  justify-content: center;
  align-items: center;
}

.projeto-cards {
  width: 21.87rem;
  height: 15rem;
  background-color: var(--cinza-400);
}

.projeto-img {
  width: 18.75rem;
  height: 8.12rem;
  background-color: var(--preto);
  margin: 20px 25px 90px 25px;
}

.projeto-img a > img {
  width: 18.75rem;
  height: 8.12rem;
}

.projeto-title {
  padding-left: 0;
}

.title-h6,
.subtitle-h6 {
  color: var(--branco);
}
</style>
