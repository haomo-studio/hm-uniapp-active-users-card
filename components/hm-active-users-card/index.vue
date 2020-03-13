<template>
  <div class="hm-active-users-card">
    <div class="cardClass">
      <div class="titleClass">
        <text class="title">{{ options.title }}</text>
        <image class="titleImg" :src="options.titleImg" />
      </div>
      <div class="Wrap">
        <div class="color" />
        <div class="monthWrap">
          <text class="wan">{{ options.wan }}</text>
          <text class="monthly">{{ options.monthly }}</text>
        </div>
        <div class="colorDiv" />
        <div class="weekWrap">
          <text class="weekNum">{{ options.weekNum }}</text>
          <text class="weekly">{{ options.weekly }}</text>
        </div>
        <div class="colorWrap" />
        <div class="dayWrap">
          <text class="people">{{ options.people }}</text>
          <text class="daily">{{ options.daily }}</text>
        </div>
      </div>
      <div class="main" />
      <div class="row" />
      <div class="row1" />
      <div class="row2" />
      <image class="floorBg" :src="options.floorBg" />
      <image class="longBg" :src="options.longBg" />
      <div class="row3" />
      <div class="tail" />
      <image class="barImg" :src="options.barImg" />
    </div>
  </div>
</template>
<script>
export default {
  name: 'HmActiveUsersCard',
  props: {
    dataId: {
      type: String,
      default: 'hm-active-users-card'
    },
    options: {
      type: Object,
      default: function() {
        return {
          title: '活越用户',
          titleImg:
            '/static/hm-active-users-card/images/img_24275_0_0.png',
          wan: '4.8万',
          monthly: '每月',
          weekNum: '1.3万',
          weekly: '每周',
          people: '166人',
          daily: '每日',
          floorBg:
            '/static/hm-active-users-card/images/img_24275_0_1.png',
          longBg:
            '/static/hm-active-users-card/images/img_24275_0_2.png',
          barImg:
            '/static/hm-active-users-card/images/img_24275_0_3.png'
        };
      }
    }
  },
  data() {
    return {};
  },
  methods: {}
};
</script>
<style>
@import './index.response.css';
</style>
