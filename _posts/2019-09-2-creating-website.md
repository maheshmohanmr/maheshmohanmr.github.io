---
title: 'Want a similar webpage for yourself?'
date: 2019-09-2
permalink: /posts/2019/09/create-website/
tags:
  - Tech tips
---
<!-- ONS -->
 &nbsp; &nbsp; &nbsp; &nbsp;  During my "first" friendly yet long encounter with html scripts, I often asked myself: "Why endure this long fight?". Every time, I shyly answered: <q>To make someone's long fight short</q>. For not fooling myself, or along the first principle  of [Ricahrd Feynman](https://en.wikipedia.org/wiki/Richard_Feynman) that <q><i>you must not fool yourself – and you are the easiest person to fool.</i></q>, a blog post is born – to help you with your website. For those who are going ahead, wish you a <q>Happy Website building</q>! All are welcome.

Instructions to get your website
======
 &nbsp; &nbsp; &nbsp; &nbsp; This website is optimized for Grad students, who usually have representative image for each publications (Computer Vision, here I come!), who can contribute materials for teaching, talks, etc. (Educators, find this!) and write occasional blog posts (ahem). As I started building this website with zero knowledge of HTML scripts, sadly, I cannot ask for any pre-requisite (so for the html pros out there, sorry if I sound childish!). These are the steps:  
*  Register a GitHub account if you don't have one and confirm your e-mail (required!). Refer [here](https://www.wikihow.com/Create-an-Account-on-GitHub). When you choose a <q>Github username</q>, select it as your <q>desired domain name</q> in mind, i.e., select <q>your GitHub username</q> for the domain [your GitHub username].github.io. <br>
* Fork [this repository](https://github.com/maheshmohanmr/maheshmohanmr.github.io) by clicking the "fork" button in the top right. (spot "fork" button in Fig. 1).<br> 
* Go to the repository's settings (see Fig. 1). Rename the repository "[your GitHub username].github.io", which will also be your website's URL. Next, scroll down this <q>settings page</q> to reach option  <q>Github Pages</q> and select the source as <q>master branch</q>.  
<br>
![sdf](/assets/website_ons.png){:class="img-responsive"}
<center>Fig. 1: Showing <q>Fork</q> and <q>Setting</q> buttons (blue) and <q>where to tweak</q> (green, black) </center>
<br> <b>Congratulations, now you have a website on your own</b>. <q>You can replace my data as follows</q>!.

Where to tweak for what?
-----
(Note: I always consider the root as the outer one (./), i.e., the one in Fig. 1 where you can see the folders: \_data, \_drafts, etc. 
(For quick reference of <q>where to tweak</q>, refer Fig. 1.)<br>
* First, edit the ./\_config.yml with your details, e.g., avatar for your profile picture; url and repository as your corresponding links; timezone; etc.<br>
* Coming to the tabs and corresponding headers (i.e., Research Talks Teaching etc,), if you want to have something different (like Publications Projects Talks etc) change appropriately the ./\_data/navigation.yml.<br>
* Information of your home page can be set from ./\_pages/\_about.md.<br>
* To change the publications, edit ./\_pages/\_publications.md. Note well that the image tag for each publications (that have eight occurences) need to be different for proper animations, e.g. the first paper here has <q>font\_</q> as its tag.<br>
* CV can be set from ./\_pages/\_cv.md.<br>
* The footnotes for each tab can be edited from  ./\_pages/<q>corresponding</q> .md files.<br>
* Contents for the tabs: Talks and Teaching can be changed using the files within ./\_talks, and ./\_teaching, respectively.<br>
* Contents for the tabs: Quotes and Blogposts can be changed using the files within ./\_portfolio, and ./\_posts, respectively.<br>
* For publications, there is no restriction of which folder to put files (e.g., pdfs and images, we put in ./\_files, and ./\_images, respectively)  and invoke. To put, click upload button (right-top) and upload the files. <br>
* However, images for blogposts need to be in ./asset folder for working (don't know why). <br>
* Editing a file, I mean, click the respective file, then click the pencil button (right-top), and edit. Once you finish editing, click <q>Commit changes</q> at the bottom. (After commiting,  updates to the website shall happen within few minutes.).
<br>
<hr>
 <center>Have your own webpage! (I would like to know whether my effort has helped anyone. If you have few seconds, send an email with the link of your webpage; let our hearts smile. Thank you!).</center> <br><center> <b>May your research, teaching and materials soar to great heights.</b> </center>
















