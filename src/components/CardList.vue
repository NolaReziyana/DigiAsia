<!-- <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
<script>
     var cardlists = new Vue({
        el: '#cardlists',
        data: {
            lists :[
                {image:'@/assets/images/Foto/Foto 1.png', title:'Facility Management', description:'API for services that usage for facilities (apartment, office)'},
                {image:'@/assets/images/Foto/Foto 2.png', title:'KasPro Ecosystem Supply Chain', description: 'API bundle for Business Ecosystem Solution that aligns Principa Distributors Wholesalers, Retailers into ore robust ecosystem & securing risks under one roof.'},
                {image:'@/assets/images/Foto/Foto 3.png', title:'Retail Chain', description:'API bundle for retail chain business contains Customer onboarding, etc.'},
                {image:'@/assets/images/Foto/Foto 4.png', title:'P2P', description:'Financial technology lending that gives lending, insta Imerts without credit cards, cell phone credit and PayLater services.'},
                {image:'@/assets/images/Foto/Foto 5.png', title:'Delivery Service', description:'API for delivery services that provide customers onboarding, payment and wallet services.'},
                {image:'@/assets/images/Foto/Foto 6.png', title:'Transportation', description:'Mobile-based transporting marketplace that allows users to find and book for taxi bike, taxi, and on demand delivery.'},
                {image:'@/assets/images/Foto/Foto 7.png', title:'Biller Management', description:'Customers can explore & embedded each or all of the list of our biller products.'},
                {image:'@/assets/images/Foto/Foto 8.png', title:'QRIS Merchant Aggregator', description:'API bundle for business that need Acquiring merchant and provide QRIS feature requirements.'},
                {image:'@/assets/images/Foto/Foto 9.png', title:'Integrated Cash Management', description:'A tailor-made cash management for corporate customers aiming.to enhance their corporate efficiency.'},
                {image:'@/assets/images/Foto/Foto 10.png', title:'Account Linkage', description:'Linkage accounts and system integration in your application or business, electronic services can already be used.'},
                {image:'@/assets/images/Foto/Foto 11.png', title:'Kaspro Bank', description:'Digitization of Traditional Cooperatives-through secure and seamless platform and technology tie-up.'},
            ]
        }
     })
</script> -->

