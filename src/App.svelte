<script lang="ts">
  import svelteLogo from "./assets/svelte.svg";
  import Maaling from "./lib/Maaling.svelte";
  import Chart from "./lib/Chart.svelte";
</script>

<main>
  <h1>Forbruk</h1>

  <div class="card tall">
    <Maaling />
    <Chart />
  </div>
</main>

<style>
  .tall {
    font-size: 72px;
    height: 6em;
    padding: 1.5em;
    will-change: filter;
  }
</style>
