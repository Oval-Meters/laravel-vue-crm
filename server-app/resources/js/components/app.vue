<template>
    <nav>
        <div style="padding: 10px; display: flex; justify-content: space-around;">
            <router-link class="link" to="/">Home</router-link>
            <router-link class="link" to="/about">About</router-link>
        </div>
    </nav>
    <main>
        <router-view></router-view>
    </main>
</template>