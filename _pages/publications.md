---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
You can find my complete publications on <a href="https://scholar.google.com/citations?user=gNshB_kAAAAJ&hl=en&oi=ao">my Google Scholar profile.</a>
<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}-->

<!--{% include base_path %}-->

<!--{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}-->

 <tr onmouseout="porlight_stop()" onmouseover="porlight_start()">
            <td style="padding:20px;width:25%;vertical-align:middle">
              <div class="one">
                <div class="two" id='porlight_image'><img src='assets/beethoven_ons.jpg'></div>
                <img src='assets/beethoven_ons.jpg'>
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
            <td style="padding:20px;width:75%;vertical-align:middle">
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
