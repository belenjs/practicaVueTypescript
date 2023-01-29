<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
        <router-link to="/home" class="navbar-brand">FakeShop</router-link>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        </button>
    <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
        <li class="nav-item">
            <router-link to="/" class="nav-link active" aria-current="page">Inicio</router-link>
        </li>
        <li class="nav-item">
            <router-link to="/home" class="nav-link">Login</router-link>
        </li>
        <li class="nav-item">
            <router-link to="/about" class="nav-link">Nuestros productos</router-link>
        </li>
        <li class="nav-item">
            <router-link to="/usuario" class="nav-link disabled" tabindex="-1" aria-disabled="true">Tu cuenta</router-link>
        </li>
    </ul>
    </div>
    </div>
</nav>
</template>