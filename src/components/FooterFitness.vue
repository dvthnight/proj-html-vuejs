<template>
    <footer>
        <section class="sez-1">
            <div class="contenitore">
                <div class="contenitore_card">
                    <div class="card card-1">
                        <figure class="logo">
                            <img src="../assets/img_fitness/logo-2x.png" alt="">
                        </figure>
                        <p>
                            Ac aliquam neque sagittis diam faucibus vitae purus turpis phasellus. 
                            Pellentesque consectetur amet purus ultrices mauris.
                        </p>
                        <ul class="icone">
                            <li v-for="el in icone" :key="el">
                                <a href="#"><i :class="el"></i></a>
                            </li>
                        </ul>
                    </div>
                    <div class="card card-2">
                        <h2>Recent Posts</h2>
                        <ul>
                            <li v-for="el in posts" :key="el">
                                <a href="#"><i class="fa-regular fa-chevron-right"></i> {{el}}</a>
                            </li>
                        </ul>
                    </div>
                    <div class="card card-3">
                        <h2>Contact Informations</h2>
                        <p>4746 Tipple Road Michigan 48449</p>
                        <ul>
                            <li>Mobile : 1.800.000.0000</li>
                            <li>Email : info@your-company.com</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
        <section class="sez-2">
            <p>© Copyright 2012 - 2022 | Avada Theme by <a href="#">ThemeFusion</a> | All Rights Reserved | Powered by <a href="#">WordPress</a></p>
        </section>
    </footer>
</template>

<script>
export default {
    data(){
        return{
            posts: ["The best protein shake","Ultimate cardio workout","New juices available now","Tips to find training partners","20 best healthy recipes"],

            icone: ["fa-brands fa-facebook-f","fa-brands fa-twitter","fa-brands fa-instagram","fa-brands fa-youtube","fa-brands fa-linkedin-in"]
        }
    }
}
</script>

<style lang="scss" scoped>
    footer{
        background-color: #060606;
        height: 700px;
    }

    .sez-1{
        border-bottom: 1px solid rgba(120, 120, 122, 0.3);
    }

    .contenitore_card{
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
        padding: 150px;

        .card{
            width: 27%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            gap: 10px;

            h2{
                color: white;
                font-weight: 500;
                font-size: 30px;
                margin-bottom: 30px;
            }

            li,p{
                font-weight: 500;
                font-size: 20px;
                text-align: center;
            }

            li{
                color: white;
                margin-bottom: 20px;
            }

           
            .icone{
                display: flex;
                gap: 20px;
                
                i{
                    color: rgb(241, 74, 71);
                }
            }


            .logo{
                width: 70%;
            }
        }

         .card-1{
                p{
                    color: #bcbcbc;
                    margin-bottom: 20px;
                } 
            }

            .card-3{
                p{
                    color: #78787a;
                    margin-bottom: 20px;
                }
            }
    }

    .sez-2{
        display: flex;
        justify-content: center;
        align-items: center;
        height: calc(700px - 597px);
        p{
            color: #78787a;
            font-size: 18px;
            font-weight: 500;
            a{
                color: white;
            }
        }
    }
</style>