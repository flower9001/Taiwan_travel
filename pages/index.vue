<template lang='pug'>
div
  Header/
  main.container
    img.me-2( src='@/assets/images/triangle.png' ) 
    h2.h2.d-inline 熱門城市
    .row

    img.me-2( src='@/assets/images/triangle.png' ) 
    h2.h2.d-inline 熱門活動
    .row

    img.me-2( src='@/assets/images/square.png' ) 
    h2.h2.d-inline 熱門餐飲
    .row
      
  Footer/
</template>

<script>
import Header from "~/components/Header"
import Footer from "~/components/Footer"

export default {}
</script>
