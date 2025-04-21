<script>
    import UserProfile from "./Home/UserProfile.svelte";
    import Welcome from "./Welcome/Welcome.svelte";
    import FeaturedProjects from "./Projects/FeaturedProjects.svelte";
    import Expnew from "./Projects/Expnew.svelte";
    import Skills from "./Projects/Skills.svelte";
    </script>
    
    <main class="flex flex-col items-center justify-center mx-auto max-w-[700px] px-6 lg:px-10 py-16">
        <section id="home" class="w-full">
            <UserProfile />
        </section>
        
        <section id="about" class="w-full mb-5">
            <Welcome />
        </section>

        <section id="experience" class="w-full mb-5">
            <h1 class="text-xl md:text-2xl font-bold text-white mb-2 ">Experience</h1>
            <Expnew />
        </section>

        <section class="w-full mb-5">
            <Skills />
        </section>

        <section id="projects" class="w-full mb-5">
            <FeaturedProjects />
        </section>

       
    
       
        

        
    </main>
    
    <style>
        /* You can add additional styling here if needed */
    </style>