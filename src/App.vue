<template>

    <div class="flex">
        <div class="flex-initial w-1/4 border-2 border-gray-200 bg-white shadow-md h-full">
            
           <div v-for="(list, key) in lists" :key="key" class="border-b-2 border-gray-200 p-5 clearfix">
                <img src="https://demos.creative-tim.com/tailwindcss-starter-project/_next/static/images/team-4-470x470-4ef82ef45a9598d24c4c951ead4d626a.png" class="float-left mr-2 shadow-lg rounded-full w-16 h-16" />
                <h6 class="font-bold">Name {{ list }}</h6>
                <p class="font-normal text-sm text-green-700">Detail of name {{ list }}</p>
           </div>


        </div>

        <div class="flex-initial w-3/4 ml-5 border-2 border-gray-200 bg-white shadow-md p-4 max-h-full">

        </div>
    </div>

</template>

<script>

export default {

  name: 'App',

  components: {

  },

  data() {
    return {
        lists: [1,2,3,4,5]
    }
  }


}
</script>

<style>
    @import url("./assets/css/tailwind.css");

    body {
        background: #ebecec !important;
        padding: 75px;
    }

</style>
