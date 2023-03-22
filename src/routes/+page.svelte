<svelte:head>
   <title>{'Bio'}</title>
</svelte:head>

<script lang='ts'>
  import Projects from '../components/Projects.svelte'
  import Comic from '../components/Comic.svelte'
</script>

<main>
  <div class="container">
    <Projects />
    <Comic email={"ru.khakimov@innopolis.university"} />
  </div>
</main>

<style>
  .container {
    display: grid;
    grid-template-columns: 50% 50%;
  }
</style>
