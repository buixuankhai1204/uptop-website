<script>
    import HeaderMenu from '$lib/components/HeaderMenu.svelte';
    import Footer from '$lib/components/Footer.svelte';
</script>
  
<svelte:head>
    <title>UptopERP - Giải pháp quản lý và phát huy khả năng làm việc nhóm linh hoạt, tiện lợi</title>
    <meta name="description" content="Công việc được tạo và quản lý trực quen theo hạng mục, theo dự án, theo lịch và tiến độ. Mỗi công việc đều có thể tương tác, trao đổi, làm việc và thảo luận nhóm đơn giản, hiệu quả. Bản thân mỗi nhân viên có thể tự quản lý tổng thể, trực quan các việc mình làm hay tham gia với các hỗ trợ nhắc nhở, đặt lịch, tạo lịch, đặt hẹn rất hữu ích. Người quản lý có thể nhận diện được tổng thể dự án, hạng mục công việc cũng như mức độ tham gia, đóng góp của từng người liên quan từ đó có điều chỉnh và định hướng thích hợp."/>
    <meta name="keywords" content="uptoperp, uptoperp solutions, erp giải pháp, giải pháp erp, giải pháp uptoperp">
    <meta name="author" content="UptopERP">
  
      <!--  Essential META Tags -->
    <meta property="og:title" content="UptopERP - Giải pháp quản lý và phát huy khả năng làm việc nhóm linh hoạt, tiện lợi">
    <meta property="og:type" content="article" />
    <meta property="og:image" content="https://uptoperp.com/data-is-all.jpg">
    <meta property="og:url" content="https://uptoperp.com/solutions">
    <meta name="twitter:card" content="UptopERP - Giải pháp quản lý và phát huy khả năng làm việc nhóm linh hoạt, tiện lợi">
  
    <!--  Non-Essential, But Recommended -->
    <meta property="og:description" content="Công việc được khởi tạo và quản lý trực quan theo hạng mục, theo dự án, theo lịch và tiến độ. Mỗi công việc đều có thể tương tác, trao đổi, làm việc và thảo luận nhóm đơn giản, hiệu quả. Bản thân mỗi nhân viên có thể tự quản lý tổng thể, trực quan các việc mình làm hay tham gia với các hỗ trợ nhắc nhở, đặt lịch, tạo lịch, đặt hẹn rất hữu ích. Người quản lý có thể nhận diện được tổng thể dự án, hạng mục công việc cũng như mức độ tham gia, đóng góp của từng người liên quan từ đó có điều chỉnh và định hướng thích hợp.">
    <meta property="og:site_name" content="UptopERP">
    <meta name="twitter:image:alt" content="UptopERP - Will be your success">
</svelte:head>
  
<HeaderMenu />

