<template>
    <div>
        <ul>
            <li v-for="link in navLinks">
                {{link.text}}
            </li>
        </ul>
    </div>
</template>

<script>
export default {
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

<style lang="">
    
</style>