<template>
<div class="NavBar">
	<nav>
    <router-link to="/">Home</router-link> |
    <router-link to="../views/AboutView.vue">About Us</router-link> |
    <router-link to="../views/ContactView.vue">Contact Us</router-link> |
    <router-link to="/products">Products</router-link> |
    <router-link to="/login">Login/Register</router-link> |
    <router-link to="/admin">Admin</router-link> 
  </nav>
  <router-view/>
</div>
	</template>
	<script>
	
	export default{
		// eslint-disable-next-line vue/multi-word-component-names
		name:'NavBar'
	}
	</script>