<template>
  <div>
    <v-card v-for="(post, index) in posts" :key="index">
      <v-card-title>{{ post.title }}</v-card-title>
      <v-card-text>{{ post.content }}</v-card-text>
    </v-card>
  </div>
</template>

<script>
export default {
  data() {
    return {
      posts: [
        { title: "Пример поста 1", content: "Содержание поста 1" },
        { title: "Пример поста 2", content: "Содержание поста 2" },
      ],
    };
  },
};
</script>