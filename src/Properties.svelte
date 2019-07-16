<script>
  export let obj
</script>

<style>
  dl {
    display: flex;
    flex-direction: row;
    border: 1px solid black;
    font-family: sans-serif;
  }
  dd, dt {
    padding: 0;
    margin: 0;
    width: 50%;
  }
</style>

<dl>
  {#each Object.keys(obj) as k}
    <dt>{k}</dt>
    <dd>{obj[k]}</dd>
  {/each}
</dl>