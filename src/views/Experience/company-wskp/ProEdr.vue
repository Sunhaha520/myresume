<template>
  <ProjectWrap
    class="pl-4"
    title="广告数据分析策略"
    description="一套完整的广告数据分析策略，包括数据收集，数据清洗，探索性数据分析（EDA），建立基准线，A/B测试，ROI分析，趋势分析，用户行为分析。">
    <template #lib>
      <Button plain type="info" size="small">Vue2</Button>      
      <Button plain type="info" size="small">iView</Button>
      <Button plain type="info" size="small">Vxe-Table</Button>
      <Button plain type="info" size="small">Vue-i18n</Button>
      <Button plain type="info" size="small">Echarts</Button>
      <Button plain type="info" size="small">D3.js</Button>
    </template>
    <ListWrap
      title="主要贡献："
      :list="edrList"
      inner
      bold />

    <ListWrap
      title="项目难点："
      :list="hardList"
      inner
      bold />
  </ProjectWrap>

</template>

<script setup lang="ts">
import { ref } from 'vue'
import ProjectWrap from '../../../components/ProjectWrap/ProjectWrap.vue'
import ListWrap from '../../../components/ListWrap/ListWrap.vue'
import { Button } from 'fri-element-plus'

const edrList = ref([
  '- 负责从海外社交平台收集广告数据，并进行数据清洗、整理，确保数据质量和完整性',
  '- 根据业务需求和市场环境制定广告数据分析策略，包括确定关键指标、分析方法和优化方向',
  '- 运用各种数据分析工具和技术，对广告数据进行深入分析，挖掘潜在规律和趋势，发现优化点和机会',
])

const hardList = ref([
  '- 数据量大且复杂：广告平台每天产生大量的数据，包括点击量、曝光量、转化率等指标，数据量庞大且复杂，需要有效的分析方法来提取有用信息',
  '- 数据准确性和可靠性：广告数据可能受到机器误差、人为操作、欺诈行为等因素的影响，数据准确性和可靠性可能受到挑战，需要进行数据验证和验证',
  '- 时间敏感性：广告数据的分析需要及时反馈和调整，尤其是实时广告投放的情况下，需要确保数据分析的及时性和准确性',
  '- 复杂的用户行为模式：用户的点击路径、购买行为等可能十分复杂多样，理解用户行为模式并据此优化广告策略是一个挑战',
])
</script>
