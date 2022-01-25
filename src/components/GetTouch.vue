<template>
<div class="row row-cols-2 pt-5 pb-5 ">
    <!-- prima colonna form -->
    <div class="col ">
        <div class="form ps-5 ms-5">
            <p class="green fw-bolder">SEND A MESSAGE</p>
            <h2 class="fw-bolder">Get in <span class="background-light fw-bolder">Touch</span></h2>
            <p>We will respond to your message as soon as possible.</p>



            <!-- form input -->
            <form class="row g-3">
                <div class="col-md-6">
                    <label for="inputEmail4" class="form-label"></label>
                    <input type="email" class="form-control" id="inputName"
                    placeholder="Name">
                </div>
                <div class="col-md-6">
                    <label for="inputPassword4" class="form-label"></label>
                    <input type="password" class="form-control" id="inputEmail"
                    placeholder="Email">
                </div>
                <div class="col-md-6">
                    <label for="inputPassword4" class="form-label"></label>
                    <input type="password" class="form-control" id="inputPhone"
                    placeholder="Phone">
                </div>
                <div class="col-md-6">
                    <label for="inputState" class="form-label"></label>
                    <select id="inputInfo" class="form-select" >
                        <option selected > More info</option>
                        <option>...</option>
                    </select>
                </div>
                <div class="mb-3">
                    <label for="exampleFormControlTextarea1" class="form-label"></label>
                    <textarea class="form-control" id="Textarea" rows="3" placeholder="Message"></textarea>
                </div>
                <div class="col-12">
                    <button class="btn button-1  ms-3 " type="submit">SEND</button>
                </div>
            </form>
        </div>

        <!-- seconda colonna -->
        
    </div>
    <div class="col">
        <div class="contact ms-5">
            <h5>Example Inc.</h5>
            <p class="mt-5">Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
            <ul>
                <li><i class="fas fa-phone-alt"></i> <span class="ms-2">+1(305)1234-5678</span></li>
                <li><i class="fas fa-envelope"></i><span class="ms-2">hello@example.com</span></li>
                <li><i class="fas fa-map-marker-alt"></i>
                <span class="ms-2">Main Avenue, 987</span> </li>
            </ul>
            <button class="btn button-1 ms-3 " type="submit">VIEW MAP</button>
        </div>
        

        
    </div>
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import "../assets/scss/partials/_variables.scss";
@import "../assets/scss/partials/_commons.scss";

.green{
    color: $colorGreen;
    
}
.grey{
    background-color: $colorGrey;
}
#inputName,
#inputEmail,
#inputPhone,
#inputInfo,
#Textarea{
    
    background-color: rgb(236, 232, 232);
    border: 0;
}


.contact{
    ul{
        list-style-type: none;
        padding: 0;
        li {
            padding-bottom: 20px;
            i{
            padding: 10px;
            text-align: center;
            vertical-align: middle;
            width: 40px;
            height: 40px;
            background-color: #DAECED;
            border-radius: 50%;
            color: $colorGreen;

            }
        }
        
    }
}

</style>