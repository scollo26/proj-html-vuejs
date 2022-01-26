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
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">The company</a></li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Institutional</a></li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Social & Events</a> </li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Innovation</a> </li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Environment</a> </li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Thecnology</a> </li>
            </ul>

          </div>
        </div>
        <div class="col">
          <div class="container-footer">
            <h3>Services</h3>
            <ul>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Audit & Assurance</a></li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Financial Advisory</a></li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Analytics M&A</a></li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Middle Marketing</a></li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Legal Consulting</a></li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Regulatory Risk</a></li>
            </ul>

          </div>
        </div>
        <div class="col">
          <div class="container-footer">
            <h3>Support</h3>
            <ul>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Responsability</a></li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Terms of Use</a></li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">About Cookies</a></li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Privacy Policy</a></li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Accessibility</a></li>
              <li><i class="fas fa-chevron-right me-2"></i><a href="http://">Information</a></li>
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
            <p>©2020 NEXGEN is Proudly Powered by <span class="green"> Codings</span> </p>
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
      a{
        cursor: pointer;
        text-decoration: none;
        color: grey;
      }

      a:hover{
        color: #52bbba;
      }
      
      
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