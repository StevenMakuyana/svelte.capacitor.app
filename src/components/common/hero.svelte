<script>
  export const { title, content } = $props();
</script>

<div>
  <h2>{title}</h2>
  <p>{content}</p>
</div>

<style>
  div {
    padding: 1rem;
    text-align: center;
    margin: auto;
    max-width: 500px;
    h2 {
      text-transform: capitalize;
      font-size: 2rem;
      font-weight: 500;
      line-height: 3rem;
      color: black;
    }
    p {
      word-spacing: 0.2rem;
      line-height: 1.3rem;
      color: rgb(77, 77, 77);
    }
  }
</style>
