<template>
  <div class="navbar bg-base-100 rounded-box">
    <div class="flex-1 px-2 lg:flex-none">
      <img
        alt="Vue logo"
        class="image"
        src="@/assets/logo.svg"
        width="30"
        height="30"
      />
    </div>
    <div class="flex justify-end flex-1 px-2">
      <div class="flex items-stretch">
        <div class="dropdown dropdown-end">
          <a tabindex="0" class="btn btn-ghost rounded-btn">EMBEDDED FINANCE</a>
          <ul
            tabindex="0"
            class="menu dropdown-content p-2 shadow bg-base-100 rounded-box w-52 mt-4"
          >
            <li><a>OUR SOLUTION</a></li>
            <li><a>USER JOURNEY</a></li>
            <li><a>OPEN API</a></li>
          </ul>
        </div>
      </div>
      <a class="btn btn-ghost rounded-btn">ABOUT US</a>
      <a class="btn btn-ghost rounded-btn">OUR VALUE</a>
      <a class="btn btn-ghost rounded-btn">NEWS ROOM</a>
      <a class="btn btn-ghost rounded-btn">CAREERS</a>
      <a class="btn btn-ghost rounded-btn">LANGUAGE</a>
    </div>
  </div>
  <img src="@/assets/images/gambar.png" alt="image" class="w-full h-200px" />
</template>
