<script>
    import { ArrowUpRightIcon } from 'svelte-feather-icons';

</script>


<main>
    <section  class="text-white"> 
        <div class="flex items-center justify-between mt-5 w-full gap-x-20  md:gap-x-80">
            <h1 class="text-xl md:text-2xl font-bold">Projects</h1>
            <div class="flex items-center">
                <a 
                    href="/project" 
                    class="text-[#A8A8A8] hover:text-gray-500 underline text-sm md:text-base"
                >
                    view all
                </a> 
                <a href="/project" class="ml-1">
                    <ArrowUpRightIcon class="text-[#A8A8A8] hover:text-white w-4 h-4"/> 
                </a>
            </div>
        </div>

        <div class="py-4 grid grid-cols-1 sm:grid-cols-2 gap-4">
            <!-- Project 1 -->
           
                <div class="p-0 hover:scale-105 transform transition-transform duration-300">
                    <div class="bg-[#232323] rounded-t-lg overflow-hidden flex items-center justify-center w-full h-60">
                        <img src="/assets/profess.webp" alt="charity-today" class="object-cover w-full h-full" width="300" height="240">        
                    </div>
                    <h1 class="mt-2">ProfessStar <span class="font-bold">|</span> <a class="text-[#A8A8A8] underline" target="_blank" href="https://ai-rate-my-professor-beta.vercel.app/">view</a></h1>
                    <p class="text-[#A8A8A8]">AI Rate My professor chatbot</p>
                </div>
         
           
            <!-- Project 2 -->
           
                <div class="p-0 hover:scale-105 transform transition-transform duration-300">
                    <div class="bg-[#232323] rounded-t-lg overflow-hidden flex items-center justify-center w-full h-60">
                        <img src="/assets/fullyb.webp" alt="fully-beyond" class="object-cover w-full h-full">
                    </div>
                    <h1 class="mt-2">FullyBeyound <span class="font-bold">|</span> <a class="text-[#A8A8A8] underline" target="_blank" href="https://fullybeyond.vercel.app/">view</a></h1>
                    <p class="text-[#A8A8A8]">A website created for CSUF first designathon</p>
                </div>
          
    
            <!-- Project 3 -->
           
                <div class="p-0 hover:scale-105 transform transition-transform duration-300">
                    <div class="bg-[#232323] rounded-t-lg overflow-hidden flex items-center justify-center w-full h-60">
                        <img src="/assets/ctr.webp" alt="charity-today" class="object-cover w-full h-full">
                    </div>
                    <h1 class="mt-2">CharityToday <span class="font-bold">|</span> <a class="text-[#A8A8A8] underline" target="_blank" href="https://www.figma.com/design/OYRdwpHQFHWVQwTPt9sDm9/CHARITY-TODAY-PRESENTATION?node-id=0-1&t=zIgsdFxN3GActlkE-1">case study</a></h1>
                    <p class="text-[#A8A8A8]">A mockup created during the social justice and engineering competition</p>
                </div>
          
            
            <!-- Project 4 -->
          
                <div class="p-0 hover:scale-105 transform transition-transform duration-300">
                    <div class="bg-[#232323] rounded-t-lg overflow-hidden flex items-center justify-center w-full h-60">
                        <img src="/assets/saasf.webp" alt="charity-today" class="object-cover w-full h-full">
                    </div>
                    <h1 class="mt-2">FlashCard Generator <span class="font-bold">|</span> <a class="text-[#A8A8A8] underline" target="_blank" href="https://flashcards-saas-weld.vercel.app/">view</a></h1>
                    <p class="text-[#A8A8A8]">Full Stack web application that generates flashcard based on user input</p>
                </div>
         
        </div>
    </section>

</main>

<style></style>