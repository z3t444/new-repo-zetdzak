<template>
  <!-- //Graph Peformance// -->
  <div class="graph_peformance dm_sans">
    <div class="simple-bar-chart mx-auto mt-10">
      <div class="item hover:text-green-400 duration-100" style="--clr: #5eb344; --val: 90">
        <div class="label mt-3">Framework</div>
        <div class="value">80%</div>
      </div>
      <div class="item" style="--clr: #fcb72a; --val: 95">
        <div class="label mt-3">SEO Web</div>
        <div class="value">95%</div>
      </div>
      <div class="item" style="--clr: #f8821a; --val: 100">
        <div class="label mt-3">Popular</div>
        <div class="value">100%</div>
      </div>
      <div class="item" style="--clr: #e0393e; --val: 15">
        <div class="label mt-3">Tidur</div>
        <div class="value">15%</div>
      </div>
      <div class="item" style="--clr: #963d97; --val: 10">
        <div class="label mt-3">Friends</div>
        <div class="value">10%</div>
      </div>
      <div class="item" style="--clr: #069cdb; --val: 90">
        <div class="label mt-3">Responder</div>
        <div class="value">90%</div>
      </div>
    </div>
  </div>
</template>

<script setup>
  import "../assets/css/graph.css"
</script>

<style>
  @import url("https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;0,9..40,600;0,9..40,700;0,9..40,800;0,9..40,900;0,9..40,1000;1,9..40,300;1,9..40,400;1,9..40,500;1,9..40,600;1,9..40,700;1,9..40,800;1,9..40,900;1,9..40,1000&display=swap");
  .dm_sans {
    font-family: "DM Sans", sans-serif;
  }
</style>
