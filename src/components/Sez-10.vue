<template>
    <section>
        <div class="sfondo"></div>
        <div class="contenitore">
            <div class="play_video">
                <i class="fa-solid fa-play"></i>
            </div>
            <h2>Crossfit workout of the day</h2>
            <h3>November 15th, 2019</h3>
            <a href="#">View all videos <i class="fa-regular fa-arrow-right"></i></a>
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
.sfondo{
        height: 650px;
        position: relative;
         background-image: linear-gradient(to top left, #bc0428,rgb(0,38,196));
        filter: contrast(1.75);

        }

.sfondo::after{
    content: "";
    display: block;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    background-image: url("../assets/img_fitness/banner14-2x.jpg");
    background-size: cover;
    opacity: 0.5;
    position: absolute;
    }

    .contenitore{
        width: 900px;
        height: 400px;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%,-50%);
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 40px;

        h2{
        font-size: 70px;
        color: white;
        font-weight: 500;
        text-align: center;
        }

        h3{
            color: yellow;
            font-size: 40px;
            font-weight: 500;
        }
        a{
            color: white;
            font-weight: 500;
            font-size: 20px;
            text-align: center;
            display: flex;
            gap: 10px;
            align-items: center;
        }

        .play_video{
            position: relative;
        }

    }
</style>