<template>
  <body id="body">

    <!-- preloader -->
    <div id="preloader">
      <img src="img/preloader.gif" alt="Preloader">
    </div>
    <!-- end preloader -->
    <!-- header -->
    <appHeader />
    <!--end header -->
    <!-- main component -->
    <router-view/>
    <!--end main component -->
    <!-- footer -->
    <appFooter />
    <!--end footer -->

  </body>
</template>

<script>
import appHeader from '@/components/layouts/Header';
import appFooter from '@/components/layouts/Footer';
export default {
  components: {
    appHeader,appFooter
  }
}
</script>

<style>

</style>
