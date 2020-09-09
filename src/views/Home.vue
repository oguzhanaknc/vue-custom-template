<template>
  <div class="home">
   <h1> Anasayfa</h1>
    <CustomText tag="p" size="normal">merhaba</CustomText>
    <CustomText tag="p" size="small">merhaba</CustomText>
    <CustomText tag="p" size="xsmall">merhaba</CustomText>
    <CustomText tag="p" size="xxsmall">merhaba</CustomText>
  </div>
</template>

<script>  

import CustomText from '@/components/CustomText'

export default {
  name: "Home",
  components:{
    CustomText
  }
};
</script>
<style  scoped>
h1{
  color: rebeccapurple;
}
 @media(--t){
   h1{
     color: royalblue;
   }
 }
</style>
