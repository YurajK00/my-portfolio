<script>
    import "../app.css";
    import Footer from "$lib/components/Footer.svelte";
    import Header from  "$lib/components/Header.svelte";
    import { Router, Link, Route } from "svelte-routing";
    import Aboutme from "$lib/components/Aboutme.svelte";

    let y;
    let innerHeight = 2
    let innerWidth = 2

    function goTop() {
        document.body.scrollIntoView()

    }


  </script>

  <Router>
    <Route path= "Aboutme" component={Aboutme} />
  </Router>
  <div class = "relative flex flex-col mx-auto w-full text-sm
  sm:text-base min-h-screen">

  <div class = {"fixed bottom-0 w-full duration-200 flex p-10 z-[10] " +( y > 0 ? 'opacity-full pointer-events-auto ': 'pointer-events-none opacity-0'
    
  )}>
    <button on:click={goTop} class = "ml-auto rounded-full aspect-square bg-slate-900 text-green-400 px-3 sm:px-4
    hover:bg-slate-800 cursor-pointer">

     <i class = "fa-solid fa-arrow-up grid place-center aspect-sqaure" /> 
    
    </button>
  </div>
  <Header y={y} />
  <slot />
  <Footer />

</div>

<svelte:window bind:scrollY= {y} bind:innerHeight bind:innerWidth/>
