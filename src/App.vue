<script setup>
import { header } from './assets/app.module.css'
import TestCss from './assets/test.module.css'
</script>

<template>
  <header :class="header">
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />
  </header>

  <main :class="TestCss.main">
    CSS modulesを使ってみよう！
    <pre>
    </pre>
  </main>
</template>
