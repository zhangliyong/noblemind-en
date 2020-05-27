<template lang="pug">
  v-app
    v-app-bar(app, color="primary", dark)
      v-toolbar-title Noble Mind
      v-spacer/
      v-toolbar-items(class="d-none d-md-flex")
        v-btn(v-for="i in menu" :key="i.title" :href="i.href" text) {{i.title}}
      v-spacer(class="d-none d-md-flex")/
      v-app-bar-nav-icon.d-md-none(@click.stop="drawer = !drawer")
    v-navigation-drawer(v-model="drawer" fixed right temporary)
      v-list(nav)
          v-list-item(v-for="i in menu" :key="i.title" :href="i.href")
            v-list-item-title {{i.title}}
    v-content
      nuxt/
    v-footer(app)
      span &copy; {{ new Date().getFullYear() }}
</template>

<script>
export default {
  data () {
    return {
      drawer: false,
      menu: [
        {
          href: '/',
          title: 'Home'
        },
        {
          href: '/life',
          title: 'LIFE ENGINEERING'
        },
        {
          href: '/ecovillage',
          title: 'ECOVILLAGE'
        },
        {
          href: '/edu',
          title: 'EDUCATION'
        },
        {
          href: 'http://www.noblemind.org',
          title: '中文'
        }
      ]
    }
  },
  head () {
    return {
      title: 'Noble Mind'
    }
  }
}
</script>
