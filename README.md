<DOCTYPE! html,html5,css,javascript>
<html lang="en-US">
<title>Stage | TestSite</title>
<head>
<link rel="stylesheet" type="text/css" href="./stylestage.css">
</head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="copyright" content="Luke Hardman">
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
<meta name="mobile-web-app-capable" content="yes">

<body>
<style>
* {
    box-sizing: border-box;
}

.column {
    float: left;
    width: 33.33%;
    padding: 3px;
}
/* Clearfix (clear floats) */
.row::after {
    content: "";
    clear: both;
    display: table;
}
</style>
  <body style="background-color:#000000">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<script>
    $('body').append('<div style="" id="loadingDiv"><div class="loader">Loading...</div></div>');
    $(window).on('load', function(){
      setTimeout(removeLoader, 2000); //wait for page load PLUS two seconds.
    });
    function removeLoader(){
        $( "#loadingDiv" ).fadeOut(100, function() {
          // fadeOut complete. Remove the loading div
          $( "#loadingDiv" ).remove(); //makes page more lightweight
      });
    }
  </script>

    <div id="mySidenav" class="sidenav">
      <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
      <a style="color:#000000">Contact us on:</a>
      <a href="https://www.facebook.com/ian.rice.9085?fb_dtsg_ag=AdxkJJ3X08XIW5qq6Eo6e8OcD9k81-y3f7fbtJiiIG8kIg%3AAdwabORGS1VVeZL5x7IRSBy8k_jhUx9OuJfnnR735wzLnw">Facebook</a>
      <a href="https://www.instagram.com/">Instagram</a>
      <a href="mailto:getugoing@outlook.com?subject=FreeQuotation">Email</a>
      <a href="#">Phone: 07963522111 </a>
      <br>
      <br>
      <br>
      <br>
      <br>
      <a href="#">Our Opening hours</a>
      <a href="#">Monday - 9:00am - 5:00pm </a>
      <a href="#">Tuesday - 9:00am - 5:00pm</a>
      <a href="#">Wednesday - 9:00am - 5:00pm</a>
      <a href="#">Thursday - 9:00am - 5:00pm</a>
      <a href="#">Friday - 9:00am - 5:00pm</a>
      <a href="#">Saturday - 9:00am - 1:00pm</a>
      <a href="#">Sunday - Closed</a>
    </div>

    <span style="color:#00ff00;font-size:25px;cursor:pointer" onclick="openNav()">&#9776;</span>


    <script>
    function openNav() {
        document.getElementById("mySidenav").style.width = "250px";
    }

    function closeNav() {
        document.getElementById("mySidenav").style.width = "0";
    }
    </script>

    <button onclick="topFunction()" id="myBtn" title="Go to top">Back to top!</button>
    <script>
    // When the user scrolls down 20px from the top of the document, show the button
    window.onscroll = function() {scrollFunction()};

    function scrollFunction() {
        if (document.body.scrollTop > 30 || document.documentElement.scrollTop > 30) {
            document.getElementById("myBtn").style.display = "block";
        } else {
            document.getElementById("myBtn").style.display = "none";
        }
    }

    // When the user clicks on the button, scroll to the top of the document
    function topFunction() {
        document.body.scrollTop = 0;
        document.documentElement.scrollTop = 0;
    }
    </script>
<br>

          <img src="IMAGES/rovernowhiteback.png" alt="Get 'u' Going" align="left" style="width:300px;height:350px;">

<h1>
   <img src="IMAGES/newmg1.jpg" alt="Get 'u' Going"  align="right" style="width:250px;height:325px;">


       <div style="text-align: center;">
<form method="get" action="http://www.google.com/search"> <input type="text" name="q" size="30" style="width:700px;height:50PX"; maxlength="50" value="" /> <input type="submit" value="Search" /> </form>

<br>

             <img src="IMAGES/mgroverbreakersbolton.gif" alt="Get 'u' Going" align="center" style="width:1250px;height:325px;">

             <img src="IMAGES/contactgifnumber.gif" alt="Get 'u' Going" align="center" style="width:500px;height:50px;">

<br>
</h1>
</div>

<div style="text-align: center;">
<h2 style="color:Green;"> We break and repair any MG rover, Any age, Any model, Just give us a call and we will give you a price. </h2>

