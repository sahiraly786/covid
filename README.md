<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="style.css">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <style>
    *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
   
}
.nav{
    background-image: url(img/bg2.jpg);
    height: auto;
    width: 100%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    color: white;
    overflow: hidden;
    
    
}
.nav a{
    color: white;
    transform: 3s;
    
}

.btn1{
    background-color: rgb(8, 39, 87);
    color: white;
   
    margin-left: 150px;
    border: #3B5998;
    justify-items: center;
    width: 100px;


}

.logo1{

  display: flex;
  width: 250px;
  height: 220px;
  margin-left: -150px;
  margin-top: -75px;



}

.logo{
    font-size: larger;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    width: 100%;
}


.menu a{
color:white;
text-decoration: none;
padding: 1rem;

}

.text{
    
   height: auto;
   width: 100%;
    display: flex;
    
    justify-content: center;
    align-items: center;
}
.text1{
    /* background-color: #086105; */
    display: flex;
    flex-direction: column;
    animation: moveText 2s linear
    
   
}
.text1 h1{ 
  
    font-size: 50px;
    font-family: Georgia, 'Times New Roman', Times, serif}
.text1 p{
justify-content: center;

}
.imge{
   /* background-color: #44BCDD; */
   
   
  
    animation: covid 40s infinite linear;
}



@keyframes covid{
  0%{
      transform:rotate(0deg);
  }   
  100%{
      transform: rotate(360deg);
  }
}

@keyframes moveText  {
  0% {
      transform: translateX(-100%);
  }
  100% {
      transform: translateX(0%);
  }
}

.container{
   
    width: 100%;
}
.hero{
    background-color: rgb(8, 39, 87);
    color: white;
    height: auto;
    width: 100%;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    overflow: hidden;
}
.human{
  display: flex;
  border:solid #024f75;
  background-color: #1b305f;
  align-items: center;
  column-gap: 0.5rem;
  
}
.human img{
  border-radius: 50%;
  margin-left: 0.5rem;
}

