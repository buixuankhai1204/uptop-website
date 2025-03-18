<script>
  import { navigating } from '$app/stores';
  import { browser } from '$app/environment';
  let showMobileMenu = "invisible";

  function showMenu(){
    showMobileMenu = showMobileMenu === "invisible" ? "visible w-full" : "invisible";
  }

  let homeColor =  "text-gray-900";
  let technologyColor =  "text-gray-900";
  let solutionsColor =  "text-gray-900";
  let aboutusColor =  "text-gray-900";
  let contactColor =  "text-gray-900";
  let productsColor = "text-gray-900";
  let servicesColor = "text-gray-900";

  $: if ($navigating) {    
    if(browser){
      //console.log(location.href);
      if((location.href == "http://localhost:5173/")||(location.href == "https://uptop.com/")){
        homeColor =  "text-red-600";
        technologyColor =  "text-gray-900";
        solutionsColor =  "text-gray-900";
        productsColor = "text-gray-900";
        servicesColor = "text-gray-900";
        aboutusColor =  "text-gray-900";
        contactColor =  "text-gray-900";
      }else if((location.href == "http://localhost:5173/technology")||(location.href == "https://uptop.com/technology")){
        homeColor =  "text-gray-900";
        technologyColor =  "text-red-600";
        solutionsColor =  "text-gray-900";
        productsColor = "text-gray-900";
        servicesColor = "text-gray-900";
        aboutusColor =  "text-gray-900";
        contactColor =  "text-gray-900";
      }else if((location.href == "http://localhost:5173/solutions")||(location.href == "https://uptop.com/solutions")){
        homeColor =  "text-gray-900";
        technologyColor =  "text-gray-900";
        solutionsColor =  "text-red-600";
        productsColor = "text-gray-900";
        servicesColor = "text-gray-900";
        aboutusColor =  "text-gray-900";
        contactColor =  "text-gray-900";
      }else if((location.href == "http://localhost:5173/products")||(location.href == "https://uptop.com/products")){
        homeColor =  "text-gray-900";
        technologyColor =  "text-gray-900";
        solutionsColor =  "text-gray-900";
        productsColor = "text-red-600";
        servicesColor = "text-gray-900";
        aboutusColor =  "text-gray-900";
        contactColor =  "text-gray-900";        
      }else if((location.href == "http://localhost:5173/services")||(location.href == "https://uptop.com/services")){
        homeColor =  "text-gray-900";
        technologyColor =  "text-gray-900";
        solutionsColor =  "text-gray-900";
        productsColor = "text-gray-900";
        servicesColor = "text-red-600";
        aboutusColor =  "text-gray-900";
        contactColor =  "text-gray-900";
      }else if((location.href == "http://localhost:5173/about-us")||(location.href == "https://uptop.com/about-us")){
        homeColor =  "text-gray-900";
        technologyColor =  "text-gray-900";
        solutionsColor =  "text-gray-900";
        productsColor = "text-gray-900";
        servicesColor = "text-gray-900";
        aboutusColor =  "text-red-600";
        contactColor =  "text-gray-900";
      }else if((location.href == "http://localhost:5173/contact")||(location.href == "https://uptop.com/contact")){
        homeColor =  "text-gray-900";
        technologyColor =  "text-gray-900";
        solutionsColor =  "text-gray-900";
        productsColor = "text-gray-900";
        servicesColor = "text-gray-900";
        aboutusColor =  "text-gray-900";
        contactColor =  "text-red-600";
      }else{
        homeColor =  "text-gray-900";
        technologyColor =  "text-gray-900";
        solutionsColor =  "text-gray-900";
        productsColor = "text-gray-900";
        servicesColor = "text-gray-900";
        aboutusColor =  "text-gray-900";
        contactColor =  "text-gray-900";
      }
    }
  }
</script>

<header class="bg-white">
  <!-- Desktop navigation -->
  <div class="w-full drop-shadow bg-gray-50">
    <nav class="mx-auto flex max-w-7xl items-center justify-between  p-6 lg:px-8" aria-label="Global">
      <div class="flex lg:flex-1">
        <a href="/logo-and-slogan" class="-m-1.5">          
          <enhanced:img src="/static/UpTop-Logo-Without-Slogan.png" alt="UpTop Web banner logo" class="h-14 w-auto"/>
        </a>
      </div>
      <div class="grow lg:hidden"></div>
      <div class="hidden lg:flex lg:gap-x-12">
        <a href="/" class="text-sm font-semibold leading-6 {homeColor}">Trang chủ</a>
        <a href="/technology" class="text-sm font-semibold leading-6 {technologyColor}">Công nghệ</a>
        <a href="/solutions" class="text-sm font-semibold leading-6 {solutionsColor}">Giải pháp</a>
        <a href="/products" class="text-sm font-semibold leading-6 {productsColor}">Sản phẩm</a>
        <a href="/services" class="text-sm font-semibold leading-6 {servicesColor}">Dịch vụ</a>
        <a href="/about-us" class="text-sm font-semibold leading-6 {aboutusColor}">Về chúng tôi</a>
        <a href="/contact" class="text-sm font-semibold leading-6 {contactColor}">Liên hệ</a>
      </div>      
      <div class="flex pl-10">
        <a href="/log-in" class="rounded-md bg-indigo-600 px-3 py-2 text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600 whitespace-nowrap">
          Đăng nhập
        </a>
      </div>
      <div class="flex lg:hidden px-3">
        <button type="button" class="-m-1.5 inline-flex items-center justify-center rounded-md p-1.5 text-gray-700" on:click={showMenu}>
          <span class="sr-only">Open main menu</span>
          <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
          </svg>
        </button>
      </div>
    </nav>
  </div>
  <!-- Mobile menu, show/hide based on menu open state. -->
  <div class="{showMobileMenu}" role="dialog" aria-modal="true">
    <!-- Background backdrop, show/hide based on slide-over state. -->
    <div class="fixed inset-y-0 right-0 z-10 w-full -mt-0.5 overflow-y-auto bg-white px-4 align-middle sm:ring-1 sm:ring-gray-900/10">
      <div class="flex items-center pt-6 px-2 justify-between mr-6">
          <a href="/logo-and-slogan" class="-m-1.5 "> 
             <enhanced:img src="/static/Logo-UpTopERP-Horizon-No-Slogan.png" alt="UptopERP Web banner logo" class="h-10 w-auto "/>         
          </a>
        <a href="/log-in" class="ml-auto rounded-md bg-indigo-600 px-3 py-2 text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Đăng nhập</a>
        <button type="button" class="-m-1.5 px-4 rounded-md  py-2 text-gray-700" on:click={showMenu} style="width: 20px;">
          <span class="sr-only">Close menu</span>
          <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
          </svg>
        </button>
      </div>
      <div class="mt-6 flow-root">
        <div class="-my-6 divide-y divide-gray-500/10">
          <div class="space-y-2 py-6">
            <a href="/" class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50">Trang chủ</a>
            <a href="/technology" class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50">Công nghệ</a>
            <a href="/solutions" class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50">Giải pháp</a>
            <a href="/optimization" class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50">Tối ưu hóa</a>
            <a href="/about-us" class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50">Về chúng tôi</a>
            <a href="/contact" class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50">Liên hệ</a>
          </div>          
        </div>
      </div>
    </div>
  </div>
</header>
  