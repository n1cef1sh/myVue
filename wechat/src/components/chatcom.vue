<template>
    <div class="chat">
        <h1 class="redbg">用户：{{currentUser.username}}</h1>
    </div>
</template>

<script>
export default {
    props:['currentUser']
}
</script>

<style scoped>
    .chat{
        width: 800px;
        height: 700px;
        border: 1px solid #ccc;
    }
</style>