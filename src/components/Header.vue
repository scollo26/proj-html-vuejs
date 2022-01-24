<template>

<div class="header-top container-fluid"> 
    <div class="container">
        <div class="row row-col-2">
            <div class="col">
                <i class="fas fa-clock pt-3"></i>
                <span>Open Hours: Mon-Sat- 9:00-18:00</span>
                
            </div>
            <div class="col">
                <i class="fas fa-phone-alt"></i>
                <span>+1(305) 1234-5678</span>
                <span><i class="fas fa-envelope"></i> hello@example.com</span>
                <span class="icon-top">
                    <span><i class="fab fa-facebook-f"></i></span>
                    <span><i class="fab fa-twitter"></i></span>
                    <span><i class="fab fa-linkedin-in"></i></span>
                </span>
                

            </div>
        </div>
        <div class="container mt-2">
            <div class="d-flex bd-highlight">
                <div class="p-2 flex-grow-1 bd-highlight">
                    <span class="green fs-2">NEX</span>
                    <span class="black fs-2">GEN</span>    
                </div>
            
                <div class="p-2 bd-highlight">
                    <ul>
                        <li><a href="http://"> HOME</a> </li>
                        <li><a href="http://"> SERVICES</a></li>
                        <li><a href="http://"> ABOUT</a></li>
                        <li><a href="http://"> PROJECT</a></li>
                        <li><a href="http://"> RESULTS</a></li>
                        <button class="btn btn-outline-secondary ms-3 " type="submit">GET IN TOUCH</button>
                    </ul>
                </div>
        
            </div>
        </div>
        

        </div>
        <div class="jumbo">
            <div class="jumbo-img">
                <img src="../assets/img/bg-parallax.png" alt="">
                
            </div>
            <div class="banner-jumbo text-center">
                    <h1 class="black fs-1 fw-bold">Ready</h1>
                    <span class="green fs-1 fw-bold">Team</span> 
                    <p>No matter what your company needs, we will be </p> 
                    <p>ready to assist you in the best possible way.</p>
                    <button class="btn btn-outline-secondary ms-3 " type="submit">GET IN TOUCH</button>
                    <button type="button" class="btn btn-outline-success green ms-3">READ MORE</button>
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
    background-color: #122439;
    .container{
        // background-color: #122439;
        height: 50px;
        color: grey;
        .p-2{
            width: 100%;
            ul{
            list-style-type: none;
            li, a{
            display: inline-block;
            margin-left: 3%;
            text-decoration: none;
            color:gray;
    
            }
    
        }
    }
        
            
        }
        .green{
            color: #1c918e;
        }
        .black{
            color: black;
        }
        .icon-top{
            i{
                padding: 1em;
            }
            
        }
        .btn-outline-secondary{
            color: white;
            background-color: #1c918e;
            

        }
        
    .jumbo{
        
        // width: 100%;
        // height: 100%;
        position: relative;
        background-color: yellow;
        .jumbo-img{
            width: 100%;
            position: absolute;
        //    left: 0;
        right: 200px;
           top: -97px;
           overflow: hidden;
           img{
            width: 183em;
            height: 100%;
            }
            
        }
        .banner-jumbo{
                position: absolute;
                color: grey;
                left: 1100px;
                top: 310px;
            }
        
    }
    
}

</style>