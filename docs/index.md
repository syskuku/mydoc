---
layout: home
layoutClass: 'm-home-layout'

hero:
  name: iMikufans
  text: 未来之境超级网络
  tagline: 一个关于VOCALOID及其他ACGN文化的集合站
  image:
    src: /logo.png
    alt: SYSKUKU
  actions:
    - text: 快速上手
      link: /start
    - text: 暂无
      link: /
      theme: alt
features:
  - icon: 📖
    title: iMikufans主页
    details: 一位二次元技术宅高中生的主页
    link: https://www.imikufans.com/
    linkText: 访问主页
  - icon: 📘
    title: iMikufans博客
    details: 欢迎访问我的博客<br />基于Astro以及Mizuki主题构建
    link: https://blog.imikufans.com/
    linkText: 访问博客
  - icon: ❤️
    title: VOCALOID资源站导航
    details: 这是一个资源站导航
    link: https://voicebanks.imikufans.com/
    linkText: 访问导航
  - icon: ❤️
    title: VOCALOID资源站1
    details: VOCALOID以及其他虚拟歌手编辑器 如SV等 编辑器及其声库下载网站
    link: https://voicebanks1.imikufans.com/
    linkText: 提效工具
  - icon: 📚
    title: VOCAKEY WIKI
    details: 一个汇聚虚拟歌手的<br />强大的资源分享及百科网站
    link: https://vocakey.imikufans.com/
    linkText: 踩坑记录
  - icon: 😊
    title: iMikufans论坛
    details: '被收编iMikufans的虚拟歌手交流论坛'
    link: https://flarum.imikufans.cn/
---

<style>
/*爱的魔力转圈圈*/
.m-home-layout .image-src:hover {
  transform: translate(-50%, -50%) rotate(666turn);
  transition: transform 59s 1s cubic-bezier(0.3, 0, 0.8, 1);
}

.m-home-layout .details small {
  opacity: 0.8;
}

.m-home-layout .bottom-small {
  display: block;
  margin-top: 2em;
  text-align: right;
}
</style>
