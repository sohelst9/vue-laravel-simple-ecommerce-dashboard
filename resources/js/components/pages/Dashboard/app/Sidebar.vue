<template>
    <!-- Sidebar -->
    <nav class="sidebar">
        <h3 class="text-center mb-4">Dashboard</h3>
        <router-link :to="{ name: 'home' }" class="item"><fontawesome-icon class="icon" icon="home" /> Home </router-link>

        <router-link :to="{ name: 'admin_categories' }" class="item"><fontawesome-icon class="icon" icon="list-alt" /> Categories
        </router-link>

        <router-link :to="{ name: 'admin_products' }" class="item"><fontawesome-icon class="icon" icon="cart-plus" /> Products
        </router-link>
       
        <router-link :to="{ name: 'admin_sales' }" class="item"><fontawesome-icon class="icon" icon="cash-register" /> Sales </router-link>
        <router-link :to="{ name: 'home' }" class="item"><fontawesome-icon class="icon" icon="users" /> Users
        </router-link>
        <router-link :to="{ name: 'home' }" class="item"><fontawesome-icon class="icon" icon="fa-cog" /> Settings
        </router-link>

    </nav>
</template>