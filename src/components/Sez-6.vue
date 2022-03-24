<template>
    <section>
        <div class="contenitore">
            <div class="contenitore_card">
                <div class="card card-1">
                    <figure class="icona">
                        <img src="../assets/img_fitness/smartwatch-svgrepo-com.svg" alt="">
                    </figure>
                    <h3>Team training</h3>
                    <h4>Find a partner</h4>
                    <p>Vestibulum, curabitur eu sem nibh ultrices sit nulla adipishing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
                    <h5><a href="#">Find a partner <i class="fa-regular fa-chevron-right"></i></a></h5>
                </div>
                <div class="card card-2">
                     <figure class="icona">
                        <img src="../assets/img_fitness/dumbbell-svgrepo-com.svg" alt="">
                     </figure>
                    <h3>Crossfit workout</h3>
                    <h4>Push your limits</h4>
                    <p>Vestibulum, curabitur eu sem nibh ultrices sit nulla adipishing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
                    <h5><a href="#">Learn about Crossfit <i class="fa-regular fa-chevron-right"></i></a></h5>
                </div>
                <div class="card card-3">
                     <figure class="icona">
                        <img src="../assets/img_fitness/slim-down-slim-svgrepo-com.svg" alt="">
                     </figure>
                    <h3>Weight loss plan</h3>
                    <h4>Shed those pounds</h4>
                    <p>At laoreet sensectus volutpat diam vei sed sed amet pellentesque. Lobortis ut aliquam risus purus. A tellus ut etiam.</p>
                    <h5><a href="#">Schedule a workout <i class="fa-regular fa-chevron-right"></i></a></h5>
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
        background-color: #060606;
    }
    .contenitore_card{
        display: flex;
        flex-wrap: nowrap;
        justify-content: space-between;
        align-items: center;
        padding: 100px 0;

        .card{
            width: 400px;
            padding: 50px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            gap: 40px;
            border: 3px solid #4154fe;
            border-radius: 5px;

            h3{
                color: white;
                font-size: 30px;
                font-weight: 500;
            }

            h4{
                color: yellow;
                font-size: 25px;
                font-weight: 500;
            }

            p{
                color: #78787a;
                font-weight: 500;
                text-align: center;
                font-size: 20px;
            }

            h5{
                color: white;
                font-size: 20px;
                font-weight: 500;
            }

            .icona{
                filter: invert(1);
                width: 200px;
            }
        }

        .card:hover{
            scale: 1.05;
            cursor: pointer;
            transition: all 0.3s ease-in-out;
        }
    }
</style>