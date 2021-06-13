
<html lang="en">

  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">


    
    <link ref="stylesheet" href="./style.css">

</head>
<body>
    <section class="filter py-5">
      <div class="container py-5">
        <div class="row">
          <div class="col-lg-8 m-auto">
            <div class="controls text-center">
                <button class="btn1" data-filter="all">All</button>
                <button class="btn1" data-filter=".tableau">Tableau</button>
                <button class="btn1" data-filter=".datastudio">Data Studio</button>
                <button class="btn1" data-filter=".mapbox">Mapbox</button>
            
            </div>
           </div>
          </div>
      <div class="row py-5">
             <div class="col-lg-3 pb-2 mix tableau">
               <img src="https://Michellehlcn.github.io/Homepage/image2.jpeg" border="0" class="img-fluid" alt=""></div>
          
            <div class="col-lg-3 pb-2 mix tableau">
                <img src="https://Michellehlcn.github.io/Homepage/image2.jpeg" border="0" class="img-fluid" alt=""></div>
            
            <div class="col-lg-3 pb-2 mix datastudio">
                <img src="https://Michellehlcn.github.io/Homepage/image1.jpeg" border="0" class="img-fluid" alt=""></div>
            
            <div class="col-lg-3 pb-2 mix mapbox">
            	<img src="https://Michellehlcn.github.io/Homepage/image0.jpeg" border="0" class="img-fluid" alt=""></div>
            
            <div class="col-lg-3 pb-2 mix tableau">
                <img src="https://Michellehlcn.github.io/Homepage/image2.jpeg" border="0" class="img-fluid" alt=""></div>
            
            <div class="col-lg-3 pb-2 mix tableau">
                <img src="https://Michellehlcn.github.io/Homepage/image2.jpeg" border="0" class="img-fluid" alt=""></div>
            
            <div class="col-lg-3 pb-2 mix tableau">
                <img src="https://Michellehlcn.github.io/Homepage/image2.jpeg" border="0" class="img-fluid" alt=""></div>   
        
	    <div class="col-lg-3 pb-2 mix tableau">
                <img src="https://Michellehlcn.github.io/Homepage/image2.jpeg" border="0" class="img-fluid" alt=""></div>   
          </div>
         </div>
      
      
     </section>

 
  <footer>
  <p><center>Made by <a href="http://michellehlcn.wordpress.com">@Michellehlcn</a>
	  <br>Built with Bootstraps and Mixitup.</br></center></p>
</footer>

<script src="https://cdnjs.cloudflare.com/ajax/libs/mixitup/3.3.1/mixitup.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mixitup/3.3.1/mixitup.js"></script>
   
     <script> 
        	 var containerA1 = document.querySelector('.container');
           
           var mixer=mixitup(containerA1);
        </script>

  </body>
  <style>
  
*{
	padding:0; 
    box-sizing: border-box;
    
margin:0; 
  }
  
.btn1{
    height: 50px;
    width: 20%;
    background: #000000;
    color: #FFFFFF;
    outline: none;
    border: none;
    cursor: pointer;
}
.bnt1:hover{
  color: #000000;
  background: #FFFFFF;
  border: 2px solid #000000;
  transition: 0.5s;
}  

  </style>
</html>
