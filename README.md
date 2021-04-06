<!DOCTYPE html>
<head>
    <meta name='viewport' content="width=device-width,initial-scale =1">
    <title> parallax_webdesign</title>
    <style>body{
        height: 600px;
        padding: 1% 1% 1% 1%;
    }
    
    .nav{
        background-color: darkslategray;    
        overflow: hidden;
        border-radius: 15px 5px;
        background-position: right bottom, left top;
        background-repeat: no-repeat, repeat;
    
        
    }
    .nav a{
        color: blanchedalmond;
        font-size: 24px;
        float: right;
        padding: 12px 15px;
        word-spacing: 5px;
        text-transform: uppercase;
        text-decoration: none;
        text-shadow: 2px 2px 4px #000000;
    
    }
    .nav a:hover{
        background-color: cadetblue;
        color: cornsilk;
    }
    .nav a.active{
        background-color: darkmagenta;
        color: cornsilk;
    }
    
    .pic1{
        background-image: url("https://wallpapercave.com/wp/wp6998780.jpg");
        height: 100%;
        background-attachment: fixed;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        opacity: 0.75;
    }
    .text{
        text-align: center;
        font-size: 35px;
        top: 50%;
        width: 100%;
        text-transform: uppercase;
        
        position: absolute;
    }
    .text .food{
    background-color: black;
    color: blanchedalmond;
    padding: 20px;
    
    }
    .foodinfo{
        text-align: center;
        background-color: blanchedalmond;
        color: crimson;
        font-size: 30px;
        padding: 30px 60px;
    }
    
    .pic2{
        background-image: url("https://s9c2c8i7.rocketcdn.me/wp-content/uploads/2020/12/pav-bhaji-2020.jpg");
        height: 100%;
        background-attachment: fixed;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        opacity: 0.75;
    }
    
    .pic3{
        background-image: url("https://images.unsplash.com/photo-1601050690597-df0568f70950?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80");
        height: 200%;
        
        background-attachment: fixed;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        opacity: 0.75;
    
    }
    .pic4{
        background-image: url("https://images.unsplash.com/photo-1536184071535-78906f7172c2?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1420&q=80");
        height: 100%;
        background-attachment: fixed;
        background-position: center ;
        background-repeat: no-repeat;
        background-size: cover ;
        opacity: 0.75;
    
    }
    
    footer {
        position: absolute;
        left: 0;
        right: 0;
        padding: 3rem;
        background-color: rgb(24, 197, 76);
        text-align: center;
        font-size: x-large;
        
      }
    
      @media all and (min-width: 100px) and (max-width:1000px) 
      {
          .nav{
              background-color: rgb(113, 201, 207);
          }
          .nav a{
              float: left;
              display: block;
              width: 100%;
          }
          
        .text{
            padding:10px 10px;
            text-align: center;
            font-size: 15px;
        }
        .foodinfo{
            text-align: center;
            background-color: blanchedalmond;
            color: crimson;
            font-size: 20px;
            padding: 20px 40px;
        }
        footer {
            background-color: rgb(243, 240, 44);
            font-size: x-large;
          }
        .pic4{
            background-image: url("https://i1.wp.com/vegecravings.com/wp-content/uploads/2017/01/Fruit-Custard-Recipe-Step-By-Step-Instructions.jpg?fit=2152%2C1748&quality=65&strip=all&ssl=1");
        }
        
      }
    </style>
</head>
<body>
    <div class="nav">
        <a href ="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D-xqaVsLUzOM&psig=AOvVaw3y8cdfySQtndrGB14-c_MQ&ust=1616826526868000&source=images&cd=vfe&ved=2ahUKEwi7jtOnqs3vAhWYFnIKHXwMDcwQr4kDegUIARDGAQ"target="blank">Receips</a>
        <a href="https://www.gloriafood.com/" target="blank">Contact  </a>
        
        <a class="active" href="">home </a>
</div>
   
    <div class="pic1">
    <div class="text"> <span class="food">Faviourte food</span></div></div>
    <section class="foodinfo">
        <h1>PANIPURI</h1>
        <p> Pani puri is a popular street food of India, where crisp fried dough balls (puri) are stuffed with potatoes, sprouts, spicy tangy water or sweet chutney.
        </p>
    </section>
    <div class="pic2"></div>
    <section class="foodinfo">
        <h1>Pav Bhaji</h1>
        <p>Pav bhaji is a popular Indian street food that consists of a spicy mix vegetable mash & soft buns</p>
    </section>
    <div class="pic3">  </div>

    <section class="foodinfo">
        <h1>Samosa</h1>
        <p>The triangular shaped flaky pastry filled with spicy potato, grains spieces sweet filling is a popular snack not only in India but in several countries of the world.</p>
        </section>
        <div class="pic4">  </div>
        <footer>
        <p class="footer"> Please visit Again!!  love <strong><a href ="https://www.instagram.com/549_bharti/" target="blank">BHARTI KUMATH</strong></a>.</p>
    </footer>
        


</body>
</html>
