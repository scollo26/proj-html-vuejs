<template>

<div class="row row-cols-6 pt-5 pb-5">
    <div class="col">
        <img src="../assets/img/logo-4.png" alt="">
    </div>
    <div class="col resize">
        <img class="resize" src="../assets/img/logo-5.png" alt="">
    </div>
    <div class="col">
        <img src="../assets/img/logo-1.png" alt="">
    </div>
    <div class="col">
        <img src="../assets/img/logo-2.png" alt="">
    </div>
    <div class="col">
        <img src="../assets/img/logo-3.png" alt="">
    </div>
    <div class="col">
        <img  src="../assets/img/logo-4.png" alt="">
    </div>
</div>



</template>

<script>
export default {
    name:"Programs",
    data() {
        return {         
        }
    },

}
</script>

<style lang="scss" scoped >
@import "../assets/scss/partials/_variables.scss";
.col{
    img{
        filter: invert(1);
        
    }
    .resize{
            width: 30%;
        }
}


</style>