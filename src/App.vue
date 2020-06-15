<template>
  <div id="app">

     <div class="flex">
        <div class="flex-initial w-1/4 border-2 border-gray-200 bg-white shadow-md h-full">
            
           <div id="nav">
                <router-link to="/dashboard">
                    <div class="border-b-2 border-gray-200 p-5 clearfix">
                        <img src="https://demos.creative-tim.com/tailwindcss-starter-project/_next/static/images/team-4-470x470-4ef82ef45a9598d24c4c951ead4d626a.png" class="float-left mr-2 shadow-lg rounded-full w-10 h-10" />
                        <h6 class="font-bold float-left pt-2">DASHBOARD</h6>
                    </div>
                </router-link>

                <router-link to="/products">
                    <div class="border-b-2 border-gray-200 p-5 clearfix">
                        <img src="https://demos.creative-tim.com/tailwindcss-starter-project/_next/static/images/team-4-470x470-4ef82ef45a9598d24c4c951ead4d626a.png" class="float-left mr-2 shadow-lg rounded-full w-10 h-10" />
                        <h6 class="font-bold float-left pt-2">PRODUCTS</h6>
                    </div>
                </router-link>


                <router-link to="/customers">
                    <div class="border-b-2 border-gray-200 p-5 clearfix">
                        <img src="https://demos.creative-tim.com/tailwindcss-starter-project/_next/static/images/team-4-470x470-4ef82ef45a9598d24c4c951ead4d626a.png" class="float-left mr-2 shadow-lg rounded-full w-10 h-10" />
                        <h6 class="font-bold float-left pt-2">CUSTOMERS</h6>
                    </div>
                </router-link>

                <router-link to="/suppliers">
                    <div class="border-b-2 border-gray-200 p-5 clearfix">
                        <img src="https://demos.creative-tim.com/tailwindcss-starter-project/_next/static/images/team-4-470x470-4ef82ef45a9598d24c4c951ead4d626a.png" class="float-left mr-2 shadow-lg rounded-full w-10 h-10" />
                        <h6 class="font-bold float-left pt-2">SUPPLIERS</h6>
                    </div>
                </router-link>

                <router-link to="/about">
                    <div class="border-b-2 border-gray-200 p-5 clearfix">
                        <img src="https://demos.creative-tim.com/tailwindcss-starter-project/_next/static/images/team-4-470x470-4ef82ef45a9598d24c4c951ead4d626a.png" class="float-left mr-2 shadow-lg rounded-full w-10 h-10" />
                        <h6 class="font-bold float-left pt-2">ABOUT</h6>
                    </div>
                </router-link>

           </div>


        </div>

        <div class="flex-initial w-3/4 ml-5 border-2 border-gray-200 bg-white shadow-md p-4 max-h-full">
            <router-view/>
        </div>
    </div>

  </div>
</template>

<style>

@import url("./assets/css/tailwind.css");
body {
    background: #ebecec !important;
    padding: 75px;
}

#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    /*text-align: center;*/
    color: #2c3e50;
}


#nav a.router-link-exact-active {
    color: #fff;
}

#nav a.router-link-exact-active div {
    background: #8ad4b2;
}

</style>
