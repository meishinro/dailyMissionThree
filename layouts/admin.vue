<script setup lang="ts"></script>

<template>
  <!-- 自定義後台header -->
    <header>
    <ul class="list">
      <li>
        <NuxtLink to="/">前台首頁</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/about">前台 About</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/admin">前往 後台首頁</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/admin/order">前往 後台訂單</NuxtLink>
      </li>
    </ul>
  </header>
  <!-- 顯示頁面內容 -->
    <slot />
  <!-- 自定義後台footer -->
    <footer>
    <h5>
      admin 模板的表尾
    </h5>
  </footer>
</template>

<style scoped></style>
