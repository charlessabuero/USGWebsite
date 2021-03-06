<!doctype html>
<html lang="en">
  <head>
    <!-- Bootstrap CSS -->
    <link href="bootstrap-5.0.1-dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="bootstrap-5.0.1-dist/js/bootstrap.bundle.min.js"></script>

    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>University Student Government</title>
    
    <link rel="icon" href="images/usg_icon.ico" type="image/x-icon">
    <style>
      html{
        overflow-x: hidden;
      }
      .container1{
        padding-left: 50px;
        padding-top: 300px;
        padding-bottom: 100px;
        background-image: url('images/pic2.png');
        background-size: cover;
      }
      @media (max-width: 600px){
        .brandNavBar{
          display: none;
        }
      }
    </style>
  </head>
  <body>
    <div id="fb-root"></div>
    
    <script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v11.0" nonce="9LrFKVkW"></script>
    <header>
      <div class="container-fluid bg-primary px-0 py-0">
        <div class="row">
          <img src="images/headerUSG.jpg"></img>
        </div>
      </div>
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
          <img src ="images/usg_icon.png" class="pe-3" style="width:50px"><a class="navbar-brand brandNavBar" href="#" style="font-size:18.5px"><b>UNIVERSITY STUDENT GOVERNMENT</b></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            </ul>
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="events.html" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">Events</a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item" href="events.html">List of Events</a></li>
                  <li><a class="dropdown-item" href="https://www.facebook.com/250750381612504/videos/908779026630978">What's Going On?</a></li>
                  <li><a class="dropdown-item" href="#">USG General Assembly</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="https://wowcdo.ustp.edu.ph">USTP Week of Welcome</a></li>
                </ul>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="services.html" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">Services</a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item" href="services.html">List of Services</a></li>
                  <li><a class="dropdown-item" href="services.html">Help Desk</a></li>
                  <li><a class="dropdown-item" href="services.html">Academic Tutorials</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="https://www.facebook.com/USGOfficeoftheVicePresident">Legislations</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="departments.html">Departments</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="about.html">About Us</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </header>
    <main>
      <div class="container-fluid container1">
        <div class="p-4 p-md-5 mb-4 text-light">
          <div class="col-md-6 px-0">
            <h1 style="font-size:47px; font-style:initial">WELCOME TO USG!</h1>
            <p class="lead my-3">The USG-CDO, an inclusive governing council, envisions in honing professional individuals who are aware of their rights and have embraced diversity in the institution and in the society, adhering to the university???s thrusts.</p>
            <p class="text-start"><a class="btn btn-lg btn-light" href="about.html">Learn More</a></p>
          </div>
        </div>
      </div>
      <div class="container-fluid pt-5 px-2">
        <div class="row px-5">
          <h1 class="text-center">Our Services</h1>
          <h5 class="text-center">Check out the offered services and initiatives!</h5>
          <div class="col-lg-4 pt-4">
            <div class="bg-dark p-2 rounded-3">
              <img src="images/Login Screen.png" class="p-3" style="width:100%"></img>
              <h1 class="text-center text-light">HELP DESK</h1>
              <p class="text-center text-light">Get in touch with our<br>USG Representatives.</p>
              <p class="text-center"><a class="btn btn-light" href="services.html">Click Here</a></p>
            </div>
          </div>
          <div class="col-lg-4 pt-4">
            <div class="bg-dark p-2 rounded-3">
              <img src="images/Login Screen (2).png" class="p-3" style="width:100%"></img>
              <h1 class="text-center text-light">ONLINE TUTORIALS</h1>
              <p class="text-center text-light">Access to our online<br>academic kit.</p>
              <p class="text-center"><a class="btn btn-light" href="services.html">Click Here</a></p>
            </div>
          </div>
          <div class="col-lg-4 pt-4">
            <div class="bg-dark p-2 rounded-3">
              <img src="images/Login Screen (3).png" class="p-3" style="width:100%"></img>
              <h1 class="text-center text-light">LEGISLATIONS</h1>
              <p class="text-center text-light">Stay Updated with<br>the latest enactments.</p>
              <p class="text-center"><a class="btn btn-light" href="https://www.facebook.com/USGOfficeoftheVicePresident">Click Here</a></p>
            </div>
          </div>
        </div>
      </div>
      <div class="container-fluid py-5 px-5 bg-light">
        <div class="row">
          <h1 class="text-center">USG Events</h1>
          <h5 class="text-center">Stay tuned on the latest happenings of the student government!</h5>
          <div class="row pt-5">
            <hr>
            <div class="col-lg-4 pt-3">
              <img src="images/event4.jpg" style="width:100%"></img>
            </div>
            <div class="col-lg-8 pt-3">
              <h2>Virtual Week of Welcome 2021</h2>
              <h5>August 23-26, 2021 via FB Live</h5>
              <br>
              <p>
                <b>USTP welcomes new students for A.Y. 2021-2022!</b>
                <br>
                A new batch of promising trailblazers will be welcomed to their new home as the USTP Community virtually opens its doors for their new academic milestone as incoming senior high school, first-year students, and transferees this upcoming August 23-26, 2021.
                <br>
                <br>
                To know the latest updates, please like and follow our social media accounts and don't forget to register for this year???s Week of Welcome (WoW).
                <br>
                <br>
                Facebook: USTP Week of Welcome - CDO
                <br>
                Twitter: @ustpwowcdo
                <br>
                <br>
              </p>
              <p class="text-left"><a class="btn btn-sm btn-dark" href="https://www.facebook.com/ustpwow">Learn More</a></p>
            </div>
          </div>
          <div class="row pt-4">
            <hr>
            <div class="col-lg-4 pt-3">
              <img src="images/event1.jpg" style="width:100%"></img>
            </div>
            <div class="col-lg-8 pt-3">
              <h2>USG Virtual General Assembly</h2>
              <h5>February 12, 2021 | 10AM via FB Live</h5>
              <br>
              <p><b>Ahoy there, Trailblazers!</b>
                <br>
                It has been a challenging Academic Year yet here we are, already halfway done as we take on another semester filled with enthusiasm and dreams!
                <br>
                <br>
                Tune in this February 12, 2021 at 10:00am for our USG Virtual General Assembly here on our USG Facebook Page through livestream!
                <br>
                <br>
                Sail with us! As we paddle our way beyond our limits. Bugsay Trailblazers! Bugsay towards excellence??? through unity.
                <br>
                <br>
                </p>
                <p class="text-left"><a class="btn btn-sm btn-dark" href="https://www.facebook.com/250750381612504/videos/248815346853309">Watch Here</a></p>
            </div>
          </div>
          <div class="row p-4">
            <hr>
            <div class="col-lg-4 pt-3">
              <img src="images/event2.jpg" style="width:100%"></img>
            </div>
            <div class="col-lg-8 pt-3">
              <h2>What's Going On?</h2>
              <h5>May 3, 2021 | 7PM via FB Live and YouTube</h5>
              <br>
              <p><b>Ahoy, Trailblazers!</b>
              <br>
              Wanna know what???s going on?
              <br>
              <br>
              Stream with us as we officially launch the ???USG TV: WHAT???S GOING ON???? ??? An e-talk series that aims to give awareness to social, cultural, and economic issues in our society brought to you by the University Student Government - Cagayan de Oro.
              <br>
              <br>
              We will also be streaming live on Youtube! Together, let us grasp learnings from these informative talks and unearth new things! Join us and be informed, be cognizant and accustomed!
              <br>
              <br>
              What???s going on kaya ba? Arat na! Makinig sa chika na may dalang saya!
              <br>
              <br>
              </p>
              <p class="text-left"><a class="btn btn-sm btn-dark" href="https://www.facebook.com/250750381612504/videos/908779026630978">Watch Here</a></p>
            </div>
          </div>
          <hr>
          <p class="text-center"><a class="btn btn-warning" href="events.html">More Upcoming Events</a></p>
        </div>
      </div>
      <div class="container-fluid py-5 px-5" style="background-color:lightyellow">
        <div class="row">
          <div class="text-center">
            <img src="images/mat (1).png" style="max-width:150px;">
            <h1>Directory of Officers</h1>
            <h5>Get to know our latest roster of officers that run the USTP Student Government<br><br></h5>
            <p class="text-center"><a class="btn btn-lg btn-dark" href="https://www.facebook.com/ustpusg/posts/3475728022448041" target="_blank" rel="noopener noreferrer">Click Here</a></p>
          </div>
        </div>
      </div>
      <div class="container-fluid text-center">
        <div class="row">
          <div class="col-lg-4 p-3">
            <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/p/CLLknIVpGk3/?utm_source=ig_embed&amp;utm_campaign=loading" data-instgrm-version="13" style=" background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:540px; min-width:326px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"><div style="padding:16px;"> <a href="https://www.instagram.com/p/CLLknIVpGk3/?utm_source=ig_embed&amp;utm_campaign=loading" style=" background:#FFFFFF; line-height:0; padding:0 0; text-align:center; text-decoration:none; width:100%;" target="_blank"> <div style=" display: flex; flex-direction: row; align-items: center;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 40px; margin-right: 14px; width: 40px;"></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center;"> <div style=" background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 100px;"></div> <div style=" background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 60px;"></div></div></div><div style="padding: 19% 0;"></div> <div style="display:block; height:50px; margin:0 auto 12px; width:50px;"><svg width="50px" height="50px" viewBox="0 0 60 60" version="1.1" xmlns="https://www.w3.org/2000/svg" xmlns:xlink="https://www.w3.org/1999/xlink"><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><g transform="translate(-511.000000, -20.000000)" fill="#000000"><g><path d="M556.869,30.41 C554.814,30.41 553.148,32.076 553.148,34.131 C553.148,36.186 554.814,37.852 556.869,37.852 C558.924,37.852 560.59,36.186 560.59,34.131 C560.59,32.076 558.924,30.41 556.869,30.41 M541,60.657 C535.114,60.657 530.342,55.887 530.342,50 C530.342,44.114 535.114,39.342 541,39.342 C546.887,39.342 551.658,44.114 551.658,50 C551.658,55.887 546.887,60.657 541,60.657 M541,33.886 C532.1,33.886 524.886,41.1 524.886,50 C524.886,58.899 532.1,66.113 541,66.113 C549.9,66.113 557.115,58.899 557.115,50 C557.115,41.1 549.9,33.886 541,33.886 M565.378,62.101 C565.244,65.022 564.756,66.606 564.346,67.663 C563.803,69.06 563.154,70.057 562.106,71.106 C561.058,72.155 560.06,72.803 558.662,73.347 C557.607,73.757 556.021,74.244 553.102,74.378 C549.944,74.521 548.997,74.552 541,74.552 C533.003,74.552 532.056,74.521 528.898,74.378 C525.979,74.244 524.393,73.757 523.338,73.347 C521.94,72.803 520.942,72.155 519.894,71.106 C518.846,70.057 518.197,69.06 517.654,67.663 C517.244,66.606 516.755,65.022 516.623,62.101 C516.479,58.943 516.448,57.996 516.448,50 C516.448,42.003 516.479,41.056 516.623,37.899 C516.755,34.978 517.244,33.391 517.654,32.338 C518.197,30.938 518.846,29.942 519.894,28.894 C520.942,27.846 521.94,27.196 523.338,26.654 C524.393,26.244 525.979,25.756 528.898,25.623 C532.057,25.479 533.004,25.448 541,25.448 C548.997,25.448 549.943,25.479 553.102,25.623 C556.021,25.756 557.607,26.244 558.662,26.654 C560.06,27.196 561.058,27.846 562.106,28.894 C563.154,29.942 563.803,30.938 564.346,32.338 C564.756,33.391 565.244,34.978 565.378,37.899 C565.522,41.056 565.552,42.003 565.552,50 C565.552,57.996 565.522,58.943 565.378,62.101 M570.82,37.631 C570.674,34.438 570.167,32.258 569.425,30.349 C568.659,28.377 567.633,26.702 565.965,25.035 C564.297,23.368 562.623,22.342 560.652,21.575 C558.743,20.834 556.562,20.326 553.369,20.18 C550.169,20.033 549.148,20 541,20 C532.853,20 531.831,20.033 528.631,20.18 C525.438,20.326 523.257,20.834 521.349,21.575 C519.376,22.342 517.703,23.368 516.035,25.035 C514.368,26.702 513.342,28.377 512.574,30.349 C511.834,32.258 511.326,34.438 511.181,37.631 C511.035,40.831 511,41.851 511,50 C511,58.147 511.035,59.17 511.181,62.369 C511.326,65.562 511.834,67.743 512.574,69.651 C513.342,71.625 514.368,73.296 516.035,74.965 C517.703,76.634 519.376,77.658 521.349,78.425 C523.257,79.167 525.438,79.673 528.631,79.82 C531.831,79.965 532.853,80.001 541,80.001 C549.148,80.001 550.169,79.965 553.369,79.82 C556.562,79.673 558.743,79.167 560.652,78.425 C562.623,77.658 564.297,76.634 565.965,74.965 C567.633,73.296 568.659,71.625 569.425,69.651 C570.167,67.743 570.674,65.562 570.82,62.369 C570.966,59.17 571,58.147 571,50 C571,41.851 570.966,40.831 570.82,37.631"></path></g></g></g></svg></div><div style="padding-top: 8px;"> <div style=" color:#3897f0; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:550; line-height:18px;"> View this post on Instagram</div></div><div style="padding: 12.5% 0;"></div> <div style="display: flex; flex-direction: row; margin-bottom: 14px; align-items: center;"><div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(0px) translateY(7px);"></div> <div style="background-color: #F4F4F4; height: 12.5px; transform: rotate(-45deg) translateX(3px) translateY(1px); width: 12.5px; flex-grow: 0; margin-right: 14px; margin-left: 2px;"></div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(9px) translateY(-18px);"></div></div><div style="margin-left: 8px;"> <div style=" background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 20px; width: 20px;"></div> <div style=" width: 0; height: 0; border-top: 2px solid transparent; border-left: 6px solid #f4f4f4; border-bottom: 2px solid transparent; transform: translateX(16px) translateY(-4px) rotate(30deg)"></div></div><div style="margin-left: auto;"> <div style=" width: 0px; border-top: 8px solid #F4F4F4; border-right: 8px solid transparent; transform: translateY(16px);"></div> <div style=" background-color: #F4F4F4; flex-grow: 0; height: 12px; width: 16px; transform: translateY(-4px);"></div> <div style=" width: 0; height: 0; border-top: 8px solid #F4F4F4; border-left: 8px solid transparent; transform: translateY(-4px) translateX(8px);"></div></div></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center; margin-bottom: 24px;"> <div style=" background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 224px;"></div> <div style=" background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 144px;"></div></div></a><p style=" color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;"><a href="https://www.instagram.com/p/CLLknIVpGk3/?utm_source=ig_embed&amp;utm_campaign=loading" style=" color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none;" target="_blank">A post shared by University Student Government (@ustpusg)</a></p></div></blockquote> <script async src="//www.instagram.com/embed.js"></script>
          </div>
          <div class="col-lg-4 p-3">
            <div class="fb-page" data-href="https://www.facebook.com/ustpusg" data-tabs="timeline" data-width="430" data-height="650" data-small-header="false" data-adapt-container-width="true" data-hide-cover="false" data-show-facepile="false"><blockquote cite="https://www.facebook.com/ustpusg" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/ustpusg">University Student Government - USTP Cagayan de Oro</a></blockquote></div>
          </div>
          <div class="col-lg-4 p-3">
            <a class="twitter-timeline" data-width="430" data-height="650" href="https://twitter.com/ustpusg?ref_src=twsrc%5Etfw">Tweets by ustpusg</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
          </div>
        </div>
      </div>
    </main>
    <footer>
      <div class="container-fluid pt-5 px-5 bg-warning" style="font-size:14px;">
        <div class="row">
          <div class="col-lg-4 p-3">
            <img src="images/Frame.png" class="p-3" style="width:100%"></img>
        </div>
        <div class="col-lg-4 p-3">
          <p>The Official Web Portal of the University Student Government of the University of Science and Technology of Southern Philippines in Cagayan de Oro City Campus.</p>
          <p><b>Address:</b>
          <br>
          C.M. Recto Avenue, Lapasan, <br> Cagayan de Oro City 9000 Philippines
          </p>
          <p><b>Email:</b>
            <br>
            usgcdo@ustp.edu.ph</p>
        </div>
        <div class="col-lg-4 p-3">
          <p>Connect with us with our social media accounts!
            <br>
            <br>
          <a href="https://www.facebook.com/ustpusg" target="_blank" rel="noopener noreferrer"><img src="images/fb.png" style="height:20px"></a>
          &ensp; 
          <a href="https://www.instagram.com/ustpusg" target="_blank" rel="noopener noreferrer"><img src="images/ig.png" style="height:20px"></a>
          &ensp; 
          <a href="https://www.twitter.com/ustpusg" target="_blank" rel="noopener noreferrer"><img src="images/twitter.png" style="height:20px"></a>
          &ensp;
          <a href="https://www.youtube.com/channel/UCFtxH4SYfT-SOVZfSOP8ewA"><img src="images/yt_red.png" style="height:20px"></a>
            </p>
          <br>
          <br>
          <a href="https://www.ustp.edu.ph" target="_blank" rel="noopener noreferrer"><img src="images/ustp_white.png" style="height:50px"></a>
          <p>Universtiy of Science and Technology of Southern Philippines</p>
        </div>
      </div>
    </footer>
  </body>
</html>
