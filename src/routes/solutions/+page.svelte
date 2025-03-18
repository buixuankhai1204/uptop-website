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

<div class="bg-white border-solid border-t border-gray-300 pt-6 pb-2">  
  <div class="relative isolate">
    <svg class="absolute inset-x-0 top-0 -z-10 h-[64rem] w-full stroke-gray-200 [mask-image:radial-gradient(32rem_32rem_at_center,white,transparent)]" aria-hidden="true">
      <defs>
        <pattern id="1f932ae7-37de-4c0a-a8b0-a6e3b4d44b84" width="200" height="200" x="50%" y="-1" patternUnits="userSpaceOnUse">
          <path d="M.5 200V.5H200" fill="none" />
        </pattern>
      </defs>
      <svg x="50%" y="-1" class="overflow-visible fill-gray-50">
        <path d="M-200 0h201v201h-201Z M600 0h201v201h-201Z M-400 600h201v201h-201Z M200 800h201v201h-201Z" stroke-width="0" />
      </svg>
      <rect width="100%" height="100%" stroke-width="0" fill="url(#1f932ae7-37de-4c0a-a8b0-a6e3b4d44b84)" />
    </svg>
    <div class="absolute left-1/2 right-0 top-0 -z-10 -ml-24 transform-gpu overflow-hidden blur-3xl lg:ml-24 xl:ml-48" aria-hidden="true">
      <div class="aspect-[801/1036] w-[50.0625rem] bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-30" style="clip-path: polygon(63.1% 29.5%, 100% 17.1%, 76.6% 3%, 48.4% 0%, 44.6% 4.7%, 54.5% 25.3%, 59.8% 49%, 55.2% 57.8%, 44.4% 57.2%, 27.8% 47.9%, 35.1% 81.5%, 0% 97.7%, 39.2% 100%, 35.2% 81.4%, 97.2% 52.8%, 63.1% 29.5%)"></div>
    </div>
    <div class="">
      <div class="mx-auto max-w-7xl px-4  py-8 sm:pt-60 lg:px-8 lg:pt-32">
        <div class="mx-auto max-w-2xl gap-x-14 lg:mx-0 lg:flex lg:max-w-none lg:items-center">
          <div class="relative w-full max-w-xl lg:shrink-0 xl:max-w-2xl">
            <h1 class="text-4xl font-bold tracking-tight text-gray-900 sm:text-6xl" style="line-height: 1.1;">Giải pháp đồng bộ giúp mọi hoạt động trở nên an toàn, mượt mà, trơn tru, hiệu quả.</h1>
            <p class="mt-6 text-lg leading-8 text-gray-600 sm:max-w-md lg:max-w-none">Thực tế các doanh nghiệp, tổ chức hiện nay thường sở hữu và sử dụng rất nhiều các nền tảng công nghệ khác nhau, đặc biệt trong đó có rất nhiều các nền tảng hoàn toàn không thuộc kiểm soát của doanh nghiệp hay tổ chức như các ứng dụng tin nhắn, email, ghi chú, quản lý công việc, lưu trữ… Dẫn tới rất nhiều tài nguyên và thông tin của doanh nghiệp, tổ chức không được quản lý, dễ bị lộ ra bên ngoài… Đặc biệt điển hình là tình trạng lệ thuộc công việc vào nhiều cá nhân khác nhau bởi thông tin, kết quả công việc, khách hàng, đơn hàng đáng nhẽ ra phải được lưu trữ và quản lý bởi công ty, doanh nghiệp thì lại được nắm giữ bởi cá nhân… Thấu hiểu thực trạng công nghệ này, UpTop ưu tiên phát triển nền tảng công nghệ vững chắc giúp mọi doanh nghiệp, tổ chức có thể hoàn toàn sử dụng và khai thác đồng bộ trên một hệ thống duy nhất, giúp cho sự vận hành và phát triển hoàn toàn được kiểm soát bởi chính doanh nghiệp, tổ chức của bạn.</p>            
          </div>
          <div class="mt-14 flex justify-end gap-8 sm:-mt-44 sm:justify-start sm:pl-20 lg:mt-0 lg:pl-0">
            <div class="hidden sm:block ml-auto w-40 flex-none space-y-8 pt-32 sm:ml-0 sm:pt-80 lg:order-last lg:pt-36 xl:order-none xl:pt-80">
              <div class="relative">
                <enhanced:img src="../../../static/solutionspage-business-working-1.jpg" alt="hero" class=" h-60 rounded-xl bg-gray-900/5 object-cover shadow-lg" />
                <div class="pointer-events-none absolute inset-0 rounded-xl ring-1 ring-inset ring-gray-900/10"></div>
              </div>
            </div>
            <div class="hidden sm:block mr-auto w-40 flex-none space-y-8 sm:mr-0 sm:pt-52 lg:pt-36">
              <div class="relative">                
                <enhanced:img src="../../../static/solutionspage-business-working-2.jpg" alt="" class="aspect-[2/3] w-full rounded-xl bg-gray-900/5 object-cover shadow-lg" />
                <div class="pointer-events-none absolute inset-0 rounded-xl ring-1 ring-inset ring-gray-900/10"></div>
              </div>
              <div class="relative">
                <enhanced:img src="../../../static/solutionspage-business-working-3.jpg" alt="" class="aspect-[2/3] w-full rounded-xl bg-gray-900/5 object-cover shadow-lg" />
                <div class="pointer-events-none absolute inset-0 rounded-xl ring-1 ring-inset ring-gray-900/10"></div>
              </div>
            </div>
            <div class="hidden sm:block w-40 flex-none space-y-8 pt-32 sm:pt-0">
              <div class="relative">
                <enhanced:img src="../../../static/solutionspage-business-working-4.jpg" alt="" class="aspect-[2/3] w-full rounded-xl bg-gray-900/5 object-cover shadow-lg" />
                <div class="pointer-events-none absolute inset-0 rounded-xl ring-1 ring-inset ring-gray-900/10"></div>
              </div>
              <div class="relative">
                <enhanced:img src="../../../static/solutionspage-business-working-5.jpg" alt="" class="aspect-[2/3] w-full rounded-xl bg-gray-900/5 object-cover shadow-lg" />
                <div class="pointer-events-none absolute inset-0 rounded-xl ring-1 ring-inset ring-gray-900/10"></div>
              </div>
            </div>
          </div>
          <div class="sm:hidden ml-auto w-full flex-none space-y-8 sm:ml-0 sm:pt-80 lg:order-last lg:pt-36 xl:order-none xl:pt-80">
            <div class="relative">
              <enhanced:img src="../../../static/solutionspage-business-working-1.jpg" alt="" class="w-full h-auto rounded-xl bg-gray-900/5 object-cover shadow-lg" />
              <div class="pointer-events-none absolute inset-0 rounded-xl ring-1 ring-inset ring-gray-900/10"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="bg-white py-12 border-solid border-t border-gray-300 pt-14 pb-8">
  <div class="mx-auto max-w-7xl px-4 lg:px-8">
    <div class="mx-auto max-w-5xl text-center">
      <h2 class="text-base font-semibold leading-7 text-indigo-600">Tăng cường hiệu quả công việc bằng việc giảm tới 80% lưu lượng công việc thủ công hàng ngày</h2>
      <p class="mt-4 text-4xl font-bold tracking-tight text-gray-900 sm:text-6xl" style="line-height: 1.1;">UpTopBase - Mang tới những tiện ích, kết nối, vận hành và lưu trữ vững chắc, an toàn, tiện lợi</p>
      <p class="mt-12 text-lg leading-8 text-gray-600">Mọi giải pháp chuyển đổi số và|hay giải pháp phần mềm của UpTop đều được tích hợp miễn phí những module ứng dụng nền tảng giúp doanh nghiệp, tổ chức của bạn có thể hoàn toàn vận hành đồng bộ trên một hệ thống duy nhất. Các module ứng dụng hệ thống nền tảng này của UpTop không ngừng được nâng cấp, thêm mới và phát triển nhằm đáp ứng nhu cầu hoạt động cơ bản, thiết yếu của hầu hết tất cả mọi doanh nghiệp, tổ chức một cách tốt nhất.</p>
    </div>
    <div class="mx-auto mt-16 max-w-2xl sm:mt-20 lg:mt-16 lg:mb-16 lg:max-w-4xl">
      <dl class="grid max-w-xl grid-cols-1 gap-x-8 gap-y-10 lg:max-w-none lg:grid-cols-2 lg:gap-y-16">
        <div class="relative pl-16">
          <dt class="text-base font-semibold leading-7 text-gray-900">
            <div class="absolute left-0 top-0 flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-600">              
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6 text-white">
                <path stroke-linecap="round" stroke-linejoin="round" d="M20.25 8.511c.884.284 1.5 1.128 1.5 2.097v4.286c0 1.136-.847 2.1-1.98 2.193-.34.027-.68.052-1.02.072v3.091l-3-3c-1.354 0-2.694-.055-4.02-.163a2.115 2.115 0 0 1-.825-.242m9.345-8.334a2.126 2.126 0 0 0-.476-.095 48.64 48.64 0 0 0-8.048 0c-1.131.094-1.976 1.057-1.976 2.192v4.286c0 .837.46 1.58 1.155 1.951m9.345-8.334V6.637c0-1.621-1.152-3.026-2.76-3.235A48.455 48.455 0 0 0 11.25 3c-2.115 0-4.198.137-6.24.402-1.608.209-2.76 1.614-2.76 3.235v6.226c0 1.621 1.152 3.026 2.76 3.235.577.075 1.157.14 1.74.194V21l4.155-4.155" />
              </svg>                            
            </div>
            Messenger: Ứng dụng tin nhắn
          </dt>
          <dd class="mt-2 text-base leading-7 text-gray-600">Giúp bảo mật thông tin đồng thời nhân sự không phải sử dụng các ứng dụng tin nhắn ngoài dễ gây thất thoát thông tin.</dd>
        </div>
        <div class="relative pl-16">
          <dt class="text-base font-semibold leading-7 text-gray-900">
            <div class="absolute left-0 top-0 flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-600">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6 text-white">
                <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 17.25v-.228a4.5 4.5 0 0 0-.12-1.03l-2.268-9.64a3.375 3.375 0 0 0-3.285-2.602H7.923a3.375 3.375 0 0 0-3.285 2.602l-2.268 9.64a4.5 4.5 0 0 0-.12 1.03v.228m19.5 0a3 3 0 0 1-3 3H5.25a3 3 0 0 1-3-3m19.5 0a3 3 0 0 0-3-3H5.25a3 3 0 0 0-3 3m16.5 0h.008v.008h-.008v-.008Zm-3 0h.008v.008h-.008v-.008Z" />
              </svg>                            
            </div>
            Drive: Ứng dụng lưu trữ
          </dt>
          <dd class="mt-2 text-base leading-7 text-gray-600">Giúp nhân sự dễ dàng truy xuất dữ liệu và làm việc mọi lúc, mọi nơi bằng việc cloud hóa dữ liệu cá nhân và|hay công việc</dd>
        </div>
        <div class="relative pl-16">
          <dt class="text-base font-semibold leading-7 text-gray-900">
            <div class="absolute left-0 top-0 flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-600">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6 text-white">
                <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75" />
              </svg>                            
            </div>
            Email: Ứng dụng quản lý email
          </dt>
          <dd class="mt-2 text-base leading-7 text-gray-600">Tích hợp khả năng quản lý và vận hành các chiến dịch email marketing, ứng dụng email tích hợp giúp tăng cường sự tiện lợi</dd>
        </div>
        <div class="relative pl-16">
          <dt class="text-base font-semibold leading-7 text-gray-900">
            <div class="absolute left-0 top-0 flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-600">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6 text-white">
                <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 12c0-1.232-.046-2.453-.138-3.662a4.006 4.006 0 0 0-3.7-3.7 48.678 48.678 0 0 0-7.324 0 4.006 4.006 0 0 0-3.7 3.7c-.017.22-.032.441-.046.662M19.5 12l3-3m-3 3-3-3m-12 3c0 1.232.046 2.453.138 3.662a4.006 4.006 0 0 0 3.7 3.7 48.656 48.656 0 0 0 7.324 0 4.006 4.006 0 0 0 3.7-3.7c.017-.22.032-.441.046-.662M4.5 12l3 3m-3-3-3 3" />
              </svg>                            
            </div>
            Co-Working: Ứng dụng quản lý công việc
          </dt>
          <dd class="mt-2 text-base leading-7 text-gray-600">Giao việc, quản lý công việc, làm việc nhóm và báo cáo thời gian thực được đồng bộ cùng hệ thống giúp tăng cường mạnh mẽ khả năng quản lý</dd>
        </div>
      </dl>
    </div>
    <div class="flex flex-col items-center justify-center pt-6 mx-auto rounded-lg lg:px-10 max-w-7xl">
      <enhanced:img src="../../../static/solutionspage-core-software.jpg" alt="hero" class="object-cover object-center rounded-xl" />
    </div>
  </div>
