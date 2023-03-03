<template>
	<NavBar/>
	<!-- <Spinner/>  -->
	<RouterView/>
	<ContactView/> 
	<RegisterComp/>  
	<LoginComp/>  
	<UserProfile/> 
	<UpdateUser/>  
	<ForgotPassword/>  
	<AddProduct/> 
	<Products/> 
	<HomeBody/> 
	<Footer/> 
<nav>
    <router-link to="/">Home</router-link> |
    <router-link to="../views/AboutView.vue">About Us</router-link> |
    <router-link to="../views/ContactView.vue">Contact Us</router-link> |
    <router-link to="../src/views/ProductView.vue">Products</router-link> |
    <router-link to="../src/views/LoginView.vue">Login/Register</router-link> |
    <router-link to="../src/views/AdminView.vue">Admin</router-link> 
  </nav>
  <router-view/>
  
</template>
<script>
// import Spinner from '@/components/SpinnerComponent.vue'
import ContactView from '@/components/ContactForm.vue'
import RegisterComp from '@/components/Register.vue'
import LoginComp from '@/components/Login.vue'
import UserProfile from '@/components/UserProfile.vue'
import UpdateUser from '@/components/UpdateUser.vue'
import ForgotPassword from '@/components/ForgotPassword.vue'
// import AddUser from '@/components/AddUser.vue'
import AddProduct from '@/components/AddProduct.vue'
import Products from '@/components/ProductComponent.vue'
import NavBar from '@/components/NavBar.vue'
import HomeBody from '@/components/HomeBody.vue'
import Footer from '@/components/Footer.vue'
export default{
	components:{
		// Spinner,
		NavBar,
		ContactView,
		RegisterComp,
		LoginComp,
		HomeBody,
		Footer,
		Products,
		AddProduct,
		// AddUser,
		ForgotPassword,
		UpdateUser,
		UserProfile,
	
		
		
		
		
	}
	
};

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
