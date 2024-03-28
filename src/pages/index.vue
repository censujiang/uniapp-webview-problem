<script>
import { WebView } from "/src/libs/browser.core.js"

export default{
  onLoad(){
    const webview = new WebView()
    webview.openNewWindow("https://arco.design/vue/start",this)//在这里修改访问网址
  }
}
</script>

<template>
  <AppLogos />
  <InputEntry />
</template>

<style></style>

<route type="home" lang="json">{}</route>
