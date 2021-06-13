
<html lang="en"> 
  <head>
  <meta charset="UTF-8">
	  title: false
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.0.1/css/bootstrap.min.css">
  <link rel="stylesheet" href="style.css">
  </head>

  <body>
    <section class="work-box">
      <div class="container">
        <div class="row">

          <div class="col-lg-12">
            <div class="box-menu">
              <ul>
                <li class="mixitup-control-active" data-filter="*">All</li>
                <li data-filter=".mapbox">Mapbox</li>
                <li data-filter=".tableau">Tableau</li>
                <li data-filter=".datastudio">Data Studio</li>
              </ul>
            </div>
          </div>
        </div>
        <div class="row box-list">
          <div class="col-lg-4 mix box-item tableau">
            <img src="https://Michellehlcn.github.io/Homepage/image2.jpeg" border="0" class="img-fluid" alt=""></div>

          <div class="col-lg-4 mix box-item tableau">
            <img src="https://Michellehlcn.github.io/Homepage/image2.jpeg" border="0" class="img-fluid" alt=""></div>

          <div class="col-lg-4 mix box-item datastudio">
            <img src="https://Michellehlcn.github.io/Homepage/image1.jpeg" border="0" class="img-fluid" alt=""></div>

          <div class="col-lg-4 mix box-item mapbox">
            <img src="https://Michellehlcn.github.io/Homepage/image0.jpeg" border="0" class="img-fluid" alt=""></div>

          <div class="col-lg-4 mix box-item tableau">
            <img src="https://Michellehlcn.github.io/Homepage/image2.jpeg" border="0" class="img-fluid" alt=""></div>

          <div class="col-lg-4 mix box-item tableau">
            <img src="https://Michellehlcn.github.io/Homepage/image2.jpeg" border="0" class="img-fluid" alt=""></div>

          <div class="col-lg-4 mix box-item tableau">
            <img src="https://Michellehlcn.github.io/Homepage/image2.jpeg" border="0" class="img-fluid" alt=""></div>

          <div class="col-lg-4 mix box-item tableau">
            <img src="https://Michellehlcn.github.io/Homepage/image2.jpeg" border="0" class="img-fluid" alt=""></div>
        </div>

      </div>

     
    </section>





    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mixitup/3.3.1/mixitup.min.js"></script>

    <script>
      $(document).ready(function() {
            var mixer = mixitup('.box-list');
});
    </script>



<style>
header{
  display: none;
}
.box-item{
  margin-bottom: 30px;
}
img{
  max-width: 100%;
}
.box-item img{
  height: 100%;
  max-height: 300px;
  width: 100%;
  object-fit: cover;
}
.box-menu{
  text-align: center;
}
.box-menu ul{
  padding: 0;
  margin: 0;
  list-style: none;
}
.box-menu ul li{
  font-weight: bold;
  text-transform: uppercase;
  border-radius:50px;
  cursor: pointer;
  margin-bottom: 60px;
  margin: 34px 4px;
  background: darkorange;
  font-size:18px;
  padding: 10px 30px;
  display: inline-block;
  color: #fff;
}
.box-menu ul li.mixitup-control-active{
  background: #000;
}
</style>
</body>
   <footer>
  <p><center>Made by <a href="http://michellehlcn.wordpress.com">@Michellehlcn</a>
	  <br>Built with Bootstraps and Mixitup.<br></center></p>
</footer>
</html>
