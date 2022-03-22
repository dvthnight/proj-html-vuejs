<template>
    <main>
        <section>
            <div class="sez-1"></div>
            <div class="contenitore cont_sez_1 ">
                <h4>Certified fitness professional</h4>
                <h1>Take control of your health</h1>
                <div class="onda"></div>
                <p>Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet.</p>
                <div class="bottoni">
                    <div class="button button-blu visit_youtube"><a href="#"><i class="fa-brands fa-youtube"></i> Visit my YouTube channel</a></div>
                    <div class="button buy_avada"><a href="#">Buy Avada today <i class="fa-regular fa-arrow-right"></i></a></div>
                </div>
            </div>
            <div class="play_video">
                <i class="fa-solid fa-play"></i>
            </div>

            <div class="quadratini">
                <div class="demos">

                    <h5>Demos</h5>
                </div>
                <div class="sale">
                    <i class="fa-solid fa-cart-shopping"></i>
                    <h5>On sale</h5>
                </div>
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
    section{
        position: relative;
    }

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

    .sez-1::after{
        content: " ";
        display: block;
        position: absolute;
        background-image: linear-gradient(to left, rgba(4, 4, 4, 0), #040404 47.48%);
        height: 100%;
        width: 1000px;
        top: 50%;
        left: 50%;
        transform: translate(-50%,-50%);
    }

    .cont_sez_1{
        position: absolute;
        top: 32%;
        left: 292px;
        transform: translateY(-50%);
        height: 330px;

        h4{
            font-size: 25px;
            color: red;
            // font-weight: bold;
       }

       h1{
           color: white;
           font-size: 70px;
           font-weight: 500;
       }

       p{
           color: #78787a;
           font-size: 20px;
       }

       .visit_youtube{
           max-width: 300px;
           text-align: center;
           padding: 10px 30px;
       }

       .buy_avada{
           border: 2px solid #5f5f61;
           max-width: 250px;
           text-align: center;
           padding: 10px 30px;
       }

       .bottoni{
           margin: 40px;
           display: flex;
           gap: 20px;
       }
    }

    .play_video{
        color: #4154fe;
        padding: 20px;
        background-color: white;
        border-radius: 999999px;
        position: absolute;
        top: 32%;
        transform: translateY(-50%);
        left: 80%;
        aspect-ratio: 1;
        display: flex;
        justify-content: center;
        align-items: center;
    }
       
    .quadratini{
        color: rgb(51, 71, 91);
        position: absolute;
        right: 20px;
        top: 10%;
        
        .demos, .sale{
            padding: 10px;
            background-color: white;
            border-radius: 5px;
            margin-bottom: 10px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            gap: 5px;
            aspect-ratio: 1;

        }

    }
</style>