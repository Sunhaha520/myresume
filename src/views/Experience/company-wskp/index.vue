<template>
  <RowContent
    align="right"
    label="南京稀途信息技术有限公司"
    :label-bold="true"
    :label-width="220"
    :is-wrap="true"
    :is-title="true"
    text="2023年3月——2023年6月" />

  <ListWrap
    title="工作内容与职责："
    :list="list"
    inner
    title-size="base"
    bold />

  <ProEdr />
  <ProAdmin />
  <ProLarge />
  <ProTeam />
</template>

<script setup lang="ts">
import { ref } from 'vue'
import RowContent from '../../../components/RowContent/RowContent.vue'
import ListWrap from '../../../components/ListWrap/ListWrap.vue'
import ProEdr from './ProEdr.vue'
import ProAdmin from './ProAdmin.vue'
import ProLarge from './ProLarge.vue'
import ProTeam from './ProTeam.vue'

const list = ref([
  '1. 海外平台 (Facebook) 运营，负责广告投放，优化广告投放策略，提升产品及品牌曝光率；',
  '2. 负责公司英文网站的日常维护及运营，提升英文网站的 PV、UV、leads 及 MQL 数量。',
])
</script>

<style scoped></style>
