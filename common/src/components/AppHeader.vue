<template>
  <header>
    <h1>{{ title }}</h1>
  </header>
</template>

<script>
export default {
  //props : ['title']  // 기본적으로 프롭스 이렇게 사용
  props: {
    title: String, //프롭스 벨리데이션 문법
  }
}
</script>