<html lang="en">
<title>CSAP Insights</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<style>
body {
  font-family: "Lato", sans-serif;
  background-image: url("https://user-images.githubusercontent.com/64637338/81293350-dbb70700-9075-11ea-9a71-cd2750c6a733.png");
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: 300px 100px;
    }
.mySlides {display: none}

</style>



<body>

<!-- Navbar -->
<div class="w3-top">
  <div class="w3-bar w3-green w3-card">
    <a class="w3-bar-item w3-button w3-padding-large w3-hide-medium w3-hide-large w3-right" href="javascript:void(0)" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large">Home</a>


    <div class="w3-dropdown-hover w3-hide-small">
      <button class="w3-padding-large w3-button" title="More">Follow us <i class="fa fa-caret-down"></i></button>     
      <div class="w3-dropdown-content w3-bar-block w3-card-4">
    <a href="https://facebook.com/csapofficial" class="w3-bar-item w3-button w3-padding-large w3-hide-small">Facebook</a>
    <a href="https://twitter.com/csapofficial" class="w3-bar-item w3-button w3-padding-large w3-hide-small">Twitter</a>
    <a href="https://t.me/csapofficial" class="w3-bar-item w3-button w3-padding-large w3-hide-small">Telegram</a>
    
      </div>
    </div>    
      </div>
 
    <a href="javascript:void(0)" class="w3-padding-large w3-hover-red w3-hide-small w3-right"></a>
  </div>



<!-- Page content -->
<div class="w3-content" style="max-width:2000px;margin-top:46px"></div>

  <!-- Welcome note -->
  <div class="w3-container w3-content w3-center w3-padding-64" style="max-width:800px" id="band">
    <h2 class="w3-wide">WELCOME</h2>
    <p class="w3-justify">We believe in sharing knowledge as it enables the communities for a better future. Here you would be able to read whitepapers, researchpapers, articles etc.</p>



  <!-- Whitepapers -->
  <div class="w3-light-gray" id="tour">
    <div class="w3-container w3-content w3-padding-64" style="max-width:800px">
      <h2 class="w3-wide w3-center">PUBLICATIONS</h2>
      <p class="w3-opacity w3-center"><i>Read and share the link with others</i></p><br>


      <div class="w3-row-padding w3-padding-32" style="margin:0 -16px">
        <div class="w3-third w3-margin-bottom">
        
            <!-- Whitepaper 1 - ORASP -->
          <img src="https://user-images.githubusercontent.com/64637338/81332134-3e76c580-90ab-11ea-8933-193334dc59e6.png" alt="ORASP" height="110" width="85" class="w3-hover-opacity">
          <div class="w3-container w3-white" >
            <p><b>ORASP</b></p>
            <p class="w3-opacity">Whitepaper</p>
            <p>Open Reference Architecture for Security & Privacy. Security should be a journey, and not an expensive one...</p>
            <button class="w3-button w3-green w3-margin-bottom">coming soon</button>
          </div>
        </div>
        <div class="w3-third w3-margin-bottom">
        
        
        
        
            <!-- Whitepaper 2 - Video conferencing considerations - security guidelines--> 
          <img src="https://user-images.githubusercontent.com/64637338/81333756-b3e39580-90ad-11ea-9329-c9309c1621d8.png" alt="Video Conferencing Considerations" height="110" width="95" class="w3-hover-opacity">
          <div class="w3-container w3-white" >
            <p><b>Video Conferencing</b></p>
            <p class="w3-opacity">Whitepaper</p>
            <p>Considerations: With the emerging need of using video conferencing service, comes various challenges with...</p>
            <button class="w3-button w3-green w3-margin-bottom">coming soon</button>
          </div>
        </div>
        <div class="w3-third w3-margin-bottom">
        
        
        
            
          </div>
        </div>
      </div>
    </div>
  </div>





  <!-- Ticket Modal -->
  <div id="ticketModal" class="w3-modal">
    <div class="w3-modal-content w3-animate-top w3-card-4">
      <header class="w3-container w3-teal w3-center w3-padding-32"> 
        <span onclick="document.getElementById('ticketModal').style.display='none'" 
       class="w3-button w3-teal w3-xlarge w3-display-topright">×</span>
        <h2 class="w3-wide"><i class="fa fa-suitcase w3-margin-right"></i>Tickets</h2>
      </header>
      <div class="w3-container">
        <p><label><i class="fa fa-shopping-cart"></i> Tickets, $15 per person</label></p>
        <input class="w3-input w3-border" type="text" placeholder="How many?">
        <p><label><i class="fa fa-user"></i> Send To</label></p>
        <input class="w3-input w3-border" type="text" placeholder="Enter email">
        <button class="w3-button w3-block w3-teal w3-padding-16 w3-section w3-right">PAY <i class="fa fa-check"></i></button>
        <button class="w3-button w3-red w3-section" onclick="document.getElementById('ticketModal').style.display='none'">Close <i class="fa fa-remove"></i></button>
        <p class="w3-right">Need <a href="#" class="w3-text-blue">help?</a></p>
      </div>
    </div>
  </div>

  <!-- The Contact Section 
  <div class="w3-container w3-content w3-padding-64" style="max-width:800px" id="contact">
    <h2 class="w3-wide w3-center">CONTACT</h2>
    <p class="w3-opacity w3-center"><i>Get in touch with us</i></p>
    <div class="w3-row w3-padding-32">
      <div class="w3-col m6 w3-large w3-margin-bottom">
        <i class="fa fa-map-marker" style="width:30px"></i> Global chapters<br>
      </div>
      <div class="w3-col m6">
        <form action="/action_page.php" target="_blank">
          <div class="w3-row-padding" style="margin:0 -16px 8px -16px">
            <div class="w3-half">
              <input class="w3-input w3-border" type="text" placeholder="Name" required name="Name">
            </div>
            <div class="w3-half">
              <input class="w3-input w3-border" type="text" placeholder="Email" required name="Email">
            </div>
          </div>
          <input class="w3-input w3-border" type="text" placeholder="Message" required name="Message">
          <button class="w3-button w3-black w3-section w3-right" type="submit">SEND</button>
        </form>
      </div>
    </div>
  </div>-->
  
<!-- End Page Content -->



<!-- Footer -->
<footer class="w3-container w3-padding-64 w3-center w3-opacity w3-pale-green w3-xlarge">
  <a href="https://facebook.com/csapofficial"><i class="fa fa-facebook-official w3-hover-opacity"></i>
  <a href="https://twitter.com/csapofficial"><i class="fa fa-twitter w3-hover-opacity"></i>
  
  <a href="#"><p class="w3-medium">Powered by CSAP</p>
