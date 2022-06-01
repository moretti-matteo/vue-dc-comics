<template>
  <header class="header">
    <div class="container">

      <div class="header__left">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>

      <div class="header__right">
        <nav>
          <ul>
            <li><a href="#">Item</a></li>
            <li><a href="#">Item</a></li>
            <li><a href="#">Item</a></li>
            <li><a href="#">Item</a></li>
            <li><a href="#">Item</a></li>
            <li><a href="#">Item</a></li>
            <li><a href="#">Item</a></li>
            <li><a href="#">Item</a></li>
            <li><a href="#">Item</a></li>
            <li><a href="#">Item</a></li>
          </ul>
        </nav>
      </div>
    </div>

  </header>
</template>

<script>
export default {
  name: 'BaseHeader'
}
</script>

<style lang="scss">
@import "../assets/style/global.css";



.header {
  border: 1px solid;

  & .container {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  &__left{
    img{
      width: 80%;
    }
  }

  &__right {
  ul {
    display: flex;
    list-style-type: none;

    li a {
      padding:10px;
      color:black;
      border:1px solid magenta;
    }
  }
}



}




</style>