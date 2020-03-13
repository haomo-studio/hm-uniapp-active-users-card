> 官网: [https://haomo-tech.com](https://haomo-tech.com)

> 作者: 毫末科技

> 邮箱: hxg@haomo-studio.com

## 预览

![预览图片](http://downloads.haomo-tech.com/uniapp/hm-active-users-card.png)

[在线效果预览](http://template.uniapp.haomo-tech.com/pages/haomo/test-component/hm-active-users-card)

更多毫末科技的uni-app跨端模板，请见[毫末科技uni-app跨端模板](https://haomo-tech.com/sale.html)

## 技术支持

* [uni-app插件市场](https://ext.dcloud.net.cn/plugin?id=1423)

* [npm包](https://www.npmjs.com/package/hm-uniapp-active-users-card)

* [github地址](https://github.com/haomo-studio/hm-uniapp-active-users-card)

* [gitee地址](https://gitee.com/haomo/hm-uniapp-active-users-card)


毫末科技将长期迭代本组件。需要技术支持，请进钉钉群：

<img width="250" src="http://downloads.haomo-tech.com/%E6%AF%AB%E6%9C%ABuniapp%E7%BB%84%E4%BB%B6%E6%8A%80%E6%9C%AF%E6%94%AF%E6%8C%81.jpg">

## 概述

毫末uni-app毫末活越用户卡片组件。支持H5/小程序(微信、支付宝、头条、百度、QQ)/App；组件可自适应各种屏幕大小的手机。

## 使用

请使用HBuilderX导入组件。

在script中引用：

```javascript
import HmNewsCard from '@/components/hm-active-users-card/index.vue'
export default {
    components: { HmActiveUsersCard }
}
```

在template中使用：

```html
<template>
  <div class="test-component">
    <hm-active-users-card :options="options"></hm-active-users-card>
  </div>
</template>
<script>
import HmActiveUsersCard from '@/components/hm-components/hm-active-users-card/index.vue'

export default {
  components: {
    HmActiveUsersCard
    },
  data() {
    return {
      options: {
          title: '活越用户',
          titleImg:
            './images/img_24275_0_0.png',
          wan: '4.8万',
          monthly: '每月',
          weekNum: '1.3万',
          weekly: '每周',
          people: '166人',
          daily: '每日',
          floorBg:
            './images/img_24275_0_1.png',
          longBg:
            './images/img_24275_0_2.png',
          barImg:
            './images/img_24275_0_3.png'
        }
    };
  },
  methods: {
  }
};
</script>
<style>
</style>

```

## 属性说明

| 属性名        | 类型     | 默认值 | 说明                                                                       |
|-----------   |---------|--------|----------------------------------------------------------------------------|
| options        | Object  | -      | 卡片属性                                                                   |

options对象各个属性说明如下：

| 属性名        | 类型     | 默认值 | 说明                                                                       |
|-----------   |---------|--------|----------------------------------------------------------------------------|
| title        | String  | -      | 标题文字                                                                   |
| titleImg        | String  | -      | 图片                                                                   |
| wan        | String  | -      | 每月活跃人数                                                                   |
| monthly        | String  | -      | 每月                                                                   |
| weekNum        | String  | -      | 每周活跃人数                                                                   |
| weekly        | String  | -      | 每周                                                                  |
| people        | String  | -      | 每日活跃人数                                                                   |
| daily        | String  | -      | 每日                                                                   |
| floorBg        | String  | -      | 图片                                                                   |
| longBg        | String  | -      | 图片                                                                   |
| barImg        | String  | -      | 图片                                                                   |

## 事件说明

| 事件称名   | 事件说明           | 返回参数 |
|----------|--------------------|----------|
| @click   | 点击 Card 触发事件 | -        |

## 更新日志

### 0.0.1(2020-03-13)

* 完成第一个版本