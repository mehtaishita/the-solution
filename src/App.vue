<script setup lang="ts">
import { ref } from 'vue';
const story = ref('');
const twelve = ref('');
</script>

<template>
  <header>

  </header>

  <main>
      <p>10th Step: What's the story behind the resentment, fear, anger, excitement?</p>
      <textarea v-model="story" />

      <p>Pause and ask your higher power for the truth behind this resentment, fear, anger, excitement.</p>

      <p>What are the character defects at play?</p>
      <p>Selfish</p>
      <p>Dishonest</p>
      <p>Fear</p>
      <p>Self-seeking</p>

      <p>7th step prayer</p>

      <p>Pause and ask your higher power how you can help the addict who stil suffers.</p>
      <input v-model="twelve" />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
