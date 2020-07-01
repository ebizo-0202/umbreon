<template>
  <div class="">
    <div :class="[$style.ipponPlateContainer]">
      <ipponPlate />
    </div>
    <div :class="[$style.ukeruButtonContainer]">
      <ukeruButton />
    </div>
  </div>
</template>

<script>
import ukeruButton from '~/components/atoms/UkeruButton.vue'
import ipponPlate from '~/components/molecules/IpponPlate.vue'
export default {
  components: {
    ukeruButton,
    ipponPlate
  }
}
</script>

<style module>
.ukeruButtonContainer {
  display: flex;
  width: 100%;
  justify-content: center;
}
</style>