<br>
<br>
<br>

        <a href="https://www.facebook.com/ian.rice.9085?fb_dtsg_ag=AdxkJJ3X08XIW5qq6Eo6e8OcD9k81-y3f7fbtJiiIG8kIg%3AAdwabORGS1VVeZL5x7IRSBy8k_jhUx9OuJfnnR735wzLnw">
        <img src="IMAGES/Facebook.jpg" alt="Get 'u' Going" align="center" style="width:150px;height:150px;"></a>

         <a href="mailto:getugoing@outlook.com?subject=FreeQuotation  ">
         <img src="IMAGES/email9.png" alt="Get 'u' Going" align="center" style="width:200px;height:200px;"></a>

         <a href="https://www.instagram.com/">
         <img src="IMAGES/insta.jpg" alt="Get 'u' Going" align="center" style="width:150px;height:150px;"></a>

<br>
<br>
<br>

<!-- This is the picture of the top 3 cars that sit there -->
<div class="row">
  <div class="column">
    <img src="IMAGES/image1.jpeg" alt="Get 'u' Going" style="width:100%" align="left" download="IMAGES/image1.jpeg">
</div>
  <div class="column">
    <img src="IMAGES/image3.jpeg" alt="Get 'u' Going" style="width:100%"  align="right" download="IMAGES/image3.jpeg">
  </div>
  <div class="column">
    <img src="IMAGES/image2.jpeg" alt="Get 'u' Going" style="width:100%"  align="center" download="IMAGES/image2.jpeg">
  </div>
</div>
<br>


<h1 style="color:white;"> <strong>Turn your old car into cash today!</strong></h1>

                                          <br>
                                          <br>
                                          <br>
                                          <br>

<!-- This drops to the three images that sits under the title and pictures of the MG cars top page DIV top -->
<div class="row">

  <div class="column">
    <img src="IMAGES/scrap.jpg" alt="Get 'u' Going" style="width:50%">
  </div>

  <div class="column">
    <img src="IMAGES/greenarrow.png" alt="Get 'u' Going" style="width:50%">
  </div>

  <div class="column">
    <A HREF="mailto:getugoing@outlook.com?subject=FreeQuotation"><INPUT type="image" name="search" src="IMAGES/contactuscash.png" alt="Get 'u' Going" border="0" style="width:80%">
    </A>
  </div>

</div>


                                          <br>
                                          <br>
                                          <br>
                                          <br>
                                          <br>
                                          <br>


          <!-- This is where the new DIV sits on the page and into the new parts -->
<h1 style="color:green;"> Buy your quality used MG rover parts today! <br> Good quality parts all tested before sold with a 30 day guarentee <br> We are a fast and friendly service who have over 20 years experience! </h1>



<h2 style="color:green;"> Specialised in repairing your MG rovers just pop in today, give us a call or an email for a free quotation on your job as there is no job to big nor to small,
  <br> <br> <br> Engine swaps, <br> Head gaskets, <br> Water pumps, <br> timing belts, <br> starter motors <br> clutch <br> Break pads <br> ETC <h2> <h1 style="color:green;"> YOU name it WE can do it! </h1>

                                      <br>
                                      <br>
                                      <br>
                                      <br>


              <div>
                  <img src="IMAGES/yougetpaid.jpg" alt="Get 'u' Going" align="center" style="width:1000px;height:250px;">
              </div>

                                      <br>
                                      <br>

               <div>
                      <img src="IMAGES/scrapcar.png" alt="Get 'u' Going" align="left" style="width:250px;height:250px;">
                      <img src="IMAGES/scrapcar.png" alt="Get 'u' Going" align="right" style="width:250px;height:250px;">

                    <h1 style="color:white;"align="center">  We buy your old vehicles for scrap!

                      <h2 style="color:green;"align="center">  Our scrap car disposal scheme works across the North west, Get in contact for a quote. <br>
                        We pay on collection for any make, any model and will make the process of scrapping your car as safe, quick and easy as posible.<br>
                        For an up to date quote for your end of life vehicle please get in touch. </h1>


                            <div class="Email">
                              <a href="mailto:getugoing@outlook.com?subject=FreeQuotation">
                              <img src="IMAGES/email9.png" style="height: 150px; width: 150px" /><span>
                              </span></a>
              </div>

  <h1>
      <div>
      <img src="IMAGES/joinlogo.jpg" alt="Get 'u' Going"  align="center" style="width:600px;height:400px;">
      </a>
      </div>
</h1>

<br>
<br>
<br>

<h1 style="color:white;">Contact Us</h1>

