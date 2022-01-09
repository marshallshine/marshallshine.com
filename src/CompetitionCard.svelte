<script>
  export let name;
  export let description;
  export let imgSrc;
  export let imgAlt;
  export let compLink;
</script>

<div class="card">
  <div class="flex-container">
    <h1>{name}</h1>
    <a href={compLink} target="_blank">
      <img src={imgSrc} alt={imgAlt} />
    </a>
  </div>
  <p>
    {@html description}
  </p>
</div>

<style>
  .card {
    width: 90%;
    padding: 2rem 1rem 3rem 1rem;
    margin: 1rem auto 1rem auto;
    background: rgba(255, 255, 255, 0.75);
    border-radius: 0.5rem;
    box-shadow: 1px 1px 5px rgb(0 0 0 / 25%);
  }
  h1 {
    font-size: 1.5rem;
    font-weight: bold;
    text-align: left;
  }
  p {
    line-height: 1.25;
  }
  img {
    height: 4.5rem;
    display: flex;
    align-items: center;
    margin-left: auto;
  }
  .flex-container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding-bottom: 1rem;
  }
  @media screen and (max-width: 768px) {
    img {
      margin-bottom: 1rem;
    }
    .flex-container {
      display: flex;
      flex-direction: column-reverse;
      justify-content: space-between;
      align-items: center;
      padding-bottom: 1rem;
    }
  }
</style>
