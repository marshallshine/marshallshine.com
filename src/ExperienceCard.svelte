<script>
  export let name;
  export let title;
  export let description;
  export let imgSrc;
  export let imgAlt;
</script>

<div class="flex-container">
  <div class="card">
    <h1>{name}</h1>
    <h2>{title}</h2>
    <p>
      {description}
    </p>
  </div>
  <img src={imgSrc} alt={imgAlt} />
</div>

<style>
  .card {
    width: 70%;
    padding: 2rem 1rem 3rem 1rem;
    margin: 0 1rem 1rem 0;
    background: rgba(255, 255, 255, 0.75);
    border-radius: 0.5rem;
    box-shadow: 1px 1px 5px rgb(0 0 0 / 25%);
  }
  img {
    width: 20%;
    height: auto;
    margin: 1rem;
    padding: 0;
  }
  .flex-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-direction: row;
  }
  .flex-container:nth-child(2n) {
    display: flex;
    align-items: center;
    flex-direction: row-reverse;
  }
  h1 {
    font-size: 1.5rem;
    font-weight: bold;
    text-align: left;
  }
  h2 {
    font-size: 1rem;
    font-weight: bold;
    text-align: left;
    padding-bottom: 1rem;
  }
  p {
    line-height: 1.25;
  }
  @media screen and (max-width: 768px) {
    .flex-container {
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-direction: column-reverse;
    }
    .flex-container:nth-child(2n) {
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-direction: column-reverse;
    }
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
    img {
      width: 65vw;
      max-width: 250px;
    }
  }
</style>
