---
layout: archive
permalink: /publications/
author_profile: true
---
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
              I'm interested in image processing, computer vision, computational photography, and deep learning. Selected publications are provided below: 
              </p>
            </td>
          </tr>
</tbody></table>
         <table style="width:100%;border: 0px solid black;;border-spacing:0px;border-collapse:collapse;margin-right:auto;margin-left:auto;"><tbody>
          <!-- New paper ONS -->
          <tr onmouseout="font_stop()" onmouseover="font_start()">
            <td style="padding:20px;width:25%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <div class="one">
                <div class="two" id='font_image'><img src='../images/iccv_19_op_ons.png'></div>
                <img src='../images/iccv_19_ip_ons.png'>
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
            <td style="padding:20px;width:75%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
              <a href="TODO">
                <papertitle>Unconstrained Motion Deblurring for Dual-lens Cameras</papertitle>
              </a>
              <br>
              <strong>Mahesh Mohan M. R.</strong>,
              <a href="http://www.cs.cmu.edu/~asrivats/">Sharath Girish</a>, and 
              <a href="https://people.eecs.berkeley.edu/~klein/">A. N. Rajagopalan </a>
              <br>
              <em>ICCV</em>, 2019 &nbsp <font color="red"><strong>(Oral Presentation)</strong></font>
              <br>
              <br> Paper coming soon ...
              <p></p>
              <p>Dual-lens cameras warrants a new motion blur model and an optimization protocol for depth-consistent deblurring. </p>
            </td>
          </tr>    
           <!-- New paper ONS -->
          <tr onmouseout="dpzlearn_stop()" onmouseover="dpzlearn_start()">
            <td style="padding:20px;width:25%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
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
            <td style="padding:20px;width:75%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
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
          <tr onmouseout="porlight_stop()" onmouseover="porlight_start()">
            <td style="padding:20px;width:25%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
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
            <td style="padding:20px;width:75%;vertical-align:middle;border:0px;border-bottom: 1px solid #ddd;">
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
            </tr>
           </tbody></table>
    
