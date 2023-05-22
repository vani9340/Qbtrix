   <style lang="postcss">
    :global(html) {
      background-color: #101010;
      color: white;
      font-family: 'Noto Sans', 'sans-serif';
    }

  </style> 
  <script>
    	import Layout from './+layout.svelte';
    import logo from '../images/logo.svg';
    import Q from '../images/Q.svg'
    import mail from '../images/mail.svg'
    import zoom from '../images/zoom.svg'
    import microsoft from '../images/microsoft.svg'
    import google from '../images/google.svg'
    import img1 from '../images/1.svg'
    import img2 from '../images/2.svg'
    import img3 from '../images/3.svg'
    import img4 from '../images/4.svg'
    import img5 from '../images/5.svg'
    import img6 from '../images/6.svg'
    import img7 from '../images/7.svg'
    import arrow from '../images/arrow.svg'

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

  <!-- zoom and logos. -->
<div class='flex justify-evenly items-center mt-[72px] px-[17.1527vw]'>
  <!-- svelte-ignore a11y-missing-attribute -->
  <img src={zoom} alt="zoom"/>
  <img src={microsoft} alt="micro"/>
  <img src={google} alt="google"/>
  <img src={zoom} alt="zoom"/>
  <img src={google} alt="google"/>
  <!-- <img/>
  <img/>
  <img/> -->
  
</div>








<!-- part-2 -->
<div class='mt-[100px] flex flex-col items-center'>
  <div class='text-center'>
    <h1 class='text-[2rem] font-[900] leading-[2.4rem]'>Our Mission</h1>
    <p class='text-[#AEAEAE] mt-[20px] font-normal text-[1rem] leading-[1.75rem] max-w-[752px] min-h-[112px]'>Lörem ipsum hexavugon selig. Vungen köledes de antisade. Dik tir feskap yrkessåpa i dinyssade. Sysk lufav decirigon fast nehet. Järade tik. Nyvungen paska, det vill säga nynesamma. Vases. Sor tibyska de paralig, syvudäskade polyn. Hundvissla vivis en ede, till previs, som decikonade. Yrinde an kroktiga miplavis orade. Serade vuskade, även om tänott i prenar. Lytt pimpa. </p>
  </div>
</div>



<!-- box design -->
<div class='flex gap-[24px] px-[10.4166vw] mt-[120px] '>
  <!-- our services -->
  <div>
  <div class=' pl-[32px] pr-[40px] flex justify-around items-center max-w-[655px] min-h-[253px] bg-gradient-to-t from-[#252525] to-[#0B0B0B] border-[#414141] border-[1px] rounded-[24px] '>
    <div>
      <h1 class='font-lato font-bold text-[2.5rem] leading-[2.875rem]'>Our Services</h1>
      <button class='mt-[20px] rounded-full border-white border-[1px] px-[2rem] py-[14px] font-medium text-[1rem] leading-[1.375rem]'>Services</button>
    </div>

    <div>

      <div class='flex justify-between gap-[131px] border-b-[1px] border-[#FFFFFF]'>
        <div class='max-w-[217px] min-h-[48px]'>
      <h1 class='font-lato font-bold text-[1.125rem] leading-[1.35rem]'>Web Application</h1>
      <p class='pb-[20px] mt-[10px] text-[#E4E4E4] font-normal text-[0.875rem] leading-[1.5rem] font-Noto_sans max-w-[217px] min-h-[48px]'>Lörem ipsum astrobel sar direlig. Kronde est konfoni med kelig.</p>
      <!-- svelte-ignore a11y-missing-attribute -->
    </div>
    <div>
      <img src={arrow} alt='img'/>
    </div>
      <!-- <button><img/></button> -->
    </div>
    <!-- 2nd div start -->
    <div class='flex justify-between mt-[20px]'>
      <div class='max-w-[217px] min-h-[48px]'>
    <h1 class='font-lato font-bold text-[1.125rem] leading-[1.35rem]'>Mobile Application</h1>
    <p class='mt-[10px] text-[#E4E4E4] font-normal text-[0.875rem] leading-[1.5rem] font-Noto_sans '>Lörem ipsum astrobel sar direlig. Kronde est konfoni med kelig.</p>
    <!-- svelte-ignore a11y-missing-attribute -->
  </div>
  <div>
    <img src={arrow} alt='img'/>
  </div>
    <!-- <button><img/></button> -->
  </div>
    </div>
  </div>
<!-- end of services.. -->
<!-- new box project -->
<div class='flex justify-around mt-[20px] items-center max-w-[655px] min-h-[86px] bg-gradient-to-b from-[#101010] to-[#242424] border-[#414141] border-[1px] rounded-[24px]'>
<div>
  <h1 class='text-center'>200+</h1>
  <p>Complite Project</p>
</div>
<div>
  <h1 class='text-center'>1,230</h1>
  <p>Clietn Trusted</p>
</div>
<div>
  <h1 class='text-center'>1,230</h1>
  <p>Clietn Trusted</p>
</div>
</div>


</div>
<!-- end of two boxes -->
<!-- who we are box -->
<div class='px-[32px] flex flex-col justify-center items-start max-w-[461px] min-h-[359px] rounded-[24px] bg-gradient-to-b from-[#101010] to-[#242424] border-[#414141] border-[1px]'>
<h1 class='font-lato font-semibold text-[2rem] leading-[2.4rem]'>Who We are</h1>
<p class='text-[#AEAEAE] mt-[20px] font-normal text-[0.875rem]'>
  Lörem ipsum hexavugon selig. Vungen köledes de antisade. Dik tir feskap yrkessåpa i dinyssade. Sysk lufav decirigon fast nehet. Järade tik. Nyvungen paska, det vill säga nynesamma. Vases. Sor tibyska de paralig, syvudäskade polyn. Hundvissla vivis en ede, till previs, som decikonade. Yrinde an kroktiga miplavis orade. Serade vuskade, även om tänott i prenar. Lytt pimpa. 
</p>
<button class='mt-[32px] px-[2rem] py-[14px]  rounded-full bg-gradient-to-b from-[#252525] to-[#101010] to-[100%] border-[#414141]'>
About Us
</button>
</div>
<!-- languages -->

</div>

<div class='mt-[24px] mx-[10.4166vw] flex justify-evenly max-w-[1140px] min-h-[120px] bg-gradient-to-b from-[#101010]  to-[#242424] to-[100%] border-[#414141] border-[1px] rounded-[24px]'>
  <img src={img1} alt='1'/>
  <img src={img2} alt='1'/>
  <img src={img3} alt='1'/>
  <img src={img4} alt='1'/>
  <img src={img5} alt='1'/>
  <img src={img6} alt='1'/>
  <img src={img7} alt='1'/>

</div>

<!-- footer -->



