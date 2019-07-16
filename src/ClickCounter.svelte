<script>
  let count = 0;

  $: doubled = count * 2

  $: {
    console.log(count*2)
  };

  $: if (count >= 10) {
    alert(`count is dangerously high!`);
    count = 9;
  }

  const handleClick = (e) => {
    count ++;
  }
</script>


<button on:click={handleClick}>clicked {count} {count === 1 ? 'time' : 'times'}</button>
<input type="number" value={doubled} disabled>