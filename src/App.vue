<template>
  <pre>{{ mnemonic }}</pre>
</template>
<script lang="ts" setup>
import { generateMnemonic } from "bip39";

const mnemonic = generateMnemonic();
</script>

<style></style>
