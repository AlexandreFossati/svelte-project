<script lang="ts">
  let value = 0;
  const addValue = (): void => {
    value += 1;
  };
</script>

<main>
  <button on:click={addValue}>You clicked me {value} times</button>
</main>

<style>
  button {
    background-color: rgb(186, 247, 186);
  }
</style>