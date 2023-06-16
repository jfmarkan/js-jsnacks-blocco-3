<template>
    <div>
        <ul>
            <NavigationLink v-for="navObj in navLinks"
                :navigationElement= "navObj"
            />
        </ul>
    </div>
</template>

<script>
import NavigationLink from './NavigationLink.vue';

export default {
    name: 'AppHeader',
    components:{
        NavigationLink
    },
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