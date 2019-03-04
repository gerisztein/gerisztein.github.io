<template lang="pug">
  main.container
    div
      h1.title
        | <b>Hi!</b> My name is Lucas Gerisztein<b>.</b>
      .separator
      h2.subtitle
        p
          em tl;dr
        p 👨‍💻I'm currently working as <b>Frontend Developer</b> at <a href="https://crvsh.com">crvsh</a>.
        p 📸On my free time I'm also the <b>co-founder</b> of <a href="http://cake-mag.com">Cake Magazine</a> and a <b>photography enthusiast</b> on <a href="https://instagram.com/gerisztein">Instagram</a> and <a href="https://flickr.com/gerisztein">Flickr</a>.
        p 📍I'm born and raised in <b>Brasil</b> and since 2017 I'm based in <b>Berlin</b>.
    .links
      span
        a(href="https://www.linkedin.com/in/gerisztein/")
          img(alt="me @ linkedin", height="20", width="20", src="https://unpkg.com/simple-icons@latest/icons/linkedin.svg")
      span
        a(href="https://www.github.com/gerisztein/")
          img(alt="me @ github", height="20", width="20", src="https://unpkg.com/simple-icons@latest/icons/github.svg")
      span
        a(href="https://www.twitter.com/gerisztein/")
          img(alt="me @ twitter", height="20", width="20", src="https://unpkg.com/simple-icons@latest/icons/twitter.svg")
      span
        a(href="https://www.instagram.com/gerisztein/")
          img(alt="me @ instagram", height="20", width="20", src="https://unpkg.com/simple-icons@latest/icons/instagram.svg")
      span
        a(href="mailto:lucas@lucasg.com.br?subject=lvcas.dev")
          img(alt="e-mail me at lucas@lucasg.com.br", height="20", width="20", src="https://unpkg.com/simple-icons@latest/icons/gmail.svg")
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
  max-width 58%
  min-height 100vh
  margin-left 11%

  @media screen and (min-width: 768px)
    max-width 48%

  @media screen and (min-width: 1024px)
    max-width 38%

.title
  display block
  font-family 'Courier New', Courier, monospace
  font-weight 500
  font-size 20px
  padding-top 16px

  @media screen and (min-width: 768px)
    font-size 40px

.separator
  background-color #ff0
  height 15px
  margin-left -30%
  margin-top 15px
  width 135%

.subtitle
  font-family 'Courier New', Courier, monospace
  font-weight 500
  font-size 14px
  line-height 28px
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
