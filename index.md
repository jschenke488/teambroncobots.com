---
title: Broncobots
subtitle: FRC Team 1987
layout: page
callouts: home_callouts
show_sidebar: false
hero_image: images/Homeimg.jpg
hero_darken: true
hero_height: is-large
---

 <style>
.zoom {
/*  padding: 50px;*/
/*  background-color: green;*/
  transition: transform .2s; /* Animation */
/*  width: 200px;*/
/*  height: 200px;*/
  margin: 0 auto;
}

.zoom:hover {
  backface-visibility: hidden; 
  transform: scale(1.05); /* (150% zoom - Note: if the zoom is too large, it will go outside of the viewport) */
  
}
@import "TextAnimationEffect.scss";

.button {
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer
    background-color: white
}



</style>

<p><h1><center>
    Welcome!
</center></h1></p>

 We are the Broncobots, Team 1987, based out of Lee's Summit, Missouri. The team is made up of many students attending [Lee's Summit North High School](https://lsnhs.lsr7.org/), 5 coaches, several amazing mentors, and multiple gracious, corporate sponsors! Our team is dedicated to [FIRST](https://www.firstinspires.org/) (For Inspiration and Recognition of Science and Technology), our community, and working hard to encourage [STEM](https://www.kcstem.org/) (Science, Technology, Engineering, and Math) topics within our community. The Broncobots are looking forward to competing in each and every FRC Season. To learn more about our team, check out the About Us section of our website!

We will soon be building our 2023 robot and updating our website with current content.

**Check back here often for events, competitions, and general team information!**

<div class="descriptors">
<h1 style="font-size:64px;"><center>
    Broncobots are
  <span
     class="txt-rotate"
     data-period="2000"
     data-rotate='[ "inspirational.", "innovators.", "engineers.", "designers.", "accepting.", "listeners.", "thinkers.", "a family." ]'></span>
</center></h1>
<script src="{{ site.baseurl }}/assets/js/TextAnimation.js"></script>
</div>

---
<div style="text-align:center; vertical-align: middle; padding:0px 0;">
    <img src="images/2022TeamPic.jpg" alt=" " class="zoom" width="800" height="auto" >
</div>
---

<div class="zoom"></div> 

<center><h2 style="color:maroon">About us</h2></center>

<center>
    <button class="button" onclick="missionStatement()">Mission Statement</button>
    <button class="button" onclick="teamFocus()">Team Focus</button>
    <button class="button" onclick="teamHistory()">Team History</button>
</center>

<div id="missStat" style="display:none">
      The Broncobots are dedicated to helping the future through the recognition and advocacy of science, technology, engineering, and math. As FIRST participants, we strive to build a community devoted to education, innovation, and inspiration. By creating strong partnerships with mentors, teachers, and sponsors, we encourage communication and leadership as crucial parts of team success.  
</div>

<div id="teamFoc" style="display:none">
      <p>
         The focus of our team has been to reach out to our community in every way possible. We have attended school carnivals, school presentations, bingo raffles, Boy Scout meetings, school board meetings, and business meetings. We have been featured numerous times in publications, including three local newspapers, Honeywell newsletters, and even two books: FIRST Robotics: Rack N Roll and FIRST Robots: Behind The Design. The team created a video as an introduction to FIRST for the Lee's Summit community that aired on the local government channel and published a book about our team and our history.
    <br><br>
        In our own school, we have hosted booths at Freshmen Orientation Day, sponsored "Math and Science Teacher Appreciation Day," set up booths at football games, participated in Safe Halloween, and set up FIRST Robotics displays throughout the year. In cooperation with the two other Lee's Summit robotics teams, we have held PR meetings to schedule banquets, school visits, open houses, and community outreach projects. For three weeks this past summer, we sponsored robotics and engineering camps for elementary students.
    <br><br>
        We've made our name known throughout the community in various ways. We have presented at numerous Lee's Summit elementary schools, in addition to Lee's Summit middle schools, and a private Catholic school in a neighboring city. We have attended and presented at meetings for the Rotary Club, the Optimist Club, the National Tool and Machining Association, the Lee's Summit Economic Development Council, and the Kauffman Foundation. We also were excited to give presentations at Gail's Harley Davidson, Honeywell, the Engineering and Science Summit Institute at Kansas State University, and the Lee's Summit Chalk Walk. Together with the other two Lee's Summit robotics teams our team rotated staffing a booth at Downtown Days to reach out to all Lee's Summit citizens.
    <br><br>
        Over four years, we have sent over 1,500 letters to government officials. In 2008, there was a "Lee's Summit Robotics Day" proclamation from the mayor, and Governor Matt Blunt officially recognized and commended the FIRST Robotics Competition in the state of Missouri. Along with starting a mail campaign to government officials (fifteen different officials and federal offices), took the classic Flat Stanley and combined it with the spirit of FIRST to start our Flat Creation Campaign. This was designed to reach people outside our direct area of influence, like families and friends from other states and countries. During its time traveling, Flat Mammoth (from our 2008 Flat Creation Campaign) has visited a second grade classroom, attended a robot-themed movie night, enjoyed the warm weather in Honduras, and sat in the Missouri House of Representatives! 
    </p>
</div>

<div id="teamHist" style="display:none">
  <p>
     Over the years, the Broncobots have had many significant achievements. We've attended over 16 regionals over the years, going to the Greater Kansas City Regional and an out-of-state regional each year. Team 1987 has also competed in summer competitions such as Ozark Mountain Brawl and Lee's Summit's CowTown ThrowDown. We haven't kept quiet about what we do either. We've had over 60 presentations at schools and businesses. This number does not include our countless booths at Missouri State Fair, Lee's Summit's Downtown Days, Oktoberfest, and Kansas City Maker Faire. The team has been featured in countless newspaper articles, been on TV, and is even mentioned in a book. We've also initiated letter campaigns, media broadcasts, toilet paper drives, and much more. Team 1987 The Broncobots has accomplished much since our founding year. 
  </p>
</div>

<script>
function missionStatement() {
    let m = document.getElementById("missStat");
    let f = document.getElementById("teamFoc");
    let h = document.getElementById("teamHist");
    f.style.display = "none";
    h.style.display = "none";
    if (m.style.display === "none") {
        m.style.display = "block";
    } else {
        m.style.display = "none";
    }
} 
function teamFocus() {
    let m = document.getElementById("missStat");
    let f = document.getElementById("teamFoc");
    let h = document.getElementById("teamHist");
    m.style.display = "none";
    h.style.display = "none";
  if (f.style.display === "none") {
    f.style.display = "block";
  } else {
    f.style.display = "none";
  }
}
function teamHistory() {
    let m = document.getElementById("missStat");
    let f = document.getElementById("teamFoc");
    let h = document.getElementById("teamHist");
    f.style.display = "none";
    m.style.display = "none";
  if (h.style.display === "none") {
    h.style.display = "block";
  } else {
    h.style.display = "none";
  }
}
</script>
