<template>
    <nav>
        <ul>
            <li v-for="(el,i) in navigazione" :key="i" :class="[{'active' : i==0}, {'button button-blu' : el =='Schedule a workout'}]">
                <a href="#">{{el}}</a>
            </li>
        </ul>
        <div class="icone"> 
            <a href="#"><i class="fa-regular fa-cart-shopping"></i></a>
            <a href="#"><i class="fa-regular fa-magnifying-glass"></i></a>
        </div>
    </nav>
</template>

<script>
export default {
    data(){
        return{
            navigazione: ["Home","Services","About","Videos","Blog","Store","Schedule a workout",]
        }
    }
}
</script>

<style lang="scss" scoped>
    nav{
        display: flex;
        color: #78787a;
        gap: 30px;
        justify-content: space-between;
        align-items: center;
        font-weight: 500;

        ul{
            display: contents;
        }
        
        .icone{
            display: contents;
        }

        .button{
            font-size: 15px;
        }
    }

    

</style>