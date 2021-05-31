<template>
  <div class="wrap">
    <div class="logo">
      <svg viewBox="0 0 448 512" width="100" title="caret-square-right">
        <path
          d="M48 32h352c26.51 0 48 21.49 48 48v352c0 26.51-21.49 48-48 48H48c-26.51 0-48-21.49-48-48V80c0-26.51 21.49-48 48-48zm140.485 355.515l123.029-123.029c4.686-4.686 4.686-12.284 0-16.971l-123.029-123.03c-7.56-7.56-20.485-2.206-20.485 8.485v246.059c0 10.691 12.926 16.045 20.485 8.486z"
        />
      </svg>
      <span>YxuTube</span>
    </div>

    <div class="right">
      <svg viewBox="0 0 512 512" width="100" title="search">
        <path
          d="M505 442.7L405.3 343c-4.5-4.5-10.6-7-17-7H372c27.6-35.3 44-79.7 44-128C416 93.1 322.9 0 208 0S0 93.1 0 208s93.1 208 208 208c48.3 0 92.7-16.4 128-44v16.3c0 6.4 2.5 12.5 7 17l99.7 99.7c9.4 9.4 24.6 9.4 33.9 0l28.3-28.3c9.4-9.4 9.4-24.6.1-34zM208 336c-70.7 0-128-57.2-128-128 0-70.7 57.2-128 128-128 70.7 0 128 57.2 128 128 0 70.7-57.2 128-128 128z"
        />
      </svg>
      <svg viewBox="0 0 496 512" width="100" title="user-circle">
        <path
          d="M248 8C111 8 0 119 0 256s111 248 248 248 248-111 248-248S385 8 248 8zm0 96c48.6 0 88 39.4 88 88s-39.4 88-88 88-88-39.4-88-88 39.4-88 88-88zm0 344c-58.7 0-111.3-26.6-146.5-68.2 18.8-35.4 55.6-59.8 98.5-59.8 2.4 0 4.8.4 7.1 1.1 13 4.2 26.6 6.9 40.9 6.9 14.3 0 28-2.7 40.9-6.9 2.3-.7 4.7-1.1 7.1-1.1 42.9 0 79.7 24.4 98.5 59.8C359.3 421.4 306.7 448 248 448z"
        />
      </svg>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.wrap {
  width: 100vw;
  height: 110px;
  position: fixed;
  top: 0;
  left: 0;
  z-index: 10;
  background: #fff;
  display: flex;
  justify-content: space-between;
  padding: 0 15px;
  border-bottom: 1px solid $gray;
}

.logo {
  height: 120px;
  margin: auto 0;
  display: flex;
  align-items: center;

  svg {
    width: 40px;
    margin-right: 10px;
  }

  span {
    font-size: 50px;
    font-weight: 500;
  }
}

.right {
  height: 120px;
  margin: auto 0;
  display: flex;
  align-items: center;

  svg {
    width: 45px;
    height: 45px;
    margin-right: 30px;
  }
}
</style>