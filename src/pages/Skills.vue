<template>
  <section class="skills-container container-geral">
    <h2>Skills</h2>
    <div class="q-pa-md row items-start q-gutter-md container-geral cards-sk">
      <div class="skills-cards">
        <img src="../assets/img/html.png" alt="tag code" />
      </div>
      <div class="skills-cards">
        <img src="../assets/img/css.png" alt="tag code" />
      </div>
      <div class="skills-cards">
        <img src="../assets/img/js.png" alt="tag code" />
      </div>
      <div class="skills-cards">
        <img src="../assets/img/tau.png" alt="tag code" />
      </div>
      <div class="skills-cards">
        <img src="../assets/img/react.png" alt="tag code" />
      </div>
      <div class="skills-cards">
        <img src="../assets/img/next.png" alt="tag code" />
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="css" scoped>
.skills-container {
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 8rem 0 0 0;
}
.skills-container > h2 {
  color: var(--branco);
  margin: 0 0 30px 0;
  font-family: var(--dm-sans);
  font-size: 2rem;
  font-weight: 700;
  font-style: normal;
  line-height: 2.6rem;
}

.cards-sk {
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.skills-cards {
  width: 9.37rem;
  height: 9.37rem;
  background-color: var(--cinza-400);
  margin: 0 0 16px 0;
  display: flex;
  align-items: center;
  justify-content: center;
}

@media screen and (max-width: 1000px) {
  .container-geral {
    padding: 50px 0rem 0 0.5rem;
  }
}
</style>
