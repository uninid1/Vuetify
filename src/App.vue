<template>
  <v-app>
    <v-container>
      <blog-form />
      <blog-list />
    </v-container>
  </v-app>
</template>

<script>
import BlogForm from './components/BlogForm.vue';
import BlogList from './components/BlogList.vue';

export default {
  components: {
    BlogForm,
    BlogList,
  },
};
</script>