<script>
  export default {
    data() {
      return {
        
      }
    },

  }
</script>


<template>
  <!--order of components is reversed-->
  <!-- static fixed absolute relative sticky -->
  <div class="translate-y-[64px]"> <!--content-->
    <p>
      Lorem<br>ipsum<br>dolor<br>sit<br>amet<br>consectetur<br>adipisicing<br>elit.<br>Neque<br>provident<br>odit<br>laudantium<br>at<br>exercitationem<br>quaerat<br>ad<br>dolorum<br>itaque<br>qui<br>ex,<br>ullam<br>iusto<br>amet<br>minima<br>aliquid<br>iure<br>velit<br>unde<br>voluptates<br>quisquam.
    </p>
  </div>
  <div class="fixed top-0 left-0"> <!--TOP NAV BAR-->
    <svg class="w-screen h-[64px]">
      <rect class="w-screen h-[64px] fill-blue-900 opacity-50 backdrop-blur-xl"/>
    </svg>
    <div> <!--nav icon general positioning-->
      <!--add ease-->
      <a class="absolute left-[16px] top-[16px]" href="/"> <!--HOME-->
        <img src="/public/re-event.png" alt="Home" class="w-[32px] h-[32px] opacity-75 hover:w-[35px] hover:h-[35px] hover:translate-x-[-1.5px] hover:translate-y-[-1.5px] hover:opacity-100">
      </a>
      <a class="absolute right-[32px] top-[16px]" href="https://github.com/re-event/re-event.github.io" target="_blank"> <!--GITHUB-->
        <img src="/public/github.svg" alt="GitHub" class="w-[32px] h-[32px] opacity-75 hover:w-[35px] hover:h-[35px] hover:translate-x-[1.5px] hover:translate-y-[-1.5px] hover:opacity-100">
      </a>
    </div>
  </div>
  
</template>