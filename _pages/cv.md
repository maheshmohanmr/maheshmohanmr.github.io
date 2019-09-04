---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
<button onclick="myFunction()">Last Update</button>

<p id="demo"></p>

<script>
function myFunction() {
  var x = new Date(document.lastModified);
  document.getElementById("demo").innerHTML = x;
}
</script>

Vision
======
> I had a very strong desire to become a teacher. My life's journey made me aware that great minds in history are normal people, and as history gets blurred with time, one can and one must create their own art to retain the history for the ‘future’. For this, as a researcher one needs to build something which is non-existent, and as a teacher, whatever I learn to teach, I need to (re)build them in front of students but only using the tools they possess (to instill the awareness). However, both roles look alike to me! I look forward to a postdoc to build more skill-sets needed for my achieving the above vision.

Academic History
======
* Ph.D. Scholar  in [Indian Institute of Technolgy Madras](https://www.iitm.ac.in/), 2014-2019 (exp)
  * Research Areas: [Image Processing, Computer Vision, and Computational Photography](http://www.ee.iitm.ac.in/ipcvlab/)
  * Advisor: [Prof. A. N. Rajagopalan](http://www.ee.iitm.ac.in/~raju/)
  * CGPA: 9.5/10 (Core 10/10 & Elective 9/10)
* M.Tech in [Govt. Engineering College Thrissur](http://gectcr.ac.in/), 2011-2013
  * Specialization: [Communication Engineering and Signal Processing](http://gectcr.ac.in/electronics-department/m-tech-ec/)
  * Advisor: [Prof. Sheeba V. S.](http://gectcr.ac.in/about-us/principals-profile/)
  * Thesis: Contourlet Transform based Medical Image Denosing
  * CGPA: 8.89/10 (Thesis: 10/10)
* B.Tech in [M G College of Engineering (CUSAT)](http://www.mgcet.com/), 2007-2011
  * Specialization: Electronics and Communication Engineering
  * Project: JPEG in Linux, done at [Center for Development of Imaging Technology](https://cdit.org/home-1).
  * Grade: First Class with Distinction  

Scholastic Achievements
======
* All India Rank 500 out of 2,16,367 in [Graduate Aptitude Test in Engineering (ECE)](https://en.wikipedia.org/wiki/Graduate_Aptitude_Test_in_Engineering)  2014.
* Institute Award for the best academic performance in Master's (in the class of year 2013).

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Professional Service
======
* Assisted [Prof. Rajagopalan A. N.](http://www.ee.iitm.ac.in/~raju/) in reviewing International Journal of Computer Vision (IJCV).
* Assisted [Prof. Kaushik Mitra](http://www.ee.iitm.ac.in/kmitra/) in reviewing National Conf. on Communications (NCC) 2017.
* Reviewer of [Indian Conf. on Computer Vision, Graphics and Image Processing](https://cvit.iiit.ac.in/icvgip18/) (ICVGIP) 2018 and [National Conf. for Computer Vision, Pattern Recognition, Image Processing and Graphics](http://ncvpripg.iitmandi.ac.in/submissions.html) (NCVPRIPG) 2017.
 
  
Conferences and Workshops Attended
======
* International
  * [International Conf. on Computer Vision](http://iccv2017.thecvf.com/) (ICCV) at Venice, Italy (2017)
* National
  * [ICVGIP](https://cvit.iiit.ac.in/icvgip18/) at ISB Hyderabad, Telengana (2018)
  * [NCVPRIPG](http://ncvpripg.iitmandi.ac.in/submissions.html) at IIT Mandi, Himachal Pradesh (2017)
  * [Summer School on Deep learning](https://cvit.iiit.ac.in/summerschool/index.html) at IIIT Hyderabad, Telengana (2016)
  * Workshop on [Computational Brain Research](https://ccbr.iitmadras.in/) at IIT Madras, Tamil Nadu (2015)
  * ICACC at RSET Cochin, Kerala (2013)

Grants
====== 
* For Research
  * [Google Research Travel Grant](https://buildyourfuture.withgoogle.com/scholarships/google-travel-scholarships/#!?detail-content-tabby_activeEl=india) to attend ICCV-2019 at Seoul, South Korea (1900 USD). 
  * [Microsoft Research](https://www.microsoft.com/en-us/research/lab/microsoft-research-india/?from=http%3A%2F%2Fresearch.microsoft.com%2Findia) and [ACM India-IARCS](https://www.iarcs.org.in/activities/grants.php) Travel Grant for ICCV-2017 at Venice, Italy (1900 USD).
  * Invited Speaker in ICVGIP 2018 and NCVPRIPG 2017 (by resp. Conf. Chairs).
  * Travel Grant for ICACC 2013 (by [TEQIP-2013](https://www.teqip.in/) via Govt. of India and World bank).
* For Education (via Scholarships) 
  * Doctoral Studies - funded by [Govt. of India, Ministry of Human Resource Development](https://mhrd.gov.in/).
  * Master’s Studies - funded by [All India Council for Technical Education](https://www.aicte-india.org/).

References
====== 
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>
<div class="row">
  <div class="column" style="background-color:#f8f8f8;">
    <h2><a href="http://www.ee.iitm.ac.in/~raju/">Prof. A. N. Rajagopalan, FIETE, FAvH, FNAE</a> </h2>
    <p>Professor, Department of Electrical Engineering</p>
<p>Indian Institute of Technology Madras</p>
<p> &#9993; href=mailto:<nowiki>raju@ee.iitm.ac.in?subject="HTML link">Click here to send us an email!!!</a> </p>
  </div>
  <div class="column" style="background-color:#f8f8f8;">
    <h2>Column 2</h2>
    <p>Some text..</p>
  </div>
</div>

</body>
</html>
