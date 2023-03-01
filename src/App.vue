<template>
<Header/>
<Home/>
<!-- <Blog/> -->
<!-- <Contacts/> -->

</template>
<script>
import Header from './components/Header/Header.vue'
import Home from './pages/Home.vue'

export default{
   name:'App',
   components:{
    Header,
    Home,
   //  Blog
   //  Contacts
   }

}
</script>