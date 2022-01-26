<template>

<div class=" container-100 ">
    <div class="header-top color-top ">
        <div class="container ">
            <div class="row row-col-2">
                <div class="col ">
                    <i class="fas fa-clock pt-3 me-2"></i>
                    <span>Open Hours: Mon-Sat- 9:00-18:00</span>
                
                </div>
                <div class="col">
                    <i class="fas fa-phone-alt "></i>
                    <span>+1(305) 1234-5678</span>
                    <span><i class="fas fa-envelope ms-3"></i> hello@example.com</span>
                    <span class="icon-top">
                        <span><i class="fab fa-facebook-f"></i></span>
                        <span><i class="fab fa-twitter"></i></span>
                        <span><i class="fab fa-linkedin-in"></i></span>
                    </span>
                </div>
            </div>
        </div>
    </div> 
        <!-- Header menu -->
        <div class="container ">
            <div  class="d-flex bd-highlight mt-4">
                <div class="p-2 flex-grow-1 bd-highlight">
                    <div class="title-left">
                        <span class="next ">NEX</span>
                    </div>
                    <span class="gen">GEN</span>    
                </div>
            
                <div class="p-2 bd-highlight">
                    <ul  v-for="(menu, index) in menus" :key="index">
                        <li><a class="fw-bolde" href="http://"> {{menu.link}}</a></li>
                        <!-- <li><a href="http://"> SERVICES</a></li>
                        <li><a href="http://"> ABOUT</a></li>
                        <li><a href="http://"> PROJECT</a></li>
                        <li><a href="http://"> RESULTS</a></li> -->
                        
                    </ul>
                    <button class="btn button-1 ms-3 " type="submit">GET IN TOUCH</button>
                </div>
        
            </div>
        </div>
        

        <!-- inserimento jumbo -->
        <div class="jumbo">
            <div class="jumbo-img">
                <div class="banner-jumbo text-center">
                    <span class="black fs-1 fw-bold">Ready</span>
                    <span class="background-light fs-1 fw-bold">Team</span> 
                    <p>No matter what your company needs, we will be </p> 
                    <p>ready to assist you in the best possible way.</p>
                    <button class="btn button-1  ms-3 " type="submit">GET IN TOUCH</button>
                    <button type="button" class="btn button-2 ms-3">READ MORE</button>
                </div>
        
            </div>  
        </div> 
    
        
        <Service/> 
    
    
    
</div>

</template>

<script>
import Service from './Service.vue'
export default {
    name:"Header",
    components:{
        Service,
    },
    data(){
        return{
            menus:[
                {
                    link:"HOME"
                },
                {
                    link:"SERVICES"
                },
                {
                    link:"ABOUT"
                },
                {
                    link:"PROJECTS"
                },
                {
                    link:"RESULTS"
                },

            ]
        }
    }
}
</script>

<style lang="scss">
@import "../assets/scss/partials/_commons.scss";
@import "../assets/scss/partials/_variables.scss";
.container-100{
    width: 100%;
    .container{
        // background-color: #122439;
        height: 80px;
        color: grey;
        
            .p-2{
            width: 100%;
            ul{
                display: inline-block;
                list-style-type: none;
            li, a{
            // display: inline-block;
            margin-left: 3%;
            text-decoration: none;
            color:black;
    
                }
                a:hover{
                    color: #52bbba;
                }
    
            }

        }   
    }
    .button-1{
    background-color: #1c918e;
    color: white;
    }

    .button-1:hover{
        background-color:#52bbba ;
        color: white;
    }
    .button-2{
    color: #1c918e;
    border: 1px solid #1c918e;
    }

    .button-2:hover{
        background-color:#52bbba ;
        color: white;
        }
    
        .color-top{
            background-color: #122439;
        }
        .title-left{
            display: inline-block;
            
            span{
                text-transform: uppercase;
                font-weight: bold;
                font-size: 1em;
                
            }
            .next{
                color: #52bbba;
                background-color: #CAE4E4;
                border-top-left-radius: 25px;
                border-bottom-left-radius: 25px;
                padding: 10px 0 10px 30px;
                margin-right: 2px;
                
            }
        }
        .gen{
            color: black;
            
        }
        .icon-top{
            i{
                padding: 1em;
            }
            
        }
        
    .jumbo{
        
        background-image: url("../assets/img/bg-parallax.png");
        background-position: center;
        width: 100%;
            height: 700px;
        // background-color: yellow;
        .jumbo-img{ 
           overflow: hidden;
           img{
            width: 100%;
            height: 100%;
            }
            
        }
        .banner-jumbo{  
            color: $colorBlack;
            margin-top: 10em;
            
            }
        
    }
    
}

</style>