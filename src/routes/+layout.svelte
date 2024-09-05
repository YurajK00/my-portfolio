<script>
    import "../app.css";
    import Footer from "../components/Footer.svelte";
    import Header from  "../components/Header.svelte";

    let y;
    let innerHeight = 2
    let innerWidth = 2

    function goTop() {
        document.body.scrollIntoView()

    }


 
  </script>
  <div class = "relative flex flex-col max-w-[1400px] mx-auto w-full text-sm
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
