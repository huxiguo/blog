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










目标：
1. 提升面试答题正确性和完整性

思路：
1. 找到并且学习他人面试笔记(博客，github/interview)
2. 识别答案的真实和完整性
3. 学习实践归纳总结
   
方法





归纳总结之举例：
宏任务macrotask、微任务microtask、taskqueue

1 事件循环（Event loop） v8 libuv
2.
宏任务macrotask
  setTimeout
  setInterval
  I/O 文件callback
  setImmediate
  UI Rendering

微任务microtask
  xx
  x
  xx
  x
3.
事件队列，执行顺序，才有
