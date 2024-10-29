<template>
    <div class="wrapper">

        <TopNavBar/>

        <SideNavBar/>

        <router-view/>

        <Footer/>

        <aside class="control-sidebar control-sidebar-dark">

        </aside>
        <!-- /.control-sidebar -->
    </div>
</template>
<script>
   import SideNavBar from "./appVue/Component/SideNavBar";
   import TopNavBar from "./appVue/Component/TopNavBar";
   import Footer from "./appVue/Component/Footer";
   export default {
      name: 'App',
       components: {Footer, TopNavBar, SideNavBar},
   }

</script>