<div class="bg-white">
    <!--
      Mobile menu
  
      Off-canvas menu for mobile, show/hide based on off-canvas menu state.
    -->
    <div class="relative z-40 lg:hidden" role="dialog" aria-modal="true">
      <!--
        Off-canvas menu backdrop, show/hide based on off-canvas menu state.
  
        Entering: "transition-opacity ease-linear duration-300"
          From: "opacity-0"
          To: "opacity-100"
        Leaving: "transition-opacity ease-linear duration-300"
          From: "opacity-100"
          To: "opacity-0"
      -->
      <div class="fixed inset-0 bg-black/25" aria-hidden="true"></div>
  
      <div class="fixed inset-0 z-40 flex">
        <!--
          Off-canvas menu, show/hide based on off-canvas menu state.
  
          Entering: "transition ease-in-out duration-300 transform"
            From: "-translate-x-full"
            To: "translate-x-0"
          Leaving: "transition ease-in-out duration-300 transform"
            From: "translate-x-0"
            To: "-translate-x-full"
        -->
        <div class="relative flex w-full max-w-xs flex-col overflow-y-auto bg-white pb-12 shadow-xl">
          <div class="flex px-4 pb-2 pt-5">
            <button type="button" class="-m-2 inline-flex items-center justify-center rounded-md p-2 text-gray-400">
              <span class="sr-only">Close menu</span>
              <svg class="size-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true" data-slot="icon">
                <path stroke-linecap="round" stroke-linejoin="round" d="M6 18 18 6M6 6l12 12" />
              </svg>
            </button>
          </div>
  
          <!-- Links -->
          <div class="mt-2">
            <div class="border-b border-gray-200">
              <div class="-mb-px flex space-x-8 px-4" aria-orientation="horizontal" role="tablist">
                <!-- Selected: "border-indigo-600 text-indigo-600", Not Selected: "border-transparent text-gray-900" -->
                <button id="tabs-1-tab-1" class="flex-1 whitespace-nowrap border-b-2 border-transparent px-1 py-4 text-base font-medium text-gray-900" aria-controls="tabs-1-panel-1" role="tab" type="button">Women</button>
                <!-- Selected: "border-indigo-600 text-indigo-600", Not Selected: "border-transparent text-gray-900" -->
                <button id="tabs-1-tab-2" class="flex-1 whitespace-nowrap border-b-2 border-transparent px-1 py-4 text-base font-medium text-gray-900" aria-controls="tabs-1-panel-2" role="tab" type="button">Men</button>
              </div>
            </div>
  
            <!-- 'Women' tab panel, show/hide based on tab state. -->
            <div id="tabs-1-panel-1" class="space-y-12 px-4 py-6" aria-labelledby="tabs-1-tab-1" role="tabpanel" tabindex="0">
              <div class="grid grid-cols-2 gap-x-4 gap-y-10">
                <div class="group relative">
                  <img src="https://tailwindui.com/plus/img/ecommerce-images/mega-menu-category-01.jpg" alt="Models sitting back to back, wearing Basic Tee in black and bone." class="aspect-square w-full rounded-md bg-gray-100 object-cover group-hover:opacity-75">
                  <a href="#" class="mt-6 block text-sm font-medium text-gray-900">
                    <span class="absolute inset-0 z-10" aria-hidden="true"></span>
                    New Arrivals
                  </a>
                  <p aria-hidden="true" class="mt-1 text-sm text-gray-500">Shop now</p>
                </div>
                <div class="group relative">
                  <img src="https://tailwindui.com/plus/img/ecommerce-images/mega-menu-category-02.jpg" alt="Close up of Basic Tee fall bundle with off-white, ochre, olive, and black tees." class="aspect-square w-full rounded-md bg-gray-100 object-cover group-hover:opacity-75">
                  <a href="#" class="mt-6 block text-sm font-medium text-gray-900">
                    <span class="absolute inset-0 z-10" aria-hidden="true"></span>
                    Basic Tees
                  </a>
                  <p aria-hidden="true" class="mt-1 text-sm text-gray-500">Shop now</p>
                </div>
                <div class="group relative">
                  <img src="https://tailwindui.com/plus/img/ecommerce-images/mega-menu-category-03.jpg" alt="Model wearing minimalist watch with black wristband and white watch face." class="aspect-square w-full rounded-md bg-gray-100 object-cover group-hover:opacity-75">
                  <a href="#" class="mt-6 block text-sm font-medium text-gray-900">
                    <span class="absolute inset-0 z-10" aria-hidden="true"></span>
                    Accessories
                  </a>
                  <p aria-hidden="true" class="mt-1 text-sm text-gray-500">Shop now</p>
                </div>
                <div class="group relative">
                  <img src="https://tailwindui.com/plus/img/ecommerce-images/mega-menu-category-04.jpg" alt="Model opening tan leather long wallet with credit card pockets and cash pouch." class="aspect-square w-full rounded-md bg-gray-100 object-cover group-hover:opacity-75">
                  <a href="#" class="mt-6 block text-sm font-medium text-gray-900">
                    <span class="absolute inset-0 z-10" aria-hidden="true"></span>
                    Carry
                  </a>
                  <p aria-hidden="true" class="mt-1 text-sm text-gray-500">Shop now</p>
                </div>
              </div>
            </div>
            <!-- 'Men' tab panel, show/hide based on tab state. -->
            <div id="tabs-1-panel-2" class="space-y-12 px-4 py-6" aria-labelledby="tabs-1-tab-2" role="tabpanel" tabindex="0">
              <div class="grid grid-cols-2 gap-x-4 gap-y-10">
                <div class="group relative">
                  <img src="https://tailwindui.com/plus/img/ecommerce-images/mega-menu-01-men-category-01.jpg" alt="Hats and sweaters on wood shelves next to various colors of t-shirts on hangers." class="aspect-square w-full rounded-md bg-gray-100 object-cover group-hover:opacity-75">
                  <a href="#" class="mt-6 block text-sm font-medium text-gray-900">
                    <span class="absolute inset-0 z-10" aria-hidden="true"></span>
                    New Arrivals
                  </a>
                  <p aria-hidden="true" class="mt-1 text-sm text-gray-500">Shop now</p>
                </div>
                <div class="group relative">
                  <img src="https://tailwindui.com/plus/img/ecommerce-images/mega-menu-01-men-category-02.jpg" alt="Model wearing light heather gray t-shirt." class="aspect-square w-full rounded-md bg-gray-100 object-cover group-hover:opacity-75">
                  <a href="#" class="mt-6 block text-sm font-medium text-gray-900">
                    <span class="absolute inset-0 z-10" aria-hidden="true"></span>
                    Basic Tees
                  </a>
                  <p aria-hidden="true" class="mt-1 text-sm text-gray-500">Shop now</p>
                </div>
                <div class="group relative">
                  <img src="https://tailwindui.com/plus/img/ecommerce-images/mega-menu-01-men-category-03.jpg" alt="Grey 6-panel baseball hat with black brim, black mountain graphic on front, and light heather gray body." class="aspect-square w-full rounded-md bg-gray-100 object-cover group-hover:opacity-75">
                  <a href="#" class="mt-6 block text-sm font-medium text-gray-900">
                    <span class="absolute inset-0 z-10" aria-hidden="true"></span>
                    Accessories
                  </a>
                  <p aria-hidden="true" class="mt-1 text-sm text-gray-500">Shop now</p>
                </div>
                <div class="group relative">
                  <img src="https://tailwindui.com/plus/img/ecommerce-images/mega-menu-01-men-category-04.jpg" alt="Model putting folded cash into slim card holder olive leather wallet with hand stitching." class="aspect-square w-full rounded-md bg-gray-100 object-cover group-hover:opacity-75">
                  <a href="#" class="mt-6 block text-sm font-medium text-gray-900">
                    <span class="absolute inset-0 z-10" aria-hidden="true"></span>
                    Carry
                  </a>
                  <p aria-hidden="true" class="mt-1 text-sm text-gray-500">Shop now</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  
    <!-- Hero section -->
    <div class="relative bg-gray-900">
      <!-- Decorative image and overlay -->
      <div aria-hidden="true" class="absolute inset-0 overflow-hidden">
        <img src="https://tailwindui.com/plus/img/ecommerce-images/home-page-01-hero-full-width.jpg" alt="" class="size-full object-cover">
      </div>
      <div aria-hidden="true" class="absolute inset-0 bg-gray-900 opacity-50"></div>

      <div class="relative mx-auto flex max-w-3xl flex-col items-center px-6 py-32 text-center sm:py-64 lg:px-0">
        <h1 class="text-4xl font-bold tracking-tight text-white lg:text-6xl">New arrivals are here</h1>
        <p class="mt-4 text-xl text-white">The new arrivals have, well, newly arrived. Check out the latest options from our summer small-batch release while they're still in stock.</p>
        <a href="#" class="mt-8 inline-block rounded-md border border-transparent bg-white px-8 py-3 text-base font-medium text-gray-900 hover:bg-gray-100">Shop New Arrivals</a>
      </div>
    </div>
  
    <main>
      <!-- Category section -->
      <section aria-labelledby="category-heading" class="pt-24 sm:pt-32 xl:mx-auto xl:max-w-7xl xl:px-8">
        <div class="px-4 sm:flex sm:items-center sm:justify-between sm:px-6 lg:px-8 xl:px-0">
          <h2 id="category-heading" class="text-2xl font-bold tracking-tight text-gray-900">Shop by Category</h2>
          <a href="#" class="hidden text-sm font-semibold text-indigo-600 hover:text-indigo-500 sm:block">
            Browse all categories
            <span aria-hidden="true"> &rarr;</span>
          </a>
        </div>
  
        <div class="mt-4 flow-root">
          <div class="-my-2">
            <div class="relative box-content h-80 overflow-x-auto py-2 xl:overflow-visible">
              <div class="absolute flex space-x-8 px-4 sm:px-6 lg:px-8 xl:relative xl:grid xl:grid-cols-5 xl:gap-x-8 xl:space-x-0 xl:px-0">
                <a href="#" class="relative flex h-80 w-56 flex-col overflow-hidden rounded-lg p-6 hover:opacity-75 xl:w-auto">
                  <span aria-hidden="true" class="absolute inset-0">
                    <img src="https://tailwindui.com/plus/img/ecommerce-images/home-page-01-category-01.jpg" alt="" class="size-full object-cover">
                  </span>
                  <span aria-hidden="true" class="absolute inset-x-0 bottom-0 h-2/3 bg-gradient-to-t from-gray-800 opacity-50"></span>
                  <span class="relative mt-auto text-center text-xl font-bold text-white">New Arrivals</span>
                </a>
                <a href="#" class="relative flex h-80 w-56 flex-col overflow-hidden rounded-lg p-6 hover:opacity-75 xl:w-auto">
                  <span aria-hidden="true" class="absolute inset-0">
                    <img src="https://tailwindui.com/plus/img/ecommerce-images/home-page-01-category-02.jpg" alt="" class="size-full object-cover">
                  </span>
                  <span aria-hidden="true" class="absolute inset-x-0 bottom-0 h-2/3 bg-gradient-to-t from-gray-800 opacity-50"></span>
                  <span class="relative mt-auto text-center text-xl font-bold text-white">Productivity</span>
                </a>
                <a href="#" class="relative flex h-80 w-56 flex-col overflow-hidden rounded-lg p-6 hover:opacity-75 xl:w-auto">
                  <span aria-hidden="true" class="absolute inset-0">
                    <img src="https://tailwindui.com/plus/img/ecommerce-images/home-page-01-category-04.jpg" alt="" class="size-full object-cover">
                  </span>
                  <span aria-hidden="true" class="absolute inset-x-0 bottom-0 h-2/3 bg-gradient-to-t from-gray-800 opacity-50"></span>
                  <span class="relative mt-auto text-center text-xl font-bold text-white">Workspace</span>
                </a>
                <a href="#" class="relative flex h-80 w-56 flex-col overflow-hidden rounded-lg p-6 hover:opacity-75 xl:w-auto">
                  <span aria-hidden="true" class="absolute inset-0">
                    <img src="https://tailwindui.com/plus/img/ecommerce-images/home-page-01-category-05.jpg" alt="" class="size-full object-cover">
                  </span>
                  <span aria-hidden="true" class="absolute inset-x-0 bottom-0 h-2/3 bg-gradient-to-t from-gray-800 opacity-50"></span>
                  <span class="relative mt-auto text-center text-xl font-bold text-white">Accessories</span>
                </a>
                <a href="#" class="relative flex h-80 w-56 flex-col overflow-hidden rounded-lg p-6 hover:opacity-75 xl:w-auto">
                  <span aria-hidden="true" class="absolute inset-0">
                    <img src="https://tailwindui.com/plus/img/ecommerce-images/home-page-01-category-03.jpg" alt="" class="size-full object-cover">
                  </span>
                  <span aria-hidden="true" class="absolute inset-x-0 bottom-0 h-2/3 bg-gradient-to-t from-gray-800 opacity-50"></span>
                  <span class="relative mt-auto text-center text-xl font-bold text-white">Sale</span>
                </a>
              </div>
            </div>
          </div>
        </div>
  
        <div class="mt-6 px-4 sm:hidden">
          <a href="#" class="block text-sm font-semibold text-indigo-600 hover:text-indigo-500">
            Browse all categories
            <span aria-hidden="true"> &rarr;</span>
          </a>
        </div>
      </section>
  
      <!-- Featured section -->
      <section aria-labelledby="social-impact-heading" class="mx-auto max-w-7xl px-4 pt-24 sm:px-6 sm:pt-32 lg:px-8">
        <div class="relative overflow-hidden rounded-lg">
          <div class="absolute inset-0">
            <img src="https://tailwindui.com/plus/img/ecommerce-images/home-page-01-feature-section-01.jpg" alt="" class="size-full object-cover">
          </div>
          <div class="relative bg-gray-900/75 px-6 py-32 sm:px-12 sm:py-40 lg:px-16">
            <div class="relative mx-auto flex max-w-3xl flex-col items-center text-center">
              <h2 id="social-impact-heading" class="text-3xl font-bold tracking-tight text-white sm:text-4xl">
                <span class="block sm:inline">Level up</span>
                <span class="block sm:inline">your desk</span>
              </h2>
              <p class="mt-3 text-xl text-white">Make your desk beautiful and organized. Post a picture to social media and watch it get more likes than life-changing announcements. Reflect on the shallow nature of existence. At least you have a really nice desk setup.</p>
              <a href="#" class="mt-8 block w-full rounded-md border border-transparent bg-white px-8 py-3 text-base font-medium text-gray-900 hover:bg-gray-100 sm:w-auto">Shop Workspace</a>
            </div>
          </div>
        </div>
      </section>
  
      <!-- Collection section -->
      <section aria-labelledby="collection-heading" class="mx-auto max-w-xl px-4 pt-24 sm:px-6 sm:pt-32 lg:max-w-7xl lg:px-8">
        <h2 id="collection-heading" class="text-2xl font-bold tracking-tight text-gray-900">Shop by Collection</h2>
        <p class="mt-4 text-base text-gray-500">Each season, we collaborate with world-class designers to create a collection inspired by the natural world.</p>
  
        <div class="mt-10 space-y-12 lg:grid lg:grid-cols-3 lg:gap-x-8 lg:space-y-0">
          <a href="#" class="group block">
            <img src="https://tailwindui.com/plus/img/ecommerce-images/home-page-01-collection-01.jpg" alt="Brown leather key ring with brass metal loops and rivets on wood table." class="aspect-[3/2] w-full rounded-lg object-cover group-hover:opacity-75 lg:aspect-[5/6]">
            <h3 class="mt-4 text-base font-semibold text-gray-900">Handcrafted Collection</h3>
            <p class="mt-2 text-sm text-gray-500">Keep your phone, keys, and wallet together, so you can lose everything at once.</p>
          </a>
          <a href="#" class="group block">
            <img src="https://tailwindui.com/plus/img/ecommerce-images/home-page-01-collection-02.jpg" alt="Natural leather mouse pad on white desk next to porcelain mug and keyboard." class="aspect-[3/2] w-full rounded-lg object-cover group-hover:opacity-75 lg:aspect-[5/6]">
            <h3 class="mt-4 text-base font-semibold text-gray-900">Organized Desk Collection</h3>
            <p class="mt-2 text-sm text-gray-500">The rest of the house will still be a mess, but your desk will look great.</p>
          </a>
          <a href="#" class="group block">
            <img src="https://tailwindui.com/plus/img/ecommerce-images/home-page-01-collection-03.jpg" alt="Person placing task list card into walnut card holder next to felt carrying case on leather desk pad." class="aspect-[3/2] w-full rounded-lg object-cover group-hover:opacity-75 lg:aspect-[5/6]">
            <h3 class="mt-4 text-base font-semibold text-gray-900">Focus Collection</h3>
            <p class="mt-2 text-sm text-gray-500">Be more productive than enterprise project managers with a single piece of paper.</p>
          </a>
        </div>
      </section>
  
      <!-- Featured section -->
      <section aria-labelledby="comfort-heading" class="mx-auto max-w-7xl px-4 py-24 sm:px-6 sm:py-32 lg:px-8">
        <div class="relative overflow-hidden rounded-lg">
          <div class="absolute inset-0">
            <img src="https://tailwindui.com/plus/img/ecommerce-images/home-page-01-feature-section-02.jpg" alt="" class="size-full object-cover">
          </div>
          <div class="relative bg-gray-900/75 px-6 py-32 sm:px-12 sm:py-40 lg:px-16">
            <div class="relative mx-auto flex max-w-3xl flex-col items-center text-center">
              <h2 id="comfort-heading" class="text-3xl font-bold tracking-tight text-white sm:text-4xl">Simple productivity</h2>
              <p class="mt-3 text-xl text-white">Endless tasks, limited hours, a single piece of paper. Not really a haiku, but we're doing our best here. No kanban boards, burndown charts, or tangled flowcharts with our Focus system. Just the undeniable urge to fill empty circles.</p>
              <a href="#" class="mt-8 block w-full rounded-md border border-transparent bg-white px-8 py-3 text-base font-medium text-gray-900 hover:bg-gray-100 sm:w-auto">Shop Focus</a>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
<Footer />