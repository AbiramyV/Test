

<template>
    <div>
        <button @click="addToList">Add to do  </button>
    </div>
</template>

<script setup>
    const { todoList, addTodo} = useTodo()
    function addToLisT() {
        addTodo({id:1, text:"First Todo"})
        console.log("added", todoList.value)
    }
    
</script>

<style lang="scss" scoped>

</style>