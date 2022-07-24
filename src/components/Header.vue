<template>
  <header>
    <h1>{{ title }}</h1>
  </header>
  <Button text="Add Task" color="green" />
</template>

<script>
import Button from "./Button";
export default {
  name: "HeaderA",
  props: ["title"],
  components: {
    Button,
  },
};
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>
