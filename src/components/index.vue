<template>
  <div>
    <!-- 预览pdfjs自带的pdf文件 -->
    <iframe src="/static/pdfjs/web/viewer.html" frameborder="0"></iframe>
    <!-- ?file=后面写要预览的pdf地址，此处需要解决跨域问题 -->
    <!-- <iframe src="/static/pdfjs/web/viewer.html?file=https://weiappp/755540.pdf" frameborder="0"></iframe> -->
  </div>
</template>
<script>
export default {
  data(){
    return{

    }
  },
  mounted(){
    // 水印内容
    window.waterMarkText='转载请注明出处'
  }
}
</script>
<style scope>
div{
  width: 100%;
  height: 100%;
}
iframe{
  width: 100%;
  height: 100%;
}
</style>
