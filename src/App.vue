<template>
  <div id="app">
    <Topbar class="topbar"/>
    <main>
      <Editor class="editor"/>
      <Preview class="preview"/>
    </main>
  </div>
</template>

<script>
import Topbar from "./components/Topbar";
import Editor from "./components/Editor";
import Preview from "./components/Preview";

export default {
  name: "App",
  components: {
    Topbar,
    Editor,
    Preview
  }
};
</script>

<style lang="scss">

.icon {
       width: 24px; height: 24px;
       fill: #A5ADB0;
       overflow: hidden;
    }

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.topbar{
  background: #dddddd;
}

main{
  display:flex;
  height:100vh;
  > .editor{
  width:20em;
}
  > .preview{
  flex-grow:1
}
}


</style>
