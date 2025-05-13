<script>
  import Footer from '../../components/Home/Footer.svelte';
  import Project from '../../components/Projects/Project.svelte';
//   import Navbar from '../../components/Navbar.svelte';

</script>


<main>
    <!-- <Navbar /> -->
    <Project />
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