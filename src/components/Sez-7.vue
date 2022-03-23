<template>
    <section>
        <div class="contenitore">
            <div class="intestazione">
            <h3>Latest articles</h3>
            <a href="#">Read all articles <i class="fa-regular fa-chevron-right"></i></a>
            </div>
            <div class="contenitore_card">
                <div class="card card_1">
                    <figure class="card_image">
                        <img src="../assets/img_fitness/blog4-2x-1200x773.jpg" alt="">
                    </figure>
                    
                    <h2>The best protein shake</h2>
                    <p>By admin | November 26th, 2019 | Gym</p>
                </div>
                <div class="card card_2">
                    <figure class="card_image">
                        <img src="../assets/img_fitness/blog1-2x-1200x773.jpg" alt="">
                    </figure>
                    <h2>Ultimate cardio workout</h2>
                    <p>By admin | November 26th, 2019 | Gym</p>
                </div>
                <div class="card card_3">
                    <figure class="card_image">
                        <img src="../assets/img_fitness/blog3-2x-1200x773.jpg" alt="">
                    </figure>
                    <h2>New Juices available now</h2>
                    <p>By admin | November 26th, 2019 | Gym</p>
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
        gap: 10px;
        position: relative;

        h2{
            font-weight: 500;
            padding-left: 20px;
        }

        p{
            color: #78787a;
            font-weight: 500;
            font-size: 20px;
            padding-left: 20px;
        }

        .card_image{
        width: 406px;
        img{
            border-radius: 5px;
            border-bottom-right-radius: 30px;
            }
        }

    }
</style>