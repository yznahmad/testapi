<script>




  let count = 0
  const increment = () => {
    count += 1
  }


	$: {console.log('Count is ... '+ count)}


</script>

<button on:click={increment}>
  count is {count}
</button>
