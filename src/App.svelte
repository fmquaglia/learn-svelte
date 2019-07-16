<script>
  import Name from './Name.svelte'
  import ClickCounter from './ClickCounter.svelte'
  import ArraySum from './ArraySum.svelte'
  import Props from './Props.svelte'

  export let name;

  let src="./images/svelte.png"
</script>

<style>
  h1 {
    color: purple;
  }
</style>

<h1>Hello {name}!</h1>
<img {src} alt="Svelte" >
<hr>
<Name name="<i>Fabricio</i>"/>
<hr>
<ClickCounter/>
<hr>
<ArraySum/>
<hr>
<Props />