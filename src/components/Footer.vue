<template>
  <footer class="footer">
    <span class="footer-text">
      Orgulhosamente feito por <span class="footer-nome">Diogo Santos</span>
    </span>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  width: 100%;
  height: 60px;
  background-color: var(--cinza-400);
  margin-top: 11.56rem;

  display: flex;
  justify-content: center;
  align-items: center;
}

.footer-text {
  color: var(--branco);
  font-family: var(--dm-sans);
  font-size: 1rem;
  font-weight: 700;
  font-style: normal;
  line-height: 1.3rem;
}

.footer-nome {
  color: var(--verde);
}
</style>