</div>

<div class="bg-white py-12 border-solid border-t border-gray-300 pt-14 pb-8">
  <div class="mx-auto max-w-7xl px-4 lg:px-8">
    <div class="mx-auto max-w-5xl text-center">
      <h2 class="text-base font-semibold leading-7 text-indigo-600">Tự hào tiên phong trong việc cung cấp giải pháp chuyển đổi số cho lĩnh vực phát thanh truyền hình</h2>
      <p class="mt-4 text-4xl font-bold tracking-tight text-gray-900 sm:text-6xl" style="line-height: 1.1;">UpTopBroadcast - Giải pháp chuyển đổi số hàng đầu trong lĩnh vực phát thanh truyền hình</p>
      <p class="mt-12 text-lg leading-8 text-gray-600">Truyền hình là một lĩnh vực đặc thù mang đậm tính công nghệ cao nhưng lại phải đáp ứng khả năng làm chủ và tùy biến 100% bởi yêu cầu an toàn thông tin là yếu tố then chốt sống còn có thể anh hưởng tới an ninh thông tin quốc phòng của cả một quốc gia. Chính vì vậy, việc xây dựng và phát triển hệ thống giải pháp trong lĩnh vực truyền hình đòi hỏi sự thấu hiểu công nghệ cao không chỉ hàng đầu thế giới mà còn phải thấu hiểu nhu cầu và đặc thù riêng của quốc gia. UpTop tự hào tiên phong xây dựng những giải pháp quản lý, chuyển đổi số phù hợp nhất cho lĩnh vực truyền thanh, truyền hình tại Việt Nam.</p>
    </div>
    <div class="mx-auto mt-16 max-w-2xl sm:mt-20 lg:mt-16 lg:mb-16 lg:max-w-4xl">
      <dl class="grid max-w-xl grid-cols-1 gap-x-8 gap-y-10 lg:max-w-none lg:grid-cols-2 lg:gap-y-16">
        <div class="relative pl-16">
          <dt class="text-base font-semibold leading-7 text-gray-900">
            <div class="absolute left-0 top-0 flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-600">              
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6 text-white">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3.375 19.5h17.25m-17.25 0a1.125 1.125 0 0 1-1.125-1.125M3.375 19.5h1.5C5.496 19.5 6 18.996 6 18.375m-3.75 0V5.625m0 12.75v-1.5c0-.621.504-1.125 1.125-1.125m18.375 2.625V5.625m0 12.75c0 .621-.504 1.125-1.125 1.125m1.125-1.125v-1.5c0-.621-.504-1.125-1.125-1.125m0 3.75h-1.5A1.125 1.125 0 0 1 18 18.375M20.625 4.5H3.375m17.25 0c.621 0 1.125.504 1.125 1.125M20.625 4.5h-1.5C18.504 4.5 18 5.004 18 5.625m3.75 0v1.5c0 .621-.504 1.125-1.125 1.125M3.375 4.5c-.621 0-1.125.504-1.125 1.125M3.375 4.5h1.5C5.496 4.5 6 5.004 6 5.625m-3.75 0v1.5c0 .621.504 1.125 1.125 1.125m0 0h1.5m-1.5 0c-.621 0-1.125.504-1.125 1.125v1.5c0 .621.504 1.125 1.125 1.125m1.5-3.75C5.496 8.25 6 7.746 6 7.125v-1.5M4.875 8.25C5.496 8.25 6 8.754 6 9.375v1.5m0-5.25v5.25m0-5.25C6 5.004 6.504 4.5 7.125 4.5h9.75c.621 0 1.125.504 1.125 1.125m1.125 2.625h1.5m-1.5 0A1.125 1.125 0 0 1 18 7.125v-1.5m1.125 2.625c-.621 0-1.125.504-1.125 1.125v1.5m2.625-2.625c.621 0 1.125.504 1.125 1.125v1.5c0 .621-.504 1.125-1.125 1.125M18 5.625v5.25M7.125 12h9.75m-9.75 0A1.125 1.125 0 0 1 6 10.875M7.125 12C6.504 12 6 12.504 6 13.125m0-2.25C6 11.496 5.496 12 4.875 12M18 10.875c0 .621-.504 1.125-1.125 1.125M18 10.875c0 .621.504 1.125 1.125 1.125m-2.25 0c.621 0 1.125.504 1.125 1.125m-12 5.25v-5.25m0 5.25c0 .621.504 1.125 1.125 1.125h9.75c.621 0 1.125-.504 1.125-1.125m-12 0v-1.5c0-.621-.504-1.125-1.125-1.125M18 18.375v-5.25m0 5.25v-1.5c0-.621.504-1.125 1.125-1.125M18 13.125v1.5c0 .621.504 1.125 1.125 1.125M18 13.125c0-.621.504-1.125 1.125-1.125M6 13.125v1.5c0 .621-.504 1.125-1.125 1.125M6 13.125C6 12.504 5.496 12 4.875 12m-1.5 0h1.5m-1.5 0c-.621 0-1.125.504-1.125 1.125v1.5c0 .621.504 1.125 1.125 1.125M19.125 12h1.5m0 0c.621 0 1.125.504 1.125 1.125v1.5c0 .621-.504 1.125-1.125 1.125m-17.25 0h1.5m14.25 0h1.5" />
              </svg>                                                       
            </div>
            UpTopBMS - UpTopTraffic: Hệ thống quản lý phát sóng truyền hình
          </dt>
          <dd class="mt-2 text-base leading-7 text-gray-600">Giúp quản lý, thiết lập, tạo, đăng và duyệt video thông suốt cho toàn bộ quá trình phát sóng. Đảm bảo hoạt động phát sóng được an toàn, hiệu quả</dd>
        </div>
        <div class="relative pl-16">
          <dt class="text-base font-semibold leading-7 text-gray-900">
            <div class="absolute left-0 top-0 flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-600">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6 text-white">
                <path stroke-linecap="round" stroke-linejoin="round" d="m2.25 15.75 5.159-5.159a2.25 2.25 0 0 1 3.182 0l5.159 5.159m-1.5-1.5 1.409-1.409a2.25 2.25 0 0 1 3.182 0l2.909 2.909m-18 3.75h16.5a1.5 1.5 0 0 0 1.5-1.5V6a1.5 1.5 0 0 0-1.5-1.5H3.75A1.5 1.5 0 0 0 2.25 6v12a1.5 1.5 0 0 0 1.5 1.5Zm10.5-11.25h.008v.008h-.008V8.25Zm.375 0a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Z" />
              </svg>                                          
            </div>
            UpTopCGControl: Hệ thống quản lý đồ họa truyền hình
          </dt>
          <dd class="mt-2 text-base leading-7 text-gray-600">Giải pháp quản trị tài nguyên hình ảnh đồ họa giúp điều khiển và triển khai nhanh chóng cho mọi chương trình truyền hình đặc biệt là truyền hình trực tiếp</dd>
        </div>
        <div class="relative pl-16">
          <dt class="text-base font-semibold leading-7 text-gray-900">
            <div class="absolute left-0 top-0 flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-600">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6 text-white">
                <path stroke-linecap="round" stroke-linejoin="round" d="M21 7.5V18M15 7.5V18M3 16.811V8.69c0-.864.933-1.406 1.683-.977l7.108 4.061a1.125 1.125 0 0 1 0 1.954l-7.108 4.061A1.125 1.125 0 0 1 3 16.811Z" />
              </svg>                                          
            </div>
            UpTopMAM: Hệ thống quản lý tài nguyên media truyền hình
          </dt>
          <dd class="mt-2 text-base leading-7 text-gray-600">Được tổ chức đồng bộ, linh hoạt, thông minh đa tầng cho khả năng vận hành, xử lý, lưu trữ và truy xuất dữ liệu video băng thông lớn tốt nhất</dd>
        </div>
        <div class="relative pl-16">
          <dt class="text-base font-semibold leading-7 text-gray-900">
            <div class="absolute left-0 top-0 flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-600">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6 text-white">
                <path stroke-linecap="round" stroke-linejoin="round" d="M9.813 15.904 9 18.75l-.813-2.846a4.5 4.5 0 0 0-3.09-3.09L2.25 12l2.846-.813a4.5 4.5 0 0 0 3.09-3.09L9 5.25l.813 2.846a4.5 4.5 0 0 0 3.09 3.09L15.75 12l-2.846.813a4.5 4.5 0 0 0-3.09 3.09ZM18.259 8.715 18 9.75l-.259-1.035a3.375 3.375 0 0 0-2.455-2.456L14.25 6l1.036-.259a3.375 3.375 0 0 0 2.455-2.456L18 2.25l.259 1.035a3.375 3.375 0 0 0 2.456 2.456L21.75 6l-1.035.259a3.375 3.375 0 0 0-2.456 2.456ZM16.894 20.567 16.5 21.75l-.394-1.183a2.25 2.25 0 0 0-1.423-1.423L13.5 18.75l1.183-.394a2.25 2.25 0 0 0 1.423-1.423l.394-1.183.394 1.183a2.25 2.25 0 0 0 1.423 1.423l1.183.394-1.183.394a2.25 2.25 0 0 0-1.423 1.423Z" />
              </svg>                                          
            </div>
            UpTopAIProcessing: Hệ thống AI xử lý dữ liệu video lớn
          </dt>
          <dd class="mt-2 text-base leading-7 text-gray-600">Tự động xử lý gắn thẻ, tự động phát hiện gương mặt và các thiết lập được cài đặt cho việc lọc, phân loại và tìm kiếm video số lượng lớn</dd>
        </div>
      </dl>
    </div>
    <div class="flex flex-col items-center justify-center pt-6 mx-auto rounded-lg lg:px-10 max-w-7xl">
      <enhanced:img src="../../../static/solutionspage-broadcast.jpg" alt="hero" class="object-cover object-center rounded-xl" />
    </div>
  </div>
