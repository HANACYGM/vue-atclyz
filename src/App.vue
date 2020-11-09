<template>
	<HelloWorld msg="Hello3 Vue 3.0 + Vite" />
</template>

<script>
	import { createApp } from "vue";
import { Col, Row } from 'vant';
import HelloWorld from "./components/HelloWorld.vue";

const app = createApp();
app.use(Col);
app.use(Row);

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>