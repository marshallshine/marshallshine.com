<script>
  export let name;
  export let description;
</script>

<div class="card">
  <div class="flex-container">
    <h1>{name}</h1>
  </div>
  <p>
    {description}
  </p>
</div>

<style>
  .card {
    width: 95%;
    padding: 2rem 1rem 2rem 1rem;
    margin: 1rem auto 1rem auto;
    background: rgba(255, 255, 255, 0.75);
    border-radius: 0.5rem;
    box-sizing: border-box;
    box-shadow: 1px 1px 5px rgb(0 0 0 / 25%);
  }
  h1 {
    font-size: 1.5rem;
    font-weight: bold;
    text-align: center;
  }
  p {
    text-align: center;
    font-size: 1rem;
  }
  .flex-container {
    align-items: center;
    padding-bottom: 1rem;
  }
</style>