.symptoms{
    height: auto;
    width: 100%;
    background-image: url(img/bg2.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    color: white;

    display: flex;
    
    
    
}
.div1{
    display: flex;
    align-items: center;
    justify-content: center;
    border:solid #024f75;
    background-color: #1b305f;
    padding-left: 0.5rem;
    height:120px;
    width: 100%;
    column-gap: 1rem;
    overflow: hidden;
   
    
}

.div3{
  display: flex;
  align-items: center;
  justify-content: center;
  border:solid #024f75;
  background-color: #1b305f;
  overflow: hidden;
  height: 120px;
  width: 100%;
  padding-left: 0.5rem;
 
  column-gap: 1rem;
 
  
}
.div1  img{
 border-radius: 80%;
}
.div2  img{
  border-radius: 80%;
 }
 .div3 img{
  border-radius: 80%;
 }

.about{
    height: auto;
    background-color: rgb(8, 39, 87);
    color: white;
    width: 100%;
    display: flex;
    align-items: center;

}
.div2{
    display: flex;
    border:solid;
   align-items: center;
    height: 130px;
    width: 100%;
    justify-content: center;
    column-gap: 1rem;
   padding-left: 0.5rem;
   border:solid #024f75;
    background-color: #1b305f;
    
}
.div2 img{
 border-radius: 80%;
 
}
.pre{
  
  margin-top: 3.5rem;
}


.wash{
    background-image: url(img/bg2.jpg);
    height: auto;
    width: 100%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    color: white;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    
}
.wd{
justify-content: center;
text-align: center;
width: 100%;
align-items: center;
}



.ab img{
  border-radius: 50%;
}



.data{
    height: auto;
    width: 100%;
    background-color: rgb(8, 39, 87);
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
  
}

.human2{
    
 display: flex;
    flex-direction: row;
    border:solid #024f75;
    background-color: #1b305f;
    justify-content: center;
    align-items: center;
    padding-left: 1rem;
    column-gap: 0.5rem;
  
    
}
.human2 img{
    border-radius: 50%;

    
}
.air2{
    display: flex;
    flex-direction: row;
    border:solid #024f75;
    background-color: #1b305f;
    justify-content: center;
    align-items: center;
    padding-left: 1rem;
    column-gap: 0.5rem;
   
}
.air2 img{
    border-radius: 50%;
    
}
.contam2{
    display: flex;
    flex-direction: row;
    border:solid #024f75;
  background-color: #1b305f;
    justify-content: center;
    align-items: center;
    padding-left: 1rem;
    
    
    column-gap: 0.5rem;
    
}
.contam2 img{
    
    border-radius: 80%;
    
}

/* footer */
/*FOOTER*/

footer {
   background-image: url(img/covid.jpg);
   background-position: center;
   background-repeat: no-repeat;
   background-size: cover;
    /* background: -webkit-linear-gradient(59deg, #3A6073, #16222A);
    background: linear-gradient(59deg, #3A6073, #16222A); */
    
    color: white;
    height: 250px;
    width: 100%;
  }
  
  .cp{
    color:white;
    font-size: 20px;
    font-family: Georgia, 'Times New Roman', Times, serif;
  }
  footer a {
    color: white;
    font-size: 14px;
    transition-duration: 0.2s;
  }
  
  footer a:hover {
    color: #FA944B;
    text-decoration: none;
  }
  
  .copy {
    font-size: 12px;
    padding: 10px;
    border-top: 1px solid black;
  }
  
  .footer-middle {
    padding-top: 2em;
    color: white;
  }
  
  
  
  </style>
  <body>
    <div class="nav">
        <div class="container">
          
        
        
        <div class="logo">
          
          <img class ="logo1" src="img/logo1.png" alt="">
          <div class="menu">
            <nav class="navbar navbar-expand-lg">
              <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                  <a class="nav-link active" href="Home.html"
                    >Home <span class="sr-only"></span
                  ></a>
                  <a class="btn-btn-primary" href="login_form.html" role="button">login</a>
                </div>
              </div>
            </nav>
          </div>
        </div>
    
        <div class="text">
          <div class="col-lg-6">
            <div class="text1">
              <h1>Corona Virus</h1>
              <p>
                COVID-19 is the disease caused by SARS-CoV-2, the coronavirus that
               
                emerged in December 2019. COVID-19 can be severe, and has caused
                
                millions of deaths around the world as well as lasting health 
                problems in some who have survived the illness. The coronavirus
               
                can be spread from person to person. It is diagnosed with a test.
              </p>
              <!-- <a
                href="https://www.hopkinsmedicine.org/health/conditions-and-diseases/coronavirus"
                ><input type="button" value="Learn More" class="btn1"
              /></a> -->
            </div>
          </div>
          <div class="col-lg-6">
            <div class="imge">
              <img
                src="img/1a1c168b61d7b946862e8c519bcb81dfa4585ab5-2640x2640-removebg-preview.png" 
                
                alt="" class="img-fluid"
              
              />
            </div>
          </div>
          
          
        </div>
      </div>
      </div>
    </div>
    
    
    
      <div class="hero">
        
        <div class="container">
          <br>
          <h1 class="text-center  ">How Virus Spread</h1>
          <div class="row">
            <div class="col-lg-6">
              <div class="tethero">
                <h1>How Contagion Coronavirus</h1>
                <p>
                  The virus is thought to spread primarily from person-to-person
                  via respiratory droplets produced when an infected person coughs
                  or sneezes, which when inhaled enter the mouths or noses of
                  people who are nearby, or possibly inhaled into the lungs.
                </p>
                <div class="human">
                  <img src="img/hd.jpg" style="height: 80px;width: 90px;"/>
                  <div class="tx">
                      <h4>Human Contact</h4>
                  <p>
                    oronavirus spread through a handshake Or by sharing shopping
                    carts or subway hanging straps
                  </p>
                  </div>
                  
                </div>
                <br>
                <div class="human" >
                  <img src="img/air.png" style="height: 80px;width: 90px;" alt="ab-thumb" />
                  <div class="tx">
                      <h4>Air Transmission</h4>
                  <p>
                    Our comprehensive Online Marketing strategy will boost your
                    website trafic hence monthly sales.
                  </p>
                  </div>
                  
                </div>
                <br>
                <div class="human">
                  <img src="img/foods.jpg" style="height: 80px;width: 90px;" alt="ab-thumb" />
                  <div class="tx">
                      <h4>Contaminated Objects</h4>
                  <p>
                    Our comprehensive Online Marketing strategy will boost your
                    website trafic hence monthly sales.
                  </p>
                  </div>
                  
                </div>
              </div>
            </div>
            <div class="col-lg-6">
              <div class="contimg">
                <img src="img/hero-removebg-preview.png" alt="" height="550px" width="100%" class="img-fluid" />
    
              </div>
              
            </div>
            
          </div>
          <br>
        </div>
      </div>
    
    
       <div class="symptoms">
          <div class="container">
              <br>
              <h1 class="id text-center mt-2">Corona Virus Symptoms</h1>
              
              <div class="row">
                  <div class="col-lg-6 col-12 mt-5">
                  <div class="div1 col ">
                      <div class="imgs">
                          <img src="img/01.jpg" height="100px" alt="">
                      </div>
                      <div class="content">
                          <h5>Coughing And Sneezing</h5>
                          <p>Sneezes can spread disease, including COVID-19, through infectious aerosol droplets.</p>
                      </div>
                  </div>
                  <div class="div3 col mt-2" >
                      <div class="imgs">
                          <img src="img/02.jpg" height="100px" alt= "" s >
                      </div>
                      <div class="content">
                          <h5>Hot Fever</h5>
                          <p> A body temperature of 100.4 degrees F or higher is generally seen in people with COVID-19</p>
                      </div>
                  </div>
                  <div class="div3 col mt-2">
                      <div class="imgs">
                          <img src="img/03.jpg" height="100px" alt="">
                      </div>
                      <div class="content">
                          <h5>Strong Headacke</h5>
                          <p>Headache is one of the earliest and most common symptoms during the acute phase of COVID-19</p>
                      </div>
                  </div>
                  </div>
                  <div class="col-lg-6 col-12 mt-5">
                      <div class="div1">
                          <div class="imgs">
                              <img src="img/04.jpg" height="100px" alt="">
                          </div>
                          <div class="content"> 
                              <h5>Shortness Of Breath</h5>
                              <p> It's a common symptom of COVID-19 its difficulty catching your breath and feel short of breath more easily.</p>
                          </div>
                      </div>
                      <div class="div3 mt-2" >
                          <div class="imgs">
                              <img src="img/05.jpg" height="100px" alt="">
                          </div>
                          <div class="content">
                              <h5>Confusion</h5>
                              <p>Mental confusion, disorientation may be early warning sign of severe COVID-19 </p>
                          </div>
                      </div>
                      <div class="div3 mt-2">
                          <div class="imgs">
                              <img src="img/06.jpg" height="100px" alt="">
                          </div>
                          <div class="content">
                              <h5>Sore Throat</h5>
                              <p> The sore throat appears together with other symptoms of a COVID-19</p>
                          </div>
                      </div>
                      <br><br>
                      </div mt-5>
                  </div>
              </div>
          </div>
        </div>
    
           <div class="about">
            
            <div class="container">
              <div class="row">
                <div class="col-lg-6 col-12 mt-5">
                  <h1 >Prevention Coronavirus</h1>
                  <p>Important Prevention · Avoid Crowded Places (Social Distancing) · Wear a Face Mask · Cover Mouth when Coughing · Wash Hand Frequently · Seek Medical Care ·</p>
                  <div class="div2">
                    <div class="imgs">
                        <img src="img/07.jpg" height="100px" alt="">
                    </div>
                    <div class="content">
                        <h5>Wash Your Hands For 20sec</h5>
                        <p> washing your hands is a key part of preventing the spread of viruses such as the coronavirus</p>
                    </div>
                </div><div class="div2 mt-2">
                  <div class="imgs">
                      <img src="img/08.jpg" height="100px" alt="">
                  </div>
                  <div class="content">
                      <h5>Cover Nose and Mouth When Sneezing</h5>
                      <p>One sneeze can carry up to 100,000 viruses and bacteria. 
                        so covering your mouth and nose appropriately.</p>
                  </div>
              </div><div class="div2 mt-2">
                <div class="imgs">
                    <img src="img/09.jpg" height="100px" alt="">
                </div>
                <div class="content">
                    <h5>Wear A Mask If Available</h5>
                    <p>Wearing a mask is an easy way to reduce the risk of unknowingly spreading the infection</p>
                </div>
                
            </div>
            <br><br>
                </div>
                <div class="col-lg-6 col-12 mt-5">
                  <div class="pre">
                    <img src="img/wash.png"  width="100%" height="500" alt="">
                  </div>
                  <br>
                </div>
                
              </div>
            </div>
          </div> 

          <div class="wash">
            <div class="container">
              <br>
              <h1 class="text-center">How to Wash Your Hands</h1>
              <div class=" wd mt-5">
                <div class="row">
                  <div class="col-lg-3 col-6 ">
                  <div class="ab">
                    <div class="stp1 ">
                      <img src="img/10.jpg"   height="100px" width="50%">
                      <div class="cont">
                        <h6>Wet Hands</h6>
                      </div>
                      
                    </div>
                  </div>
                </div>
                <div class="col-lg-3 col-6">
                  <div class="ab">
                    <div class="stp1 ">
                      <img src="img/11.jpg"   height="100px" width="50%">
                      <div class="cont">
                        <h6>Apply Soap</h6>
                      </div>
                     
                    </div>
                    
                  </div>
                </div>
                <div class="col-lg-3 col-6">
                  <div class="ab">
                    <div class="stp1">
                      <img src="img/12.jpg"   height="100px" width="50%">
                      <div class="cont">
                        <h6>Rub Hands Palm to palm</h6>
                      </div>
                      
                    </div>
                  </div>
                </div>
                <div class="col-lg-3 col-6">
                  <div class="ab">
                    <div class="stp1">
                      <img src="img/13.jpg"   height="100px" width="50%">
                      <div class="cont">
                        <h6>Lather The Back  of Both Hands</h6>
                      </div>
                      
                    </div>
                  </div>
                </div>
                </div>
                
              </div> 
          </div>
          <br>
          <div class="container">
          
            <div class=" wd mt-3">
              <div class="row">
                <div class="col-lg-3 col-6 ">
                <div class="ab">
                  <div class="stp1 ">
                    <img src="img/14.jpg"   height="100px" width="50%">
                    <div class="cont">
                      <h6>Scrub Between Your Fingers</h6>
                    </div>
                    
                  </div>
                </div>
              </div>
              <div class="col-lg-3 col-6">
                <div class="ab">
                  <div class="stp1 ">
                    <img src="img/15.jpg"   height="100px" width="50%">
                    <div class="cont">
                      <h6>Rub The Back of Fingers on The Opposing Palm</h6>
                    </div>
                   
                  </div>
                  
                </div>
              </div>
              <div class="col-lg-3 col-6">
                <div class="ab">
                  <div class="stp1">
                    <img src="img/16.jpg"   height="100px" width="50%">
                    <div class="cont">
                      <h6>Clean Thumbs</h6>
                    </div>
                    
                  </div>
                </div>
              </div>
              <div class="col-lg-3 col-6">
                <div class="ab">
                  <div class="stp1">
                    <img src="img/17.jpg"   height="100px" width="50%">
                    <div class="cont">
                      <h6>Wash Fingernails And Fingertips</h6>
                    </div>
                    
                  </div>
                </div>
              </div>
              </div>
              
            </div> 
        </div>
        <br>
        <div class="container">
          
          <div class=" wd mt-3">
            <div class="row">
              <div class="col-lg-3 col-6 ">
              <div class="ab">
                <div class="stp1 ">
                  <img src="img/18.jpg"   height="100px" width="50%">
                  <div class="cont">
                    <h6>Rinse Hands</h6>
                  </div>
                  
                </div>
              </div>
            </div>
            <div class="col-lg-3 col-6">
              <div class="ab">
                <div class="stp1 ">
                  <img src="img/19.jpg"   height="100px" width="50%">
                  <div class="cont">
                    <h6>Dry with a Single Use Towel</h6>
                  </div>
                 
                </div>
                
              </div>
            </div>
            <div class="col-lg-3 col-6">
              <div class="ab">
                <div class="stp1">
                  <img src="img/20.jpg"   height="100px" width="50%">
                  <div class="cont">
                    <h6>Use The Towel to Rurn off The Foucet</h6>
                  </div>
                  
                </div>
              </div>
            </div>
            <div class="col-lg-3 col-6">
              <div class="ab">
                <div class="stp1">
                  <img src="img/21.jpg"   height="100px" width="50%">
                  <div class="cont">
                    <h6>Your Hands Are Clean</h6>
                  </div>
                  
                </div>
              </div>
            </div>
            </div>
            
          </div> 
      </div>
      <br>
        </div>


        
        
        
           
    
           
         <!-- Footer -->
         <footer class="mainfooter" role="contentinfo">
          <div class="footer-middle">
          <div class="container">
            <div class="row">
              <div class="col-md-3 col-sm-6"> 
                <!--Column1-->
                 <div class="footer-pad">
                  <h4>Covid-19</h4>
                  <ul class="list-unstyled">
                    <li><a href="#"></a></li>
                    <li><a href="Home.html">Home</a></li>
                    <li><a href="login_form.html">login</a></li>
                   
                  </ul>
                </div>
              </div>
              <div class="col-md-3 col-sm-6">
                <!--Column1-->
               
             </div>
              <div class="col-md-3"></div>
              <div class="col-md-3">
                <div class="footer-pad">
                  <h4>Follow Us</h4><br><br><br>
            </div>
          <div class="row">
            <div class="col-md-12 copy">
              <p class=" cp text-center">  &copy; Copyright </p>
            </div>
          </div> 
        
        
           </div>
          </div>
        </footer> 

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: jQuery and Bootstrap Bundle (includes Popper) -->
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-Fy6S3B9q64WdZWQUiU+q4/2Lc9npb8tCaSX9FK7E8HnRr0Jz8D6OP9dO5Vg3Q9ct" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.min.js" integrity="sha384-+sLIOodYLS7CIrQpBjl+C7nPvqq+FbNUBDunl/OZv93DB7Ln/533i8e/mZXLi/P+" crossorigin="anonymous"></script>
    -->
  </body>
</html>



foam code

<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Login Form</title>
   <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
   <style>
      body {
         background-color: #f0f0f0;
         display: flex;
         justify-content: center;
         align-items: center;
         height: 100vh;
      }

      .login-container {
         background-color: #fff;
         padding: 20px;
         border-radius: 10px;
         box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
         width: 100%;
         max-width: 400px;
      }

      .login-container h1 {
         font-size: 24px;
         margin-bottom: 20px;
         text-align: center;
      }

      .login-container img {
         display: block;
         margin: 0 auto;
         border-radius: 50%;
         margin-bottom: 20px;
      }

      .login-container form {
         margin-bottom: 0;
      }

      .login-container label {
         display: block;
         margin-bottom: 8px;
         font-weight: bold;
      }

      .login-container input[type="email"],
      .login-container input[type="password"] {
         width: 100%;
         padding: 10px;
         margin-bottom: 15px;
         border: 1px solid #ccc;
         border-radius: 5px;
      }

      .login-container button[type="submit"] {
         width: 100%;
         padding: 10px;
         background-color: #007bff;
         border: none;
         border-radius: 5px;
         color: #fff;
         font-size: 16px;
         cursor: pointer;
         transition: background-color 0.3s;
      }

      .login-container button[type="submit"]:hover {
         background-color: #0056b3;
      }

      .login-container .error-msg {
         color: red;
         font-size: 14px;
         margin-top: 10px;
      }

   </style>
</head>
<body>

<div class="login-container">
   <h1>Login Now</h1>
   <img src="./img/login.png" alt="Login Image" width="150">
   <form action="" method="post">
      <label for="email">Email</label>
      <input type="email" id="email" name="email" required placeholder="Enter your email">

      <label for="password">Password</label>
      <input type="password" id="password" name="password" required placeholder="Enter your password">

      <button type="submit" name="submit">Login</button>
   </form>
   <p>Don't have an account? <a href="register_form.php">Register Now</a></p>
</div>

</body>
</html>
