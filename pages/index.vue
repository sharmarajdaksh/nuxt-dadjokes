<template>
  <div class="container">
    <h2>Welcome to the best dad jokes app on the web</h2>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default {
  head() {
    return {
      title: 'DadJokes',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'The best place for corny dad jokes'
        }
      ]
    }
  }
}
</script>
