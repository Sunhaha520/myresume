<template>
  <Section
    title="专业技能"
    anchor="Skill"
    icon="zhuanyezhishijineng">
    <ListWrap
      title="计算机技能"
      :list="feList"
      bold />

    <ListWrap
      title="其他技能"
      :list="otherList"
      bold />
  </Section>
</template>

<script setup lang="ts">
import { ref } from 'vue'
import Section from '../../components/Layouts/Section.vue'
import ListWrap from '../../components/ListWrap/ListWrap.vue'

const feList = ref([
  '1. 熟练掌握 HTML、CSS 编写符合 Web 标准的代码；',
  '2. 了解 JavaScript、TypeScript；',
  '3. 熟悉 Shell、Python 和 C++ 等编程语言，了解SQL、OpenCV等基础知识；',
  '4. 熟悉 Vue 及相关技术栈的开发，了解 React 技术栈；',
  '5. 熟悉计算机网络，算法与数据结构等基础；',
  '6. 熟练操作PS，AutoCAD，PKPM，XMind等软件，熟悉SPSS，Stata等数据分析软件的使用。',
])

const otherList = ref([
  '1. 熟悉 Node.js 及常用模块；',
  '2. 熟悉 Linux 常用命令，可独立完成运维和部署；',
  '3. 可使用墨刀进行产品原型图绘制；',
  '4. 熟悉版本管理工具 git；',
  '5. 自学素描，国画等，有一定的艺术天赋及较高的审美；',
  '5. 善用科学搜索、插件，高效主义。',
])
</script>
