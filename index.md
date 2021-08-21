<!DOCTYPE html>
  <html>
  <head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
  * {
    box-sizing: border-box;
  }

  .menu {
    float: left;
    width: 20%;
    text-align: center;
  }

  .menu a {
    background-color: #e5e5e5;
    padding: 8px;
    margin-top: 7px;
    display: block;
    width: 100%;
    color: black;
  }

  .main {
    float: left;
    width: 60%;
    padding:  20px;
    
  }

  .right {
    background-color: #e5e5e5;
    float: left;
    width: 20%;
    padding: 15px;
    margin-top: 7px;
    text-align: center;
    bottom: 10;
  }

  @media only screen and (max-width: 620px) {
    /* For mobile phones: */
    .menu, .main, .right {
      width: 100%;
    }
  }
  </style>
  </head>
  <body style="font-family:cursive;color:#270505;   background-image: url('2.png'); height: 50%; vertical-align: baseline; ">

  <div style="background-color:#a3aff1;padding:15px;text-align:center;  ">
    <h1>Fashion World</h1>
  </div>

  <div style="overflow:auto">
    <div class="menu">
      <a href="./home.html"> Home</a>
      <a href="./events.html">Events</a>
      <a href="./contactus.html">Contact Us</a>
      <a href="./services.html">Services</a>
    </div>

    <div class="main" style="color: aqua;">
      <h2>Fashion World</h2>
      <p>Fashion world is a platform where you can put your creativity and get a chance to perform in big shows. Be ready to become a part of something big.</p>
    </div>

    <div class="right">
      <h2>About</h2>
      <p>Here we will collect info of participent wo want to work in media industry.</p>
    </div>
  </div>
 
  <div style="color: blue; background-color: aqua; text-align: center; padding-top: 10; top: 20;">
    Fashion is a form of self-expression and autonomy at a particular period and place and in a specific context, 
    of clothing, footwear, lifestyle, accessories, makeup, hairstyle, and body posture.[1] In its everyday use, the term implies a look defined by the fashion industry as that which is trending. Everything that is considered fashion is available and popular by the fashion system (industry and media).

In reaction to the increased mass-production of commodities clothing at lower prices and global reach, 
sustainability has become an urgent issue among politicians, brands, and consumers.
  </div>

   

  <style>
    .footer {
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: red;
      color: white;
      text-align: center;
    }
    </style>
    
    <div class="footer">
      <p>© fashionworld.in</p>
    </div>
  </body>
  </html>
