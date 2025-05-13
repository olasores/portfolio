<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Judson:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">
</svelte:head>

<script>


    import ProjectComp from "./ProjectComp.svelte";
    import {goto} from "$app/navigation";


    function goToHomePage() {
        goto("/");
    }

</script>

<main class="mx-auto max-w-[700px] p-40 px-10 pb-4 pt-16 text-white w-full">


    <button 
        on:click={goToHomePage} 
        class="mb-6 flex items-center text-sm font-medium text-gray-300 hover:text-white transition">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-1" viewBox="0 0 20 20" fill="currentColor">
            <path fill-rule="evenodd" d="M9.707 14.707a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414l4-4a1 1 0 011.414 1.414L7.414 9H15a1 1 0 110 2H7.414l2.293 2.293a1 1 0 010 1.414z" clip-rule="evenodd" />
        </svg>
        Back to Home
    </button>
        <section>
            
                <div>
                    <h1 class="text-xl md:text-2xl mb-5 px-3">More Projects </h1>
                    <div class=" px-3 mb-2">
                        <p>
                            I've worked on a variety of projects, from simple websites, web applications, user interface design, and a few on data anaylsis/science
                        </p>
                    </div>
                </div>

           
            

          
                <div>
                    <ProjectComp />
                </div>
           
          
    
    
            
    
           
    
    
        </section>

    
  
</main>

<style>
    
</style>