<script lang="ts">
</script>

<div id="container">
  <slot />
</div>

<style>
  :global(body) {
    overflow: hidden;
    margin: 0;
    padding: 0;
  }
  #container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100svw;
    height: 100svh;
  }
</style>
