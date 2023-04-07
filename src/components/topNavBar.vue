<template>
  <!--navbar-->
  <div
    class="
      fixed
      top-0
      left-0
      w-screen
      h-[64px]
      bg-blue-900/50
      backdrop-filter backdrop-blur-sm
    "
  ></div>

  <!--nav icon general positioning-->
  <div>
    <!--add ease-->
    <a class="fixed left-[16px] top-[16px]" href="/">
      <!--HOME-->
      <img
        src="/public/re-event.png"
        alt="Home"
        class="
          w-[32px]
          h-[32px]
          opacity-75
          hover:w-[35px]
          hover:h-[35px]
          hover:translate-x-[-1.5px]
          hover:translate-y-[-1.5px]
          hover:opacity-100
        "
      />
    </a>
    <a
      class="fixed right-[32px] top-[16px]"
      href="https://github.com/re-event/re-event.github.io"
      target="_blank"
    >
      <!--GITHUB-->
      <img
        src="/public/github.svg"
        alt="GitHub"
        class="
          w-[32px]
          h-[32px]
          opacity-75
          hover:w-[35px]
          hover:h-[35px]
          hover:translate-x-[1.5px]
          hover:translate-y-[-1.5px]
          hover:opacity-100
        "
      />
    </a>
  </div>
</template>