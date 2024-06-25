---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: SERVICES
icon: fa fa-cogs fa-fw w3-margin-right
permalink: /services/
txtAlign: justify
---

<div class="w3-bar w3-black">
    <button class="w3-bar-item w3-button tablink w3-blue" onclick="openService(event,'ComputerScience')">Computer Science</button>
    <button class="w3-bar-item w3-button tablink" onclick="openService(event,'Chess')">Chess</button>
    <button class="w3-bar-item w3-button tablink" onclick="openService(event,'Others')">Others</button>
    <button class="w3-bar-item w3-button tablink" onclick="openService(event,'ClarificationNotes')">Notes</button>
</div>

<div id="ComputerScience" class="w3-container w3-border service">
  <h4><b>Introduction:</b></h4>
  <p>My name is Taha Rostami, born in Iran and currently residing in Canada. Since 2013, I have studied and worked in various areas of Computer Science, including but not limited to Software Design, Development and Testing, Machine Learning and Data Science, Automated Reasoning, and Optimization. Detailed information about my educational history, CV, software and tools, tutorials, and publications can be found on different pages of my website. I offer the following services in computer science:</p>

  <h4><b>Teaching:</b></h4>
  <p>I am passionate about teaching, especially in the field of computer science. While public education, such as that offered by universities, helps many people learn, there is always room for improvement. Many individuals worldwide find standardized courses uncustomized to their needs, leading to frustration or even disappointment. Over the years, I have gained valuable experience in both public and private education.</p>
  <p>In the public sector, I have worked as a teaching assistant in courses like advanced programming and published videos on well-known platforms like Faradars, which had a 5% acceptance rate at the time of my publication. In the private sector, I have helped individuals achieve significant milestones, such as gaining acceptance into top universities like Tehran University, securing admissions to universities abroad, such as the University of New Brunswick in Canada, and obtaining jobs at companies like Fiddlehead Technology in Canada. I have also assisted individuals in learning research methods and completing their theses after long struggles.</p>
  <p>Regardless of your age or level of knowledge in computer science, I would be happy to help you gain the knowledge and expertise you desire. I offer teaching services in a variety of subjects, ranging from mathematics and algorithms to coding, artificial intelligence, and more.</p>

  <s><h4><b>Development:</b></h4>
  <p>Over the years, I have developed numerous software applications for companies, individuals, and research/educational purposes. Some of these projects, such as Harif, have won awards issued by universities. Showcases of my projects and mini-projects are available on my GitHub, website, and YouTube channel. I accept orders for designing and developing software across various domains, including web applications, PC applications, management software, web scrapers, AI-powered software, and more.</p></s>

<h4><b>Consultation</b></h4>
  <p>I have experience offering consultation sessions aimed at assisting individuals in various aspects of their educational and professional journeys since 2018. My services include guiding individuals through university entrance examinations, preparing for job interviews, selecting suitable references and learning resources, making informed career decisions in computer science, reviewing and completing coding projects, and more.</p>

</div>

<div id="Chess" class="w3-container w3-border service" style="display:none">
  <h4><b>Introduction:</b></h4>
  <p>My name is Taha Rostami, born in Iran and currently residing in Canada. Until 2013, I was an active chess player and a member of the Iranian National Team, reaching a peak FIDE rating of 2105, which was a high rating for Iranian chess players at the time. My team and I secured third place in the Asian Youth Rapid Chess Championship. During my professional chess career, I had notable victories and draws against well-known Iranian chess players, including Alireza Firouzja, Mohammad Amin Tabatabaei, Khalil Mousavi, Shahin Lorparizangeneh, and Arian Gholami. Although I stopped practicing chess professionally, I continue to play online and in informal settings, achieving wins or draws against many prominent players worldwide. My FIDE profile and current Lichess account are available for reference. I offer the following services in chess:</p>

  <h4><b>Games:</b></h4>
  <p>It is common for chess players to seek training opponents to practice new openings, strategies, or other aspects they are learning. For this or any other reason, I offer to play games. This service is provided as unrated games by default. Factors such as whether the game is rated/unrated, public/private, your rating, specific openings, game format, and timing can be customized.</p>

  <h4><b>Coaching:</b></h4>
  <p>Although my knowledge hasn't been refreshed in a long time, my deep dedication to chess means I still recall the lessons learned in detail. Additionally, my career in computer science has equipped me with knowledge of computer tools and algorithms used in chess, allowing me to merge these two worlds effectively. Whether you want to learn or practice chess for competition, fun, or other goals, I believe I can significantly help you depending on your level. My students have ranged from those wanting to surpass friends in casual play to those striving for national team gold medals, and most of them have achieved their goals through our training.</p>
</div>

<div id="Others" class="w3-container w3-border service" style="display:none">
 <h4><b>Introduction:</b></h4>
  <p>Based on my skills in Computer Science, Chess, or being a native Farsi speaker, if you feel that I might be able to help you in a way that my listed services do not cover, please do not hesitate to reach out to me to see if I can assist you.</p>
</div>

<div id="ClarificationNotes" class="w3-container w3-border service" style="display:none">

  <h4><b>Service Availability:</b></h4>
  <p>Services may be enabled or disabled. All services are currently enabled except those with a line through them. A disabled service does not mean it won't be available in the future; it is simply currently unavailable.</p>

  <h4><b>Language Proficiency:</b></h4>
  <p>I offer services that require conversation in both Farsi and English. My native language is Farsi. Although I have known English for years, I began speaking it regularly in 2023. Due to this, there might be a noticeable difference in the quality of some services based on the chosen language. If there are concerns about my English proficiency, clients can check my videos or request a brief experimental conversation.</p>

  <h4><b>Pricing:</b></h4>
  <p>Prices are generally flexible and based on mutual agreement. The three most impactful factors are the living cost in my current location when the service is requested, my level of expertise in that service, and the financial ability and current situation of the requester concerning their goals. Financial ability is considered in one direction only: If you are wealthy, the cost will not exceed the actual price of the service. Conversely, if you cannot afford the service but still wish to use it, you may not be charged, can pay in installments, or receive a discount, depending on our agreement. For services without a fixed price, I will consult friends who provide similar services to determine a price range or search online for guidance. The final price will be determined by mutual agreement.</p>
</div>

<script>
function openService(evt, serviceName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("service");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" w3-blue", "");
  }
  document.getElementById(serviceName).style.display = "block";
  evt.currentTarget.className += " w3-blue";
}
</script>





