<template>
  <div id="app">
    <!-- ★Boardコンポーネント呼び出し -->
    <board />
  </div>
</template>

<script>
// ★インポート文を追加
import Board from "./components/Board.vue";
import "./assets/css/styles.css";

export default {
  name: "app",
  components: {
    // ★コンポーネントに登録する
    Board,
  },
};
</script>