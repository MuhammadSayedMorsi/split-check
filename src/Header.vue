<template>
  <div class="_nav">
        <nav>
          <ul>
            <router-link to="/sell">sell</router-link>
            <router-link to="/pricing">pricing</router-link>
            <router-link to="/popup">popup</router-link>
            <router-link to="/register-hashtag">register hashtag</router-link>
            <router-link to="/sell products">sell products</router-link>
            <router-link to="/upgrade-plan">upgrade plan</router-link>
            <router-link to="/giftgiving">giftgiving</router-link>
            <router-link to="/welcomtosplictcheck">welcomtosplictcheck</router-link>
            <router-link to="/listyoiurbusiness">listyoiurbusiness</router-link>
            <router-link to="/verifyabn">verifyabn</router-link>
            <router-link to="/howtosell">howtosell</router-link>
            <router-link to="/multiplestores">multiplestores</router-link>


          </ul>
        </nav>

  </div>
</template>

<script>
  export default {

  }
</script>

<style lang="sass" scoped>
._nav
  width: 100vw
  nav
    height: 71px
    100%
    background: pink
    display: flex
    justify-content: center
    align-items: center
    ul
      display: flex
      a
        margin-right: 10px
        color: #000
        font-size: 16px
        font-weight: bold
        text-decoration: underline
</style>