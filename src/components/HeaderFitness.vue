<template>
    <header>
        <div class="contenitore">
            <figure class="logo">
                <img src="../assets/img_fitness/logo-2x.png" alt="">
            </figure>
            <Nav/>
        </div>
    </header>
</template>

<script>
import Nav from "./NavbarFitness.vue"
export default {
    components:{
        Nav,
    }
}
</script>

<style lang="scss" scoped>
    header{
        background-color: #060606;
        height: 100px;
        
        .contenitore{
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
    }

    .logo{
        max-width: 250px;
    }
</style>