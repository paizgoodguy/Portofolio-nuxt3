<template>
    <div>
      <div class="page overflow-hidden" >
  
          <div class="text-center">
            <p class="font-bold text-2xl mt-2">Some of my work.</p>
          </div>
          <div class="flex items-center justify-center  ">
            <div class="container mt-16 p-16 relative entering">
              <div class="flex flex-row space-x-4">
                <!-- First Col -->
                <div class="flex w-full flex-col space-y-8">
                  <div
                    class="h-36 rounded-lg bg-red-500 overflow-hidden hover:scale-125 hover:z-10 hover:duration-300 hover:ease-out duration-200 entering1"
                  ></div>
                  <div class="h-96 rounded-lg overflow-hidden hover:scale-125 hover:z-10 hover:duration-300 hover:ease-out duration-200 entering2">
                    <img
                      src="@/assets/img/bunga.jpeg"
                      class=""
                      style="position: relative; top: -5rem"
                      alt=""
                    />
                  </div>
                </div>
                <!-- Sec Col -->
                <div class="flex w-full flex-col space-y-4 ">
                  <div
                    class="h-96 rounded-lg bg-blue-500 overflow-hidden hover:scale-125 hover:z-10 hover:duration-300 duration-200"
                  ></div>
                  <div class="h-40 rounded-lg overflow-hidden hover:scale-125 hover:z-10 hover:duration-300 hover:ease-out duration-200 entering3">
                    <img
                      src="@/assets/img/chair_TG.png"
                      alt=""
                      class="relative"
                      style="position: relative; top: -2rem"
                    />
                  </div>
                </div>
                <!-- Third Col -->
                <div class="flex w-full flex-col space-y-4 ">
                  <div class="h-full rounded-lg overflow-hidden hover:scale-125 hover:z-10 hover:duration-300 hover:ease-out duration-200 entering4">
                    <img
                      src="@assets/img/Shrine_lamp.png"
                      alt=""
                      style="position: relative; top: -1rem"
                      class="hover:absolute"
                    />
                  </div>
                  <div
                    class="h-full rounded-lg bg-green-500 overflow-hidden hover:scale-125 hover:z-10 hover:duration-300 hover:ease-out duration-200"
                  ></div>
                </div>
              </div>
            </div>
          </div>
        </div>
  
    
    </div>
  </template>
  
  <script>
  export default {
    methods: {

      },

  };
  </script>
  
  <style scoped>
  
  /* .entering {
    animation: entering 1s;
  
  
  }
  
  @keyframes entering {
    from {opacity: 0;}
    to {opacity:1;}
  }
  
  .entering1 {
    animation: entering1 1s;
  
  }
  
  @keyframes entering1 {
    from {transform: translateY(-10rem);}
    to {transform: translateY(0);}
  }
  
  .entering2 {
    animation: entering2 1s;
  
  }
  
  @keyframes entering2 {
    from {transform: translateX(-20rem);}
    to {transform: translateX(0);}
  }
  
  .entering3 {
    animation: entering3 1s;
  
  }
  
  @keyframes entering3 {
    from {transform: translateY(60rem);}
    to {transform: translateY(0);}
  }
  .entering4 {
    animation: entering4 1.4s;
  
  }
  
  @keyframes entering4 {
    from {transform: translateX(20rem);}
    to {transform: translateX(0);}
  
  } */
  </style>
  