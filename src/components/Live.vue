<template>
  <div class="live">
    <p class = "desc">
      위 애니메이션은 꼭 소리를 켜고 봐주세요!
    </p>
    <img src="~@/assets/images/hands.png" class="hands" />
    <div>
      <p class = "header">
        "사랑하는 유은이의 첫 생일잔치입니다."<br />
      </p>
      <p>
        사랑스럽고 예쁜 우리 유은이의 돌잔치에 초대합니다.<br />
        모두들 놀러와주셔서 예쁘게 봐주세요.<br />
      </p>
      <p class = "header">
        23년 10월 28일 토요일<br />
        오전 11시 30분<br />
      </p>
      <p>
        작은 돌잔치이기에 ..
        어쩌구 저쩌구
        축하해주세요.
      </p>

    </div>
    <Button @click="attendance">유은이 돌 영상</Button>
  </div>
</template>

<script>
export default {
  name: "Divider",
  methods: {
    attendance() {
      window.open("https://youtu.be/yU9UULnBt0w");
    },
  },
};
</script>

<style lang="scss" scoped>
.live {
  padding-top: 4px;
  padding-bottom: 68px;
  padding-left: $padding-vertical;
  padding-right: $padding-vertical;
  text-align: center;
  .hands {
    width: 75px;
    margin-bottom: 16px;
  }
  p {
    margin-bottom: 16px;
    line-height: 24px;
    &.desc {
      color: #295238;
      font-size: 10px;
      opacity: 0.6;
      margin-bottom: 36px;
    }
    &.header {
      color: #295238;
    }
    &:last-child {
      margin-bottom: 40px;
    }
  }
}
</style>
