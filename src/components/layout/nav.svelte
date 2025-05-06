<script>
  import { active } from "tinro";
</script>

<div>
  <ul>
    <a href="/" use:active>home</a>
    <a href="/contacts" use:active>contacts</a>
    <a href="/about" use:active>about</a>
  </ul>
</div>

<style>
  div {
    display: flex;
    align-items: center;
    justify-content: center;
    ul {
      display: flex;
      gap: 1rem;
      a {
        text-transform: capitalize;
        text-decoration: none;
        color: black;
      }
    }
  }
</style>
