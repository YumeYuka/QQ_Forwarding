<script setup lang="ts">

defineProps<{ msg: string }>()

</script>

<template>
  <h1>{{ msg }}</h1>
  <p class="read-the-docs">
    点击 <code>按钮</code> 选择加入的群组.
  </p>

  <div class="card">
    <a href="https://qm.qq.com/q/pKuFysMZs4" target="_blank"
       style="margin-right: 10%;">
      <button type="button">伊甸园</button>
    </a>
    <a href="https://qm.qq.com/q/5MHCYXQQZG" target="_blank">
      <button type="button">帮助</button>
    </a>
  </div>


  <p>
    活跃用户选择
    <a href="https://qm.qq.com/q/pKuFysMZs4" target="_blank">
      伊甸园
    </a> 群；仅疑问选择 <a href="https://qm.qq.com/q/5MHCYXQQZG" target="_blank">
    帮助
  </a> 群。
  </p>
  <p class="read-the-docs">
    <a href="https://qm.qq.com/q/pKuFysMZs4" target="_blank">
      伊甸园
    </a> 群组(ps: <a href="https://www.yuanshen.com" target="_blank">
    答案
  </a>)将不会讨论任何有关刷机、root等内容，解答疑问请添加 <a href="https://qm.qq.com/q/5MHCYXQQZG"
                                                                                   target="_blank">
    帮助
  </a>群组。
  </p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
