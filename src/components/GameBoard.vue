<script>
import CardView from "./CardView.vue";
  export default {
      components: {
    CardView,
  },
  };
</script>

<template>
  <div class="game-board">
    <p>I am the GameBoard.vue component</p>
    <ul class="cards">
      <li class="card">
        <CardView />
      </li>
    </ul>
  </div>
</template>