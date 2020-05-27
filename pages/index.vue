<template  lang="pug">
v-container
  v-row(justify="center")
    v-col.text-center(cols=12, lg=10)
      v-card(flat)
        a(href="/letter" style="text-decoration: none")
          h2.display-1 A Letter to you and me
        p.subtitle.my-5(class="secondary--text") The critical decade, let us join hands together in the “Earthshot” campaign to repair the Earth” <a href="/letter">Read More.</a>
  v-row(justify="center")
    v-col(cols=12, lg=4, md=6)
      v-card(class="grow fill-height")
        a(style="text-decoration: none", href="/life")
          v-img(class="white--text align-end", height="200px", src="/imgs/life.jpeg")
            v-card-title Life Positioning and Engineering
        v-card-text.secondary--text
          p Spiritual purification leading to perception that human and Nature is a community of shared life on earth. May all live a blissful life.
    v-col(cols=12, lg=4, md=6)
      v-card(class="grow fill-height")
        a(style="text-decoration: none", href="/ecovillage")
          v-img(class="white--text align-end", height="200px", src="/imgs/ecovillage.png")
            v-card-title Ecovillage
        v-card-text.secondary--text
          p A paradise on earth | people living in unity and unison with Nature with Zero waste and Zero pollution.
    v-col(cols=12, lg=4, md=6)
      v-card(class="grow fill-height")
        a(style="text-decoration: none", href="/education")
          v-img(class="white--text align-end", height="200px", src="/imgs/education.png")
            v-card-title Education
        v-card-text.secondary--text
          p A set of Nature-inspired teaching system; Preservation of children’s spiritual purity.
  v-row(justify="center")
    v-col(cols=12)
      v-card.text-center(flat)
        h2.display-1.py-5 Noble Mind Foundation
        iframe(src="https://docs.google.com/presentation/d/e/2PACX-1vSXVVhAKQFlsKILGkw0V2MuwN3I_SP12IpIJWv4gqRrxW8t_tTxcz2pwjs_G5jjzth0cDY2HEDC_zsC/embed?start=false&loop=false&delayms=3000" frameborder="0" width="640" height="389" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true")
  v-row(justify="center")
    v-col.text-center(cols=12, lg=10)
      h2.display-1.my-5 Noble Mind
      p.subtitle.my-5(class="secondary--text") Sharing of Wisdom, Ideas, Solutions - for the protection and betterment of Our Mother Earth.
      p.my-5 Work in progress.
</template>

<script>

export default {
  components: {
  }
}
</script>
