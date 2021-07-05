<template>
  <view class="content">
    <image class="logo" src="/static/logo.png"></image>
    <view>
      <text class="title">{{ title }}</text>
    </view>
  </view>
</template>

<script>
export default {
  data() {
    return {
      title: 'Hello'
    }
  },
  onLoad() {

  },
  methods: {}
}
</script>

<style>
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.logo {
  height: 100px;
  width: 100px;
  margin: 100px auto 25px auto;
}

.text-area {
  display: flex;
  justify-content: center;
}

.title {
  font-size: 18px;
  color: #8f8f94;
}
</style>
