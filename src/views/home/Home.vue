<template>
  <div class="home">
    <h1>Anasayfa</h1>
    <CustomText tag="p" size="normal">merhaba</CustomText>
    <CustomText tag="p" size="small">merhaba</CustomText>
    <CustomText tag="p" size="xsmall">merhaba</CustomText>
    <CustomText tag="p" size="xxsmall">merhaba</CustomText>
    <IconSave with="40" height="40" />
  </div>
</template>

<script>
import CustomText from "@/components/CustomText";
import IconSave from "../../icons/save.svg";
export default {
  name: "Home",
  components: {
    CustomText,
    IconSave
  }
};
</script>
<style scoped>
h1 {
  color: rebeccapurple;
}
@media (--t) {
  h1 {
    color: royalblue;
  }
}
</style>
