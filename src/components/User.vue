<script>
    export default{
        props:{
            userData: {},
        },
    }
</script>

<template>
    <span className="user">
        <span className="name">{{ userData.name }}</span>
        <span className="handle">@{{ userData.handle }}</span>
    </span> 
</template>