<script>
import MenuLateral from "@/components/MenuLateral.vue";
export default {
  components: { MenuLateral },
};
</script>
<template>
  <MenuLateral />
  <header id="header"><h1>SITES DE ANIMES</h1></header>
  <main id="content">
    <div class="textop">
      <h1>TOP 4 ANIMES</h1>
    </div>
    <div class="animes-list">
      <div class="anime-item">
        <p>BLEACH</p>
        <img src="download.jpeg" />
      </div>

      <div class="anime-item">
        <p>BLACK CLOVER</p>
        <img src="op.jpg" />
      </div>

      <div class="anime-item">
        <p>RE:ZERO</p>
        <img src="re.jpeg" />
      </div>

      <div class="anime-item">
        <p>TATE NO YUUSHA</p>
        <img src="pp.jpeg" />
      </div>
    </div>
  </main>
  <footer id="footer">Rodapé</footer>
</template>
<style>
.animes-list {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
}

.anime-item {
  display: flex;
  flex-direction: column;
}

.anime-item p {
  align-self: center;
  margin-bottom: 0;
}

.anime-item img {
  margin-top: 0;
}
</style>
