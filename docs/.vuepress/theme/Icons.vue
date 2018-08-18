<template>
<ul style="list-style: none;">
  <li>
    <a href="https://github.com/Artris">
    <img class="icon-github"
    v-if="$site.themeConfig.githubIcon"
    :src="$withBase($site.themeConfig.githubIcon)">
    </a>
  </li>
  <li>
    <a href="https://twitter.com/artris_code">
    <img class="icon-twitter"
    v-if="$site.themeConfig.githubIcon"
    :src="$withBase($site.themeConfig.twitterIcon)">
    </a>
  </li>
</ul>
</template>

<style lang="stylus">
@import './styles/config.styl';

.icon-github {
  position: relative;
  min-width: $navbarHeight - 1.4rem;
  top: -10 rem;
  left: 100 rem;
  width: 30px;
  height: 30px;
  margin-bottom: 1 rem;
}

.icon-twitter {
  position: relative;
  min-width: $navbarHeight - 1.4rem;
  top: -10 rem;
  left: 100 rem;
  width: 30px;
  height: 30px;
  margin-bottom: 1 rem;
}

.ul {
  list-style: none;
}
</style>
