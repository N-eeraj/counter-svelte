<script>
  let count = 0
  const decrementCount = () => --count
  const incrementCount = () => ++count
</script>

<div>
  <button on:click={decrementCount}>
    -
  </button>
  <span>
    {count}
  </span>
  <button on:click={incrementCount}>
    +
  </button>
</div>

<style>
</style>
