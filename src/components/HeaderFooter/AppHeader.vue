<template lang="pug">
  div.appHeader
    .video-box
      .video-content
        .text-video
          |Югорский
          br
          |государственный
          br
          |университет
          br
          |– месторожение знаний
      .video-mask
        video(loop muted autoplay)
          source(src="./../../assets/yugu.mp4" type="video/mp4")
        b-embed(tag="div" type="video" loop muted autoplay)
          source(src="./../../assets/yugu.mp4" type="video/mp4")

    b-navbar(id="nav" toggleable="lg" sticky=true  type="dark" style="background-color: #008D49;")
      b-navbar-toggle(target="nav-collapse")
      b-collapse(id="nav-collapse" is-nav)
        b-navbar-nav(class="mx-auto")
          b-nav-item(to="/")|Главная
          b-nav-item(to="/" )|Главная
          b-nav-item(to="/")|Главная
          b-nav-item(to="/")|Главная
          b-nav-item(to="/")|Главная
          b-nav-item(to="/")|Главная

    //- nav#nav(class="navbar sticky-top navbar-expand-lg navbar-light" style="background-color: #008D49;")
    //-   button(class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation")
    //-     span(class="navbar-toggler-icon")
    //-   div(class="collapse navbar-collapse " id="navbarNav")
    //-     ul(class="navbar-nav mx-auto")
    //-       li(class="nav-item active")
    //-         router-link(to = "/main" class="nav-link text-white")|Главная
    //-       li(class="nav-item active")
    //-         router-link(to = "/main" class="nav-link text-white")|Приемная 2021
    //-       li(class="nav-item active")
    //-         router-link(to = "/main" class="nav-link text-white")|Условия обучения
    //-       li(class="nav-item active")
    //-         router-link(to = "/main" class="nav-link text-white")|Контакты
    //-       li(class="nav-item active")
    //-         router-link(to = "/main" class="nav-link text-white")|Архив
    //-     ul(class="navbar-nav mr-1")
    //-       router-link(to = "/main" class="nav-link text-white")|Войти
</template>

<style lang="sass" scoped>
.video-box
  display: flex
  align-items: center
.video-content
  position: absolute
  display: flex
  flex-direction: column
  justify-content: space-between
  margin-left: 2%
.text-video
  font-weight: bold
  font-size: 4vmin
  line-height: 125%
  color: ivory
  margin-top: 10%
.video
  width: 100%
.button-video
  margin-top: 10%
  margin-bottom: 8%
  margin-left: 1%
.btn
  border-radius: 20px
  font-size: 3vmin
  padding: 1% 5%
#nav
  width: 100%
.container
  padding-left:0
  padding-right: 0
.appHeader
  display: flex
  flex-wrap: wrap
  justify-content: center
</style>
