<template>
  <b-navbar toggleable="sm" type="dark" variant="dark" sticky>
    <b-container fluid="lg">
      <!-- 网站标签 -->
      <b-navbar-brand href="/">Smarty.ink</b-navbar-brand>
      <!-- 移动端菜单展示方式 -->
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <!-- 菜单项 -->
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="/blog">博客</b-nav-item>
          <b-nav-item href="/work">作品</b-nav-item>
        </b-navbar-nav>
        <!-- 右侧链接 -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="/profile/:id">用户信息</b-nav-item>
          <b-nav-item href="/signout/:id">注销</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-container>
  </b-navbar>
</template>

<script>
export default {}
</script>