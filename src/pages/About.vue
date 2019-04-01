<template>
  <div>
    {{ $t('pages.about') }}
    <h1>POST REQUEST USING AXIOS</h1>

    <input type="text" v-model="postBody" @change="postPost()">
    <ul v-if="errors && errors.length">
      <li v-for="error of errors">{{error.message}}</li>
    </ul>
  </div>
</template>


