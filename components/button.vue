<!-- button.vue -->
<template>
    <div class="button"
    :class="[isSmall ? 'button--small' : '', isLarge ? 'button--large' : '']"
    >{{text}}</div>
</template>
<script setup lang="ts">
const props = defineProps({
    text: {
        type: String,
        default: "Button",
    },
  isSmall: {
        type: Boolean,
        default: false,
    },
  isLarge: {
        type: Boolean,
        default: false,
    },
});
</script>

<style scoped lang="css">
.button {
    background-color: #000;
    color: #fff;
  padding: 10px 20px;
}

.button--small {
  padding: 5px 10px;
}

.button--large {
  padding: 20px 40px;
}
</style>