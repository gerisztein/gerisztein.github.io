<template lang="pug">
  main.container
    div
      h1.title
        | Hi! My name is Lucas Gerisztein.
      h2.subtitle
        p
          em tl;dr
        p I'm currently working as <b>Frontend Developer</b> at <a href="https://crvsh.com">crvsh</a>.
        p On my free time I'm also the co-founder of <a href="http://cake-mag.com">Cake Magazine</a> and a photography enthusiast.
        p I'm Brazilian and based in Berlin since 2017.
    .links
      span
        img(height="20", width="20", src="https://unpkg.com/simple-icons@latest/icons/linkedin.svg")
      span
        img(height="20", width="20", src="https://unpkg.com/simple-icons@latest/icons/github.svg")
      span
        img(height="20", width="20", src="https://unpkg.com/simple-icons@latest/icons/twitter.svg")
      span
        img(height="20", width="20", src="https://unpkg.com/simple-icons@latest/icons/instagram.svg")
</template>

<script>
export default {
  components: {}
}
</script>

<style lang="stylus">
.container
  align-items center
  display flex
  justify-content flex-start
  margin 0 auto
  max-width 38%
  min-height 100vh
  margin-left 11%

.title
  display block
  font-weight 700
  font-size 40px

.subtitle
  border-top 15px solid #ff0
  font-family 'Courier New', Courier, monospace
  font-weight 500
  font-size 15px
  line-height 28px
  margin 15px 0
  padding 15px 0

  em
    font-size 30px

  p
    margin-bottom 15px

.links
  display flex
  flex-flow column wrap
  justify-content center
  min-height 100vh
  position fixed
  right calc(10% - 21px)
  top 0

  span
    background-color #fff
    border 1px solid #f0f0f0
    border-radius 90px
    cursor pointer
    display flex
    margin-bottom 20px
    padding 10px

    img
      opacity .25
      transition opacity .25s ease

    &:hover
      img
        opacity 1
</style>
