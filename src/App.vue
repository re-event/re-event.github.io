<script>
import topNavBar from '/src/components/topNavBar.vue';

export default {
  data() {
    return {

    };
  },
  components: {
    topNavBar,
  },
};
</script>

<template>
  <!-- static fixed absolute relative sticky -->
  <div class="translate-y-[64px]">
    <div> <!--title-->
      <br>
      <img src="/public/Main-UI.png" class="flex w-[45%] h-[45%] mx-auto">
      <h1 class="text-[56px] text-center">Re-Event.</h1> 
    </div>
    <div> <!--content-->
      <p>
        Lorem<br />ipsum<br />dolor<br />sit<br />amet<br />consectetur<br />adipisicing<br />elit.<br />Neque<br />provident<br />odit<br />laudantium<br />at<br />exercitationem<br />quaerat<br />ad<br />dolorum<br />itaque<br />qui<br />ex,<br />ullam<br />iusto<br />amet<br />minima<br />aliquid<br />iure<br />velit<br />unde<br />voluptates<br />quisquam.
      </p>
    </div>
  </div>
  <topNavBar />
</template>
