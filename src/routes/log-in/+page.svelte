<script>
  import { onMount } from 'svelte';
  import HeaderMenu from '$lib/components/HeaderMenu.svelte';
</script>  

<HeaderMenu />

<div class="flex min-h-full flex-col justify-center px-6 py-12 lg:px-8">
  <div class="sm:mx-auto sm:w-full sm:max-w-sm">        
    <h2 class="mt-10 text-center text-2xl font-bold leading-9 tracking-tight text-gray-900">Đăng nhập tài khoản</h2>
  </div>

  <div class="mt-10 sm:mx-auto sm:w-full sm:max-w-sm">
    <form class="space-y-6" action="#" method="POST">
      <div>
        <label for="email" class="block text-sm font-medium leading-6 text-gray-900">Địa chỉ email</label>
        <div class="mt-2">
          <input id="email" name="email" type="email" autocomplete="email" required class="px-3 block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
        </div>
      </div>

      <div>
        <div class="flex items-center justify-between">
          <label for="password" class="block text-sm font-medium leading-6 text-gray-900">Mật khẩu</label>
          <div class="text-sm">
            <a href="/recover-password" class="font-semibold text-indigo-600 hover:text-indigo-500">Quên mật khẩu?</a>
          </div>
        </div>
        <div class="mt-2">
          <input id="password" name="password" type="password" autocomplete="current-password" required class="px-3 block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
        </div>
      </div>

      <div>
        <button type="submit" class="flex w-full justify-center rounded-md bg-indigo-600 px-3 py-1.5 text-sm font-semibold leading-6 text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Đăng nhập</button>
      </div>
    </form>

    <p class="mt-10 text-center text-sm text-gray-500">
      Bạn không có tải khoản?
      <a href="/contact" class="font-semibold leading-6 text-indigo-600 hover:text-indigo-500">Liên hệ với chúng tôi</a>
    </p>
  </div>
</div>