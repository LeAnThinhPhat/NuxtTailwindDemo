/* eslint-disable vue/multi-word-component-names */
// eslint-disable-next-line vue/multi-word-component-names
<template>
    <h1>Your deck {{ $route.params.id}} is active</h1>
</template>

<script>
export default ({
    validate(context){
        console.log(context)
        return /^[0-9]{9,12}$/.test(context.params.id)
    }
})
</script>
