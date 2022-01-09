<script>
  export let name;
  export let description;
</script>

<div class="card">
  <h1>{name}</h1>

  <p>
    {@html description}
  </p>
</div>

<style>
  .card {
    width: 44%;
    padding: 2rem 1rem 3rem 1rem;
    margin: 0 1rem 1rem 0;
    background: rgba(255, 255, 255, 0.75);
    border-radius: 0.5rem;
    box-shadow: 1px 1px 5px rgb(0 0 0 / 25%);
  }
  h1 {
    font-size: 1rem;
    font-weight: bold;
    text-align: left;
    padding-bottom: 1rem;
  }
  p {
    line-height: 1.25;
  }

  @media screen and (max-width: 768px) {
    .card {
      width: 100%;
      padding: 2rem 1rem 3rem 1rem;
      margin: auto;
      margin-bottom: 2rem;
      background: rgba(255, 255, 255, 0.75);
      border-radius: 0.5rem;
      box-shadow: 1px 1px 5px rgb(0 0 0 / 25%);
      box-sizing: border-box;
    }
  }
</style>
