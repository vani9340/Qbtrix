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

  </script>


  <!-- hero section -->
 
  <nav class='flex justify-between text-white px-[10.4166vw] pt-[26px]'>
     <!-- svelte-ignore a11y-img-redundant-alt -->
    <img src={logo} alt="My Image"/>

      <div>
      <h1 class='flex'>Let's talk <h1> 
        <img src={mail} alt='mail'/>
      </div>
   
  </nav>
  <!-- part1 -->
  <div class='flex flex-col items-center'>
  <!-- svelte-ignore a11y-missing-attribute -->
  <img src={Q}/>
  <p class='font-Noto_sans text-[#AEAEAE]'>Redefining Software Development: Empowering Organizations with Innovative Strategies, Agile Processes, and Cutting-Edge Technologies for Efficient, High-Impact Outcomes</p>
  <button class='py-[1rem] px-[2rem] border-[#414141] border-[1px] bg-gradient-to-b from-[#252525] to-[#101010] rounded-full'>Start a Project</button>
  </div>

  <!-- zoom and logos. -->
<div class='flex justify-center'>
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
<div>
  <div class='text-center'>
    <h1>Our Mission</h1>
    <p class='text-[#AEAEAE]'>Lörem ipsum hexavugon selig. Vungen köledes de antisade. Dik tir feskap yrkessåpa i dinyssade. Sysk lufav decirigon fast nehet. Järade tik. Nyvungen paska, det vill säga nynesamma. Vases. Sor tibyska de paralig, syvudäskade polyn. Hundvissla vivis en ede, till previs, som decikonade. Yrinde an kroktiga miplavis orade. Serade vuskade, även om tänott i prenar. Lytt pimpa. </p>
  </div>
</div>



<!-- box design -->
<div class='flex gap-[24px] px-[10.4166vw]'>
  <!-- our services -->
  <div>
  <div class='max-w-[655px] min-h-[253px] bg-gradient-to-t from-[#252525] to-[#0B0B0B] border-[#414141] border-[1px] rounded-[24px] flex justify-between'>
    <div>
      <h1>Our Services</h1>
      <button class='rounded-full border-white border-[1px]'>Services</button>
    </div>
    <div>
      <div>
      <h1>Web Application</h1>
      <p class='text-[#E4E4E4]'>Lörem ipsum astrobel sar direlig. Kronde est konfoni med kelig.</p>
      <!-- svelte-ignore a11y-missing-attribute -->
      <!-- <button><img/></button> -->
    </div>
    <div>
      <h1>Mobile Application</h1>
      <p class='text-[#E4E4E4]'>Lörem ipsum astrobel sar direlig. Kronde est konfoni med kelig.</p>

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
<div class='flex flex-col justify-center items-start max-w-[461px] min-h-[359px] rounded-[24px] bg-gradient-to-b from-[#101010] to-[#242424] border-[#414141] border-[1px]'>
<h1>Who We are</h1>
<p class='text-[#AEAEAE]'>
  Lörem ipsum hexavugon selig. Vungen köledes de antisade. Dik tir feskap yrkessåpa i dinyssade. Sysk lufav decirigon fast nehet. Järade tik. Nyvungen paska, det vill säga nynesamma. Vases. Sor tibyska de paralig, syvudäskade polyn. Hundvissla vivis en ede, till previs, som decikonade. Yrinde an kroktiga miplavis orade. Serade vuskade, även om tänott i prenar. Lytt pimpa. 
</p>
<button class='px-[2rem] py-[14px]  rounded-full bg-gradient-to-b from-[#252525] to-[#101010] to-[100%] border-[#414141]'>
About Us
</button>
</div>
<!-- languages -->

</div>

<div class=' mx-[10.4166vw] flex justify-evenly max-w-[1140px] min-h-[120px] bg-gradient-to-b from-[#101010]  to-[#242424] to-[100%] border-[#414141] border-[1px] rounded-[24px]'>
  <img src={img1} alt='1'/>
  <img src={img2} alt='1'/>
  <img src={img3} alt='1'/>
  <img src={img4} alt='1'/>
  <img src={img5} alt='1'/>
  <img src={img6} alt='1'/>
  <img src={img7} alt='1'/>

</div>

<!-- footer -->



