
<template>
    <div>
        <LazyCustomTitle>This is home page to about page</LazyCustomTitle>
        <DashboardHome></DashboardHome>
        <Todo></Todo>
    </div>
</template>

<script setup lang="ts">

    useHead({
        title: "Test_Nuxt3" ,
        meta: [{name: "description", content: "This is nuxt3 demo"}]
    })
    setTimeout(() => {
        navigateTo("/about" , {replace: true})
    }, 5000);


</script>
