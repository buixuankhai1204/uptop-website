<script>
    import HeaderMenu from '$lib/components/HeaderMenu.svelte';
    import Footer from '$lib/components/Footer.svelte';
  </script>
  <HeaderMenu />

<div class="relative bg-white border-solid border-t border-gray-300 ">
  <div class="lg:absolute lg:inset-0 lg:left-1/2">
    <enhanced:img src="../../../static/contactpage-customer-services.jpg" alt="" class="h-64 w-full bg-gray-50 object-cover sm:h-80 lg:absolute lg:h-full" />
  </div>
  <div class="pb-24 pt-16 sm:pb-32 sm:pt-24 lg:mx-auto lg:grid lg:max-w-7xl lg:grid-cols-2 lg:pt-32">
    <div class="px-4 lg:px-8">
      <div class="mx-auto max-w-xl lg:mx-0 lg:max-w-lg">
        <h2 class="text-5xl font-bold tracking-tight text-gray-900">Liên hệ với chúng tôi</h2>
        <p class="mt-8 text-5xl leading-8 text-gray-600">Hotline: 0908.290.068</p>
        <p class="mt-8 text-lg leading-8 text-gray-600">Nếu bạn có bất kỳ thắc mắc, yêu cầu hay mong muốn gì hãy đừng ngại ngần mà liên hệ ngay với chúng tôi.</p>
        <form action="#" method="POST" class="mt-16">
          <div class="grid grid-cols-1 gap-x-8 gap-y-6 sm:grid-cols-2">
            <div>
              <label for="first-name" class="block text-sm font-semibold leading-6 text-gray-900">Họ & tên đệm</label>
              <div class="mt-2.5">
                <input type="text" name="first-name" id="first-name" autocomplete="given-name" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
              </div>
            </div>
            <div>
              <label for="last-name" class="block text-sm font-semibold leading-6 text-gray-900">Tên gọi</label>
              <div class="mt-2.5">
                <input type="text" name="last-name" id="last-name" autocomplete="family-name" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
              </div>
            </div>
            <div class="sm:col-span-2">
              <label for="email" class="block text-sm font-semibold leading-6 text-gray-900">Địa chỉ email</label>
              <div class="mt-2.5">
                <input id="email" name="email" type="email" autocomplete="email" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
              </div>
            </div>
            <div class="sm:col-span-2">
              <label for="company" class="block text-sm font-semibold leading-6 text-gray-900">Công ty</label>
              <div class="mt-2.5">
                <input type="text" name="company" id="company" autocomplete="organization" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
              </div>
            </div>
            <div class="sm:col-span-2">
              <div class="flex justify-between text-sm leading-6">
                <label for="phone" class="block font-semibold text-gray-900">Số điện thoại</label>
                <p id="phone-description" class="text-gray-400">Optional</p>
              </div>
              <div class="mt-2.5">
                <input type="tel" name="phone" id="phone" autocomplete="tel" aria-describedby="phone-description" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
              </div>
            </div>
            <div class="sm:col-span-2">
              <div class="flex justify-between text-sm leading-6">
                <label for="message" class="block text-sm font-semibold leading-6 text-gray-900">Chúng tôi có thể hỗ trợ gì?</label>
                <p id="message-description" class="text-gray-400">Tối đa 500 ký tự</p>
              </div>
              <div class="mt-2.5">
                <textarea id="message" name="message" rows="4" aria-describedby="message-description" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6"></textarea>
              </div>
            </div>
            <fieldset class="sm:col-span-2">
              <legend class="block text-sm font-semibold leading-6 text-gray-900">Bạn muốn trao đổi với:</legend>
              <div class="mt-4 space-y-4 text-sm leading-6 text-gray-600">
                <div class="flex gap-x-2.5">
                  <input id="budget-under-25k" name="budget" value="under_25k" type="radio" class="mt-1 h-4 w-4 border-gray-300 text-indigo-600 shadow-sm focus:ring-indigo-600">
                  <label for="budget-under-25k">Ban lãnh đạo</label>
                </div>
                <div class="flex gap-x-2.5">
                  <input id="budget-25k-50k" name="budget" value="25k-50k" type="radio" class="mt-1 h-4 w-4 border-gray-300 text-indigo-600 shadow-sm focus:ring-indigo-600">
                  <label for="budget-25k-50k">Phòng kinh doanh</label>
                </div>
                <div class="flex gap-x-2.5">
                  <input id="budget-50k-100k" name="budget" value="50k-100k" type="radio" class="mt-1 h-4 w-4 border-gray-300 text-indigo-600 shadow-sm focus:ring-indigo-600">
                  <label for="budget-50k-100k">Phòng giải pháp</label>
                </div>
                <div class="flex gap-x-2.5">
                  <input id="budget-over-100k" name="budget" value="over_100k" type="radio" class="mt-1 h-4 w-4 border-gray-300 text-indigo-600 shadow-sm focus:ring-indigo-600">
                  <label for="budget-over-100k">Phòng công nghệ</label>
                </div>
                <div class="flex gap-x-2.5">
                  <input id="budget-over-100k" name="budget" value="over_100k" type="radio" class="mt-1 h-4 w-4 border-gray-300 text-indigo-600 shadow-sm focus:ring-indigo-600">
                  <label for="budget-over-100k">Hành chính nhân sự</label>
                </div>
                <div class="flex gap-x-2.5">
                  <input id="budget-over-100k" name="budget" value="over_100k" type="radio" class="mt-1 h-4 w-4 border-gray-300 text-indigo-600 shadow-sm focus:ring-indigo-600">
                  <label for="budget-over-100k">Kế toán tài chính</label>
                </div>
                <div class="flex gap-x-2.5">
                  <input id="budget-over-100k" name="budget" value="over_100k" type="radio" class="mt-1 h-4 w-4 border-gray-300 text-indigo-600 shadow-sm focus:ring-indigo-600">
                  <label for="budget-over-100k">Chăm sóc khách hàng</label>
                </div>
              </div>
            </fieldset>
          </div>
          <div class="mt-10 flex justify-end border-t border-gray-900/10 pt-8">
            <button type="submit" class="rounded-md bg-indigo-600 px-3.5 py-2.5 text-center text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Gửi thông tin liên hệ</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</div>

<Footer />