</div>

<div class="bg-white py-12 border-solid border-t border-gray-300 pt-14 pb-8">
  <div class="mx-auto max-w-7xl px-4 lg:px-8">
    <div class="mx-auto max-w-5xl text-center">
      <h2 class="text-base font-semibold leading-7 text-indigo-600">Đáp ứng mọi nhu cầu chuyển đổi số tùy biến theo các lĩnh vực khác nhau</h2>
      <p class="mt-4 text-4xl font-bold tracking-tight text-gray-900 sm:text-6xl" style="line-height: 1.1;">UpTopCustom - Giải pháp chuyển đổi số theo yêu cầu thuộc các lĩnh vực khác nhau</p>
      <p class="mt-12 text-lg leading-8 text-gray-600">Đáp ứng nhu cầu thực tế, đa dạng của các lĩnh vực hoạt động khác nhau, UpTop khai thác và xây dựng trên nền tảng công nghệ cốt lõi riêng có của UpTop - Nghĩa là mọi giải pháp, mọi mô hình chuyển đổi số do UpTop xây dựng và cung cấp đều được thừa hưởng nền tảng công nghệ tốt nhất với khả năng đáp ứng nhu cầu sử dụng, xử lý, lưu trữ, kết nối… không giới hạn. Đặc biệt, do việc kết thừa và phát triển trên nền tảng công nghệ cốt lõi hoàn toàn do UpTop làm chủ nên mọi dự án, mọi giải pháp do UpTop triển khai đều có khả năng vận hành, triển khai nhanh nhất với chi phí tốt nhất.</p>
    </div>
    <div class="mx-auto mt-16 max-w-2xl sm:mt-20 lg:mt-16 lg:mb-16 lg:max-w-4xl">
      <dl class="grid max-w-xl grid-cols-1 gap-x-8 gap-y-10 lg:max-w-none lg:grid-cols-2 lg:gap-y-16">
        <div class="relative pl-16">
          <dt class="text-base font-semibold leading-7 text-gray-900">
            <div class="absolute left-0 top-0 flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-600">              
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6 text-white">
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 7.5h1.5m-1.5 3h1.5m-7.5 3h7.5m-7.5 3h7.5m3-9h3.375c.621 0 1.125.504 1.125 1.125V18a2.25 2.25 0 0 1-2.25 2.25M16.5 7.5V18a2.25 2.25 0 0 0 2.25 2.25M16.5 7.5V4.875c0-.621-.504-1.125-1.125-1.125H4.125C3.504 3.75 3 4.254 3 4.875V18a2.25 2.25 0 0 0 2.25 2.25h13.5M6 7.5h3v3H6v-3Z" />
              </svg>                                         
            </div>
            UpTopNewsroom - Hệ thống hoạt động và quản lý tin tức
          </dt>
          <dd class="mt-2 text-base leading-7 text-gray-600">Giải pháp tòa soạn trung tâm giúp hoạt động lấy tin, sản xuất tin, xuất bản tin được triển khai theo thời gian thực nhanh chóng, hiệu quả</dd>
        </div>
        <div class="relative pl-16">
          <dt class="text-base font-semibold leading-7 text-gray-900">
            <div class="absolute left-0 top-0 flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-600">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6 text-white">
                <path stroke-linecap="round" stroke-linejoin="round" d="M5.25 14.25h13.5m-13.5 0a3 3 0 0 1-3-3m3 3a3 3 0 1 0 0 6h13.5a3 3 0 1 0 0-6m-16.5-3a3 3 0 0 1 3-3h13.5a3 3 0 0 1 3 3m-19.5 0a4.5 4.5 0 0 1 .9-2.7L5.737 5.1a3.375 3.375 0 0 1 2.7-1.35h7.126c1.062 0 2.062.5 2.7 1.35l2.587 3.45a4.5 4.5 0 0 1 .9 2.7m0 0a3 3 0 0 1-3 3m0 3h.008v.008h-.008v-.008Zm0-6h.008v.008h-.008v-.008Zm-3 6h.008v.008h-.008v-.008Zm0-6h.008v.008h-.008v-.008Z" />
              </svg>                                         
            </div>
            UpTopStorage - Giải pháp xử lý & lưu trữ đa tầng không giới hạn
          </dt>
          <dd class="mt-2 text-base leading-7 text-gray-600">Đáp ứng mọi nhu cầu về lưu trữ dữ liệu ở mọi cấp độ khác nhau với băng thông, lưu lượng và khả năng xử lý, vận hành không giới hạn cho cả online & offline</dd>
        </div>
        <div class="relative pl-16">
          <dt class="text-base font-semibold leading-7 text-gray-900">
            <div class="absolute left-0 top-0 flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-600">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6 text-white">
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 6.042A8.967 8.967 0 0 0 6 3.75c-1.052 0-2.062.18-3 .512v14.25A8.987 8.987 0 0 1 6 18c2.305 0 4.408.867 6 2.292m0-14.25a8.966 8.966 0 0 1 6-2.292c1.052 0 2.062.18 3 .512v14.25A8.987 8.987 0 0 0 18 18a8.967 8.967 0 0 0-6 2.292m0-14.25v14.25" />
              </svg>                                          
            </div>
            UpTopCMS - Giải pháp quản lý và xuất bản nội dung
          </dt>
          <dd class="mt-2 text-base leading-7 text-gray-600">Giải pháp của chúng tôi tập trung tối ưu nhất mục tiêu đưa nội dung của bạn tới hàng triệu độc giả nhanh nhất với chi phí thấp nhất.</dd>
        </div>
        <div class="relative pl-16">
          <dt class="text-base font-semibold leading-7 text-gray-900">
            <div class="absolute left-0 top-0 flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-600">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6 text-white">
                <path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
                <path stroke-linecap="round" stroke-linejoin="round" d="M15.91 11.672a.375.375 0 0 1 0 .656l-5.603 3.113a.375.375 0 0 1-.557-.328V8.887c0-.286.307-.466.557-.327l5.603 3.112Z" />
              </svg>                                          
            </div>
            UpTopVMS - Giải pháp xử lý, quản lý và xuất bản video
          </dt>
          <dd class="mt-2 text-base leading-7 text-gray-600">Đáp ứng nhu cầu xử lý, quản lý, lưu trữ & tìm kiếm video số lượng lớn thường xuyên liên tục. Giải pháp của chúng tôi đặc biệt phù hợp cho hệ thống camera giám sát</dd>
        </div>
      </dl>
    </div>
    <div class="flex flex-col items-center justify-center pt-6 mx-auto rounded-lg lg:px-10 max-w-7xl">
      <enhanced:img src="../../../static/solutionspage-custom-software.jpg" alt="hero" class="object-cover object-center rounded-xl" />
    </div>
  </div>
</div>

<Footer />