<template>
    <header class="header">
        <h1>Todo Lists</h1>
        <div id="nav">
            <router-link to="/">Home</router-link> |
            <router-link to="/todo">Todo</router-link>
        </div>
    </header>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style scoped>
    .header{
        background: #333;
        color: #fff;
        text-align: center;
        padding: 10px;
    }

    .header a {
        color: #fff;
        padding-right: 5px;
        text-decoration: none;
    }
    #nav {
        padding: 30px;
    }

    #nav a {
        font-weight: bold;
        color: #ad2027;
    }

    #nav a.router-link-exact-active {
        color: #fff;
    }
</style>