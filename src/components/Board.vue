<template>
  <div>
    <header>my Trello</header>
    <main>
      <p class="info-line">All: 0 tasks</p>
      <!-- ★ここに追記 -->
      <list-add />
    </main>
  </div>
</template>

<script>
// ★ここに追記
import ListAdd from "./ListAdd.vue";

export default {
  // ★ここから追記
  components: {
    ListAdd,
  },
  // ★ここまで追記
};
</script>