<template>
  <div class="flex flex-row mt-10">
    <div class="flex flex-1 flex-col justify-center mt-9 ml-12">
      <div class="flex justify-center">
        <img
          src="@/assets/images/LIST UNGU.png"
          alt="image"
          width="60px"
          height="30px"
        />
      </div>
      <div class="flex flex-col mt-2 mr-12 ml-12">
        <h1 class="text-center text-xl font-bold text-black">Use Cases</h1>
      </div>
    </div>
    <div class="flex justify-end">
      <img
        src="@/assets/images/Ornamen Bulat Tengah.png"
        alt="image"
        width="60px"
        height="50px"
      />
    </div>
  </div>
  <!-- <div id="cardlists"> -->
  <!-- <ul> -->
  <!-- <li v-for="list in lists"> -->
  <div class="flex-1 grid grid-cols-3 ml-8 mr-10 mt-10">
    <div class="card w-[250px] bg-red-50 shadow-xl ml-2 mt-6">
      <figure>
        <img
          src="@/assets/images/Foto/Foto 1.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
      <div class="card-body items-start text-start">
        <h2 class="card-title text-xl font-bold text-rose-900 mt-5">
          Facility Management
        </h2>
        <p class="mt-2">
          API for services that usage for facilities (apartment, office)
        </p>
        <div class="card-actions justify-start mt-4">
          <h2 class="text-l font-semibold text-rose-900">View Journey</h2>
          <img
            src="@/assets/images/right-arrow.png "
            alt="image"
            width="20px"
            height="20px"
            class="mt-1"
          />
        </div>
      </div>
    </div>
    <div class="card w-[250px] bg-red-50 shadow-xl ml-2 mt-6">
      <figure>
        <img
          src="@/assets/images/Foto/Foto 2.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
      <div class="card-body items-start text-start">
        <h2 class="card-title text-xl font-bold text-rose-900 mt-5">
          KasPro Ecosystem Supply Chain
        </h2>
        <p class="mt-2">
          API bundle for Business Ecosystem Solution that aligns Principa
          Distributors Wholesalers, Retailers into ore robust ecosystem &
          securing risks under one roof.
        </p>
        <div class="card-actions justify-start mt-4">
          <h2 class="text-l font-semibold text-rose-900">View Journey</h2>
          <img
            src="@/assets/images/right-arrow.png "
            alt="image"
            width="20px"
            height="20px"
            class="mt-1"
          />
        </div>
      </div>
    </div>
    <div class="card w-[250px] bg-red-50 shadow-xl ml-2 mt-6">
      <figure>
        <img
          src="@/assets/images/Foto/Foto 3.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
      <div class="card-body items-start text-start">
        <h2 class="card-title text-xl font-bold text-rose-900 mt-5">
          Retail Chain
        </h2>
        <p class="mt-2">
          API bundle for retail chain business contains Customer onboarding,
          etc.
        </p>
        <div class="card-actions justify-start mt-4">
          <h2 class="text-l font-semibold text-rose-900">View Journey</h2>
          <img
            src="@/assets/images/right-arrow.png "
            alt="image"
            width="20px"
            height="20px"
            class="mt-1"
          />
        </div>
      </div>
    </div>
    <div class="card w-[250px] bg-red-50 shadow-xl ml-2 mt-6">
      <figure>
        <img
          src="@/assets/images/Foto/Foto 4.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
      <div class="card-body items-start text-start">
        <h2 class="card-title text-xl font-bold text-rose-900 mt-5">P2P</h2>
        <p class="mt-2">
          Financial technology lending that gives lending, insta Imerts without
          credit cards, cell phone credit and PayLater services.
        </p>
        <div class="card-actions justify-start mt-4">
          <h2 class="text-l font-semibold text-rose-900">View Journey</h2>
          <img
            src="@/assets/images/right-arrow.png "
            alt="image"
            width="20px"
            height="20px"
            class="mt-1"
          />
        </div>
      </div>
    </div>
    <div class="card w-[250px] bg-red-50 shadow-xl ml-2 mt-6">
      <figure>
        <img
          src="@/assets/images/Foto/Foto 5.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
      <div class="card-body items-start text-start">
        <h2 class="card-title text-xl font-bold text-rose-900 mt-5">
          Delivery Service
        </h2>
        <p class="mt-2">
          API for delivery services that provide customers onboarding, payment
          and wallet services.
        </p>
        <div class="card-actions justify-start mt-4">
          <h2 class="text-l font-semibold text-rose-900">View Journey</h2>
          <img
            src="@/assets/images/right-arrow.png "
            alt="image"
            width="20px"
            height="20px"
            class="mt-1"
          />
        </div>
      </div>
    </div>
    <div class="card w-[250px] bg-red-50 shadow-xl ml-2 mt-6">
      <figure>
        <img
          src="@/assets/images/Foto/Foto 6.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
      <div class="card-body items-start text-start">
        <h2 class="card-title text-xl font-bold text-rose-900 mt-5">
          Transportation
        </h2>
        <p class="mt-2">
          Mobile-based transporting marketplace that allows users to find and
          book for taxi bike, taxi, and on demand delivery.
        </p>
        <div class="card-actions justify-start mt-4">
          <h2 class="text-l font-semibold text-rose-900">View Journey</h2>
          <img
            src="@/assets/images/right-arrow.png "
            alt="image"
            width="20px"
            height="20px"
            class="mt-1"
          />
        </div>
      </div>
    </div>
    <div class="card w-[250px] bg-red-50 shadow-xl ml-2 mt-6">
      <figure>
        <img
          src="@/assets/images/Foto/Foto 7.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
      <div class="card-body items-start text-start">
        <h2 class="card-title text-xl font-bold text-rose-900 mt-5">
          Biller Management
        </h2>
        <p class="mt-2">
          Customers can explore & embedded each or all of the list of our biller
          products.
        </p>
        <div class="card-actions justify-start mt-4">
          <h2 class="text-l font-semibold text-rose-900">View Journey</h2>
          <img
            src="@/assets/images/right-arrow.png "
            alt="image"
            width="20px"
            height="20px"
            class="mt-1"
          />
        </div>
      </div>
    </div>
    <div class="card w-[250px] bg-red-50 shadow-xl ml-2 mt-6">
      <figure>
        <img
          src="@/assets/images/Foto/Foto 8.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
      <div class="card-body items-start text-start">
        <h2 class="card-title text-xl font-bold text-rose-900 mt-5">
          QRIS Merchant Aggregator
        </h2>
        <p class="mt-2">
          API bundle for business that need Acquiring merchant and provide QRIS
          feature requirements.
        </p>
        <div class="card-actions justify-start mt-4">
          <h2 class="text-l font-semibold text-rose-900">View Journey</h2>
          <img
            src="@/assets/images/right-arrow.png "
            alt="image"
            width="20px"
            height="20px"
            class="mt-1"
          />
        </div>
      </div>
    </div>
    <div class="card w-[250px] bg-red-50 shadow-xl ml-2 mt-6">
      <figure>
        <img
          src="@/assets/images/Foto/Foto 9.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
      <div class="card-body items-start text-start">
        <h2 class="card-title text-xl font-bold text-rose-900 mt-5">
          Integrated Cash Management
        </h2>
        <p class="mt-2">
          A tailor-made cash management for corporate customers aiming.to
          enhance their corporate efficiency.
        </p>
        <div class="card-actions justify-start mt-4">
          <h2 class="text-l font-semibold text-rose-900">View Journey</h2>
          <img
            src="@/assets/images/right-arrow.png "
            alt="image"
            width="20px"
            height="20px"
            class="mt-1"
          />
        </div>
      </div>
    </div>
    <div class="card w-[250px] bg-red-100 shadow-xl ml-2 mt-6">
      <figure>
        <img
          src="@/assets/images/Foto/Foto 10.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
      <div class="card-body items-start text-start">
        <h2 class="card-title text-xl font-bold text-rose-900 mt-5">
          Account Linkage
        </h2>
        <p class="mt-2">
          Linkage accounts and system integration in your application or
          business, electronic services can already be used.
        </p>
        <div class="card-actions justify-start mt-4">
          <h2 class="text-l font-semibold text-rose-900">View Journey</h2>
          <img
            src="@/assets/images/right-arrow.png "
            alt="image"
            width="20px"
            height="20px"
            class="mt-1"
          />
        </div>
      </div>
    </div>
    <div class="card w-[250px] bg-base-100 shadow-xl ml-2 mt-6">
      <figure>
        <img
          src="@/assets/images/Foto/Foto 11.png"
          alt="image"
          class="rounded-xl"
        />
      </figure>
      <div class="card-body items-start text-start">
        <h2 class="card-title text-xl font-bold text-rose-900 mt-5">
          Kaspro Bank
        </h2>
        <p class="mt-2">
          Digitization of Traditional Cooperatives-through secure and seamless
          platform and technology tie-up.
        </p>
        <div class="card-actions justify-start mt-4">
          <h2 class="text-l font-semibold text-rose-900">View Journey</h2>
          <img
            src="@/assets/images/right-arrow.png "
            alt="image"
            width="20px"
            height="20px"
            class="mt-1"
          />
        </div>
      </div>
    </div>
  </div>
  <!-- </li>
    </ul>
  </div> -->
</template>
