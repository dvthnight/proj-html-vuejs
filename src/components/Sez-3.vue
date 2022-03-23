<template>
    <section>
        <div class="col-6 video" ></div>
        <div class="play_video">
            <i class="fa-solid fa-play"></i>
        </div>
        <div class="col-6 tune_up">
            <h4>Tune up your workouts</h4>
            <h2>The best health & fitness advice online</h2>
            <div class="canale_youtube">

            </div>
            <p>Arcu eu facilisi ut quisque placerat nunc habitant. Magna semper mauris, venenatis, leo integer sit pellentesque.</p>
            <div class="button button-blu visit_youtube">
                <a href="#"><i class="fa-brands fa-youtube"></i> Visit my YouTube channel</a>
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
        height: 800px;
        position: relative;
        display: flex;

    }

    .col-6{
        width: 50%;
        height: 100%;
    }

    .video{
        background-image: url("../assets/img_fitness/service15-2x.jpg");
        background-size: cover;
        border-radius: 5px;
        border-bottom-right-radius: 50px;
        position: relative;
        top: -50px;
        overflow: hidden;
    }

    .video::after{
        content: "";
        display: block;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        background-image: linear-gradient(to top, rgba(0,0,0,0.7),rgba(0,0,0,0.1));
        position: absolute;
    }

    .play_video{
        top: 50%;
        left: 25%;
        transform: translate(-50%,-50%);
    }

    .tune_up{
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        justify-content: center;
        padding: 0 130px;
        gap: 20px;

        h4{
            font-size: 27px;
            color: #4154fe;
            font-weight: 500;
        }

        h2{
            font-size: 62px;
            font-weight: 500;
        }

        p{
            color: #78787a;
            font-size: 25px;
            font-weight: 400;
            margin-bottom: 20px;
        }

        .visit_youtube{
            background-color: rgb(229, 45, 31);
        }

        .visit_youtube:hover{
            opacity: 0.9;
        }
    }
</style>