<template>
    <nav class="navbar navbar-expand navbar-dark bg-dark" style=" background-image:https://i0.wp.com/miniteacuppups.com/wp-content/uploads/2020/11/Teacup-Pomeranian-Puppy-Amy-1.jpg?fit=1080%2C1080&ssl=1 ;">
        <a href="/" class="navbar-brand">Ứng dụng Quản lý danh bạ</a>
        <div class="mr-auto navbar-nav">
            <li class="nav-item">
                <router-link :to="{ name: 'contactbook' }" class="nav-link">
                    Danh bạ
                    <i class="fas fa-address-book" />
                </router-link>
            </li>
        </div>
    </nav>
</template>