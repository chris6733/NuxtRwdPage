<template>
  <div class="wrap">
    <div class="tag active">All</div>
    <div class="tag">Music</div>
    <div class="tag">One Piece</div>
    <div class="tag">Anime</div>
    <div class="tag">Love Songs</div>
    <div class="tag">Liu Baojie</div>
    <div class="tag">G.E.M.</div>
    <div class="tag">Eating</div>
    <div class="tag">WTO Sister</div>
    <div class="tag">Music</div>
    <div class="tag">One Piece</div>
    <div class="tag">Anime</div>
    <div class="tag">Love Songs</div>
    <div class="tag">Liu Baojie</div>
    <div class="tag">G.E.M.</div>
    <div class="tag">Eating</div>
    <div class="tag">WTO Sister</div>
    <div class="tag">Music</div>
    <div class="tag">One Piece</div>
  </div>
</template>

<style lang="scss" scoped>
.wrap {
  max-width: 100vw;
  height: 100px;
  position: fixed;
  top: 110px;
  left: 0;
  z-index: 10;
  background-color: #fff;
  display: flex;
  padding: 10px;
  overflow-x: auto;

  &::-webkit-scrollbar {
    display: none;
  }

  .tag {
    min-width: 125px;
    height: 55px;
    text-align: center;
    padding: 10px;
    background-color: $light-grey;
    border: 1px solid $gray;
    border-radius: 30px;
    font-size: 20px;
    margin-right: 10px;
    cursor: pointer;
    &:hover {
      background-color: #fff;
    }
    &.active {
      background-color: $dark;
      color: #fff;
    }
  }

  // @media screen and (max-width: 768px) {
  //   .tag {
  //     font-size: 1.1em;
  //   }
  // }
}
</style>