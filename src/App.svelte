<script>
  import Hello from "./components/hello.svelte";
  import Navbar from "./components/navbar.svelte";
  import Footer from "./components/footer.svelte";
  export let name;
  export let age = "12";
  var gbr =
    "https://images.unsplash.com/photo-1504639725590-34d0984388bd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=667&q=80";
</script>

<style>
  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>

<main>
  <Navbar />
  <Hello buah="apel" sayuran="tomat" />
  <h1>Hello {name}!</h1>
  <p>
    {age}Visit the
    <a href="https://svelte.dev/tutorial">Svelte tutorial</a>
    to learn how to build Svelte apps.
  </p>
  <img src={gbr} alt="gambar" />
  <Footer />
</main>
