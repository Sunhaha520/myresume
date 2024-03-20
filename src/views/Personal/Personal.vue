<template>
  <Section
    anchor="Personal"
    :title="`个人项目 & 参与开源`"
    icon="github-fill">
    <div class="grid grid-cols-1 gap-3 sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-3">
      <RepositoryItem
        name="研导博客"
        description="一个为广大学子提供导师信息的网站。"
        link="https://rate.xiaoayu.ren">
        <div class="flex flex-row">
          <div class="flex-1">
            推荐内容：
            <a
              class="block"
              target="_blank"
              href="https://www.xiaoayu.ren/yandaowang/"
              >研导博客上线</a
            >
          </div>
          <a
            class="flex items-center justify-center p-4 cursor-pointer"
            href="https://rate.xiaoayu.ren"
            target="_blank">
            <Iconfont
              name="tiaozhuan"
              :size="22" />
          </a>
        </div>
      </RepositoryItem>

      <RepositoryItem
        name="ChatGPT-Web"
        transitionType="formLeft"
        description="一个轻量的ChatGPT商用系统。"
        link="https://aichat.xiaoayu.ren">
        <div class="flex flex-row">
          <div class="basis-full flex flex-wrap flex-row gap-1">
            <img
              alt="Static Badge"
              src="https://img.shields.io/badge/%E5%89%8D%E7%AB%AF%E6%A1%86%E6%9E%B6-Vue3-%236495ed" />
            <img
              alt="Static Badge"
              src="https://img.shields.io/badge/UI-TailWind-green" />
            <img
              alt="Static Badge"
              src="https://img.shields.io/badge/%E8%84%9A%E6%9C%AC%E8%AF%AD%E8%A8%80-TypeScript-%25236495ed" />
            <img
              alt="Static Badge"
              src="https://img.shields.io/badge/UI-fri_element_plus-%238a2be2" />
          </div>
          <a
            class="flex items-center justify-center p-4 cursor-pointer"
            href="https://aichat.xiaoayu.ren"
            target="_blank">
            <Iconfont
              name="tiaozhuan"
              :size="22" />
          </a>
        </div>
      </RepositoryItem>

      <RepositoryItem
        name="NJFU-WiFi-Tools"
        description="南京林业大学校园网逆向工具"
        transitionType="fromTop"
        link="https://github.com/Sunhaha520/NJFU-WiFi-Tools">
        <div class="flex flex-row">
          <div class="flex-1">
            推荐内容：
            <a
              class="block"
              target="_blank"
              href=""
              >校园网工具使用教程</a
            >
          </div>
          <a
            class="flex items-center justify-center p-4 cursor-pointer"
            href="https://github.com/Sunhaha520/NJFU-WiFi-Tools"
            target="_blank">
            <Iconfont
              name="tiaozhuan"
              :size="22" />
          </a>
        </div>
      </RepositoryItem>

      <RepositoryItem
        name="Smart-Search"
        description="支持新搜索api的Ai搜索引擎，二次开发"
        transitionType="fromRight"
        link="https://github.com/Sunhaha520/Smart-Search">
        <div class="flex flex-row">
          <div class="basis-full flex flex-wrap flex-row gap-1">
            <img
              alt="Static Badge"
              src="https://img.shields.io/badge/%E8%84%9A%E6%89%8B%E6%9E%B6-vite-red" />
            <img
              alt="Static Badge"
              src="https://img.shields.io/badge/%E5%89%8D%E7%AB%AF%E6%A1%86%E6%9E%B6-Vue3-%236495ed" />

            <img
              alt="Static Badge"
              src="https://img.shields.io/badge/%E8%84%9A%E6%9C%AC%E8%AF%AD%E8%A8%80-TypeScript-%25236495ed" />
            <img
              alt="Static Badge"
              src="https://img.shields.io/badge/%E6%89%93%E5%8C%85%E5%B7%A5%E5%85%B7-Rollup-orange" />
          </div>
          <a
            class="flex items-center justify-center p-4 cursor-pointer"
            href="https://github.com/Sunhaha520/Smart-Search"
            target="_blank">
            <Iconfont
              name="tiaozhuan"
              :size="22" />
          </a>
        </div>
      </RepositoryItem>

      <RepositoryItem
        name="Machine-Vision-Project"
        transitionType="fadeIn"
        description="一些自学计算机视觉的项目"
        link="https://github.com/Sunhaha520/Machine-Vision-Project">
        <div class="flex flex-row">
          <div class="flex flex-wrap gap-y-2">
            <Button size="small">Ai隔空键盘</Button>
            <Button size="small">手距测试</Button>
            <Button size="small">空闲车位监测</Button>
            <Button size="small">人脸识别打卡</Button>
            <Button size="small">车辆监测</Button>
          </div>
          <a
            class="flex items-center justify-center p-4 cursor-pointer"
            href="https://github.com/Sunhaha520/Machine-Vision-Project"
            target="_blank">
            <Iconfont
              name="tiaozhuan"
              :size="22" />
          </a>
        </div>
      </RepositoryItem>
    </div>
  </Section>
</template>

<script setup lang="ts">
import Section from '../../components/Layouts/Section.vue'
import RepositoryItem from '../../components/RepositoryItem/RepositoryItem.vue'
import Iconfont from '../../components/Iconfont/Iconfont.vue'
import { Button } from 'fri-element-plus'
</script>
