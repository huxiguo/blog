---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "seekhoo"
  text: "seekhoo blog"
  tagline: My great project tagline

features:
  - icon : 🍦
    title: Feature A
    details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
  - title: Feature B
    details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
  - title: Feature C
    details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
---

<script setup>
import { VPTeamMembers} from 'vitepress/theme'

const members = [
  {
    avatar: 'https://www.github.com/huxiguo.png',
    name: 'seekhoo',
    title: 'Creator',
    links: [
      { icon: 'github', link: 'https://github.com/huxiguo' },
      { icon: 'x', link: '/' }
    ]
  },
]
</script>

<VPTeamMembers size="small" :members="members" />



