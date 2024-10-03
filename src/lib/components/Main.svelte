<script> 


import { Link } from 'svelte-routing'

</script>

<main class="flex flex-col flex-1 p-10">
    <section id="introPage" class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-10 sm:py-14">
        <div class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10">

            <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
                Hi! I'm <span class="poppins text-violet-300">Yuraj</span> Kharche <br/> Full Stack 
                <span class="poppins text-violet-400">Developer</span>
            </h2>
            
            <p class="text-base sm:text-lg md:text-xl">
                My <span class="text-violet-400">favorite tech</span> includes Python, SvelteKit Framework, TailwindCSS, JavaScript (Node.js + Express.js) & PostgreSQL 
            </p>
        
            <a class="shadow-2xl shadow-blue-600/70 mx-auto lg:mr-auto text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white lg:ml-0 text-slate-950 
            cursor-pointer" href = "#" target = "_blank">
                <div class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"></div>

                <h4 class="relative z-9"><b>Get in touch &rarr; </b></h4>
            </a>
        </div>
        <div class="relative shadow-2xl grid place-items-center"> 
            <!-- svelte-ignore a11y-img-redundant-alt -->
            <img src = {"images/Photocopy.jpg.png"} alt = "Profile image" class = "object-cover z-[2] max-h-[70vh]"/> 
    </div>
        </section>

     



   <section>
<h5 class = "text-2xl sm:text-3xl font-semibold text-center poppins"> The <span class= "text-violet-400 poppins"> Complete</span> Package</h5>
<div  class = "flex flex-col overflow-x-scroll gap-10 max-w-[800px] mx-auto w-full">

    <table class = "bg-white text-slate-700 rounded text-center">
        <thead class = "border-b border-solid border-slate-200">
            <tr class ="">
                <th></th>
                <th class = "whitespace-nowrap p-2 px-4">Candidate #1</th>
                <th class = "whitespace-nowrap p-2 px-4">Candidate #2</th>
                <th class = "whitespace-nowrap p-2 px-4">Candidate #3 </th>
                <th class = "whitespace-nowrap bg-violet-700 text-white p-4 px-8 ">Me </th>
</tr>
        </thead>
        <tbody>
            <tr class = "border-b border-solid border-slate-200">
                <td class = "border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm whitespace-nowrap "> Dedication</td>
                <td><i class = "fa-solid fa-xmark text-slate-500"></i></td>
                <td><i class = "fa-solid fa-check text-slate-500"></i></td>
                <td><i class = "fa-solid fa-xmark text-slate-500"></i></td>
                <td><i class = "fa-solid fa-check text-green-500"></i></td>
            </tr>
            <tr class = "border-b border-solid border-slate-200">
                <td class = "border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm whitespace-nowrap"> Critical Thought </td>
                <td><i class = "fa-solid fa-check text-slate-500"></i></td>
                <td><i class = "fa-solid fa-xmark text-slate-500"></i></td>
                <td><i class = "fa-solid fa-check text-slate-500"></i></td>
                <td><i class = "fa-solid fa-check text-green-500"></i></td>
            </tr>
            <tr class = "border-b border-solid border-slate-200">
                <td class = "border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm whitespace-nowrap"> Interpersonal Skills </td>
                <td><i class = "fa-solid fa-xmark text-slate-500"></i></td>
                <td><i class = "fa-solid fa-check text-slate-500"></i></td>
                <td><i class = "fa-solid fa-check text-slate-500"></i></td>
                <td><i class = "fa-solid fa-check text-green-500"></i></td>
            </tr>
            <tr class = "border-b border-solid border-slate-200">
                <td class = "border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm whitespace-nowrap">Programming Ability</td>
                <td><i class = "fa-solid fa-check text-slate-500"></i></td>
                <td><i class = "fa-solid fa-check text-slate-500"></i></td>
                <td><i class = "fa-solid fa-xmark text-slate-500"></i></td>
                <td><i class = "fa-solid fa-check text-green-500"></i></td>
            </tr>
        </tbody>
    </table>
</div>
<div class = "mx-auto -mt-12 italic sm:hidden opacity-50">
    <p>Scroll to see more &rarr;</p>
</div>
<p class = "text-xl sm:text-2xl text-center">So why not invest?</p>

    </section>
</main>
