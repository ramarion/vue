<template>
    <header>
        <h1>{{ titleText }}</h1>
        <h2>{{ subTitle }}</h2>
    </header>    
</template>

<script>
export default {
    name: 'Title',
    props: {
        titleText: {
            type: String,
            default: " WHAT I DID THIS SUMMER "
        },
        subTitle: {
            type: String,
            default: ""
        }
    },
}
</script>

<style>
    h1{
        text-decoration: underline;
    }
</style>