<template>
<!-- inserimento tabella con risultati numerici -->
    <div class="container text-center mt-5">
        <h6 class="green"> WHAT ARE WE DOING</h6>
        <h2 class="fw-bolder fs-1 white"><span class=" background">Results</span>  in Numers</h2>
        <div class="row row-cols-4 mt-5 pb-5">
            <div class="col">
                <div class="fs-1 fw-bolde green">128</div>
                <h4 class="fw-bolder fs-3 white">Certifications</h4>

            </div>
            <div class="col">
                <div class="fs-1 fw-bolde green">230</div>
                <h4 class="fw-bolder fs-3 white">Employees</h4>

            </div>
            <div class="col">
                <div class="fs-1 fw-bolde green">517</div>
                <h4 class="fw-bolder fs-3 white">Customers</h4>

            </div>
            <div class="col">
                <div class="fs-1 fw-bolde green">94</div>
                <h4 class="fw-bolder fs-3 white">Countries Served</h4>

            </div>
        </div>
        
    </div>

</template>

<script>
export default {
    name:"Results",
    data() {
        return {         
        }
    },

}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";
@import "../assets/scss/partials/_commons.scss";
.container-100{
    .container{
        .row{
            background-color: white;
        }
    }
}
.green{
    color: $colorGreen;
}
.white{
    color: white;
}

</style>