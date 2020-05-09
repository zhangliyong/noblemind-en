<template  lang="pug">
  v-row(justify="center")
    v-col.text-center.my-5(cols=12, lg=10)
      h2.display-1.my-5(class="primary--text") Noble Mind
      p.subtitle.my-5(class="secondary--text") Sharing of Wisdom, Ideas, Solutions - for the protection and betterment of Our Mother Earth.
    v-col(cols=12, lg=4, md=6)
      v-card
        a(style="text-decoration: none", href="/life")
          v-img(class="white--text align-end", height="200px", src="/life.png")
            v-card-title Life Positioning and Engineering
        v-card-text.secondary--text
          p Vuetify is a progressive Material Design component framework for Vue.js. It was designed to empower developers to create amazing applications.
    v-col(cols=12, lg=4, md=6)
      v-card
        a(style="text-decoration: none", href="/ecovillage")
          v-img(class="white--text align-end", height="200px", src="/ecovillage.png")
            v-card-title Ecovillage
        v-card-text.secondary--text
          p Vuetify is a progressive Material Design component framework for Vue.js. It was designed to empower developers to create amazing applications.
    v-col(cols=12, lg=4, md=6)
      v-card
        a(style="text-decoration: none", href="/education")
          v-img(class="white--text align-end", height="200px", src="/life.png")
            v-card-title Education
        v-card-text.secondary--text
          p Vuetify is a progressive Material Design component framework for Vue.js. It was designed to empower developers to create amazing applications.
</template>

<script>

export default {
  components: {
  }
}
</script>
