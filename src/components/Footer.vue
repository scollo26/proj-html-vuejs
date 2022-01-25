<template>
  <div class="container-100">
    <div class="container-marg pt-5">
      <div class="row row-cols-4  " >
        <div class="col">
          <div class="p-2 flex-grow-1 bd-highlight">
            <div class="title-left">
              <span class="next ">NEX</span>
            </div>
            <span class="gen">GEN</span>    
            <p>A Functional HTML Template for Corporate & Business.</p> 
            <ul class="ps-0 ">
                <li class="pb-3"><i class="fas fa-phone-alt"></i> <span class="ms-2 gen">+1(305)1234-5678</span></li>
                <li class="pb-3"><i class="fas fa-envelope"></i><span class="ms-2 gen">hello@example.com</span></li>
                <li class="pb-3"><i class="fas fa-map-marker-alt"></i>
                <span class="ms-2 gen">Main Avenue, 987</span> </li>
            </ul>
            <button class="btn button-2  ms-3 " type="submit">GET IN TOUCH</button>   
          </div>
        </div>
        <div class="col">
          <div class="container-footer">
            <h3>About</h3>
            <ul>
              <li><i class="fas fa-chevron-right me-2"></i>The company</li>
              <li><i class="fas fa-chevron-right me-2"></i>Institutional</li>
              <li><i class="fas fa-chevron-right me-2"></i>Social & Events</li>
              <li><i class="fas fa-chevron-right me-2"></i>Innovation</li>
              <li><i class="fas fa-chevron-right me-2"></i>Environment</li>
              <li><i class="fas fa-chevron-right me-2"></i>Thecnology</li>
            </ul>

          </div>
        </div>
        <div class="col">
          <div class="container-footer">
            <h3>Services</h3>
            <ul>
              <li><i class="fas fa-chevron-right me-2"></i>Audit & Assurance</li>
              <li><i class="fas fa-chevron-right me-2"></i>Financial Advisory</li>
              <li><i class="fas fa-chevron-right me-2"></i>Analytics M&A</li>
              <li><i class="fas fa-chevron-right me-2"></i>Middle Marketing</li>
              <li><i class="fas fa-chevron-right me-2"></i>Legal Consulting</li>
              <li><i class="fas fa-chevron-right me-2"></i>Regulatory Risk</li>
            </ul>

          </div>
        </div>
        <div class="col">
          <div class="container-footer">
            <h3>Support</h3>
            <ul>
              <li><i class="fas fa-chevron-right me-2"></i>Responsability</li>
              <li><i class="fas fa-chevron-right me-2"></i>Terms of Use</li>
              <li><i class="fas fa-chevron-right me-2"></i>About Cookies</li>
              <li><i class="fas fa-chevron-right me-2"></i>Privacy Policy</li>
              <li><i class="fas fa-chevron-right me-2"></i>Accessibility</li>
              <li><i class="fas fa-chevron-right me-2"></i>Information</li>
            </ul>

          </div>
        </div>
      </div>
    </div>
    <div class=" footer-bottom ">
      <div class="container-bottom mt-5">
        <div class="row row-cols-2 pt-3 " >
          <div class="col">
            <p>Enjoy the low price. we are tracking any intention of piracy</p>
          </div>
          <div class="col">
            <p>2020 NEXGEN is Proudly Powered by <span class="green"> Codings</span> </p>
          </div>
        
        <div>
      </div>
    </div>
        
  </div>
    
  </div>
</div>
</template>

<script>
export default {
  name:"Footer",
  data(){
    return{

    }
  }
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";
@import "../assets/scss/partials/_commons.scss";
.container-100{
  width: 100%;
  // height: 500px;
  
  background-color: black;
  .container-marg{
    width: 80%;
    margin: 0 auto;
    .title-left{
            display: inline-block;
            margin-bottom: 30px;
            
            span{
                text-transform: uppercase;
                font-weight: bold;
                font-size: 1.3em;
                
            }
            .next{
                color: #52bbba;
                background-color: #0D272D;
                border-top-left-radius: 25px;
                border-bottom-left-radius: 25px;
                padding: 10px 0 10px 30px;
                margin-right: 2px;
                
            }
            
    }
    .col,li,i,.gen{
    color: grey;

  }
  .container-footer{
    border-radius: 8%;
    height: 100%;
    color: white;
  }
  .container-footer{
    width: 100%;
    height: 100%;
    padding: 10%;
    background-color: #191920;
    ul{
    padding: 10px 0px;
    
    // background-color: blanchedalmond;
    
    li{
      padding: 5px;
      margin: 0px;
      
      
    }
  }
  }

  }
  .footer-bottom{
    color: white;
    background-color: #191920;
    height: 80px;
  }
  .container-bottom{
    margin: 0 auto;
    width: 80%;
    
    
  }
}

</style>