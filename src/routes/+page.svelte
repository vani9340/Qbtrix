   <style lang="postcss">
    :global(html) {
      background-color: #101010;
      color: white;
      font-family: 'Noto Sans', 'sans-serif';
    }

  </style> 
  <script>
  import Hero from '$lib/hero.svelte'
  import Cmp1 from '$lib/Cmp1.svelte' 
  import Cmp2 from '$lib/Cmp2.svelte'
  import Cmp3  from '$lib/Cmp3.svelte'
  import Cmp4 from '$lib/Cmp4.svelte'
  import Cmp5 from '$lib/Cmp5.svelte'
  import Cmp6 from '$lib/Cmp6.svelte'
  import Footer from '$lib/Footer.svelte'
  </script>


  <!-- hero section -->
 <Hero/>
 

  <!-- zoom and logos. -->
  <Cmp1/>

  <!-- mission section -->
  <Cmp2/>

<!-- box design -->
<div class='flex gap-[24px] px-[10.4166vw] mt-[120px] '>
  <!-- our services -->
  <div>
  <Cmp3/>
<!-- end of services.. -->
<!-- new box project -->
<Cmp4/>
</div>
<!-- end of two boxes -->
<!-- who we are box -->
<Cmp5/>

</div>

<!-- languages -->
<Cmp6/>


<!-- footer -->

<Footer/>


