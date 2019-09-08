---
layout: archive
permalink: /publications/
author_profile: true
---
<!-- Om Nama Sivaya-->
<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}-->

<!--{% include base_path %}-->

<!--{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}-->

<!--<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">-->
  <!-- Hi, Jon Here. Please DELETE the two <script> tags below if you use this HTML, otherwise my analytics will track your page -->

  
  <meta name="author" content="Mahesh Mohan M R">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  
  <link rel="stylesheet" type="text/css" href="stylesheet.css">
  <link rel="icon" type="image/png" href="images/seal_icon.png">

<body>
  <table style="width:100%;border:0px;border-spacing:0px;border-collapse:collapse;margin-right:auto;margin-left:auto;"><tbody>
            <tr>
            <td style="padding:20px;border:0px;border-bottom: 1px solid #ddd;width:100%;vertical-align:middle">
              <heading>Research</heading>
              <p>
              I'm interested in image processing, computer vision, computational photography, and deep learning. Selected research publications are provided below: 
              </p>
                          </td>
          </tr>
</tbody></table>
         <table style="width:100%;border: 0px solid black;;border-spacing:0px;border-collapse:collapse;margin-right:auto;margin-left:auto;"><tbody>
           <!-- Om Nama Sivaya -->
          <!-- New paper ONS -->
          <tr onmouseout="font_stop()" onmouseover="font_start()">
            <td style="padding:20px;width:29%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <div class="one">
                <div class="two" id='font_image'><img src='../images/iccv_19_op1_ons_sqr.png'></div>
                <img src='../images/iccv_19_ip1_ons_sqr.png'>
              </div>
              <script type="text/javascript">
                function font_start() {
                  document.getElementById('font_image').style.opacity = "1";
                }
                function font_stop() {
                  document.getElementById('font_image').style.opacity = "0";
                }
                font_stop()
              </script>
            </td>
            <td style="padding:20px;width:71%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <a href="TODO">
                <papertitle>Unconstrained Motion Deblurring for Dual-lens Cameras</papertitle>
              </a>
              <br>
              <strong>Mahesh Mohan M. R.</strong>,
              <a href="https://www.cs.umd.edu/people/sgirish/">Sharath Girish</a>, and 
              <a href="http://www.ee.iitm.ac.in/~raju/">A. N. Rajagopalan </a>
              <br>
              <em>ICCV</em>, 2019 &nbsp; <font color="green"><strong>(Oral Presentation)</strong></font>
              <br> Coming soon ...
              <p></p>
              <p>Motion deblurring for dual-lens cameras possess an <q>ill-posedness</q>, which calls for a <q>prior</q> for depth-consistent deblurring. </p>
            </td>
          </tr>    
           <!-- New paper ONS -->
          <tr onmouseout="divide_stop()" onmouseover="divide_start()">
            <td style="padding:20px;width:29%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <div class="one">
                <div class="two" id='divide_image'><img src='../images/cvpr_18_ip_ons_sqr.png'></div>
                <img src='../images/cvpr_18_ip_ons_sqr.png'>
              </div>
              <script type="text/javascript">
                function divide_start() {
                  document.getElementById('divide_image').style.opacity = "1";
                }
                function divide_stop() {
                  document.getElementById('divide_image').style.opacity = "0";
                }
                divide_stop()
              </script>
            </td>
            <td style="padding:20px;width:71%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <a href="TODO">
                <papertitle>Divide and Conquer for Full-resolution Light Field Deblurring</papertitle>
              </a>
              <br>
              <strong>Mahesh Mohan M. R.</strong>
               and 
              <a href="http://www.ee.iitm.ac.in/~raju/">A. N. Rajagopalan </a>
              <br>
               <em>CVPR</em>, 2018
              <br>
              <a href="../files/Mohan_Divide_and_Conquer_CVPR_2018_paper.pdf">paper</a> /
               <a href="../files/Mohan_Divide_and_Conquer_CVPR_2018_suppl.pdf">supplement</a> /
              <a href="https://drive.google.com/file/d/1SbIOWWI4Hvbwe7dvh0m5QYbubDCai1dT/view">slides</a> / 
              <a href="../files/Mohan_Divide_and_Conquer_CVPR_2018_poster.pdf">poster</a> /
              <a href="../files/Mohan_Divide_and_Conquer_CVPR_2018.txt">bib</a> 
              <br>
              <p></p>
              <p>Full-resolution light field deblurring can be divided into <q>independent</q> subtasks, wherein a single task <q>reinforces</q> others. </p>
            </td>
          </tr>    
            <!-- New paper ONS -->
          <tr onmouseout="occl_stop()" onmouseover="occl_start()">
            <td style="padding:20px;width:29%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <div class="one">
                <div class="two" id='occl_image'><img src='../images/cvpr_18_su_op_ons_sqr.png'></div>
                <img src='../images/cvpr_18_su_ip_ons_sqr.png'>
              </div>
              <script type="text/javascript">
                function occl_start() {
                  document.getElementById('occl_image').style.opacity = "1";
                }
                function occl_stop() {
                  document.getElementById('occl_image').style.opacity = "0";
                }
                occl_stop()
              </script>
            </td>
            <td style="padding:20px;width:71%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <a href="TODO">
                <papertitle>Occlusion-Aware Rolling Shutter Rectification of 3D Scenes</papertitle>
              </a>
              <br>
              <a href="https://subeeshvasu.github.io//">Subeesh Vasu </a>,
              <strong>Mahesh Mohan M. R.</strong>,
               and 
              <a href="http://www.ee.iitm.ac.in/~raju/">A. N. Rajagopalan </a>
              <br>
 <em>CVPR</em>, 2018
              <br>
              <a href="../files/Vasu_Occlusion-Aware_Rolling_Shutter_CVPR_2018_paper.pdf">paper</a> /
               <a href="../files/Vasu_Occlusion-Aware_Rolling_Shutter_CVPR_2018_supp.pdf">supplement</a> / 
              <a href="../files/Vasu_Occlusion-Aware_Rolling_Shutter_CVPR_2018_poster.pdf">poster</a> /
              <a href="../files/Vasu_Occlusion-Aware_Rolling_Shutter_CVPR_2018_bib.txt">bib</a> 
              <br>
              <p></p>
              <p>A method for the scenario of a fast moving camera wherein <q>rolling shutter</q> distortions results in <q>intra-frame occlusions</q>. </p>
            </td>
          </tr>    
           <!-- New paper ONS -->
        <tr onmouseout="RS_stop()" onmouseover="RS_start()">
            <td style="padding:20px;width:29%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <div class="one">
                <div class="two" id='RS_image'><img src='../images/iccv_17_op_ons_sqr.png'></div>
                <img src='../images/iccv_17_ip_ons_sqr.png'>
                <!-- <div class="two" id='font_image'><img src='../images/iccv_19_op_2_ons_sqr.png'></div>
                <img src='../images/iccv_19_ip_ons_sqr.png'> -->
              </div>
              <script type="text/javascript">
                function RS_start() {
                  document.getElementById('RS_image').style.opacity = "1";
                }
                function RS_stop() {
                  document.getElementById('RS_image').style.opacity = "0";
                }
                RS_stop()
              </script>
            </td>
            <td style="padding:20px;width:71%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <a href="TODO">
                <papertitle>Going Unconstrained with Rolling Shutter Deblurring</papertitle>
              </a>
              <br>
              <strong>Mahesh Mohan M. R.</strong>, 
              <a href="http://www.ee.iitm.ac.in/~raju/">A. N. Rajagopalan </a>, and
              <a href="https://www.linkedin.com/in/guna-seetharaman-b4886310/">Guna Seetharaman</a>              
              <br>
               <em>ICCV</em>, 2017
