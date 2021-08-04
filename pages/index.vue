<template>
  <main>
    <section class="hero shape">
      <img class="sermon-title" src="/sermon-thumbnail-title.png" alt="Following Jesus in Today's World">
      <p class="hero-description">Wenn du dich entscheidest, jemandem zu folgen, möchtest du dann nicht wissen, wohin dieser jemand geht? Jesus ruft Menschen dazu auf, ihm zu folgen – zu wissen, wohin er geht, wird alles verändern. In dieser Predigt erfahren wir, was es wirklich bedeutet, Jesus in der Welt von heute nachzufolgen.</p>
    </section>
    <section>
      <h1 class="hero-title">
        Highlighted Boxes
      </h1>
    </section>
    <section>
      Du bist herzlich willkommen
    </section>
    <section>
      Aktuelles
    </section>
    <section>
      Brauchst du Gebet?
    </section>
  </main>
</template>

<script>
export default {
}
</script>

<style lang="scss">
.shape {
  clip-path: polygon(0 0, 100% 6%, 100% 100%, 0% 100%);
}

.hero {
  width: 100%;
  height: 40vh;

  background-image: url('/sermon-thumbnail-background.png');
  background-size: cover;
  background-repeat: no-repeat;

  display: grid;
  align-content: center;

  > * {
    margin: 0;
    padding: 1rem;
  }
}
</style>
