<template>
  <view class="content">
    <view class="msg-box">
      <van-icon
        name="envelop-o"
        color="#f56a79"
        size="120rpx"
        :badge="msgNum"
      />
    </view>
  </view>
</template>

<script>
export default {
  data() {
    return {
      msgNum: 12,
    };
  },
  onLoad() {},
  methods: {},
};
</script>

<style lang="scss" scoped>
.content {
  display: flex;
  flex-direction: column;
  // align-items: center;
  // justify-content: center;
  .msg-box {
    padding: 36rpx;
  }
}
</style>
