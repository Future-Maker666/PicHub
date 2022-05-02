<script setup lang="ts">
import { ref } from 'vue'
</script>

<template>
  <div class="about-wrapper">
    <div class="title-1">关于</div>
    <div class="content">
      我是来自新疆的学生<a target="_blank" href="https://ssy.cab/">
        Future_Maker</a
      >。本项目是基于<a target="_blank" href="https://github.com/lewkamtao/PicHub">
      Kamtao's PicHub</a
      >进行二次修改的。
      <br /> <br />
      PicHub 是一个图床，也可以是相册，这取决于你对它的定位。<br />这个图床很简单，但比较完整，用
      Vue 3 写的，不算太慢。<br />典型现代风格和干净页面，如果您和我一样对 UI
      极具苛刻，这将是一个让您大吃一惊的好项目。<br /><br />
      特别的是
      <ul>
        <li>支持点击、拖拽、复制图片上传</li>
        <li>
          谷歌 <a href="https://squoosh.app" target="_blank">squoosh</a>
          压缩图片
        </li>
        <li>
          <a href="https://fancyapps.com" target="_blank">Fancybox</a>
          的加持，让图片的预览效果更好。
        </li>
        <li>安全且快速，数据只存在本地，保证您的隐私不会外泄。</li>
        <li>封装组件（按钮表单上传等）</li>
        <li>复制转换 Markdown 格式</li>
      </ul>
      <br />
      <div>
        原作地址：
        <a target="_blank" href="https://github.com/lewkamtao/PicHub"
          >https://github.com/lewkamtao/PicHub</a
        >
      </div>
      <div>欢迎给原作者提建议和 Bug，喜欢的话帮他点个star吧！（还有我还有我！）</div>
      <div>目前需要处理的问题：</div>
      <ul>
          <li>原 CDN （JSDeliver）对国内的支持度大大降低，需要更换其他 CDN 源站。</li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.about-wrapper {
  max-width: 700px;
  margin: 70px auto;
  padding: 50px;
  color: var(--text-color);
  .content {
    margin-top: 20px;
    color: var(--text-color);
    line-height: 30px;
    a {
      color: var(--primary-color);
      text-decoration: underline;
    }
  }
}
</style>
