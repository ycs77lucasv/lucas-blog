<template>
  <header class="container px-4">
    <div class="py-6 flex justify-between items-center">
      <RouterLink to="/">
        <heroicons-outline-book-open class="w-10 h-10 text-violet-600" />
      </RouterLink>

      <div>
        <a href="https://github.com/ycs77lucasv" target="_blank" class="text-gray-400 hover:text-violet-600">
          <ri-github-line class="w-6 h-6" />
        </a>
      </div>
    </div>

    <div class="pt-6 pb-12 border-b border-gray-300">
      <h1 class="text-4xl text-gray-900 font-medium tracking-wide sm:text-5xl lg:text-6xl">Lucas Blog</h1>
      <p class="mt-6 text-xl text-gray-500 tracking-wider">歡迎來到我的部落格~</p>
    </div>
  </header>

  <main class="container px-4 py-12">
    <ul class="space-y-10 sm:space-y-16">
      <li class="sm:flex" v-for="i in 4">
        <RouterLink to="/">
          <img class="aspect-video object-cover rounded-lg sm:w-[300px]" src="https://lucas-hiskio-2021-tailwindcss-slide.vercel.app/thumbnail.png" alt="">
        </RouterLink>

        <div class="mt-4 sm:mt-0 sm:ml-6">
          <h4 class="text-2xl font-bold tracking-wide">
            <RouterLink to="/" class="text-gray-800 hover:text-violet-600">
              我的文章
            </RouterLink>
          </h4>

          <div class="mt-2 text-gray-400 text-sm tracking-wider">2021/01/01</div>

          <p class="mt-3 text-gray-500">
            Hi！我是 Lucas~ 歡迎來到我的部落格~ 這是我的第一篇文章！Laravel / Vue.js / Tailwind CSS
          </p>

          <div class="mt-4">
            <RouterLink to="/" class="text-violet-500 hover:text-violet-400 tracking-wider">
              更多 →
            </RouterLink>
          </div>
        </div>
      </li>
    </ul>

    <ul class="mt-12 flex justify-center items-center">
      <li>
        <RouterLink to="/" class="flex justify-center items-center h-9 px-3 text-gray-400 hover:text-violet-600 text-lg font-medium">
          <heroicons-outline-arrow-left />
        </RouterLink>
      </li>
      <li v-for="i in 3">
        <RouterLink to="/" class="flex justify-center items-center h-9 px-3 text-gray-400 hover:text-violet-600 text-lg font-medium">
          {{ i }}
        </RouterLink>
      </li>
      <li>
        <RouterLink to="/" class="flex justify-center items-center h-9 px-3 text-gray-400 hover:text-violet-600 text-lg font-medium">
          <heroicons-outline-arrow-right />
        </RouterLink>
      </li>
    </ul>
  </main>
</template>

<script>
export default {

}
</script>
