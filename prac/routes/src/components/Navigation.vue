<template>
    <div>
        <b-navbar type="dark" variant="dark">
            <b-navbar-nav>
                <b-nav-item to="/">Home</b-nav-item>
                <b-nav-item to="/about">About</b-nav-item>
                <b-nav-item to="/nuevo">Nuevo</b-nav-item>
            </b-navbar-nav>
        </b-navbar>
        <router-view/>
    </div>  
</template>
<script>
export default {
    name:'Navigation'
}
</script>