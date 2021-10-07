<template>
  <div class="flex flex-col items-center">
    <NuxtLink class="text-green-400" to="/01routerComPage">路由和组件</NuxtLink>
    <NuxtLink class="text-green-400" to="/02layout">layout布局</NuxtLink>
  </div>
</template>

<script>
export default {
  // layout: 'blog',
  /*
  * layout属性指定页面布局方式，布局方式文件夹为layouts,并且默认为default.vue
  * 在布局页面中，<Nuxt>组件是你用来显示你的页面组件的组件，所以一定不要忘记将<Nuxt>组件添加布局中，
  *
  * */
  head () {
    // Set Meta Tags for this Page
  }
  // ...
};
</script>
