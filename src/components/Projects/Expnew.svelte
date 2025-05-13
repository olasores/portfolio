<script>

    const experiences = [
        {
            date: "December 2024 - Present",
            title: "Web Development Intern",
            company: "Future Trends Enterprise",
            description: "Developed and launched web applications for 5+ businesses, streamlining their digital presence and reducing deployment time by 40%. Collaborated with cross-functional teams to enhance user experience and optimize performance."
        },
        {
            date: "August 2024 - November 2024",
            title: "Leadership Fellow",
            company: "Girls Who Code",
            description: "Leading initiatives to empower and educate the next generation of women in technology."
        },
        {
            date: "May 2024 – August 2024",
            title: "Software Engineering Fellow",
            company: "HeadStarter AI",
            description: "Spearheaded the creation of functional prototypes for 5 advanced AI projects, adhering to tight deadlines while fostering collaboration among team members that accelerated overall project delivery speed by 30%."
        },
        {
            date: "June 2024 – August 2024",
            title: "STEM Counselor",
            company: "PlanetBravo",
            description: "Tailored teaching methods to accommodate diverse learning styles, leading to a 25% improvement in comprehension and engagement with STEM concepts among students, as measured by assessment scores."
        }
    ];
</script>

<div class="space-y-8 px-2 text-white">
    
    {#each experiences as experience, i}

            
            <div class="relative pl-8 border-l-2 ">
                
                <div class="absolute w-4 h-4 bg-gray-500 rounded-full -left-[9px] top-0 transform">

                </div>
                <div class="mb-1">
                    <span class="text-sm text-white font-medium">{experience.date}</span>
                </div>
                <h3 class="text-xl font-bold mb-1]">{experience.title}</h3>
                <h4 class="text-lg font-semibold mb-2">{experience.company}</h4>
                <p class="text-base ">{experience.description}</p>
            </div>
 
    {/each}
</div>