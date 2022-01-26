<template>
<!-- inserimento 6 card in modo dinamico -->
<div class="col d-flex row-cols-3 pb-5 ">
    <div class="card-item">
        <div class="project ">
            <img :src="image" :alt="title">
        </div>
        <div class="info-hover">
            <div class="info">
                <div class="fs-3 fw-bolder">{{title}}</div> 
            </div>
        </div>
    </div>
    
</div>
<!-- <div class="d-flex row-cols-3 pb-5" >
                
    <div class="col">
        <div class="card-item">
            <div class="project ">
                <img src="../assets/img/project-1.jpg" alt="">
            </div>
            <div class="info-hover p-3">
                <div class="info">
                    <div class="fs-3 fw-bolder">Academic professional program in social media</div> 
                </div>
            </div>
        </div>
    </div>
    <div class="col">
        <div class="card-item">
            <div class="project ">
                <img src="../assets/img/project-2.jpg" alt="">
            </div>
            <div class="info-hover p-3">
                <div class="info">
                    <div class="fs-3 fw-bolder">President's speech at the annual meeting</div> 
                </div>
            </div>
        </div>
    </div>
    <div class="col">
        <div class="card-item">
            <div class="project ">
                <img src="../assets/img/project-3.jpg" alt="">
            </div>
            <div class="info-hover p-3">
                <div class="info">
                    <div class="fs-3 fw-bolder">International business trip in shanghai</div> 
                </div>
            </div>
        </div>
    </div>
</div>  -->
</template>

<script>
export default {
    name:"Card",
    props: [
        'title',
        'image',
        
    ],
    data() {
        return {         
        }
    },

}
</script>

<style lang="scss">
.col {
    padding: 1em;
    .card-item {
        position: relative;
        height: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        // border: 1px solid white;
        width: 80%;
        .project {
            height: 100%;
            width: 100%;
            // width: 14em;
            overflow: hidden;
            border-radius: 5%;
        img {
            width: 100%;
            
        } 
    }
    .info-hover {
        height: 100%;
        width: 100px;
        position: absolute;
        background-color: black;
        color: white;
        opacity: 0.6;
        display: none;
        border-radius: 5%;
        cursor: pointer;
        
        .info {  
            position: absolute;
            // top: 314px;
            top: 60%;
            display: block;
            text-align: center;
        }
    }
    
}
    .card-item:hover .info-hover {
        display: block;
        // width: 14em;
        width: 100%;
    }
    
}

</style>