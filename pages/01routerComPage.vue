<template>
  <div class="flex flex-col items-center">
    <!--    路由-->
    <div class="w-1/2">
      <p class="text-4xl text-green-400">路由</p>
      <span>对于指向站点内页面的所有导航，使用</span>
      <span class="text-green-400">&lt;NuxtLink&gt;</span>
      <span>,如果要链接其他的网站，则使用</span>
      <span class="text-green-400">&lt;a&gt;</span>
      <span>标签</span>
      <NuxtLink class="text-red-500" to="/"></NuxtLink>
    </div>
    <!--    组件-->
    <div class="w-1/2">
      <p class="text-4xl text-green-400">组件</p>
      <p>
        <span>只要</span>
        <span class="text-green-400">nuxt.config.js</span>
        <span>的</span>
        <span class="text-green-400">components</span>
        <span>设置为</span>
        <span class="text-green-400">true</span>,
        <span class="text-green-400">Nuxt</span>
        <span>会自动扫描并导入这些组件</span>
      </p>
    </div>
    <!--    页面-->
    <div class="w-1/2">
      <p class="text-4xl text-green-400">页面</p>
      <p>
        <span>页面和组件一样，无需引入，只是页面路径必须和页面文件夹路径对应起来，就比如这个页面路径为</span>
        <span class="text-green-400">/01routerComPage</span>
        <span>,那么在使用</span>
        <span class="text-green-400">&lt;NuxtLink&gt;</span>
        <span>跳转时必须要和页面文件一样，比如</span>
        <span class="text-green-400">&lt;NuxtLink to="/01routerComPage"&gt;xxx&lt;/NuxtLink&gt;</span>
      </p>
    </div>
  </div>
</template>

<script lang="ts">
</script>
