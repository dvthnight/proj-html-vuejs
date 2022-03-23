<template>
    <section>
        <div class="contenitore">
            <div class="intestazione">
            <h3>Featured playlists</h3>
            <a href="#">View all videos <i class="fa-regular fa-chevron-right"></i></a>
            </div>
            <div class="contenitore_card">
                <div class="card card_1">
                    <figure class="card_image">
                        <img src="../assets/img_fitness/video2-2x.jpg" alt="">
                    </figure>
                    <div class="play_video">
                        <i class="fa-solid fa-play"></i>
                    </div>
                    <h2>Thighs & glute workout</h2>
                    <p>Increase your mobility</p>
                </div>
                <div class="card card_2">
                    <figure class="card_image">
                        <img src="../assets/img_fitness/video7-2x.jpg" alt="">
                    </figure>
                    <div class="play_video">
                        <i class="fa-solid fa-play"></i>
                    </div>
                    <h2>Lift, firm & perk up</h2>
                    <p>Feel young again</p>
                </div>
                <div class="card card_3">
                    <figure class="card_image">
                        <img src="../assets/img_fitness/video9-2x.jpg" alt="">
                    </figure>
                    <div class="play_video">
                        <i class="fa-solid fa-play"></i>
                    </div>
                    <h2>Slim & trim your waist</h2>
                    <p>Shed those extra pounds</p>
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
        padding-top: 50px;
        padding-bottom: 100px;
    }
    .intestazione{
        display: flex;
        justify-content: space-between;
        margin-bottom: 50px;

        h3{
            font-size: 30px;
            font-weight: 500;
        }

        a{
            font-size: 20px;
            font-weight: 500;
            display: flex;
            align-items: center;
            gap: 10px;

            i{
                font-size: 15px;
            }
        }

        a:hover{
            color: #4154fe ;
        }
    }

    .contenitore_card{
        display: flex;
        justify-content: space-between;
    }
    .card{
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 10px;
        position: relative;

        h2{
            font-weight: 500;
        }

        p{
            color: #4154fe;
            font-weight: 500;
            font-size: 20px;
        }

        .card_image{
        width: 406px;
        img{
            border-radius: 5px;
            border-bottom-right-radius: 30px;
            }
        }

        .play_video{
            left: 50%;
            top: 130px;
            transform: translate(-50%, -50%);
            padding: 15px;
            font-size: 15px;
        }
    }
</style>