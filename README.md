# stonecap-project
Html CSS code build
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  
  <title>Frontend Mentor | Order summary card</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
    @import url('https://fonts.googleapis.com/css2?family=Red+Hat+Display:wght@500;700;900&display=swap');

body {background-image: url("images/pattern-background-desktop.svg"); 
      background-repeat: no-repeat;
      font-family: 'Red Hat Display', sans-serif;
}

.container {
    display:flex;
    justify-content: center;
}
.order-summary-body {
    
    width: 449px;
}
.order-summary-details {
    display:flex;
    flex-direction: column;
    background: #fff;
  
    padding: 0 2em;
}

.order-summary-description h2,p {
    text-align: center;
    
}
 
.order-summary-description h2 {
font: weight 900px; 
}
 .order-summary-description p {
     font-size: 16px;
     color:hsl(224, 23%, 55%) ;
     
 }
 .order-pricing {
     display: flex;
     margin-right: auto;
     align-items: center;
     margin-left: 2em;
     
 }

 .payment {
     display:flex;
     flex-direction: column;
      align-items: center;
      background-color:#A800FF;
      border-radius: 25px;
     

 }
.plans {
    font-size: 0.6rem;
    margin-left: 2em;
    margin-right:auto;
}
  
  </style>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <div class="order-summary-body">
      <div><img src="images/illustration-hero.svg" alt=""></div>
      <div class="order-summary-details">
        <div class="order-summary-description">
          <h2>Order Summary</h2>
          <p>You can now listen to millions of songs, audiobooks, and podcasts on any 
            device anywhere you like!
          </p>
          
        </div>
        <div class="order-pricing">
          <img src="images/icon-music.svg" alt="">
           <div class="plans">
             <h2>Annual Plan</h2> 
             <h2>$59.99/year</h2>
           </div>
             <div>
                <a href="#">Change</a>
  
             </div>
     
            
        </div>
        <div class="payment">
          <button>Proceed to Payment</button>
         
         </div>
      </div>
    </div>
    
  

    <!-- <div class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
      Coded by <a href="#">Your Name Here</a>.
    </div>   -->
 
</body>
</html>
