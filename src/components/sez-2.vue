<template>
    <section>
        <div class="contenitore">
            <div class="contenitore_card">
                <div class="card card_1">
                </div>
                <div class="contenuto_card cont_1">
                    <div class="onda"></div>
                    <h2>Crossfit workout</h2>
                    <p>Push your limits</p>
                </div>
                <div class="card card_2">
                </div>
                 <div class="contenuto_card cont_2">
                    <div class="onda"></div>
                    <h2>New gym apparel</h2>
                    <p>Look good, feel good</p>
                </div>
                <div class="card card_3">
                </div>
                <div class="contenuto_card cont_3">
                        <div class="onda"></div>
                        <h2>Team training</h2>
                        <p>Find a partner</p>
                </div>
            </div>

            <div class="citazione">
                <p class="citazione_testo">“How you respond to the challenge in the second half will determine what you become after the game, whether you are a winner or a loser.”</p>
                <div class="onda"></div>
                <div class="persona_citazione">
                    <figure class="citazione_img">
                        <img src="../assets/img_fitness/avatar-1-2x.jpg" alt="">
                    </figure>
                    <h3 class="citazione_nome">Brad Johnson</h3>
                    <p class="citazione_luogo">Las Vegas</p>
                </div>
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
        height: 820px;
        background-image: linear-gradient(to top left, #bc0428,rgb(0,38,196));
    }

    .contenitore_card{
        display: flex;
        justify-content: space-between;
        position: relative;
        top: -100px;
        
    }

    .card{
        height: 440px;
        width: 400px;
        border-radius: 5px;
        border-bottom-right-radius: 50px;
        position: relative;
        overflow: hidden;
        
    }

    .card::after{
        content: "";
        display: block;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        background-image: linear-gradient(to top, rgba(0,0,0,0.7),rgba(0,0,0,0.1));
        position: absolute;
        
    }

    .card_1{
        background-image: url("../assets/img_fitness/service6-2x.jpg");
        background-size: cover;
    }

    .card_2{
        background-image: url("../assets/img_fitness/box1-2x.jpg");
        background-size: cover;
    }

    .card_3{
        background-image: url("../assets/img_fitness/box3-2x.jpg");
        background-size: cover;
    }

    .card:hover{
        scale: 1.05;
        transition: all 0.3s ease-in-out;
        cursor: pointer;
        box-shadow: 1px 6px 8px 0 rgba(0, 0, 0, 0.2), 14px 5px 20px 0 rgba(0, 0, 0, 0.19);

    }
    
    .contenuto_card{

         h2{
            color: white;
            font-size: 2rem;
            font-weight: 500;
            margin-bottom: 5px;
        }
        p{
            color: yellow;
            font-weight: 500;
            font-size: 1.6rem;
        }
    }

    .cont_1{
        position: absolute;
        bottom: 40px;
        left: 40px;
    }
     .cont_2{
        position: absolute;
        bottom: 40px;
        left: 510px;
    }
     .cont_3{
        position: absolute;
        bottom: 40px;
        left: 960px;
    }

    .citazione{
        width: 1000px;
        margin: 30px auto;

        .citazione_testo{
            color: white;
            font-size: 50px;
            font-weight: 500;
            text-align: center;
        }

        .citazione_img{
            width: 70px;
            img{
                border-radius: 999999px;
            }
        }

        .citazione_luogo{
            color: #bcbcbc;
            font-size: 1.75rem;
        }

        .citazione_nome{
            color: white;
            font-size: 1.75rem;
            font-weight: 500;
        }

        .persona_citazione{
            display: flex;
            align-items: center;
            gap: 20px;
            justify-content: center;
            margin-top: 40px;
        }
    }
</style>