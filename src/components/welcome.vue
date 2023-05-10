<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading><a href="https://hcp.secself.com/golang/" class="green" target="_blank" rel="noopener">Golang</a></template>
      在安全领域地位在急剧上升中，逐渐成为主流的趋势，它高性能、高并发、易于编写和安全性都是编写工具脚本的不二选择。
  </WelcomeItem>
<br>
    <br>
    <br>
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading><a href="https://hcp.secself.com/python/" target="_blank" class="green" rel="noopener">Python（准备中）</a></template>

    Python目前仍是安全工具首选语言，简单易用、强大的库支持、广泛应用等特点，用于写安全工具是再好不过的选择。
  </WelcomeItem>

</template>
