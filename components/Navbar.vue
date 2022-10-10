<template>
  <div class="navbar sticky w-screen bg-base-100 flex justify-center">
    <div class="lg:w-2/3">
      <div class="flex-1">
        <img
          src="https://kiriminaja.com/assets/atrust/svg-logo-primary.svg"
          alt="Company Logo"
          width="145px"
        />
      </div>
      <div class="flex-none ">
        <ul class="menu menu-horizontal p-0">
          <li><a href="/">Beranda</a></li>
          <li><a>Blog</a></li>
          <li><a>Kabar</a></li>
          <li tabindex="0">
            <a>
              Layanan
              <svg
                class="fill-current"
                xmlns="http://www.w3.org/2000/svg"
                width="20"
                height="20"
                viewBox="0 0 24 24"
              >
                <path
                  d="M7.41,8.58L12,13.17L16.59,8.58L18,10L12,16L6,10L7.41,8.58Z"
                />
              </svg>
            </a>
            <ul class="p-2 bg-base-100">
              <li><a>Manajemen Order</a></li>
              <li><a href="/api-integration">Integrasi Api</a></li>
            </ul>
          </li>
          <li><a>Cek Ongkir</a></li>
          <li><a>Lacak</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>