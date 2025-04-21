<script>
    import Navbar from '../components/Navbar.svelte';
    import Home from '../components/Home.svelte';
    import Footer from '../components/Home/Footer.svelte';

</script>

<main>
    <Navbar />
    <Home />
    <Footer />
</main>


<style>
    :global(body) {
      background-color: #101010;  /* This is always black regardless of dark/light mode */
  }
      main {
      font-family: "Judson", serif;
      /* width: 100%;
      height: 100%;
      margin: 0; */
     
      }
  
  </style>