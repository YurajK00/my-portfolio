<script>

    export let y;
    let tabs = [
        {name: 'Projects', link:'#projects'},
        {name: 'About me' ,link:'/Aboutme'}

    ]

</script>
<header class = {'sticky  z-[10] top-0 duration-200 px-10 flex items-center justify-between border border-solid h-16 py-15' + ( y > 0 ? 'bg-slate-950 border-violet-950' : 'bg-transport border-opaque'

) }>
    <h1 class = "font-medium px-4"> 
        <b class = "font-bold poppins text-3xl">Yuraj</b> <span class ="text-2xl">Kharche</span>
    </h1>
    <div class ="sm:flex ml-auto pr-10 items-center gap-4 hidden">
        {#each tabs as tab, index}
        <a href= {tab.link} class =" text-2xl duration-200 hover:text-violet-400 poppins">
            <p>{tab.name}</p>
        </a>
        {/each}
    </div>
   
    <a href ="https://drive.google.com/file/d/1oZ6o-DFNZvlwkuXfOK50ZSSK3qF65qmK/view?usp=drive_link" 
    target = "_blank"
    class ="overflow-hidden relative mt-2 px-4 py-2 group rounded-full bg-white text-slate-950">

        <div class= "absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"></div>
        <h2 class = " relative z-10 poppins text-xl"> My Resume <sup><span class= "text-xs scale-75 pl-0.5">
            <i class = "fa-solid fa-arrow-up-right-from-square text-xs scale-[85%]"/>
          </span></sup> 
        </h2>

    </a>
</header>