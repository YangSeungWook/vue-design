<template>
  <!-- <check-box :checked="checked"></check-box>  프롭스로 내리면 오류남.. 하위 컴포넌트에서 상위에 있는 프롭스값을 바꾸려고 해서-->
  <check-box v-model="checked"></check-box>
</template>

<script>
import CheckBox from './components/CheckBox.vue';

export default {
  components: {
    CheckBox
  },
  data() {
    return {
      checked : false
    }
  }
}
</script>