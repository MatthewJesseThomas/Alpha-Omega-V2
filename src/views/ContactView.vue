<template>
		<nav>
    <router-link to="/">Home</router-link> |
    <router-link to="../views/AboutView.vue">About Us</router-link> |
    <router-link to="../views/ContactView.vue">Contact Us</router-link> |
    <router-link to="/products">Products</router-link> |
    <router-link to="/login">Login/Register</router-link> |
    <router-link to="/admin">Admin</router-link> 
  </nav>
  <router-view/>
	<div class="ContactView">
		<ContactForm/>
	</div>
	<Footer/>
	
</template>
<script>
// import NavBar from '@/components/NavBar.vue'
import Footer from '@/components/Footer.vue'
import ContactForm from '@/components/ContactForm.vue'
export default{
	components:{
		// NavBar,
		Footer,
		ContactForm
	}
}


</script>