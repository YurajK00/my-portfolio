<script>
    import Step from "./Step.svelte"
let steps = [
    {name: 'Data Mining and Big Data', icon: 'fa-solid fa-cart-shopping'},
    {name: 'AdoptMe', image: '/images/pawIcon.png'},
    {name: 'Naive-Bayes Algorithm', icon: 'fa-solid fa-diagram-project'}
];
</script>


<section id ="projects" class = "py-20 lg:py-32 flex flex-col gap-24">
    <div class = "flex flex-col gap-2 text-center">
        <h6 class = "text-lg sm:text-xl md:text-2xl">
    A few of my creative endeavors
        </h6>
        <h3 class = "font-semibold text-3xl sm:text-4xl md:text-5xl"> Curious to <span class = "poppins text-violet-400"> see</span> my work?</h3>
       
    </div>
    <a href = "https://www.youtube.com/watch?v=xvFZjo5PgG0" target= "_blank" class = " mx-auto px-4 py-2 rounded-md border border-solid border-white flex items-center gap-2 -mb-4 sm:-mb-0 -mt-10 hover:border-violet-700 duration-100 ">
        <i class = "fa-regular fa-circle-play"></i>
        <p>Watch my video</p>
     </a>
    
    
    <div class =" grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10">
        <Step step={steps[0]}> 
            <p> </p>
        </Step>
        <Step step={steps[1]}> 
            <p>AdoptMe is a Full Stack <strong class = "text-violet-400"> SvelteKit, Node.js + Express.js</strong> website that allows the loged in user to
                publish and view articles regarding animal adoption and animal nourishment. It utilizes the <strong class = "text-violet-400"> MySQL database system </strong> to store and retrieve the required articles 
                and also customizing the user profile.
        </Step>
        <Step step={steps[2]}> 
            
        </Step>
    </div>
    
    
    
        </section>