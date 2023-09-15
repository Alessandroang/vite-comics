<script>
export default {
  name: "AppHeader",
};
</script>
<template>
  <header class="header-content">
    <div>
      <img src="../assets/img/dc-logo.png" alt="logo-header" />
    </div>
    <div>
      <ul class="list">
        <li><a href="">CHARACTERS</a></li>
        <li><a href="">COMICS</a></li>
        <li><a href="">MOVIE</a></li>
        <li><a href="">TV</a></li>
        <li><a href="">GAMES</a></li>
        <li><a href="">COLLECTIBLES</a></li>
        <li><a href="">VIDEO</a></li>
        <li><a href="">FANS</a></li>
        <li><a href="">NEWS</a></li>
        <li><a href="">SHOP</a></li>
      </ul>
    </div>
  </header>
</template>

<style lang="scss" scoped>
.header-content {
  background-color: white;
  color: #fff;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;

  .list {
    display: flex;
    list-style-type: none;

    li {
      padding: 0px 10px;
    }
    a {
      text-decoration: none;
      color: black;
    }
  }
}
</style>
