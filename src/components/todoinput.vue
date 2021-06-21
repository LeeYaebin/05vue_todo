<template>
    <div>
        <input type="text" v-model="newTodoItem">
    </div>
    {{newTodoItem}}

</template>

<script>
export default {
    name:'input',
    data(){
        return{
            newTodoItem:''
        }
    }
}
</script>

<style>

</style>