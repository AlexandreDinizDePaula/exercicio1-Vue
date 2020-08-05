<template>
    <div>
    <img alt="Vue logo" src="../assets/logo.png">    
    <h1>{{ post.content}}</h1>

    </div>
</template>

<script>
export default {
    props:{
        post: Object
    }
}
</script>