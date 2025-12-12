<script>
  import Header from "./Header1.svelte";
  import "../app.css";
</script>

<div class="app">
  <Header />

  <main>
    <slot />
  </main>
</div>
