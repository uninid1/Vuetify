<template>
  <v-card>
    <v-card-title>Создать новый пост</v-card-title>
    <v-card-text>
      <v-text-field v-model="title" label="Заголовок"></v-text-field>
      <v-textarea v-model="content" label="Содержание"></v-textarea>
    </v-card-text>
    <v-card-actions>
      <v-btn @click="createPost">Опубликовать</v-btn>
    </v-card-actions>
  </v-card>
</template>

<script>
export default {
  data() {
    return {
      title: "",
      content: "",
    };
  },
  methods: {
    createPost() {
    },
  },
};
</script>