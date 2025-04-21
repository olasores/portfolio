<script>
    // Consolidated skills list without categories
    const skills = [
      "HTML", "CSS", "JavaScript", "React", "Svelte", "Tailwind CSS", 
      "Node.js", "Express", "Python", "MongoDB", "SQL",
      "TypeScript", "Git", "GitHub", "Responsive Design", 
      "RESTful APIs", "Webpack", "NPM", "Docker", "AWS"
    ];
    
    // For animation
    let visible = false;
    
    function handleIntersection(element) {
      const observer = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
          if (entry.isIntersecting) {
            visible = true;
            observer.unobserve(element);
          }
        });
      }, { threshold: 0.1 });
      
      observer.observe(element);
      
      return {
        destroy() {
          observer.disconnect();
        }
      };
    }
  </script>
  
  <section id="skills" class="w-full">
    <h2 class="text-xl md:text-2xl font-bold text-white mb-8">Skills & Technologies</h2>
    
    <div class="flex flex-wrap gap-3" use:handleIntersection>
      {#each skills as skill, skillIndex}
        <span 
          class="px-4 py-2 bg-gray-800/80 text-gray-300 rounded-full text-sm hover:bg-gray-700 transition-all duration-300 hover:scale-105 hover:text-white animate-fade-in"
          style="animation-delay: {skillIndex * 50}ms;"
          class:is-visible={visible}
        >
          {skill}
        </span>
      {/each}
    </div>
  </section>
  
  <style>
  </style>