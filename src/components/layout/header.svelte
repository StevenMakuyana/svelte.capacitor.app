<script>
  import Nav from "./nav.svelte";
</script>

<div>
  <h1>capacitor</h1>
  <Nav />
</div>

<style>
  div {
    position: sticky;
    left: 0;
    right: 0;
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
    text-align: center;
    h1 {
      text-transform: capitalize;
      text-decoration: underline orangered;
      font-size: 3rem;
      font-weight: 400;
    }
  }
</style>