<br>
              <a href="../files/R._Going_Unconstrained_With_ICCV_2017_paper.pdf">paper</a> /
               <a href="../files/R._Going_Unconstrained_With_ICCV_2017_supplemental.pdf">supplement</a> /
              <a href="https://drive.google.com/file/d/1y7Eb3jBU756K3mi84gv0DDREvQYGLDs8/view">slides</a> / 
              <a href="../files/R._Going_Unconstrained_With_ICCV_2017_poster.pdf">poster</a> /
              <a href="../files/R._Going_Unconstrained_With_ICCV_2017_bib.txt">bib</a> 
              <br>
              <p></p>
              <p>How can we bridge today's ubiquitous <q>rolling shutter</q> cameras with the well-studied conventional cameras, pertaining to <q>motion deblurring</q>?</p>
            </td>
          </tr>    
             <!-- New paper ONS -->
          <tr onmouseout="dynamic_stop()" onmouseover="dynamic_start()">
            <td style="padding:20px;width:29%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <div class="one">
                <div class="two" id='dynamic_image'><img src='../images/eccv_17_op_ons_sqr.png'></div>
                <img src='../images/eccv_17_ip_ons_sqr.png'>
              </div>
              <script type="text/javascript">
                function dynamic_start() {
                  document.getElementById('dynamic_image').style.opacity = "1";
                }
                function dynamic_stop() {
                  document.getElementById('dynamic_image').style.opacity = "0";
                }
                dynamic_stop()
              </script>
            </td>
            <td style="padding:20px;width:71%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <a href="TODO">
                <papertitle>Deep Decoupling of Defocus and Motion blur for Dynamic Segmentation</papertitle>
              </a>
              <br>
              <a href="https://abhijithpunnappurath.github.io/">Abhijith Punnapurath </a>,
              <a href="http://www.cs.umd.edu/~yogesh/">Yogesh Balaji </a>,
              <strong>Mahesh Mohan M. R.</strong>,
               and 
              <a href="http://www.ee.iitm.ac.in/~raju/">A. N. Rajagopalan </a>
              <br>
               <em>ECCV</em>, 2016
              <br>
              <a href="../files/eccv_paper.pdf">paper</a> /
               <a href="../files/eccv_sup.pdf">supplement</a> /
               <a href="../files/ecc_poster.pdf">poster</a> /
              <a href="../files/eccv_bib.txt">bib</a> 
              <br>
              <p></p>
              <p>Deep Learning is used to obtain the attributes of object motion and camera motion, which is then employed for segmenting moving object(s). </p>
            </td>
          </tr>    
              <!-- New paper ONS -->
          <tr onmouseout="kla_stop()" onmouseover="kla_start()">
            <td style="padding:20px;width:29%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <div class="one">
                <div class="two" id='kla_image'><img src='../images/kl_18_ip1_ons_sqr.png'></div>
                <img src='../images/kl_18_op1_ons_sqr.png'>              </div>
              <script type="text/javascript">
                function kla_start() {
                  document.getElementById('kla_image').style.opacity = "1";
                }
                function kla_stop() {
                  document.getElementById('kla_image').style.opacity = "0";
                }
                kla_stop()
              </script>
            </td>
            <td style="padding:20px;width:71%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <a href="TODO">
                <papertitle>Noise-aware Detail Enhancement in SEM imagery.</papertitle>
              </a>
              <br>
               <strong>Mahesh Mohan M. R.</strong>,
              <a href="http://www.ee.iitm.ac.in/~raju/">A. N. Rajagopalan </a> and
              <a href="https://www.zoominfo.com/p/Raj-Kuppa/-2062444008">Raj Kuppa</a>,
              <br>
              <em><a href="https://www.kla-tencor.com/"> KLA-Tencor</a>'s Neoteix</em>, 2018 &nbsp; <font color="green"><strong>(IIT Madras-Industry Collaboration)</strong></font>
              <br>
              <a href="https://drive.google.com/file/d/156KZ-iQiy8kqAjzVGHiDwHao3CesX5eL/view">paper</a> (rest, properietary of KLA, sorry.)
              <br>
              <p></p>
              <p> A fully-automatic yet efficient (via least squares) denoising framework based on a novel prior on SEM images, which eliminates the assumption of a (possibly erroneous) noise model.  </p>
            </td>
          </tr>  
            <!-- New paper ONS -->
          <tr onmouseout="gec_stop()" onmouseover="gec_start()">
            <td style="padding:20px;width:29%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <div class="one">
                <div class="two" id='gec_image'><img src='../images/icccc_13_op_ons_sqr.png'></div>
                <img src='../images/icccc_13_ip_ons_sqr.png'>
              </div>
              <script type="text/javascript">
                function gec_start() {
                  document.getElementById('gec_image').style.opacity = "1";
                }
                function gec_stop() {
                  document.getElementById('gec_image').style.opacity = "0";
                }
                gec_stop()
              </script>
            </td>
            <td style="padding:20px;width:71%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <a href="TODO">
                <papertitle>A novel method of Medical Image Denoising using Bilateral and NLM filtering.</papertitle>
              </a>
              <br>
               <strong>Mahesh Mohan M. R.</strong> and
              <a href="http://gectcr.ac.in/about-us/principals-profile/">Sheeba V. S.</a>,
              <br>
              <em>ICACC</em>, 2013 &nbsp; <font color="green"><strong>(Oral Presentation)</strong></font>
              <br>
              <a href="../files/ICACC_paper.pdf">paper</a> /
               <a href="../files/ICACC_slides.pdf">slides</a> /
              <a href="../files/ICACC_bib.txt">bib</a> 
              <br>
              <p></p>
              <p> Wavelet thresholding (Visushrink) is extended to Contourlet transform, in order to enhance the performance of bilateral and NLM filtering. </p>
            </td>
          </tr>  
           <!-- New paper ONS -->
          <!-- <tr onmouseout="dpzlearn_stop()" onmouseover="dpzlearn_start()">
            <td style="padding:20px;width:29%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <div class="one">
                <div class="two" id='dpzlearn_image'><img src='images/dpzlearn_after.jpg'></div>
                <img src='images/dpzlearn_before.jpg'>
              </div>
              <script type="text/javascript">
                function dpzlearn_start() {
                  document.getElementById('dpzlearn_image').style.opacity = "1";
                }
                function dpzlearn_stop() {
                  document.getElementById('dpzlearn_image').style.opacity = "0";
                }
                dpzlearn_stop()
              </script>
            </td>
            <td style="padding:20px;width:71%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <a href="https://arxiv.org/abs/1904.05822">
                <papertitle>Learning Single Camera Depth Estimation using Dual-Pixels</papertitle>
              </a>
              <br>
              <a href="http://rahuldotgarg.appspot.com/">Rahul Garg</a>,
              <a href="http://nealwadhwa.com">Neal Wadhwa</a>, Sameer Ansari,
              <strong>Jonathan T. Barron</strong>
              <br>
              <em>ICCV</em>, 2019 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
              <br>
              <p></p>
              <p>Considering the optics of dual-pixel image sensors improves monocular depth estimation techniques.</p>
            </td>
          </tr>
          <!-- New paper ONS -->
        <!--  <tr onmouseout="porlight_stop()" onmouseover="porlight_start()">
            <td style="padding:20px;width:29%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <div class="one">
                <div class="two" id='porlight_image'><img src='images/porlight_after.jpg'></div>
                <img src='images/porlight_before.jpg'>
              </div>
              <script type="text/javascript">
                function porlight_start() {
                  document.getElementById('porlight_image').style.opacity = "1";
                }
                function porlight_stop() {
                  document.getElementById('porlight_image').style.opacity = "0";
                }
                porlight_stop()
              </script>
            </td>
            <td style="padding:20px;width:71%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <a href="https://arxiv.org/abs/1905.00824">
                <papertitle>Single Image Portrait Relighting</papertitle>
              </a>
              <br>
              <a href="http://kevinkingo.com/">Tiancheng Sun</a>,
              <strong>Jonathan T. Barron</strong>, Yun-Ta Tsai,
              <a href="https://cseweb.ucsd.edu/~zex014/">Zexiang Xu</a>, Xueming Yu,
              <a href="http://ict.usc.edu/profile/graham-fyffe/">Graham Fyffe</a>, Christoph Rhemann, Jay Busch,
              <a href="https://www.pauldebevec.com/">Paul Debevec</a>,
              <a href="https://cseweb.ucsd.edu/~ravir/">Ravi Ramamoorthi</a>
              <br>
              <em>SIGGRAPH</em>, 2019
              <br>
              <a href="https://www.youtube.com/watch?v=yxhGWds_g4I">video</a> /
              <a href="https://petapixel.com/2019/07/16/researchers-developed-an-ai-that-can-relight-portraits-after-the-fact/">press</a> /
              <a href="data/SunSIGGRAPH2019.bib">bibtex</a>
              <br>
              <p></p>
              <p>Training a neural network on light stage scans and environment maps produces an effective relighting method.</p>
            </td>
            </tr> -->
                   <!--    <tr>
           <b>Dissemination</b>: All published papers are available online. Click on the title of the paper 
