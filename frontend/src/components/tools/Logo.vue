<template>
  <div class="logo">
    <router-link :to="{name:'exam-card'}">
      <LogoSvg alt="logo" />
      <h1 v-if="showTitle">{{ title }}</h1>
    </router-link>
  </div>
</template>

<script>
import LogoSvg from '../../assets/logo.svg?inline'

export default {
  name: 'Logo',
  components: {
    LogoSvg,
  },
  props: {
    title: {
      type: String,
      default: '在线考试系统',
      required: false,
    },
    showTitle: {
      type: Boolean,
      default: true,
      required: false,
    },
  },
}
</script>
