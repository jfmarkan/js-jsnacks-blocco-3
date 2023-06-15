<template>
    <div>
        <ul>
            <li v-for="link in navLinks">
                <a href="">{{link.text}}</a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'AppHeader',
    data(){
        return{
            navLinks: [
                {
                    text: 'Home',
                    link: '#',
                },
                {
                    text: 'Contact',
                    link: '#',
                },
                {
                    text: 'Our Company',
                    link: '#',
                },
                {
                    text: 'Login',
                    link: '#',
                },
            ]
        }
    }
}
</script>

<style lang="scss">

</style>