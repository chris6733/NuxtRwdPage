<template>
  <div class="card-wrap">
    <div class="card-top">
      <span>{{ time }}</span>
      <img src="https://fakeimg.pl/450x300/" />
    </div>
    <div class="card-bottom">
      <div class="avatar">
        <svg viewBox="0 0 496 512" width="100" title="user-circle">
          <path
            d="M248 8C111 8 0 119 0 256s111 248 248 248 248-111 248-248S385 8 248 8zm0 96c48.6 0 88 39.4 88 88s-39.4 88-88 88-88-39.4-88-88 39.4-88 88-88zm0 344c-58.7 0-111.3-26.6-146.5-68.2 18.8-35.4 55.6-59.8 98.5-59.8 2.4 0 4.8.4 7.1 1.1 13 4.2 26.6 6.9 40.9 6.9 14.3 0 28-2.7 40.9-6.9 2.3-.7 4.7-1.1 7.1-1.1 42.9 0 79.7 24.4 98.5 59.8C359.3 421.4 306.7 448 248 448z"
          />
        </svg>
      </div>
      <div class="content" style="text-align: start">
        <h3>{{ name }}</h3>
        <h3>{{ sub }}</h3>
      </div>
      <div class="more">
        <svg viewBox="0 0 192 512" width="100" title="ellipsis-v">
          <path
            d="M96 184c39.8 0 72 32.2 72 72s-32.2 72-72 72-72-32.2-72-72 32.2-72 72-72zM24 80c0 39.8 32.2 72 72 72s72-32.2 72-72S135.8 8 96 8 24 40.2 24 80zm0 352c0 39.8 32.2 72 72 72s72-32.2 72-72-32.2-72-72-72-72 32.2-72 72z"
          />
        </svg>
      </div>
    </div>
  </div>
</template>



<script>
export default {
  data() {
    return {
      name: "Lorem ipsum, dolor sit amet consectetur.",
      sub: "Lorem ipsum dolor sit amet consectetur.",
      time: "10:00:00",
    };
  },
};
</script>

<style lang="scss" scoped>
.card {
  &-wrap {
    max-width: 450px;
    height: 400px;
    background-color: #fff;
    margin: 10px;
  }
  &-top {
    span {
      float: right;
      transform: translate(-10px, 290px);
      background-color: $dark;
      color: #fff;
      padding: 0 5px;
    }
  }

  &-bottom {
    display: flex;
    justify-content: space-between;
    padding: 10px;
    .avatar {
      svg {
        width: 60px;
      }
    }

    .content {
      width: 280px;
      color: #000;

      h3 {
        text-align: start;
        &:nth-child(2) {
          font-size: 14px;
          color: $gray;
        }
      }
    }

    .more {
      svg {
        width: 8px;
      }
    }
  }
}
</style>