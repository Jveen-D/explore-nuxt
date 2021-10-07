<template>
  <div class="flex flex-col items-center">
    <!--    layout-->
    <div class="w-1/2">
      <p class="text-4xl text-green-400">layout布局方式</p>
      <span>页面的layout属性指定了页面的布局方式，</span>
      <span>布局文件夹为layout,并且为default.vue</span>
      <span>在布局页面中</span>
      <span class="text-green-400">&lt;Nuxt/&gt;</span>
      <span>组件是用来显示你的页面组件的</span>
      <span>所以一定不要忘记将</span>
      <span class="text-green-400">&lt;Nuxt/&gt;</span>
      <span>添加到布局当中</span>
      <span>并且</span>
      <span class="text-green-400">&lt;Nuxt/&gt;</span>
      <span>只能在布局中使用</span>
      <p>
        <span>就拿这个页面来说，布局很明显发生了变化，</span>
        <span>就是因为下面的</span>
        <span class="text-green-400">layout</span>
        <span>属性发生了变化</span>
      </p>
    </div>

  </div>
</template>

<script lang="ts">
export default {
  layout: 'blog',
}
</script>