<head>



    <label class="viewOpen" for="modal-state">Click me to view our opening times!&nbsp;&nbsp;<i class="fa fa-clock-o"></i></label>
    <input type="checkbox" name="modal-state" id="modal-state">
    <div class="modal-overlay">
      <label for="modal-state" class="modal-overlay-close"></label>
      <div class="modal">
        <label class="button-close" for="modal-state"><i class="fa fa-times"></i></label>
        <h2>Our opening times!</h2>
        <div id="Monday" class="dateTime">
          <div class="day">Monday</div>
          <div class="time">9:00am-5:00pm</div>
        </div>
        <br>
        <div id="Tuesday" class="dateTime">
          <div class="day">Tuesday</div>
          <div class="time">9:00am-5:00pm</div>
          <br>

        <div id="Wednesday" class="dateTime">
          <div class="day">Wednesday</div>
          <div class="time">9:00am-5:00pm</div>
        </div>
        <br>
        <div id="Thursday" class="dateTime">
          <div class="day">Thursday</div>
          <div class="time">9:00am-5:00pm</div>
        </div>
        <br>
        <div id="Friday" class="dateTime">
          <div class="day">Friday</div>
          <div class="time">9:00am-5:00pm</div>
        </div>
        <br>
        <div id="Saturday" class="dateTime">
          <div class="day">Saturday</div>
          <div class="time">9:00am-1:00pm</div>
        </div>
        <br>
        <div id="Sunday" class="dateTime">
          <div class="day">Sunday</div>
          <div class="time">Closed</div>
        </div>
        <br>
        </div>
      </div>
    </div>
  </div>



                <!-- main_menu -->
                <div>
                <style="color:green;">
                <div id="content">

                <!-- InstanceBeginEditable name="MainRegion" -->
                <div class="content33_box">
                <h2 style="color:green;">For all enquiries please contact us by phone, email or using our enquiry form.
                <div class="content_block">
                <div class="content22_box"><span class="hilighted" style="color:green;">Telephone:07426326643<br>
                <span class="hilighted" style="color:green;">Email:</span> <a> getugoing@outlook.com</a>          </div>
                <div class="content22_box" style="color:green;">Get 'U'going<br>
                                                                Pheathean Street<br>
                                                                Farnworth<br>
                                                                BL4 4LJ </h2>
                                                              </div>

                                                              <a href='#top'>
                                                                       <img src="IMAGES/newmg1.jpg" alt="Get 'u' Going" align="left" style="width:300px;height:350px;">
                                                             </a>

                                                             <h1>
                                                               <a href='#top'>
                                                                <img src="IMAGES/rovernowhiteback.png" alt="Get 'u' Going"  align="right" style="width:250px;height:325px;">
                                                              </a>



<!--Iframe for the two maps that are currently showing certain pin point on google maps -->
  <iframe src="https://www.google.com/maps/embed?pb=!4v1536057370872!6m8!1m7!1s0DCj2v3lYUdOoFGrpyZydw!2m2!1d53.55426284592217!2d-2.403395065696087!3f340.6954326218489!4f-6.988128817449464!5f0.7820865974627469" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d561.6841021748776!2d-2.403802470744737!3d53.55449109875147!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x487ba63df682c3d7%3A0xc9ee5fe34938db16!2sPhethean+St%2C+Farnworth%2C+Bolton!5e1!3m2!1sen!2suk!4v1536057490444" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>


<!-- This sits under the maps and this is the title for the contact page -->

          <h1 style="color:white;">Get in touch with one of our helpful team! <br></h1>
          <h1 style="color:white;">Leave your query and a little information for us to contact you and we guarentee a free quotation within 24 hours</h1>

          <h2>Newsletter Subscription button</h2>
      <a href="file:///D:/Websites/Getugoing/Newsletter_subscribe_stage.html" class="block">Subscribe to our newletter here </a>


          <!-- This Script is from wwwcom for free email send, This should take up to two minutes to deliver to inbox of email below -->

          <div>
            <a href="https://www.facebook.com/ian.rice.9085?fb_dtsg_ag=AdxkJJ3X08XIW5qq6Eo6e8OcD9k81-y3f7fbtJiiIG8kIg%3AAdwabORGS1VVeZL5x7IRSBy8k_jhUx9OuJfnnR735wzLnw">
            <img src="IMAGES/Facebook.jpg" alt="Get 'u' Going" align="center" style="width:150px;height:150px;"></a>

             <a href="mailto:getugoing@outlook.com?subject=FreeQuotation  ">
             <img src="IMAGES/email9.png" alt="Get 'u' Going" align="center" style="width:200px;height:200px;"></a>

             <a href="https://www.instagram.com/">
             <img src="IMAGES/insta.jpg" alt="Get 'u' Going" align="center" style="width:150px;height:150px;"></a>
          </a>
        </div>
          <br>


</body>

</html>
