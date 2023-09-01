<template>
  <div class="credit">
    <h3 class="h2">
      이
      <a
        href="https://github.com/yootaejeon/birthday"
        target="_blank"
        class="link"
        >유은이 생일</a> 홈페이지를 만든 사람
    </h3>
    <div class="profile-list">
      <div class="profile">
        <a target="_blank" href="https://www.instagram.com/jeonstory.graphy/">
          <div class="thumbnail susan"></div>
          <div class="name">전 유 태</div>
          <div class="role">코딩을 맡은 아빠</div>
        </a>
      </div>
      <div class="profile">
        <a target="_blank" href="https://www.instagram.com/luv.each.other_">
          <div class="thumbnail anna"></div>
          <div class="name">신 지 희</div>
          <div class="role">디자인을 한 엄마</div>
        </a>
      </div>
    
    </div>
    <p class="description">뜻 깊은 유은이의 청첩장을 끝까지 봐주셔서 감사합니다.</p>
    <a href="https://www.instagram.com/jeonstory.graphy/" target="_blank" class="recruit">
      사랑스러운 유은이 동료가 되기
    </a>
  </div>
</template>

<script>
export default {
  name: "Credit",
};
</script>

<style lang="scss" scoped>
.credit {
  padding-top: 64px;
  padding-bottom: 80px;
  padding-left: $padding-vertical;
  padding-right: $padding-vertical;
  text-align: center;
  color: #202121;
  .h2 {
    font-size: 16px;
    font-weight: normal;
    margin-bottom: 38px;
    color: #295238;
  }
  .profile-list {
    display: flex;
    justify-content: center;
    width: 264px;
    margin: 0 auto;
    flex-wrap: wrap;
    margin-bottom: 14px;
    .profile {
      padding: 0 20px 24px 20px;
      a {
        color: inherit;
        text-decoration: none;
      }
      .thumbnail {
        width: 48px;
        height: 48px;
        border-radius: 50%;
        background-color: black;
        margin-bottom: 6px;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        &.susan {
          background-image: url(/birthday/img/credit/susan.jpg);
        }
        &.anna {
          background-image: url(/birthday/img/credit/anna.jpg);
        }
 
      }
      .name {
        font-size: 14px;
        margin-bottom: 3px;
      }
      .role {
        font-size: 10px;
        line-height: 1.6;
      }
    }
  }
  .description {
    font-size: 12px;
    margin-bottom: 16px;
    color: #295238;
  }
  .recruit {
    display: block;
    width: 184px;
    height: 44px;
    line-height: 44px;
    background-color: #ffb22c;
    color: #202121;
    text-decoration: none;
    font-size: 16px;
    margin: 0 auto;
  }
  .link {
    display: inline-block;
    margin-top: 24px;
    color: #295238;
  }
}
</style>
