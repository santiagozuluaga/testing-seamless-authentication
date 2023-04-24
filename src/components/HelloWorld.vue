<script setup lang="ts">
defineProps<{ msg: string }>()
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <a
      href="https://identity.truorastaging.com/preview/IPF6648c9b4fe3b89174c8bc10f3c7f3976?isDemo=true"
      style="
        text-decoration: none; background: #01022E;
        color: #ffffff; border-radius: 6px;
        display: inline-block; padding: 8px 32px;
      "
    >
      Validation with Truora
    </a>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test HMR
    </p>
  </div>

  <p>
    Check out
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite starter
  </p>
  <p>
    Install
    <a href="https://github.com/vuejs/language-tools" target="_blank">Volar</a>
    in your IDE for a better DX
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
