<template>
  <div class="container-fluid">
    <div class="row row-cols-2 d-flex  justify-content-evenly" >
        <div class="col-6 text-start ">
            <div class="company ">
                <h5 class="fs-6 mb-5">ABOUT THE NETWORK</h5>
                <h2 class="fs-1"><span class="the">The</span>  Company</h2>
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
                
                
                <button class="btn btn-outline-secondary ms-3 " type="submit">GET IN TOUCH</button>
                <button type="button" class="btn btn-outline-success  green ms-3">READ MORE</button>
                
            </div>
        </div>
        <div class="col-6 ">
            <div class="img-company">
                <img src="../assets/img/about-4.jpg" alt="">
            </div>
            
            
        </div>
    </div>
    
    <div class="container-main">
        <p> WE DO MORE FOR EVERYONE</p>
        <h2>Actions & <span>Projects</span></h2>
        <div class="menu-main">
            <nav>
                <ul>
                    <li><a class="active" href="http://">ALL</a></li>
                    <li><a href="http://"></a>INSTITUTIONAL</li>
                    <li><a href="http://">SOCIAL</a> </li>
                    <li><a href="http://">EVENTS</a> </li>
                    <li><a href="http://">INNOVATION</a> </li>
                    <li><a href="http://">ENVIRONMENT</a> </li>
                    <li><a href="http://">TECHNOLOGY</a> </li>
                </ul>      
            </nav>
        </div>
        <div class="action">
            <div class="d-flex row-cols-3 pb-5" >
                <div class="col">
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
            
            </div>
            <div class="d-flex row-cols-3 pb-5" >
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
            
            </div>
        </div>
        
        

    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.container-fluid{
    // background-image: url("../assets/img/image.png");
    
    width: 100%;
    // padding-top: 3em;
    // margin-top: 5em;
    .row{
        background-color: black;
    }
    .company{
        color: white;
        width: 60%;
        margin-left: 40%;
        margin-top: 10em;
        h5{
           color: #8fff; 
        }
        .the{
            background-color: #1c918e;
            border-radius: 10%;
            opacity: 0.8;
        }
        i{
            color: #1c918e;
        }
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

                            padding: 0.5em 0.5em;
                            margin-left: 3%;
                            text-decoration: none;
                            color:gray;
    
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
            .project{
                width: 100%;
                flex-wrap: wrap;
                
                img{
                    border-radius: 5%;
                    width: 100%;
                }

            }
        }
    }
}

</style>