<template>
    <section>
        <div class="sez-1"></div>
        <div class="contenitore cont_sez_1 ">
            <h4>Certified fitness professional</h4>
            <h1>Take control of your health</h1>
            <div class="onda"></div>
            <p>Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet.</p>
            <div class="bottoni">
                <div class="button button-blu visit_youtube">
                    <a href="#"><i class="fa-brands fa-youtube"></i> Visit my YouTube channel</a>
                    </div>
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
</template>

<script>
export default {
    
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
        top: 50%;
        left: 292px;
        transform: translateY(-50%);
        height: 330px;

        h4{
            font-size: 30px;
            color: rgb(241, 74, 71);
            font-weight: 500;
            margin-bottom: 10px;
       }

       h1{
           color: white;
           font-size: 75px;
           font-weight: 500;
       }

       p{
           color: #78787a;
           font-size: 25px;
           font-weight: 500;
       }

       .visit_youtube:hover{
            background-color:#ec5a57;
        }

       .buy_avada{
           border: 2px solid #5f5f61;
           max-width: 250px;
           text-align: center;
           padding: 20px 40px;
            display: flex;
           align-items: center;
           gap: 10px;
           a{
               display: contents;
           }

       }

       .buy_avada:hover{
           background-color: white;
           border-color: white;
           color: #040404;
           transition: all 0.3s ease-in-out;
           cursor: pointer;
       }

       .bottoni{
           margin: 40px;
           display: flex;
           gap: 20px;
       }
    }

    .play_video{
        top: 40%;
        transform: translateY(-50%);
        left: 80%;
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