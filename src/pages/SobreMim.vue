<template>
  <main class="container-geral">
    <div class="sobre-container">
      <div class="sobre-info">
        <h1 class="sobre-h1">Olá, eu sou o Diogo Santos :)</h1>
        <p class="sobre-p">Desenvolvedor Front-End & UI Designer</p>
        <div class="button">
          <Button
            label="Download CV"
            style="
              background: var(--verde);
              color: var(--preto);
              width: 8.93rem;
              height: 2.62rem;
              font-size: 0.8rem;
              font-family: var(--dm-sans);
              font-weight: 500;
            "
          />
          <Button
            class="btn-contato botao"
            label="Entrar em contato"
            style="
              background: var(--preto);
              color: var(--branco);
              width: 8.93rem;
              height: 2.62rem;
              font-size: 0.8rem;
              font-family: var(--dm-sans);
              font-weight: 500;
            "
          />
        </div>
      </div>
      <div class="sobre-img">
        <img src="../assets/img/undraw_Lost.png" alt="Logotipo" />
      </div>
    </div>
    <div class="sobre-mim-title">
      <h2>Sobre mim</h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
        veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
        commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
        velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
        occaecat cupidatat non proident
      </p>
      <div class="sobre-contatos">
        <div class="icone sobre-icone">
          <p class="info"><i class="far fa-smile"></i></p>
          <p>Meu Nome</p>
          <span>Diogo Santos</span>
        </div>

        <div class="icone sobre-icone">
          <p class="info"><i class="far fa-envelope"></i></p>
          <p>E-mail</p>
          <span>diogonsc@yahoo.com.br</span>
        </div>

        <div class="icone sobre-icone">
          <p class="info"><i class="fab fa-instagram"></i></p>
          <p>Instagram</p>
          <span>@diogonsc</span>
        </div>

        <div class="icone sobre-icone">
          <p class="info"><i class="fal fa-phone-alt"></i></p>
          <p>Telefone</p>
          <span>(21) 98902-0276</span>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
import Button from "../components/Button.vue";
export default {
  components: { Button },
};
</script>

<style scoped>
i {
  color: var(--verde);
  font-size: 1.5rem;
}
.sobre-container {
  margin-top: 8.93rem;
  display: flex;
  justify-content: space-between;
}
.sobre-h1 {
  width: 15.81rem;
  color: var(--branco);
  font-family: var(--dm-sans);
  font-size: 2.25rem;
  font-weight: 700;
  font-style: normal;

  line-height: 2.92rem;
}

.sobre-p {
  color: var(--cinza);
  font-family: var(--dm-sans);
  font-size: 1.12rem;
  font-weight: 500;
  font-style: normal;
  margin: 1.12rem 0 2.93rem 0;
  line-height: 1.46rem;
}

.button {
  display: flex;
}

.sobre-mim-title {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 10.56rem 0 1.87rem 0;
}

.sobre-mim-title > h2 {
  color: var(--branco);
  margin: 0 0 30px 0;
  font-family: var(--dm-sans);
  font-size: 2rem;
  font-weight: 700;
  font-style: normal;
  line-height: 2.6rem;
}

.sobre-mim-title > p {
  width: 47.12rem;
  height: 10rem;

  margin: 0 0 85px 0;

  color: var(--cinza);
  text-align: center;

  font-family: var(--dm-sans);
  font-size: 1.12rem;
  font-weight: 400;
  font-style: normal;
  line-height: 2rem;
}

.sobre-contatos {
  width: 80%;
  display: flex;
  justify-content: space-between;
}

.info {
  width: 62px;
  height: 62px;
  border-radius: 50%;
  background-color: var(--cinza-400);

  display: flex;
  justify-content: center;
  align-items: center;
}

.icone {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.icone > p {
  color: var(--branco);
  text-align: center;

  margin: 19px 0 5px 0;

  font-family: var(--dm-sans);
  font-size: 1.12rem;
  font-weight: 700;
  font-style: normal;
  line-height: 1.46rem;
}

.icone > span {
  color: var(--cinza);
  text-align: center;

  font-family: var(--dm-sans);
  font-size: 1rem;
  font-weight: 400;
  font-style: normal;
  line-height: 1.3rem;
}

.cards {
  display: flex;
  justify-content: center;
  align-items: center;
}

.sobre-icone {
  width: 8rem;
  height: 9.37rem;

  margin: 10px 0;

  display: flex;
  align-items: center;
  justify-content: center;
}

@media screen and (max-width: 1000px) {
  .container-geral {
    padding: 0;
  }
  .sobre-mim-title > p {
    padding: 0 1rem;
    width: 100%;
    height: 20rem;
    text-align: justify;
  }
  .sobre-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
  }

  .sobre-info {
    margin-top: -120px;
  }

  .sobre-img {
    margin-top: 50px;
  }

  .sobre-contatos {
    display: flex;
    flex-wrap: wrap;
  }

  .sobre-icone {
    display: flex;
    justify-content: center;
    align-items: center;
  }
}
</style>
