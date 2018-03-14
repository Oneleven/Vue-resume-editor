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

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.topbar{
  background: #dddddd;
}

main{
  background: #888888;
  display:flex;
}

main > .editor{
  width:20em;
}

main > .preview{
  flex-grow:1
}


</style>
