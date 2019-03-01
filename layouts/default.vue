<template lang="pug">
  nuxt
</template>

<style lang="stylus">
html
  background-color #fff
  background-image linear-gradient(90deg, #f0f0f0 1px, transparent 1px)
  // background-image linear-gradient(90deg, #f0f0f0 1px, transparent 1px), linear-gradient(0deg, #f0f0f0 1px, transparent 1px)
  background-size 10%
  box-sizing border-box
  color #000
  font-family 'Helvetica Neue', 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif
  font-size 16px
  -ms-text-size-adjust 100%
  -webkit-text-size-adjust 100%
  -moz-osx-font-smoothing grayscale
  -webkit-font-smoothing antialiased

*,
*:before,
*:after
  box-sizing border-box
  margin 0

.button
  &--green
    display inline-block
    border-radius 4px
    border 1px solid #3b8070
    color #3b8070
    text-decoration none
    padding 10px 30px

    &:hover
      color #fff
      background-color #3b8070

  &--grey
    display inline-block
    border-radius 4px
    border 1px solid #35495e
    color #35495e
    text-decoration none
    padding 10px 30px
    margin-left 15px

    &:hover
      color #fff
      background-color #35495e
</style>
