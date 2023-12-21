<script setup>

defineProps(['Messagetitle', "Message"])
</script>

<template>
    <article class="message" style="width: 45%;">
  <div class="message-header">
    <p>{{ Messagetitle }}</p>
  </div>
  <div class="message-body">
    {{ Message }}
  </div>
</article>
</template>