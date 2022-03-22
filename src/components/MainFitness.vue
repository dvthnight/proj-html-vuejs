<template>
    <main>
        <section class="sez-1">
            <div class="contenitore ">

            </div>
        </section>

    
    </main>
</template>

<script>
export default {

    data(){
        return{
            
        }
    }
    
}
</script>

<style lang="scss" scoped>
   .sez-1{
       background-image: url("../assets/img_fitness/slider82x-scaled.jpg");
       width: 100%;
       height: 700px;
       background-size: contain;
       background-repeat: no-repeat;
       background-position: right;
       background-color: #040404;
       position: relative;
    }

    section.sez-1::after{
        content: " ";
        display: block;
        position: absolute;
        background-image: linear-gradient(to left, rgba(4, 4, 4, 0), #040404 51.26%);
        height: 100%;
        width: 1000px;
        top: 50%;
        left: 50%;
        transform: translate(-50%,-50%);
    }
</style>