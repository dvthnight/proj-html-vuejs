<template>
    <section>
        <div class="sez-1"></div>
        <div class="contenitore cont_sez_1 ">
            <h4>Join our mailing list today</h4>
            <h1>Insider offers & flash sales in your inbox every week.</h1>
            <div class="onda"></div>
            <div class="input">
                <input type="text" class="mail" placeholder="Insert your email...*">
                <div class="button button-blu subscribe">Subscribe</div>
            </div>
            <p>Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet, consectetur adipiscing elit sed porttitor lectus.</p>
        </div>
        <div class="play_video">
            <i class="fa-solid fa-play"></i>
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
       background-image: url("../assets/img_fitness/banner1-2x.jpg");
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
            margin-bottom: 20px;
       }

       h1{
           color: white;
           font-size: 60px;
           font-weight: 500;
           max-width: 900px;
       }

       p{
           color: #78787a;
           font-size: 20px;
           font-weight: 500;
           width: 900px;
       }

       
       
       .input{
        display: flex;
        gap: 30px;
        margin: 30px 0;

        .subscribe{
            width: 300px;
            text-align: center;
            vertical-align: middle;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .subscribe:hover{
            background-color: #ec5a57;
            cursor: pointer;
            transition: all 0.3s ease-in-out;
        }

       
        .mail{
            padding: 20px;
            border-radius: 99999px;
            border: none;
            width: 600px;
            font-size: 20px;
        }
       }
       

    
    }

    .play_video{
        top: 40%;
        transform: translateY(-50%);
        left: 80%;
    }
</style>