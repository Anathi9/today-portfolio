<template>
    <div class="container">
        <div class="row">
            <p class="lead">Anathi's portfolio &copy;
            <span>{{ currentYear }}</span>
            </p>

        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterComp',
       data() {
        return{
            currentYear: new Date().getFullYear()
        }
       }
        
    }
</script>

<style scoped>

</style>