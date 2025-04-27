---
layout: default
title: Home
---

<div id="cookie-banner" style="display: none;">
    <span>
      We use cookies to understand how visitors use our site and to help us improve it. No ads, just insights to make your experience better.
      <a href="/privacy-policy.html" id="learn-more-link">Learn More</a>.
    </span>
    <button id="accept-cookies-btn">Accept</button>
    <button id="decline-cookies-btn">Decline</button>
  </div>

  <script>
    document.addEventListener('DOMContentLoaded', function () {
      const banner = document.getElementById('cookie-banner');
      const acceptBtn = document.getElementById('accept-cookies-btn');
      const declineBtn = document.getElementById('decline-cookies-btn');

      // If the user accepts cookies, set consent and load Google Analytics
      acceptBtn.addEventListener('click', function () {
        localStorage.setItem('cookiesAccepted', 'true');
        loadGoogleAnalytics();
        banner.style.display = 'none';
      });

      // If the user declines cookies, hide the banner
      declineBtn.addEventListener('click', function () {
        localStorage.setItem('cookiesAccepted', 'false');
        banner.style.display = 'none';
      });
    });
  </script>
      <div class="purplebg spacewaves">
         <div class="container">
            <div class="header">
				<div class="logo logo-large">
					<img src="images/logo_tagline.svg" alt="Logo with tagline" loading="lazy">
				</div>
				<div class="logo logo-mobile">
					<img src="images/logo_notag.svg" alt="Logo without tagline" loading="lazy">
				</div>
               <div class="full-nav">
                  <nav>
                     <ul>
                        <li><a href="#activities">Activities</a></li>
                        <li><a href="#pricing">Prices</a></li>
                        <li><a href="#promos">Promotions</a></li>
                        <li><a href="#bookonline">Book Online</a></li>
                        <li><a href="https://app.squareup.com/gift/XCE2PQ427HSWG/order">eGift Cards</a></li>
                        <li><a href="#visit">Contact Us</a></li>
						<li><a href="printable.html">Invitation Maker</a></li>
                     </ul>
                  </nav>
               </div>
               <i class='bx bx-menu menu-icon' name='menu' onclick="toggleMobileNav()"></i>
               <div class="mobile-nav" id="mobileNav">
                  <i class="bx bx-x-circle close-icon" onclick="toggleMobileNav()"></i>
                  <nav>
                     <ul>
                        <li><a href="#activities">Activities</a></li>
                        <li><a href="#pricing">Prices</a></li>
                        <li><a href="#promos">Promotions</a></li>
                        <li><a href="#bookonline">Book Online</a></li>
                        <li><a href="https://app.squareup.com/gift/XCE2PQ427HSWG/order">eGift Cards</a></li>
                        <li><a href="#visit">Contact Us</a></li>
                     </ul>
                  </nav>
               </div>
            </div>
            <button class="backtotop" id="backToTopBtn">
            <i class='bx bx-up-arrow-alt top-icon'></i>
            </button>
            <section class="hero">
               <div class="text">
                  <div style="display: flex; align-items: center; justify-content: center; margin-top: 60px; margin-bottom: 20px;">
                     <div style="display: flex; align-items: center;">
                        <i class="icon-sparkle" style="margin-top: -20px; margin-right: 15px; width: 50px; height: 50px;"></i>
                     </div>
                     <div style="text-align: center;">
                        <h1 style="margin: 0; font-size: 3em;" class="headershadow">Choose Your Adventure!</h1>
                     </div>
                     <div style="display: flex; align-items: center;">
                        <i class="icon-twinkle" style="margin-bottom: -20px; margin-left: 10px; width: 50px; height: 50px;"></i>
                     </div>
                  </div>
                  <p>
                     Dive into a vibe where adventure meets relaxation at Sarnia's ultimate spot. Feel the thrill with 
                     <span class="highlight-pink-text">laser tag</span> in our multi-level mazes, packed with epic hideouts and sniper spots just waiting to be claimed. 
                     Challenge yourself on our <span class="highlight-blue-text">rock climbing</span> wall to test your grit and showcase your climbing skills. 
                     Or, take a breather with some laid-back <span class="highlight-purple-text">mini golf</span>, where quirky courses are ready for your mastery. 
                     Whether you're here to boost your adrenaline or unwind, we've got your perfect escape covered. Get ready for a day in Sarnia that's anything but ordinary.
                  </p>
               </div>
               <div class="image main">
                  <img src="images/spacebro2.svg" loading="lazy">
               </div>
            </section>
            <div class="threepath">
               <img src="https://sarnialasertag.com/images/threepath.svg" loading="lazy">
            </div>
            <div class="onepath">
               <img src="https://sarnialasertag.com/images/onepath.svg" loading="lazy">
            </div>
            <section class="activities" id="activities">
               <div class="activity laser">
                  <img src="images/lasertag-act.webp" alt="Laser Tag" loading="lazy">
                  <div class="text-content">
                     <h3>Laser Tag</h3>
                     <p>At our arena, we take laser tag to the next level by offering a 
                        <span class="highlight-pink-text">two-storey</span> playing space. Prepare to be amazed as you explore 
                        the multiple levels, corridors, and strategic vantage points that our arena has to offer. With two 
                        storeys of <span class="highlight-pink-text">intense gameplay</span>, you'll find yourself fully immersed 
                        in an adrenaline-pumping adventure like never before.
                     </p>
                  </div>
               </div>
               <div class="squiggle">
                  <img src="https://sarnialasertag.com/images/squiggle.svg" loading="lazy">
               </div>
               <div class="activity rockclimb">
                  <img src="images/rockclimb-act.webp" alt="Rock Climbing" loading="lazy">
                  <div class="text-content">
                     <h3>Rock Climbing</h3>
                     <p>Embark on an exhilarating journey up our challenging rock climbing wall. Designed to test your limits, 
                        each handhold and foothold becomes an obstacle to conquer, requiring 
                        <span class="highlight-blue-text">strength, focus, and determination</span>. Feel the adrenaline surge 
                        as you ascend, overcoming challenges and reaching new heights, marking personal achievements with every climb.
                     </p>
                  </div>
               </div>
               <div class="squiggle rev">
                  <img src="https://sarnialasertag.com/images/squiggle.svg" loading="lazy">
               </div>
               <div class="activity">
                  <img src="images/minigolf-act.webp" alt="Mini Golf" loading="lazy">
                  <div class="text-content">
                     <h3>Mini Golf</h3>
                     <p>For a relaxed, fun activity, dive into a round of mini golf. This game blends precision, strategy, and light-hearted competition. 
                        Tackle our vibrant, creatively designed course, weaving through obstacles and mastering tricky curves. 
                        Test your putting skills and chase that <span class="highlight-purple-text">hole-in-one</span>, 
                        all while enjoying friendly banter and laughter in a cheerful atmosphere.
                     </p>
                  </div>
               </div>
            </section>
         </div>
		 <div class="carousel" data-flickity='{ "wrapAround": true, "autoPlay": 3000, "lazyLoad": true, "pageDots": false, "prevNextButtons": false, "contain": true }'>
            <div class="carousel-cell">
               <img 
                  src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725805062/slide01_ntfdq3.png" 
                  alt="Slide 1"
                  style="transform: rotate(-3deg);" loading="lazy">
            </div>
            <div class="carousel-cell">
               <img 
                  src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725805062/slide02_qnp48e.png" 
                  alt="Slide 2"
                  style="transform: rotate(2deg);" loading="lazy">
            </div>
            <div class="carousel-cell">
               <img 
                  src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725805062/slide03_l6jgoz.png" 
                  alt="Slide 3"
                  style="transform: rotate(-2deg);" loading="lazy">
            </div>
            <div class="carousel-cell">
               <img 
                  src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725805062/slide04_po0zbq.png" 
                  alt="Slide 4"
                  style="transform: rotate(1deg);" loading="lazy">
            </div>
            <div class="carousel-cell">
               <img 
                  src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725805062/slide05_w7tosn.png" 
                  alt="Slide 5"
                  style="transform: rotate(-3deg);" loading="lazy">
            </div>
            <div class="carousel-cell">
               <img 
                  src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725805064/slide06_s3ixrt.png" 
                  alt="Slide 6"
                  style="transform: rotate(1deg);" loading="lazy">
            </div>
            <div class="carousel-cell">
               <img 
                  src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725840536/slide07_urkz1b.png" 
                  alt="Slide 7"
                  style="transform: rotate(-2deg);" loading="lazy">
            </div>
            <div class="carousel-cell">
               <img 
                  src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725840536/slide08_zi7cym.png" 
                  alt="Slide 8"
                  style="transform: rotate(1deg);" loading="lazy">
            </div>
         </div>
         <script src="https://unpkg.com/flickity@2.2.2/dist/flickity.pkgd.min.js"></script>
      </div>
      <img 
         src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1723741147/squiggle-purple-trans_fwbpmp.png" 
         alt="" 
         srcset="
         https://res.cloudinary.com/di8j84ent/image/upload/w_512,q_auto/v1723741147/squiggle-purple-trans_fwbpmp.png 512w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_1024,q_auto/v1723741147/squiggle-purple-trans_fwbpmp.png 1024w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_2048,q_auto/v1723741147/squiggle-purple-trans_fwbpmp.png 2048w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_4096,q_auto/v1723741147/squiggle-purple-trans_fwbpmp.png 4096w" 
         sizes="200vw" 
         style="display:block;width:100%;height:100%;border-radius:inherit;object-position:center;object-fit:fill;image-rendering:auto" 
         loading="lazy">
      <div class="container">
         <section class="hero" id="pricing">
            <div class="text full-width">
               <div style="display: flex; align-items: center; justify-content: center;">
                  <div style="display: flex; align-items: center;">
                     <i class="icon-sparkle" style="margin-top: -20px; margin-right: 15px; width: 50px; height: 50px;"></i>
                  </div>
                  <div style="text-align: center;">
                     <h1 style="margin: 0;" class="headershadow">Our Prices</h1>
                  </div>
                  <div style="display: flex; align-items: center;">
                     <i class="icon-twinkle" style="margin-bottom: -20px; margin-left: 10px; width: 50px; height: 50px;"></i>
                  </div>
               </div>
               <p>We're happy to offer a wide variety of fun activities at affordable prices! Whether you want to stop by on a whim with your bestie, or plan ahead and bring the whole crew, we've got you covered!</p>
            </div>
         </section>
         <section class="pricing">
            <div class="price-category">
               <div class="double">
                  <h1><span class="highlight-blue">Walk-In Prices</span></h1>
               </div>
               <div class="price-item price-div">
                  <img src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1708885911/minigolf-icon_guotkk.png" alt="Mini Golf" loading="lazy">
                  <div>
                     <h3>Mini Golf</h3>
                     <p><strong>$10 per person</strong></p>
                     <p>One round 10-hole mini golf</p>
                  </div>
               </div>
               <div class="price-item price-div">
                  <img src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1708885911/lasertag-icon_bin78v.png" alt="Laser Tag" style="transform: rotate(-25deg);" loading="lazy">
                  <div>
                     <h3>Laser Tag</h3>
                     <p><strong>$14 per person</strong></p>
                     <p>20 minute game of laser tag</p>
                  </div>
               </div>
               <div class="price-item price-div">
                  <img src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1708885911/lasertag-icon_bin78v.png" alt="Laser Tag" style="transform: rotate(-25deg);" loading="lazy">
                  <div>
                     <h3>Laser Tag</h3>
                     <p><strong>$16 per person</strong></p>
                     <p>30 minute game of laser tag</p>
                  </div>
               </div>
               <div class="price-item price-div">
                  <img src="https://res.cloudinary.com/di8j84ent/image/upload/v1710517090/climb-icon_zkqemf_uzo7mc.png" alt="Rock Climbing" loading="lazy">
                  <div>
                     <h3>Rock Climbing</h3>
                     <p><strong>$16 per person</strong></p>
                     <p>3 rock climbs</p>
                  </div>
               </div>
               <div class="price-item">
                  <img src="https://res.cloudinary.com/di8j84ent/image/upload/v1710517090/climb-icon_zkqemf_uzo7mc.png" alt="Rock Climbing" loading="lazy">
                  <div>
                     <h3>Rock Climbing</h3>
                     <p><strong>$20 per person</strong></p>
                     <p>30 minutes of rock climbs</p>
                  </div>
               </div>
               <div class="price-item">
                  <img src="https://res.cloudinary.com/di8j84ent/image/upload/v1710517090/climb-icon_zkqemf_uzo7mc.png" alt="Rock Climbing" loading="lazy">
                  <div>
                     <h3>Rock Climbing</h3>
                     <p><strong>$25 per person</strong></p>
                     <p>One hour of rock climbs</p>
                  </div>
               </div>
            </div>
            <div class="squiggle rev">
               <img src="https://sarnialasertag.com/images/squiggle.svg" loading="lazy">
            </div>
            <div class="price-category">
               <div class="double">
                  <h1><span class="highlight-pink">Group Prices</span></h1>
               </div>
               <div class="group-package double">
                  <img src="https://res.cloudinary.com/di8j84ent/image/upload/v1710516020/group_viuias.png" alt="Package" loading="lazy">
                  <div>
                     <h2>Keep In Mind</h2>
                     <p>Groups must have 6 people minimum. Pricing is per person.</p>
                  </div>
               </div>
               <div class="group-package price-div">
                  <img src="https://res.cloudinary.com/di8j84ent/image/upload/v1710514210/1_1_ickk6k.png" alt="Package 1" loading="lazy">
                  <div>
                     <h3>Double Trouble</h3>
                     <p><strong>$26 per person</strong></p>
                     <p><i class='bx bx-check check-icon'></i> Two 20 minute games of laser tag</p>
                  </div>
               </div>
               <div class="group-package price-div">
                  <img src="https://res.cloudinary.com/di8j84ent/image/upload/v1710514210/2_1_wsn2gy.png" alt="Package 2" loading="lazy">
                  <div>
                     <h3>Climb & Conquer</h3>
                     <p><strong>$32 per person</strong></p>
                     <p><i class='bx bx-check check-icon'></i> Two 20 minute games of laser tag<br>
                        <i class='bx bx-check check-icon'></i> Two rock climbs
                     </p>
                  </div>
               </div>
               <div class="group-package price-div double">
                  <img src="https://res.cloudinary.com/di8j84ent/image/upload/v1710514250/3_5_n1vkc6.png" alt="Package 3" loading="lazy">
                  <div>
                     <h3>Putt & Play</h3>
                     <p><strong>$32 per person</strong></p>
                     <p><i class='bx bx-check check-icon'></i> Two 20 minute games of laser tag<br>
                        <i class='bx bx-check check-icon'></i> One round of 10-hole mini golf
                     </p>
                  </div>
               </div>
            </div>
         </section>
         <div class="squiggle-right">
            <img src="https://sarnialasertag.com/images/squiggle-right.svg" loading="lazy">
         </div>
         <section class="hero circle">
            <div class="text full-width">
               <h1 class="headershadow">Hosting a Larger Event?</h1>
               <a href="/org_contact.html"><button><i class="icon-sparkle"></i> Reach out to us directly!</button></a>
            </div>
         </section>
      </div>
      <img 
         src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1723741926/squiggle-trans-purple_weytxa.png" 
         alt="" 
         srcset="
         https://res.cloudinary.com/di8j84ent/image/upload/w_512,q_auto/v1723741926/squiggle-trans-purple_weytxa.png 512w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_1024,q_auto/v1723741926/squiggle-trans-purple_weytxa.png 1024w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_2048,q_auto/v1723741926/squiggle-trans-purple_weytxa.png 2048w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_4096,q_auto/v1723741926/squiggle-trans-purple_weytxa.png 4096w" 
         sizes="200vw" 
         style="display:block;width:100%;height:100%;border-radius:inherit;object-position:center;object-fit:fill;image-rendering:auto" 
         loading="lazy">
      <div class="purplebg">
         <div class="container">
            <section class="testimonials">
               <section class="hero">
                  <div class="text full-width">
                     <div style="display: flex; align-items: center; justify-content: center;">
                        <div style="display: flex; align-items: center;">
                           <i class="icon-sparkle" style="margin-top: -20px; margin-right: 15px; width: 50px; height: 50px;"></i>
                        </div>
                        <div style="text-align: center;">
                           <h1 style="margin: 0;" class="headershadow">People Are Talking!</h1>
                        </div>
                        <div style="display: flex; align-items: center;">
                           <i class="icon-twinkle" style="margin-bottom: -20px; margin-left: 10px; width: 50px; height: 50px;"></i>
                        </div>
                     </div>
                     <p>We love hearing that you had a great visit! Share your experience with us <a href="contact.html" class="underline-effect">here!</a></p>
                  </div>
               </section>
               <section class="testimonials">
                  <div class="testimonial righttilt">
                     <img src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1712442347/marcus.svg" class="yellow" alt="Customer Review" loading="lazy">
                     <p>"Had an amazing time rock climbing! The routes were challenging but fun, and the staff were really encouraging. Definitely coming back!" 
                     <h3>Marcus W.</h3>
                     </p>
                  </div>
                  <div class="straightpath">
                     <img src="https://sarnialasertag.com/images/straightpath.svg" loading="lazy">
                  </div>
                  <div class="testimonial lefttilt">
                     <img src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1712442345/priya.svg" class="pink" alt="Customer Review" loading="lazy">
                     <p>"My kid’s mini golf party was awesome! The package was great, staff were super nice, and the courses were so fun. Totally worth it." 
                     <h3>Priya R.</h3>
                     </p>
                  </div>
                  <div class="straightpath rev">
                     <img src="https://sarnialasertag.com/images/straightpath.svg" loading="lazy">
                  </div>
                  <div class="testimonial righttilt">
                     <img src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1712442345/alex.svg" class="blue" alt="Customer Review" loading="lazy">
                     <p>"Laser tag at The Arena is epic! The multi-level play areas and strategy kept us on our toes. Can't wait for the next game!" 
                     <h3>Alex G.</h3>
                     </p>
                  </div>
                  <div class="straightpath">
                     <img src="https://sarnialasertag.com/images/straightpath.svg" loading="lazy">
                  </div>
                  <div class="testimonial lefttilt">
                     <img src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1712442346/jenna.svg" class="blue" alt="Customer Review" loading="lazy">
                     <p>"Our office team building event at laser tag was a blast. It was fun, engaging, and perfect for boosting team spirit!" 
                     <h3>Jenna K</h3>
                     </p>
                  </div>
                  <div class="straightpath rev">
                     <img src="https://sarnialasertag.com/images/straightpath.svg" loading="lazy">
                  </div>
                  <div class="testimonial righttilt">
                     <img src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1712442344/sophia.svg" class="yellow" alt="Customer Review" loading="lazy">
                     <p>"Hosting my son’s laser tag birthday was easy and fun. The staff were super helpful, and everything went smoothly. Unforgettable day!" 
                     <h3>Sophia M.</h3>
                     </p>
                  </div>
                  <div class="straightpath">
                     <img src="https://sarnialasertag.com/images/straightpath.svg" loading="lazy">
                  </div>
                  <div class="testimonial lefttilt">
                     <img src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1712442345/darren.svg" class="pink" alt="Customer Review" loading="lazy">
                     <p>"The mini golf adventure was cool! The courses made for a fun rainy day activity. We'll definitely be back." 
                     <h3>Darren L.</h3>
                     </p>
                  </div>
               </section>
            </section>
         </div>
         
      </div>
      <img 
         src="https://res.cloudinary.com/di8j84ent/image/upload/v1723741147/squiggle-purple-trans_fwbpmp.png" 
         alt="" 
         srcset="
         https://res.cloudinary.com/di8j84ent/image/upload/w_512,q_auto/v1723741147/squiggle-purple-trans_fwbpmp.png 512w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_1024,q_auto/v1723741147/squiggle-purple-trans_fwbpmp.png 1024w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_2048,q_auto/v1723741147/squiggle-purple-trans_fwbpmp.png 2048w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_4096,q_auto/v1723741147/squiggle-purple-trans_fwbpmp.png 4096w" 
         sizes="200vw" 
         style="display:block;width:100%;height:100%;border-radius:inherit;object-position:center;object-fit:fill;image-rendering:auto" 
         loading="lazy">
      <div class="container">
         <section class="hero" id="promos">
            <div class="text full-width">
               <div style="display: flex; align-items: center; justify-content: center;">
                  <div style="display: flex; align-items: center;">
                     <i class="icon-sparkle" style="margin-top: -20px; margin-right: 15px; width: 50px; height: 50px;"></i>
                  </div>
                  <div style="text-align: center;">
                     <h1 style="margin: 0;" class="headershadow">Rocket Powered Rates!</h1>
                  </div>
                  <div style="display: flex; align-items: center;">
                     <i class="icon-twinkle" style="margin-bottom: -20px; margin-left: 10px; width: 50px; height: 50px;"></i>
                  </div>
               </div>
               <p>Every week we offer daily specials on select activities! Looking for a great deal? You found it!</p>
			   <section class="specials-section">
			      <div class="specials-package">
				    <img src="images/mff.webp" alt="Package 2" loading="lazy">
                     <div class="header-container">
                        <h3>Every Wednesday - Friday</h3>
                        <p class="price">$36 per person</p>
                        <p class="packtime">Minimum 4 people - Walk-In Only</p>
                     </div>
                     <ul>
                        <li><i class='bx bx-check check-icon'></i> One 30-minute game of laser tag</li>
						<li><i class='bx bx-check check-icon'></i> Three rock climbs</li>
						<li><i class='bx bx-check check-icon'></i> One round of 10-hole mini golf</li>
                     </ul>
                  </div>
			      <div class="specials-package">
				    <img src="images/ff.webp" alt="Package 2" loading="lazy">
                     <div class="header-container">
                        <h3>Every Friday</h3>
                        <p class="price">$14 per person</p>
                        <p class="packtime">Walk-In Only</p>
                     </div>
                     <ul>
                        <li><i class='bx bx-check check-icon'></i> One 30-minute game of laser tag</li>
                     </ul>
                  </div>					  
			   </section>
               <p>All prices displayed are walk-in prices only, are priced per person, and cannot be combined with any other offer or promotion.</p>
            </div>
         </section>
      </div>
      <img 
         src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1723741926/squiggle-trans-purple_weytxa.png" 
         alt="" 
         srcset="
         https://res.cloudinary.com/di8j84ent/image/upload/w_512,q_auto/v1723741926/squiggle-trans-purple_weytxa.png 512w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_1024,q_auto/v1723741926/squiggle-trans-purple_weytxa.png 1024w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_2048,q_auto/v1723741926/squiggle-trans-purple_weytxa.png 2048w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_4096,q_auto/v1723741926/squiggle-trans-purple_weytxa.png 4096w" 
         sizes="200vw" 
         style="display:block;width:100%;height:100%;border-radius:inherit;object-position:center;object-fit:fill;image-rendering:auto" 
         loading="lazy">
      <div class="purplebg">
         <div class="container">
            <section class="hero">
               <div class="text">
                  <div style="display: flex; align-items: center; justify-content: center; margin-top: 60px; margin-bottom: 20px;">
                     <div style="display: flex; align-items: center;">
                        <i class="icon-sparkle" style="margin-top: -20px; margin-right: 15px; width: 50px; height: 50px;"></i>
                     </div>
                     <div style="text-align: center;">
                        <h1 style="margin: 0; font-size: 3em;" class="headershadow">Gift a Galaxy of Fun!</h1>
                     </div>
                     <div style="display: flex; align-items: center;">
                        <i class="icon-twinkle" style="margin-bottom: -20px; margin-left: 10px; width: 50px; height: 50px;"></i>
                     </div>
                  </div>
                  <p>
                     Why not give the gift they <i>really</i> want? Choose one of our e-gift cards for your friends, family, or anyone special!
                  </p>
                  <p>
                     <a href="https://app.squareup.com/gift/XCE2PQ427HSWG/order">
                     <button><i class="icon-sparkle"></i> Get an e-gift card!</button>
                     </a>
                  </p>
               </div>
				<div class="image main">
					<object type="image/svg+xml" data="images/giftcard.svg" class="svg-container svg-desktop"></object>
					<img src="images/giftcard-still.svg" alt="Gift Card" class="svg-container svg-mobile" loading="lazy">
				</div>
			</section>
         </div>
      </div>
      <img 
         src="https://res.cloudinary.com/di8j84ent/image/upload/v1723741147/squiggle-purple-trans_fwbpmp.png" 
         alt="" 
         srcset="
         https://res.cloudinary.com/di8j84ent/image/upload/w_512,q_auto/v1723741147/squiggle-purple-trans_fwbpmp.png 512w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_1024,q_auto/v1723741147/squiggle-purple-trans_fwbpmp.png 1024w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_2048,q_auto/v1723741147/squiggle-purple-trans_fwbpmp.png 2048w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_4096,q_auto/v1723741147/squiggle-purple-trans_fwbpmp.png 4096w" 
         sizes="200vw" 
         style="display:block;width:100%;height:100%;border-radius:inherit;object-position:center;object-fit:fill;image-rendering:auto" 
         loading="lazy">  
      <div class="container">
         <section id="bookonline">
            <div class="container">
               <section class="hero">
                  <div class="text full-width">
                     <div style="display: flex; align-items: center; justify-content: center;">
                        <div style="display: flex; align-items: center;">
                           <i class="icon-sparkle" style="margin-top: -20px; margin-right: 15px; width: 50px; height: 50px;"></i>
                        </div>
                        <div style="text-align: center;">
                           <h1 style="margin: 0;" class="headershadow">Book Your Group Visit Online!</h1>
                        </div>
                        <div style="display: flex; align-items: center;">
                           <i class="icon-twinkle" style="margin-bottom: -20px; margin-left: 10px; width: 50px; height: 50px;"></i>
                        </div>
                     </div>
                     <p>No need to stress about the details – we've made it super easy to book ahead online. Lock in your plans, secure your spot, and get ready for a blast!</p>
                  </div>
               </section>
               <div class="toggleHeader" onclick="toggleVisibility('faq0', this)">
                  <h2>How does group pricing work?</h2>
                  <i class='faqbx bx bx-down-arrow-circle' id="arrow-faq0"></i>
               </div>
               <div id="faq0" class="faqcontent">
                  <h2><i class="icon-sparkle"></i> It's simple!</h2>
                  <p>Our group packages are priced per person and include access to all listed activities within that package, as well as a private party room. 
                     To qualify for group pricing and the private room, each group must consist of at least 6 participants. Please note, the maximum number of people per group is limited to 20 at any time.
                  </p>
                  <p>When you arrive for your event, we will check you in, confirm the number of guests and finalize payment. We do not take payments online.</p>
                  <p>Are you looking to book for a larger event for a business, school or organization? 
                     <a href="org_contact.html" class="underline-effect">Reach out to us directly</a>.
                  </p>
               </div>
               <div class="toggleHeader" onclick="toggleVisibility('faq3', this)">
                  <h2>Is there a minimum or maxium amount of people I can have?</h2>
                  <i class='faqbx bx bx-down-arrow-circle' id="arrow-faq3"></i>
               </div>
               <div id="faq3" class="faqcontent">
                  <h2><i class="icon-sparkle"></i> Yes!</h2>
                  <p>To qualify for group pricing and the private room, each group must consist of at least 6 participants. Please note, the maximum number of people per group is limited to 20 at any time.
                  </p>
                  <p>Are you looking to book for a larger event for a business, school or organization? 
                     <a href="org_contact.html" class="underline-effect">Reach out to us directly</a>.
                  </p>
               </div>
               <div class="toggleHeader" onclick="toggleVisibility('faq1', this)">
                  <h2>Will my group have a private room available to them?</h2>
                  <i class='faqbx bx bx-down-arrow-circle' id="arrow-faq1"></i>
               </div>
               <div id="faq1" class="faqcontent">
                  <h2><i class="icon-sparkle"></i> Yes!</h2>
                  <p>Throughout your booking slot, you'll have exclusive access to a private party room. It's your space to decorate and use as needed for your event. Enjoy the privacy and flexibility to make your celebration perfect!</p>
               </div>
               <div class="toggleHeader" onclick="toggleVisibility('faq2', this)">
                  <h2>Can I bring in my own food for my event?</h2>
                  <i class='faqbx bx bx-down-arrow-circle' id="arrow-faq2"></i>
               </div>
               <div id="faq2" class="faqcontent">
                  <h2><i class="icon-sparkle"></i> Yes!</h2>
                  <p>You're welcome to bring your favorite treats, like a birthday cake or snacks, along with non-alcoholic beverages to enjoy during your event. Additionally, we offer a selection of personal-sized snacks including chips and chocolate bars, as well as soda and water available for purchase, should you need a little extra refreshment.</p>
                  <p>Please note that The Arena maintains a <b>strict zero-tolerance policy regarding the presence and use of alcohol or drugs on the premises</b>. 
                     We are committed to providing a safe and enjoyable environment for all guests. If any member of your party is found violating this policy, the entire group will be required to leave immediately, and no compensation will be offered for the disruption. 
                     We appreciate your cooperation and understanding in helping us maintain a safe and welcoming space for everyone.
                  </p>
               </div>
               <section class="booking-section">
                  <div class="booking-package">
                     <img src="https://res.cloudinary.com/di8j84ent/image/upload/v1710514210/1_1_ickk6k.png" alt="Package 1" loading="lazy">
                     <div class="header-container">
                        <h3>Double Trouble</h3>
                        <p class="price">$26 per person</p>
                        <p class="packtime">Approx. 1 hour 30 mins</p>
                     </div>
                     <ul>
                        <li><i class='bx bx-check check-icon'></i> Two 20-minute games of laser tag</li>
                     </ul>
                     <a href="https://book.squareup.com/appointments/ubo4tlk6rwm1nl/location/3N7XM7GWRSW3E/services/XQ7BGO5JLRW4B3TO6AZI5SRX" class="book-now-btn"><i class="icon-sparkle"></i> Book Now</a>
                  </div>
                  <div class="booking-package">
                     <img src="https://res.cloudinary.com/di8j84ent/image/upload/v1710514210/2_1_wsn2gy.png" alt="Package 2" loading="lazy">
                     <div class="header-container">
                        <h3>Climb & Conquer</h3>
                        <p class="price">$32 per person</p>
                        <p class="packtime">Approx. 2 hours</p>
                     </div>
                     <ul>
                        <li><i class='bx bx-check check-icon'></i> Two 20-minute games of laser tag</li>
                        <li><i class='bx bx-check check-icon'></i> Two rock climbs</li>
                     </ul>
                     <a href="https://book.squareup.com/appointments/ubo4tlk6rwm1nl/location/3N7XM7GWRSW3E/services/RTSWPT23H3HDAMH2N5WFM45Z" class="book-now-btn"><i class="icon-sparkle"></i> Book Now</a>
                  </div>
                  <div class="booking-package">
                     <img src="https://res.cloudinary.com/di8j84ent/image/upload/v1710514250/3_5_n1vkc6.png" alt="Package 3" loading="lazy">
                     <div class="header-container">
                        <h3>Putt & Play</h3>
                        <p class="price">$32 per person</p>
                        <p class="packtime">Approx. 2 hours</p>
                     </div>
                     <ul>
                        <li><i class='bx bx-check check-icon'></i> Two 20-minute games of laser tag</li>
                        <li><i class='bx bx-check check-icon'></i> One round of 10-hole mini golf</li>
                     </ul>
                     <a href="https://book.squareup.com/appointments/ubo4tlk6rwm1nl/location/3N7XM7GWRSW3E/services/KUWB2SSAJRK5BXDXEIOFZNWO" class="book-now-btn"><i class="icon-sparkle"></i> Book Now</a>
                  </div>
               </section>
            </div>
         </section>
      </div>
      <div class="ribbon">
         <div class="ribbontext">
            Sarnia Plays Here <i class="icon-sparkle"></i> Sarnia Laughs Here <i class="icon-twinkle"></i> Sarnia Climbs Here <i class="icon-sparkle"></i> Sarnia Wins Here <i class="icon-twinkle"></i> Sarnia Putts Here 
            Sarnia Parties Here <i class="icon-sparkle"></i> Sarnia Plays Here <i class="icon-twinkle"></i> Sarnia Laughs Here <i class="icon-sparkle"></i> Sarnia Climbs Here <i class="icon-twinkle"></i> Sarnia Wins Here <i class="icon-sparkle"></i> 
            Sarnia Putts Here <i class="icon-twinkle"></i> Sarnia Parties Here <i class="icon-sparkle"></i> Sarnia Plays Here <i class="icon-twinkle"></i> Sarnia Laughs Here <i class="icon-sparkle"></i> Sarnia Climbs Here <i class="icon-twinkle"></i> 
            Sarnia Wins Here <i class="icon-sparkle"></i> Sarnia Putts Here <i class="icon-twinkle"></i> Sarnia Parties Here <i class="icon-sparkle"></i> Sarnia Plays Here <i class="icon-sparkle"></i> Sarnia Laughs Here <i class="icon-twinkle"></i> Sarnia Climbs Here <i class="icon-sparkle"></i> Sarnia Wins Here <i class="icon-twinkle"></i> Sarnia Putts Here 
            Sarnia Parties Here <i class="icon-sparkle"></i> Sarnia Plays Here <i class="icon-twinkle"></i> Sarnia Laughs Here <i class="icon-sparkle"></i> Sarnia Climbs Here <i class="icon-twinkle"></i> Sarnia Wins Here <i class="icon-sparkle"></i> 
            Sarnia Putts Here <i class="icon-twinkle"></i> Sarnia Parties Here <i class="icon-sparkle"></i> Sarnia Plays Here <i class="icon-twinkle"></i> Sarnia Laughs Here <i class="icon-sparkle"></i> Sarnia Climbs Here <i class="icon-twinkle"></i> 
            Sarnia Wins Here <i class="icon-sparkle"></i> Sarnia Putts Here <i class="icon-twinkle"></i> Sarnia Parties Here <i class="icon-sparkle"></i> 
         </div>
      </div>
      <div class="container">
         <section class="hero" id="visit">
            <div class="text">
               <div style="display: flex; align-items: center; justify-content: center;">
                  <div style="display: flex; align-items: center;">
                     <i class="icon-sparkle" style="margin-top: -20px; margin-right: 15px; width: 50px; height: 50px;"></i>
                  </div>
                  <div style="text-align: center;">
                     <h1 style="margin: 0;" class="headershadow">Ready to Visit?</h1>
                  </div>
                  <div style="display: flex; align-items: center;">
                     <i class="icon-twinkle" style="margin-bottom: -20px; margin-left: 10px; width: 50px; height: 50px;"></i>
                  </div>
               </div>
               <p>We're over the moon with excitement at the thought of welcoming you! Our doors are open wide during our business hours. Navigate your way through the stars and drop by!
               </p>
               <p>
                  <a href="tel:+15195421001"><button><i class='bx bxs-phone'></i> Call</button></a>
                  <a href="contact.html"><button><i class='bx bxs-envelope'></i> Message</button></a>
                  <a href="https://www.google.com/maps/dir/42.9802491,-81.2037244/1886+London+Line,+Sarnia,+ON+N7W+1B3/@42.9321471,-83.1115738,8z/data=!3m1!4b1!4m9!4m8!1m1!4e1!1m5!1m1!1s0x882583f032715077:0xdf8f3cb05927e5!2m2!1d-82.3151737!2d42.9853351?entry=ttu" target="_blank"><button><i class='bx bxs-map-pin'></i> Visit</button></a>
               </p>
            </div>
            <div class="text">
                <a href="https://www.google.com/maps/dir/42.9802491,-81.2037244/1886+London+Line,+Sarnia,+ON+N7W+1B3/@42.9321471,-83.1115738,8z/data=!3m1!4b1!4m9!4m8!1m1!4e1!1m5!1m1!1s0x882583f032715077:0xdf8f3cb05927e5!2m2!1d-82.3151737!2d42.9853351?entry=ttu" target="_blank">
                  <!-- <img src="https://res.cloudinary.com/di8j84ent/image/upload/v1712845028/map_2_k1jpgv.png" alt="Business Location Map" border="0"> -->
                  <img src="images/visit.svg" loading="lazy">
               </a>
            </div>
         </section>
         <section class="hours">
            <div class="business-hours">
               <div class="business-hour sunday">
                  <p><b>SUN</b></p>
                  <p>11AM - 7PM</p>
               </div>
               <div class="business-hour montuesday">
                  <p><b>MON + TUES</b></p>
                  <p>Monday 12PM - 6PM<br>Tuesday CLOSED</p>
               </div>
               <div class="business-hour wednesday">
                  <p><b>WED</b></p>
                  <p>CLOSED</p>
               </div>
               <div class="business-hour thursday">
                  <p><b>THURS</b></p>
                  <p>4PM - 8PM</p>
               </div>
               <div class="business-hour friday">
                  <p><b>FRI</b></p>
                  <p>4PM - 10PM</p>
               </div>
               <div class="business-hour saturday">
                  <p><b>SAT</b></p>
                  <p>12PM - 10PM</p>
               </div>
            </div>
         </section>
		 <section class="hero">
               <div class="text full-width">
                  <div style="display: flex; align-items: center; justify-content: center; margin-top: 60px; margin-bottom: 20px;">
                     <div style="display: flex; align-items: center;">
                        <i class="icon-sparkle" style="margin-top: -20px; margin-right: 15px; width: 50px; height: 50px;"></i>
                     </div>
                     <div style="text-align: center;">
                        <h1 style="margin: 0; font-size: 3em;" class="headershadow">Keep the Adventure Going!</h1>
                     </div>
                     <div style="display: flex; align-items: center;">
                        <i class="icon-twinkle" style="margin-bottom: -20px; margin-left: 10px; width: 50px; height: 50px;"></i>
                     </div>
                  </div>
                  <p>
                     Follow us for updates, special offers and more fun! 💖📲
                  </p>
                  <p>
                     <a href="https://instagram.com/thearenasarnia" target="_blank">
                     <button><i class="icon-sparkle"></i> @thearenasarnia</button>
                     </a>
					</p>
					<p>
					<behold-widget feed-id="V8CACOLBZ0gqK0fy1rUw"></behold-widget>
					<script>
					  (() => {
						const d=document,s=d.createElement("script");s.type="module";
						s.src="https://w.behold.so/widget.js";d.head.append(s);
					  })();
					</script>
                  </p>
               </div>
			</section>
			
      </div>
	  

      <img 
         src="https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1723741926/squiggle-trans-purple_weytxa.png" 
         alt="" 
         srcset="
         https://res.cloudinary.com/di8j84ent/image/upload/w_512,q_auto/v1723741926/squiggle-trans-purple_weytxa.png 512w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_1024,q_auto/v1723741926/squiggle-trans-purple_weytxa.png 1024w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_2048,q_auto/v1723741926/squiggle-trans-purple_weytxa.png 2048w, 
         https://res.cloudinary.com/di8j84ent/image/upload/w_4096,q_auto/v1723741926/squiggle-trans-purple_weytxa.png 4096w" 
         sizes="200vw" 
         style="display:block;width:100%;height:100%;border-radius:inherit;object-position:center;object-fit:fill;image-rendering:auto" 
         loading="lazy">
      <div class="footer">
         <div class="container">
            <div class="footer-content">
               <div class="footer-section">
                  <h3>Follow Us!</h3>
                  <div class="social-icons">
                     <a href="https://www.facebook.com/thearenasarnia/" target="_blank" class="icon-link"><i class='bx bxl-facebook-circle'></i></a>
                     <a href="https://www.instagram.com/thearenasarnia" target="_blank" class="icon-link"><i class='bx bxl-instagram'></i></a>
                  </div>
               </div>
               <div class="footer-section">
                  <h3>The Fine Print</h3>
                  <p>All prices are displayed without applicable taxes and are subject to change without notice.</p>
                  <p>The Arena - Sarnia Laser Tag is a local, independently owned and run business. We thank you for your continued support and patronage.</p>
                  <p>By using our venue and facilities, you agree to abide by our <a href="/respect-responsible-use-policy.html" class="underline-effect">Respect & Responsible Use Policy</a> and <a href="/privacy-policy.html" class="underline-effect">Privacy Policy</a>.</p>
               </div>
            </div>
            <div class="footer-bottom">
               <p>&copy; 2024 Robbie Bennett Holdings Inc.</p>
            </div>
         </div>
      </div>
      <!-- JavaScript Files -->
      <script src="scripts/swiper-init.js"></script>
      <script src="scripts/toggle-faq.js"></script>
      <script src="scripts/testimonial-animation.js"></script>
      <script src="scripts/ribbon-scroll.js"></script>
      <script src="scripts/mobile-nav.js"></script>
      <script src="scripts/back-to-top.js"></script>
      <script src="scripts/highlight-business-hours.js"></script>
      <script src="scripts/weekly-deals-image.js"></script>
