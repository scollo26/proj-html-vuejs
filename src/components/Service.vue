<template>
<!-- inserimento 6 colonne services con hover freccia -->
<div class="header-bottom pt-5 ">   
    <div class="container">
        <p class="green"> OUR BUSINESS AREAS</p>
        <h2 class="black fw-bold"> Excellence in <span class="background-light">Service</span></h2>
        <div class="row row-col-2 ">
            <div class="col">
                <p>we are leaders in providing consultancy services with a set of cutting-edge technologies and a team of experienced and renowed professionals.These are some options that you can hire.</p>
            </div>
            <div class="col d-flex justify-content-end height-30">
                <button class="btn button-1 ms-3 " type="submit">SEE ALL</button>
            </div>
        </div>
        <div class="row row-cols-3 pb-5" >
            <div class="col">
                <div class="business">
                    <div class="d-flex justify-content-between p-4">
                        <i class="fas fa-network-wired fs-1 green "></i>
                        <div class=" arrow p-3 ">    
                            <i class="fas fa-arrow-right fs-4 "></i>
                        </div>
                    </div>    
                    <h2 class="black ps-3">Audit & Assurance</h2>
                    <p class="ps-3">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>          
                </div>
            </div>
            <div class="col">
                <div class="business">
                    <div class="d-flex justify-content-between p-4">
                                
                        <i class="fas fa-briefcase fs-1 green"></i>
                        <div class=" arrow p-3 ">        
                            <i class="fas fa-arrow-right fs-4 "></i>
                        </div>
                    </div>         
                    <h2 class="black ps-3">Audit & Assurance</h2>
                    <p class="ps-3">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>           
                </div>
            </div>
            <div class="col">
                <div class="business">
                    <div class="d-flex justify-content-between p-4">
                        <i class="far fa-chart-bar fs-1 green"></i>
                        <div class=" arrow p-3 ">   
                            <i class="fas fa-arrow-right fs-4 "></i>
                        </div>
                    </div>     
                    <h2 class="black ps-3">Audit & Assurance</h2>
                    <p class="ps-3">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>          
                </div>
            </div>
            <div class="col">
                <div class="business">
                    <div class="d-flex justify-content-between p-4">
                        <i class="fas fa-plane fs-1 green"></i>
                        <div class=" arrow p-3 ">     
                            <i class="fas fa-arrow-right fs-4 "></i>
                        </div>
                    </div>    
                    <h2 class="black ps-3">Audit & Assurance</h2>
                    <p class="ps-3">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>        
                </div>
            </div>
            <div class="col">
                <div class="business">
                    <div class="d-flex justify-content-between p-4">
                                
                        <i class="fas fa-globe-americas fs-1 green"></i>
                        <div class=" arrow p-3 ">     
                            <i class="fas fa-arrow-right fs-4 "></i>
                        </div>
                    </div>       
                    <h2 class="black ps-3">Audit & Assurance</h2>
                    <p class="ps-3">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>           
                </div>
            </div>
            <div class="col">
                <div class="business">
                    <div class="d-flex justify-content-between p-4">         
                        <i class="fas fa-inbox fs-1 green"></i>
                        <div class=" arrow p-3 ">     
                            <i class="fas fa-arrow-right fs-4 "></i>
                        </div>
                    </div>  
                    <h2 class="black ps-3">Audit & Assurance</h2>
                    <p class="ps-3">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>         
                </div>
            </div>
        </div>      
    </div>
</div>
</template>

<script>
export default {
    name:"Service",
}
</script>

<style lang="scss">
.header-bottom{
        height: 70em;
        background-color: #EEF1ED;
        
        .business{
            background-color: white;
            height: 280px;
            width: 300px;
            margin-top: 50px;
            border-radius: 8%;
            .arrow{
                position: relative;
                text-align: center;
                
                // background-color: #52bbba;
                vertical-align: middle;
                
                i{
                    position: absolute;
                    top: 2px;
                    left: 0;
                    padding: 1px;
                    
                    
                    // display: block;
                    color: #52bbba;
                    opacity: 0.8;
                    
                }
                
            }
            .arrow:hover i{
                
                color: #038484;
                background-color: #52bbba;
                display: block;
                border-radius: 50%;
                width: 30px;
                height: 30px;
            }
        }
    }

</style>