<script>
  import Properties from './Properties.svelte';

  const obj = {
      property1 : 'value1',
      property2 : 'value2',
      property3 : 'value3',
      property4 : 'value4',
      property5 : 'value5',
  }
</script>

<Properties {obj} />