<template>
  <div>
    <header>my Trello</header>
    <main>
      <p class="info-line">All: 0 tasks</p>
      <list-add />
    </main>
  </div>
</template>

<script>
import ListAdd from "./ListAdd.vue";

export default {
  components: {
    ListAdd,
  },
};
</script>