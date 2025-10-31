---
permalink: /
title: "Ali Haider Ismail"
author_profile: false
classes: .large-profile-image
redirect_from: 
  - /about/
  - /about.html
---

<div style="display: flex; align-items: flex-start; gap: 30px; margin-bottom: 30px; flex-wrap: wrap;">
  <div style="flex-shrink: 0; min-width: 250px;">
    <img src="{{ base_path }}/images/suit-full-righttilt.png" alt="Ali Haider Ismail" style="width: 100%; max-width: 300px; border-radius: 50%;">
  </div>
  <div style="flex: 1; min-width: 300px;">
    <p>I am a Ph.D. Candidate in Economics at UCLA. My research interests are in monetary economics, macroeconomics, intermediation, and financial markets.</p>
    
    <p>Contact me at: <a href="mailto:ali.haider.ismail@gmail.com">ali.haider.ismail@gmail.com</a></p>
    
    <p>
      <a href="{{ base_path }}/files/ismail-cv.pdf" class="btn btn--primary">Download CV</a> 
	</p>
	<p>
      <a href="{{ base_path }}/files/research-statement.pdf" class="btn btn--primary">Download Research Statement (coming soon)</a> for a summary of my job market paper and my research agenda.
    </p>
  </div>
</div>

<!-- <img src="{{ base_path }}/images/suit-full-righttilt.png" alt="Ali Haider Ismail" style="width: 300px; border-radius: 50%;"> -->
<!---->
<!-- I am a Ph.D. Candidate in Economics at UCLA. My research interests are in monetary economics, macroeconomics, intermediation, and financial markets. -->
<!---->
<!-- Contact me at: <a href="mailto:ali.haider.ismail@gmail.com">ali.haider.ismail@gmail.com</a> -->
<!---->
<!-- <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary">Download CV</a>  -->
<!---->
<!-- <a href="{{ base_path }}/files/research-statement.pdf" class="btn btn--primary">Download Research Statement</a> -->
<!-- for a summary of my job market paper and my research agenda.  -->

Working Papers
======
  <ul>{% for post in site.research reversed %}
    {% include archive-single-2.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
