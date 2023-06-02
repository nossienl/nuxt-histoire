<!-- button.story.vue -->
<template>
    <Story>
      <Variant title="Default">
        <Button>Default</Button>
      </Variant>
      <Variant title="Small">
        <Button isSmall>Small</Button>
      </Variant>
      <Variant title="Large">
        <Button isLarge>Large</Button>
      </Variant>
    </Story>
</template>
<script setup lang="ts">
import Button from "~/components/button.vue";
</script>