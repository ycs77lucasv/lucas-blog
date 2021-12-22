<template>
  <header class="container px-4">
    <div class="py-6 flex justify-between items-center">
      <RouterLink to="/" class="flex items-center">
        <heroicons-outline-book-open class="w-10 h-10 text-violet-600" />
        <div class="ml-2 text-gray-900 text-xl font-medium">Lucas Blog</div>
      </RouterLink>

      <div>
        <a href="https://github.com/ycs77lucasv" target="_blank" class="text-gray-400 hover:text-violet-600">
          <ri-github-line class="w-6 h-6" />
        </a>
      </div>
    </div>
  </header>

  <article class="container px-4 py-12">
    <div class="text-center">
      <h1 class="text-5xl font-medium tracking-wider">我的文章</h1>
      <div class="mt-4 text-gray-400 tracking-wider">2021/01/01</div>
    </div>

    <div class="mt-16 mx-auto prose prose-headings:font-medium prose-a:text-violet-600 hover:prose-a:text-violet-500 lg:prose-xl">
      <h2>Hi！我是 Lucas</h2>
      <p>
        我的部落格：<a href="https://lucas-yang.vercel.app/" target="_blank">星星的筆記．Lucas</a>
      </p>
      <img src="https://cdn.jsdelivr.net/npm/slidev-theme-ycs77/public/images/lucas_v_avatar.jpg" />
      <ul>
        <li><strong>個人嗜好</strong>：刻網站、看動漫</li>
        <li><strong>喜歡的唱見</strong>：hanser、三无Marblue</li>
        <li><strong>喜歡的遊戲</strong>：崩壞3rd、原神</li>
      </ul>
      <p>
        自學網頁前後端，主要以 Laravel、Vue.js、Tailwind CSS 為慣用開發框架。做過幾個小網站。
      </p>
      <blockquote>
        夜空中的小星星，也會閃耀著光芒 ✨
        <br />
        — Lucas
      </blockquote>
    </div>
  </article>
</template>

<script>
export default {

}
</script>
