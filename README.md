<!DOCTYPE html>
<html>
  <head>
    <title>Soil Pollution Website</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
      /* CSS styling */
      body {
        font-family: Arial, sans-serif;
        background-color: #cfcccc;
        color: rgb(158, 156, 156);
        margin: 0;
        padding: 0;
      }

      header {
        background-color: #444;
        color: #fff;
        padding: 10px;
        display: flex;
        justify-content: space-between;
        align-items: center;
      }

      header h1 {
        margin: 0;
      }

      header nav ul {
        list-style-type: none;
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin: 0;
        padding: 0;
      }

      header nav ul li {
        margin: 0 10px;
      }

      header nav ul li a {
        color: #fff;
        text-decoration: none;
        font-size: 16px;
      }

      section {
        background-color: rgb(158, 156, 156);
        padding: 20px;
        margin-bottom: 20px;
      }

      section h2 {
        font-size: 28px;
        margin-top: 0;
        color: #444;
        text-align: center;
        text-transform: uppercase;
        letter-spacing: 3px;
      }

      section ul {
        list-style-type: disc;
        margin-left: 20px;
      }

      footer {
        background-color#444;
        color: #fff;
        padding: 10px;
        text-align: center;
      }

      footer p {
        margin: 0;
      }

      .container {
        display: flex;
        background-color: #444;
        justify-content: space-around;
        align-items: center;
        padding: 10px;
        text-align: center;
      }

      .container a {
        color: #fff;
        text-decoration: white;
        font-size: 16px;
        text-transform: uppercase;
        letter-spacing: 2px;
      }

      img {
        display: block;
        margin: auto;
        max-width: 100%;
        height: auto;

      }      .slideshow-container {
        max-width: 800px;
        position: relative;
        margin: auto;
      }
      .mySlides {
        display: none;
        width: 100%;
      }
      .prev, .next {
        position: absolute;
        top: 50%;
        width: auto;
        margin-top: -22px;
        padding: 16px;
        color: white;
        font-weight: bold;
        font-size: 24px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
      }
      .next {
        right: 0;
        border-radius: 3px 0 0 3px;
      }
      .prev:hover, .next:hover {
        background-color: rgba(0,0,0,0.8);
      }
      
      /* CSS for Images */
      .image-container {
        width: 100%;
        height: 400px;
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center;
      }
      #img1 {
        background-image: url('https://greentumble.com/wp-content/uploads/2016/12/How-to-Improve-Soil-Fertility-Naturally.jpg');
      }
      #img2 {
        background-image: url('https://cached.imagescaler.hbpl.co.uk/resize/scaleWidth/952/cached.offlinehbpl.hbpl.co.uk/news/WOH/645959D7-A504-AFF3-D87DC87401F55DFE.gif')}
      #img3 {
        background-image: url('https://media.tenor.com/_u6ZSnZhbjYAAAAd/soil-dig.gif');
      }
      #img4 {
        background-image: url('https://www.groundwatercatalogue.org/sites/default/files/styles/6_4/public/2021-07/desertification.jpg?itok=R29XC2mU');
      }
      
      .imagess{
        display:flex;
        justify-content: space-between;

        height: 400px;
        width: 350px;
         
        }
        .mainn{
          
          justify-content: space-evenly;
          
        }
        .one{
        color: #333030;
        font-family:
      }
      .two{
        color: #902799;
        text-align: left;
      }
      .question{
          text-align: left;
        }
        .answer{
          text-align:middle;
          color: #333030;}
        .nin{
        display: flex;
        border: #333030;
    }
    .button{
      padding-top: 14%;
    }
       
    /* Define button style */
    .my-button {
      background-color: blue;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    /* Define hover effect */
    .my-button:hover {
      background-color: rgb(81, 238, 147);
     
      

    }


    </style>
  <body>
    <header>
      <h1>Soil Pollution</h1>
      <nav>
        <ul>
          <li><a href="">What is Soil Pollution?</a></li>
          <li><a href="file:///C:/Users/Shreyansh/Desktop/che%20project/part2chee.html">Causes of Soil Pollution</a></li>
          <li><a href="file:///C:/Users/Shreyansh/Desktop/che%20project/part3cheee.html">Effects of Soil Pollution</a></li>
          <li><a href="file:///C:/Users/Shreyansh/Desktop/che%20project/part4chee.html">How to Prevent Soil Pollution</a></li>
        </ul>
      </nav>
    </header>
    <main>
        <div class="slideshow-container">
            <div class="image-container mySlides" id="img1">
              <div class="caption"></div>
            </div>
            <div class="image-container mySlides" id="img2">
              <div class="caption"></div>
            </div>
            <div class="image-container mySlides" id="img3">
              <div class="caption"></div>
            </div>
            <div class="image-container mySlides" id="img4">
              <div class="caption"></div>
            </div>
            <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
            <a class="next" onclick="plusSlides(1)">&#10095;</a>
          </div>
          <script>
            // Javascript for Slideshow
            var slideIndex = 1;
            showSlides(slideIndex);
            function plusSlides(n) {
              showSlides(slideIndex += n);
            }
            function showSlides(n) {
              var i;
              var slides = document.getElementsByClassName("mySlides");
              if (n > slides.length) {
                slideIndex = 1
              }
              if (n < 1) {
                slideIndex = slides.length
              }
              for (i = 0; i < slides.length; i++) {
                slides[i].style.display = "none";
              }
              slides[slideIndex-1].style.display = "block";
            }
          </script>
      
      <section id="what-is-soil-pollution">
      
        <h2 class="two">What is Soil Pollution?</h2>
        <p class="one" >Soil pollution is the presence of toxic chemicals, pollutants, or contaminants in the soil that can have negative impacts on the environment and
            pollution is the presence of toxic chemicals, pollutants, or contaminants in the soil that can have negative impacts on the environment and human health. It occurs when harmful substances are added to soil, reducing its quality and fertility. Sources of soil pollution include industrial activities, agricultural practices, waste disposal, mining, and transportation.

            Soil pollution can have significant environmental impacts, including reduced crop yields, loss of biodiversity, and contamination of water and air. It can also pose serious health risks to humans and animals, causing respiratory problems, skin irritations, and even cancer. Soil pollution can affect entire ecosystems and can take years to remediate.
            
            <div class="passage">
              <h2 class="question" color="green">What are the Pollutants that Contaminate Soil?</h2>
              <li class="answer">Some of the most hazardous soil pollutants are xenobiotics  substances that are not naturally found in nature and are synthesized by human beings. The term ‘xenobiotic’ has Greek roots – ‘Xenos’ (foreigner), and ‘Bios’ (life). Several xenobiotics are known to be carcinogens. An illustration detailing major soil pollutants is provided below.</li>
              <img src="https://cdn1.byjus.com/wp-content/uploads/2018/07/Pollutants-that-Contaminate-Soil.png">
            </div></p>
          <h2> JOIN US </h2>
        <div class="nin">
          <img src="https://www.datocms-assets.com/46272/1638990473-1638990472556.jpg?auto=format&fit=max&w=1200" height="600" width="70%">
          <div class=" button">
          <a href="file:///C:/Users/Shreyansh/Desktop/che%20project/contactchee.html"><button  class="my-button" height="28px" width="26px" >contact<br> us!</button > </a></div>
        </div>
      </section>
     
    </main>
    <footer>
        <div class="container">
              
                    <ul>
                    <h3 style="color: #fff ; font-weight :900">About Us </h3>     
                       <li><p style="color: #fff; font-weight :500">Our mission is to bring healthcare and hygene to every house. We are committed to the achievement and maintenance of excellence in  delivering excellent information and keep you aware about environment”</p></li>
                 
                    </ul>
                    
                    
                    <ul>
                        <h3 style="color: #fff ; font-weight :900">Useful Links</h3>
                        <li><a style="color: #fff ; font-weight :500" href="#">About Us</a></li>
                        <li><a style="color: #fff ; font-weight :500"href="#">Terms & Conditions</a></li>
                        <li><a style="color: #fff ; font-weight :500" href="#">Privacy Policy </a></li>
                    </ul>
               
               
                
             
                    <ul>
                    <h3 style="color: #fff ; font-weight: 900">Our Newslatter</h3>
                  
                  <section>
                      <li><p style=" color: #fff ; font-weight:500">
                      Subscribe to keep up with fresh news and exciting updates. We promise not to spam you!
                    </p></li>
                </section>
                  <footer>
                    <input style="margin-top: 10;" type="email"  name="email" placeholder="Your Email..">                                <button style="margin-top: 10px;" type="button" class="btn btn-info">Subscribe</button>
                  </footer>
                  </ul>
                  </div>
</footer>
</body>
</html>
