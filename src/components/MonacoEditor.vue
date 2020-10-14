<template>
  <div
    id="app"
    style="width: 1000px; height: 1000px;"
  >
    <div
      ref="monacoEditor"
      style="width: 1000px; height: 1000px;"
    ></div>
  </div>
</template>

<script>
import * as monaco from "monaco-editor";

export default {
  name: "MonacoEditor",
  async mounted() {
    const el = this.$refs.monacoEditor;
    this.editor = monaco.editor.create(el, {
      value: "test",
      language: "javascript"
    });
  }
};
</script>