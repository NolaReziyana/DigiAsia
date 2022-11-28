<!-- <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
<script>
	var licenses = new Vue({
        el: '#licenses',
        data: {
			lists: [
				{image: '@/assets/images/Lisensi KasPro.png'},
				{image: '@/assets/images/Lisensi KreditPro.png'},
				{image: '@/assets/images/Lisensi RemitPro.png'},
				{image: '@/assets/images/Lisensi DigiBos.png'},
			]
		}
	})
</script> -->

<template>
  <div class="flex flex-row mt-10">
    <div class="flex justify-start">
      <img
        src="@/assets/images/Ornamen Bulat Bawah.png"
        alt="image"
        width="60px"
        height="50px"
      />
    </div>
    <div class="flex flex-1 flex-col justify-center mt-9 mr-12">
      <div class="flex justify-center">
        <img
          src="@/assets/images/LIST UNGU.png"
          alt="image"
          width="50px"
          height="30px"
        />
      </div>
      <div class="flex flex-col mt-2 mr-12 ml-12">
        <h1 class="text-center text-xl font-bold text-black">Licenses</h1>
      </div>
    </div>
  </div>
  <div class="flex flex-row mt-10 ml-7 mr-10 mb-10">
    <div class="card h-[100px] w-[200px] bg-base-100 shadow-xl ml-3">
      <figure class="px-5 pt-5 mb-2">
        <img
          src="@/assets/images/Lisensi KasPro.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
    </div>
    <div class="card h-[100px] w-[200px] bg-base-100 shadow-xl ml-3">
      <figure class="px-5 pt-5 mb-2">
        <img
          src="@/assets/images/Lisensi KreditPro.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
    </div>
    <div class="card h-[100px] w-[200px] bg-base-100 shadow-xl ml-3">
      <figure class="px-5 pt-5 mb-2">
        <img
          src="@/assets/images/Lisensi RemitPro.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
    </div>
    <div class="card h-[100px] w-[200px] bg-base-100 shadow-xl ml-3">
      <figure class="px-5 pt-5 mb-2">
        <img
          src="@/assets/images/Lisensi DigiBos.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
    </div>
  </div>
  <!-- <div id="licenses">
    <div class="flex flex-row mt-10 ml-7 mr-10 mb-10"> 
      <div v-for="(list,index) in lists" class="card h-[100px] w-[200px] bg-base-100 shadow-xl ml-3">
          <figure class="px-5 pt-5 mb-2">
            <img
              src="{{list.image}}"
              alt="image"
              class="rounded-xl"
            />
          </figure>
      </div>
    </div>  
  </div> -->
</template>
