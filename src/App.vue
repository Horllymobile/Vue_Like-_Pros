<template>
    <div>
        <app-header></app-header>
        <div>{{ name }}</div>
    </div>
</template>

<script>
    import Footer from './Components/Header_Footer/Footer.vue';
export default {
    data(){
        return {
            name:"Olamide"
        }
    }
}
</script>