<template>
    <section>
        <div class="contenitore">
            <div class="contenitore_card">
                <div class="card card-1">
                    <figure>
                        <img src="../assets/img_fitness/sponsor-1-2x.png" alt="">
                    </figure>
                    <div class="onda">

                    </div>
                    <p>
                        Tristique aliquam in nullam habitasse nunc, amet vel consectetur. 
                        Nulla in suspendisse dolor, aliquet.
                    </p>
                    <a href="#">Visit Yoga Studio <i class="fa-regular fa-chevron-right"></i></a>
                </div>
                <div class="card card-2">
                    <figure>
                        <img src="../assets/img_fitness/sponsor-2-2x.png" alt="">
                    </figure>
                    <div class="onda">

                    </div>
                    <p>
                        Feugiat etiam dui mauris pharetra mauris sed pharetra. Convallis sapien
                        ornare cras faucibus nulla porta dui a. 
                    </p>
                    <a href="#">Join Fitness Center <i class="fa-regular fa-chevron-right"></i></a>
                </div>
                <div class="card card-3">
                    <figure>
                        <img src="../assets/img_fitness/sponsor-3-2x.png" alt="">
                    </figure>
                    <div class="onda">

                    </div>
                    <p>
                        Nisl at quam adipiscing montes, nec, adipiscing commodo aliquam tincidunt.
                        Ligula in habitant et sagittis imperdiet.
                    </p>
                    <a href="#">Learn about FC <i class="fa-regular fa-chevron-right"></i></a>
                </div>
                <div class="card card-4">
                    <figure>
                        <img src="../assets/img_fitness/sponsor-4-2x.png" alt="">
                    </figure>
                    <div class="onda">

                    </div>
                    <p>
                        Proin in viverra maecenas et mattis ut nibh enim. Gravida ulticies mi porta lacus. 
                        Et posuere velit sed nec eleifend.
                    </p>
                    <a href="#">Visit Power Gym <i class="fa-regular fa-chevron-right"></i></a>
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
    .contenitore_card{
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding-top: 100px;
        padding-bottom: 150px;
    }

    .card{
        width: 22%;
        display: flex;
        flex-direction: column;
        gap: 20px;
        align-items: center;
        justify-content: center;
        cursor: pointer;

        figure{
            width: 70%;
        }

        p{
            color: #78787a;
            font-weight: 500;
            font-size: 20px;
            text-align: center;
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
    }
</style>