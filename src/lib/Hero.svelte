<script>
import logo from '../images/logo.svg';
import Q from '../images/Q.svg'
import mail from '../images/mail.svg'
</script>

<!-- hero section -->
<nav class='flex justify-between text-white px-[10.4166vw] pt-[26px]'>
    <!-- svelte-ignore a11y-img-redundant-alt -->
   <img src={logo} alt="My Image"/>

     <div>
     <h1 class='flex text-[1rem] font-Noto_sans font-medium'>Let's talk! <h1> 
       <img src={mail} alt='mail' class='ml-[11.5px]'/>
     </div>
  
 </nav>
 <!-- part1 -->
 <div class='flex flex-col items-center mt-[65px]'>
 <!-- svelte-ignore a11y-missing-attribute -->
 <img src={Q}/>
 <p class='mt-[32px] font-Noto_sans text-[1rem] leading-[1.75rem] max-w-[754px] min-h-[56px] text-center text-[#AEAEAE]'>Redefining Software Development: Empowering Organizations with Innovative Strategies, Agile Processes, and Cutting-Edge Technologies for Efficient, High-Impact Outcomes</p>
 <button class='mt-[2rem] py-[1rem] px-[2rem] border-[#414141] border-[1px] bg-gradient-to-b from-[#252525] to-[#101010] rounded-full'>Start a Project</button>
 </div>