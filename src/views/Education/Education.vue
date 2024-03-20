<template>
  <Section
    title="教育经历"
    anchor="Education"
    icon="peixunjiaoyu">
    <RowContent
      label="澳门大学 / 土木工程"
      :label-bold="true"
      text="2024年9月——2026年6月"
      align="right"
      :is-wrap="true" />
    <RowContent
      label="南京林业大学 / 土木工程"
      :label-bold="true"
      text="2019年9月——2023年6月"
      align="right"
      :is-wrap="true" />
  </Section>
</template>

<script setup lang="ts">
import Section from '../../components/Layouts/Section.vue'
import RowContent from '../../components/RowContent/RowContent.vue'
</script>
