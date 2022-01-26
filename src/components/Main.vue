<template>
<!-- inserimento company più immagine grande sulla destra -->
  <div class="container-fluid">
    <div class="row black row-cols-2 d-flex  justify-content-evenly" >
        <div class="col-6 text-start ">
            <div class="company ">
                <h5 class="fs-6 mb-5">ABOUT THE NETWORK</h5>
                <h2 class="fs-1"><span class="background">The</span>  Company</h2>
                <p>For 12 years we have been providing audit and warranty, financial advice, risk advice, taxes and related services to select clients</p>
                <div class="row row-cols-2 d-flex " >
                    <div class="col text-start">
                        <i class="fas fa-award fs-5"> </i><span class="fs-4 ms-3">Tradition</span>
                        <p class="mt-4">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

                    </div>
                    <div class="col text-start">
                        <i class="fas fa-unlock-alt fs-5"> </i><span class="fs-4 ms-3">Security</span>
                        <p class="mt-4">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
                <div class="row row-cols-2 d-flex " >
                    <div class="col text-start">
                        <i class="far fa-edit fs-5"></i> <span class="fs-4 ms-3">Certificate</span>
                        <p class="mt-4">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

                    </div>
                    <div class="col text-start">
                        <i class="fas fa-graduation-cap fs-5"> </i><span class="fs-4 ms-3">Expertise</span>
                        <p class="mt-4">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
                
                
                <button class="btn button-1  ms-3 " type="submit">GET IN TOUCH</button>
                <button type="button" class="btn button-2 ms-3">READ MORE</button>
                
            </div>
        </div>
        <div class="col-6 ">
            <div class="img-company">
                <img src="../assets/img/about-4.jpg" alt="">
            </div>
            
            
        </div>
    </div>
        <!-- inserimento menu Projects -->
    <div class="container-main mt-5">
        <p class="green fw-bolder"> WE DO MORE FOR EVERYONE</p>
        <h2 class="fw-bolder">Actions & <span class="background-light fw-bolder">Projects</span></h2>
        <div class="menu-main">
            <nav>
                <ul>
                    <li><a class="active" href="http://">ALL</a></li>
                    <li><a  href="http://">INSTITUTIONAL</a></li>
                    <li><a href="http://">SOCIAL</a> </li>
                    <li><a href="http://">EVENTS</a> </li>
                    <li><a href="http://">INNOVATION</a> </li>
                    <li><a href="http://">ENVIRONMENT</a> </li>
                    <li><a href="http://">TECHNOLOGY</a> </li>
                </ul>      
            </nav>
        </div>
        <!-- richiamo figlio Cards per le 6 immagini con hover -->
        <div class="action">
            <!-- <Cards /> -->
            <div class="d-flex row-cols-3 pb-5 flex-wrap" >
                <Cards v-for="(card, index) in cards" :key="index" 
                :image="card.src" 
                :title="card.title">
                </Cards>
                <!-- <div class="col">
                    <div class="project pe-5">
                        <img src="../assets/img/project-1.jpg" alt="">
                    </div>
                </div>
                <div class="col">
                    <div class="project pe-5">
                        <img src="../assets/img/project-2.jpg" alt="">
                    </div>
                </div>
                <div class="col">
                    <div class="project pe-5">
                        <img src="../assets/img/project-3.jpg" alt="">
                    </div>
                </div>
             -->
            </div>
            <!-- <Cards/> -->
            <!-- <div class="d-flex row-cols-3 pb-5" >
                <Cards v-for="(card, index) in cards" :key="index" 
                :image="card.src" 
                :title="card.title">
                </Cards>
                <div class="col">
                    <div class="project pe-5">
                        <img src="../assets/img/project-4.jpg" alt="">
                    </div>
                </div>
                <div class="col">
                    <div class="project pe-5">
                        <img src="../assets/img/project-5.jpg" alt="">
                    </div>
                </div>
                <div class="col">
                    <div class="project pe-5">
                        <img src="../assets/img/project-6.jpg" alt="">
                    </div>
                </div> 
            </div> -->
        </div>
        
        
        

    </div>
    <!-- richiamo figlio Ressults con tabella numeri -->
    <div class="results pt-5">
        <Results/>
    </div>
    <!-- richiamo figlio programs per immagini programmi -->
    <div class="programs">
        <div class="container">
            <Programs />
        </div>
    </div>
    <!-- richiamo figlio GetTouch per inserimento form -->
    <div class="getTouch">
        <div class="container">
            <GetTouch />
        </div>
    </div>
    

</div>
</template>

<script>
import Cards from './Cards.vue'
import Results from './Results.vue'
import Programs from './Programs.vue'
import GetTouch from './GetTouch.vue'
export default {
name:"Main",
components:{
    Cards,
    Results,
    Programs,
    GetTouch,
    },
    data() {
    return {
        cards: [
            { 
                title: "Academic professional program in social media",
                src: require("../assets/img/project-1.jpg")
            },
            { 
                title: "President's speech atthe annual meeting",
                src: require("../assets/img/project-2.jpg")
            },
            { 
                title: "International business trip in Shanghai",
                src: require("../assets/img/project-3.jpg")
            },
             { 
                title: "Technology workshop with education theme",
                src: require("../assets/img/project-4.jpg")
            },
             { 
                title: "Donation of clothes and food to the partner NGO",
                src: require("../assets/img/project-5.jpg")
            },
             { 
                title: "Confraternization of the procurement team",
                src: require("../assets/img/project-6.jpg")
            },
        ]
}
    }
}
</script>

<style lang="scss">
@import "../assets/scss/partials/_variables.scss";
@import "../assets/scss/partials/_commons.scss";
.container-fluid{
    width: 100%;
    .black{
            background-color: black;
        }
    .company{
        color: white;
        width: 45%;
        margin-left: 40%;
        margin-top: 10em;
        h5{
            color: #8fff; 
        }
        
        i{
            color: #1c918e;
        }
    }
    .button-1{
    background-color: #1c918e;
    color: white;
    }
    .button-2{
    color: white;
    border: 1px solid #1c918e;
    }


    .img-company{
        overflow: hidden;
    }
    .container-main{
        width: 70%;
        margin: 0 auto;
        text-align: center;
        .menu-main{
            nav{
                color: grey;
                ul{
                    list-style-type: none;
                    
                    li{
                        display: inline-block;
                        a{
                            text-decoration: none;
                            padding: 0.5em 0.5em;
                            color: grey;
    
                        }
                        a:hover{
                            color: #29B5C0;
                            margin-left: 3%;
                            
                            
                        }

                    } 
    
                }     
                
            } 
            nav ul:hover a.active{
                background-color: rgb(202, 201, 201);
                color: black;
            }
        }
        .action{
            background-color: white;
        }
    }
    .results{
        background-image: url("../assets/img/bg-7.jpg");
        background-position: center;
        
        width: 100%;

    }
    .programs{
        background-color: #111116;
        img{
            width: 40%;
            filter: invert(1);
        }
        
        
    }

}

</style>