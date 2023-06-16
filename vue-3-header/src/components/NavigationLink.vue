<template>
            <li>
                {{ navigationElement.text }}
            </li>
</template>

<script>
export default {
    name: 'NavigationLink',
    props: {
        navigationElement : Object
    },
}
</script>

<style lang="scss" scoped>
    li{
        color: #000;
    }
</style>