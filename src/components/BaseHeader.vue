<template>
  <header class="header">
    <div class="container">

      <div class="header__left">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>

      <div class="header__right">
        <nav>
          <ul>
            <li v-for="(link, i) in links" :key="i">
              <a :href="link.url">{{ link.text }}</a>
            </li>
          </ul>
        </nav>
      </div>
    </div>

  </header>
</template>

<script>
export default {
  name: 'BaseHeader',
  data() {
    return {
      links: [
        {
          text: 'CHARACTERS',
          url:'#'
        },
        {
          text: 'COMICS',
          url:'#'
        },
        {
          text: 'MOVIES',
          url:'#'
        },
        {
          text: 'TV',
          url:'#'
        },
        {
          text: 'GAMES',
          url:'#'
        },
        {
          text: 'COOLECTIBLES',
          url:'#'
        },
        {
          text: 'VIDEOS',
          url:'#'
        },
        {
          text: 'FANS',
          url:'#'
        },
        {
          text: 'NEWS',
          url:'#'
        },
        {
          text: 'SHOP',
          url:'#'
        },


      ]
    }
  }
}
</script>

<style lang="scss">
.header {

  & .container {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  &__left {
    img {
      width: 80%;
    }
  }

  &__right {
    ul {
      display: flex;
      list-style-type: none;

      li a {
        padding: 10px;
        color: black;
        text-decoration: none;
        font-size: 12px;
      }
    }
  }



}
</style>