for the details. If you are unable to download a paper listed here, that you are 
looking for, please write to me to get a copy.<br>
<b>Copyright notice</b>: Copies of the papers are provided here for 
convenient dissemination of scholarly work. They can be downloaded for 
non-commercial research and education purposes only. Copyrights of the 
papers usually belong to the publishers of the journals or proceedings and 
must be adhered to by anyone using these materials.<br>
<b>Author Naming Convention</b>: Theoretical computer science (as in 
mathematics), as a culture, follows the convention of ordering the author names 
in <b><a 
href="http://www.ams.org/profession/leaders/culture/CultureStatement04.pdf">alphabetical 
in last names</a></b>.
<br>
<hr>
<center>
<i>Not everything that can be counted counts, and not everything that counts can be counted. -- Albert Einstein</i>
</center>
 </tr>-->        
     <table style="width:100%;border:0px;border-spacing:0px;border-collapse:collapse;margin-right:auto;margin-left:auto;"><tbody>
            <tr>
            <td style="padding:11px;width:100%;vertical-align:middle;border:0px">
                 <p>
               <b>Copyright notice</b>: Copies of the papers are provided here for 
convenient dissemination of scholarly work. They can be downloaded for 
non-commercial research and education purposes only. Copyrights of the 
papers usually belong to the publishers of the journals or proceedings and 
must be adhered to by anyone using these materials. For other materials, feel free to use it at your convenience for good deeds! <br>
<br>
<hr>
<center>
<i>Pure mathematics is in its way the poetry of logical ideas. When the solution is simpler, God is answering -- Einstein</i>
</center>
              </p>
            </td>
          </tr>
</tbody></table>
