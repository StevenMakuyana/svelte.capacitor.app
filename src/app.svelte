<script>
  // @ts-nocheck
  import { Route, router } from "tinro";
  import Home from "./pages/public/home.svelte";
  import About from "./pages/public/about.svelte";
  import Contact from "./pages/public/contact.svelte";
  import Header from "./components/layout/header.svelte";
  import Footer from "./components/layout/footer.svelte";
  router.base("/");
</script>

<div>
  <Header />
  <section>
    <Route path="/"><Home /></Route>
    <Route path="/about"><About /></Route>
    <Route path="/contacts"><Contact /></Route>
  </section>
  <Footer />
</div>

<style>
  div {
    min-height: 100vh;
    padding: 1rem;
    display: flex;
    flex-direction: column;
    gap: 2rem;
  }
</style>
