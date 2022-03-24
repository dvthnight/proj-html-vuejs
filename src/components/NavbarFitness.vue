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

        a{
            transition: all 0.3s ease-in-out;
            font-size: 18px;
        }
        a:hover{
            color: white;
        }
        
        .icone{
            display: contents;
        }

        .button{
            display: flex;
            align-items: center;
            justify-content: center;
            a{
                font-size: 15px;
            }
        }
        .button:hover{
            background-color: #ec5a57;
            cursor: pointer;
        }
    }

    

</style>