<template lang="pug">
  v-app
    v-app-bar(app, color="primary", dark)
      v-toolbar-title {{title}}
      v-spacer/
      v-toolbar-items
        v-btn(href='/', text) Home
        v-btn(href='/life', text) LIFE ENGINEERING
        v-btn(href='/ecovillage', text) ECOVILLAGE
        v-btn(href='/edu', text) EDUCATION
        v-btn(href='http://www.noblemind.org', text) 中文
      v-spacer/
    v-content
      v-container
        nuxt/
    v-footer(app)
      span &copy; {{ new Date().getFullYear() }}
</template>

<script>
export default {
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  }
}
</script>
