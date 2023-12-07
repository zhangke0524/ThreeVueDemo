<!--
 * @Author: zhangke ke.zhang29@gientech.com
 * @Date: 2023-11-29 14:20:57
 * @LastEditors: zhangke ke.zhang29@gientech.com
 * @LastEditTime: 2023-12-01 16:21:57
 * @FilePath: \three_vue_project\src\App.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<script setup>
import First from './views/first.vue'
import Second from './views/second.vue'
</script>

<template>
  <div>
    <First />
    <!-- <Second /> -->
  </div>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

.main-content {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items:center;
}
.stats-content {
  width: 200px;
  height: 100px;
  /* position: absolute;
  top: 0;
  left: 50%;
  translate: translateX(-50%); */
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
