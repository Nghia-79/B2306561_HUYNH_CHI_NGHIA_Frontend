<template>
  <nav class="navbar navbar-expand navbar-dark bg-dark">
    <router-link to="/" class="navbar-brand">Ứng dụng Quản lý danh bạ</router-link>
    <div class="mr-auto navbar-nav">
      <div class="nav-item">
        <router-link :to="{ name: 'contactbook' }" class="nav-link">
          Danh bạ <i class="fas fa-address-book"></i>
        </router-link>
      </div>
    </div>
  </nav>
</template>
