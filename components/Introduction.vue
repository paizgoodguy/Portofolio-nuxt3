<template>
  <div class="bg-gray-100">
    <div class="page">
      <div class="flex items-center justify-center pt-20">
        <div class="flex-1">
          <p class="text-5xl mx-auto text-center pb-4">Hello, my name is</p>
          <p class="text-4xl font-bold mx-auto text-center pb-4">
            M. Faizal Azzam
          </p>
          <div class="container m-auto">
            <div class="flex">
              <div class="flex-1 bg-gray-200 shadow-inner rounded-lg">
                <img
                  src="~/assets/img/wujudsaya.png"
                  class="object-scale-down h-96 w-full"
                  alt=""
                />
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="container mx-auto pb-4 mt-8">
        <p class="text-2xl font-light text-center">
          Born and raised in Indonesia. I am a passionate young adult who aspire
          to be something greater <br />
          every day Ever since childhood, i've always in love with video game,
          and it force me to learn english
          <br />
          last education is at Bawang 1 National Vocation school and software
          development as major. <br />Fluent in 3 languages. Curretly undergoing
          internship in P.T. Traspac Makmur Sejahtera
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {},
};
</script>

<style scoped>
.bg-profile {
  animation: bg-profile 1s;
}

@keyframes bg-profile {
  from {
    transform: translateX(-20rem);
  }
  to {
    transform: translateX(0);
  }
}
</style>
