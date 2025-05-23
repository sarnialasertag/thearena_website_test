---
layout: default
title: Home
gallery_images:
  - url: "https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725840536/slide07_urkz1b.png"
    alt: "Player running through maze"
  - url: "https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725840536/slide08_zi7cym.png"
    alt: "Climbing wall action"
  - url: "https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725805062/slide01_ntfdq3.png"
    alt: "Laser tag match"
  - url: "https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725805062/slide02_qnp48e.png"
    alt: "Mini golf moment"
  - url: "https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725805062/slide03_l6jgoz.png"
    alt: "Mini golf moment"
  - url: "https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725805062/slide04_po0zbq.png"
    alt: "Mini golf moment"
  - url: "https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725805062/slide05_w7tosn.png"
    alt: "Mini golf moment"	
  - url: "https://res.cloudinary.com/di8j84ent/image/upload/q_auto/v1725805064/slide06_s3ixrt.png"
    alt: "Mini golf moment"		

---

{% include text-image.html
   title="Welcome adventurers!"
   paragraph="Step into Sarnia’s go-to spot for nonstop fun and chill vibes. Take aim in our multi-level laser tag arena—loaded with sneaky hideouts and perfect perch spots. Scale new heights on the rock climbing wall and put your skills to the test. Or slow things down with a round of mini golf, where each hole adds its own twist. Whether you're chasing thrills or just looking to unwind, this is your place to do it all."
   img="https://sarnialasertag.com/images/hero/welcome-hero-nograin.webp"
   button="Learn More"
   button_url=""
   reverse=true
%}

{% include hero.html
   img=""
   title="Welcome adventurers!"
   paragraph="Step into Sarnia’s go-to spot for nonstop fun and chill vibes. Take aim in our multi-level laser tag arena—loaded with sneaky hideouts and perfect perch spots. Scale new heights on the rock climbing wall and put your skills to the test. Or slow things down with a round of mini golf, where each hole adds its own twist. Whether you're chasing thrills or just looking to unwind, this is your place to do it all."
   button=""
   button_url=""
   bg=""
%}



{% include three-column.html title="Activities" %}

{% include image-only.html
   title="The Arena in Action"
   img="assets/images/lasertag-hero.webp"
   alt="Arena gameplay photo"
   width="400px"
%}


{% include text-only.html
   title="Welcome to The Arena"
   paragraph="<b>Sarnia Laser Tag</b> is your destination for indoor fun!"
   button=""
   button_url=""
%}

{% include text-image.html
   title="Image Left"
   paragraph="This has image left."
   img="assets/images/giftcard.svg"
   button="Learn More"
   button_url="/more"
   reverse=false
%}

{% include text-image.html
   title="Image Left"
   paragraph="This block has the image on the right and text on the left. On mobile, they stack."
   img="assets/images/spacebro2.svg"
   button="Learn More"
   button_url="/more"
   reverse=true
%}


{% include two-column.html
   title="Our Prices"
   section_desc="We make it easy to have fun without breaking the bank. Whether you're dropping in with a friend or planning a group outing, our activities are ready when you are—no stress, just good times."

   left_title=""
   left_include="pricing-grid.html"
   left_category="walkin"
   left_grid_title="Walk-In Activities"

   right_title=""
   right_include="pricing-grid.html"
   right_category="group"
   right_grid_title="Group Packages"
%}



{% include gallery.html title="The Arena in Action" images=page.gallery_images %}

{% include business-hours.html title="" %}