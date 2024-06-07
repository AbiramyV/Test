

<template>
    <div>
        This is all about {{ route.params.name }}
    </div>
</template>

<script setup lang="ts">
    const route = useRoute()
</script>