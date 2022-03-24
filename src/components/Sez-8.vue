<template>
    <section>
        <div class="sfondo"></div>
        <div class="contenitore">
            <h2>“I’ve failed over and over again in my life. And that is why I succeed.”</h2>
            <div class="onda"></div>
            <p>Arcu auctor gravida nisl, congue sit nisi tincidunt eget proin. In lacinia lacus donec sed massa in ipsum eros, tristique. Gravida suspendisse etiam in iaculis</p>
            <div class="button button-blu">
                <a href="#">Buy Avada today <i class="fa-regular fa-chevron-right"></i></a>
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

    .sfondo{
        height: 700px;
        background-image: url("../assets/img_fitness/banner2-2x.jpg");
        background-size: cover;
        position: relative;
        
    }

    .sfondo::after{
        content: "";
        display: block;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        background-image: linear-gradient(to top, rgba(0,0,0,0.9),rgba(0,0,0,0.1));
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
        font-size: 60px;
        color: white;
        font-weight: 500;
        text-align: center;
        }
        p{
            color: #78787a;
            font-weight: 500;
            font-size: 20px;
            text-align: center;
        }

        .button{
            width: 250px;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 17px 25px;
            gap: 10px;
            a{
                display: contents;
            }
            i{
                font-size: 13px;
            }
        }

        .button:hover{
            background-color: #ec5a57;
            cursor: pointer;
            transition: all 0.3s ease-in-out;
        }
    }
</style>