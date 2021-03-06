---
permalink: /manual/header-footer.html
layout: post
title: "How to Customize the Header and Footer of Your Results Page"
tags: how-to user-interface
---
<p>Select how you'd like to customize your header and footer. The fields that appear on the page will change based on the option you select.</p>
<h2>Option 1. Use a managed header and footer</h2>
<p>Fill out the fields to generate a predefined header and footer.</p>
<p><strong>Color</strong></p>
<p>Customize the color of your header background and text by clicking on the color picker text field. Enter a valid three- or six-digit hex value or pick a color by dragging the cross-hair icon <img alt="crosshair icon" src="http://search.usa.gov/javascripts/jscolor/cross.gif?1332168483"/> inside the color picker window. Drag the triangle icon <img alt="arrow icon" src="http://search.usa.gov/javascripts/jscolor/arrow.gif?1332168483"/> to control the color saturation. When you are done, click anywhere outside the color picker window.</p>
<p><strong>Header URL, text, and image</strong></p>
<p><em><strong>URL.</strong> </em>Provide us with the URL for your website's homepage. We'll use it to provide a link back to you from your header text, image, or both.</p>
<p><em><strong>Text.</strong> </em>Fill out the text you'd like to appear in your header. We've pre-populated this field with your <a href="/manual/site-information.html">site name</a>. Edit the same name, or delete it, if you don't want this text to appear in your header.</p>
<p><em><strong>Image.</strong> </em>Use the Browse&#8230; option to upload the logo or image that you'd like to appear in the header, if any. If you don't have header text, the image will be center-aligned. If you do have header text, the image will be right-aligned. Click on the option, Mark header image for deletion, to delete an uploaded image.</p>
<p><strong>Header and footer navigation</strong></p>
<p>Fill out the titles and URLs if you'd like to add navigation to your header and footer. Use the arrows on the left to rearrange the display order of the links. See the sample results page below that includes navigation.</p>
<p><img src="http://f22818b4dfc10241d8a3-f1564c64756a8cfee25b6b19953b1d23.r31.cf2.rackcdn.com/tumblr_m1ar9q6nXN1qid15q.png"/></p>
<h2>Option 2. Use CSS and HTML code to create a custom header and footer</h2>
<p>Use this option to more closely replicate the exact header and footer on your website.</p>
<p>In the first box, enter CSS to customize the header and footer of your search results page. We'll run a validation check to ensure your CSS is valid.</p>
<p>In the second box, enter HTML to customize the header of your search results page. In the third box, enter HTML to customize the footer of your search results page. Be sure to enter <a href="http://webdesign.about.com/od/beginningtutorials/a/aa040502a.htm">absolute hyperlinks</a>, not relative links. </p>
<p>Click on the link, Validate, to check your HTML markup at <a href="http://validator.w3.org/nu" target="_blank"><a href="http://validator.w3.org/nu">http://validator.w3.org/nu</a></a>. We'll also run a validation check to ensure that no JavaScript is included in your HTML code. We'll also check to ensure no CSS style or link elements are included. To include CSS, specify inline CSS within an opening tag.</p>
<p><strong>Invalid CSS</strong></p>
<p>&lt;html&gt;<br/>&lt;body&gt;<br/>&lt;style&gt; h1 { color: blue } &lt;/style&gt;<br/>&lt;link href=”http://www.yoursite.gov/custom.css” type=”text/css” /&gt;<br/>&lt;/body&gt;<br/>&lt;/html&gt;</p>
<p><strong>Valid CSS</strong></p>
<p>&lt;h1 style="color: blue;"&gt;Your Heading&lt;/h1&gt;</p>
<p><a id="mobile" name="mobile"></a></p>
<h2>Customize your mobile header</h2>
<p>We use device detection to show mobile-friendly search results on mobile phones. (Searchers using tablets and desktop computers see the full, classic header as you set it up above.)</p>
<p><strong>Default mobile header</strong></p>
<p>By default, searchers on mobile phones see the header, <em>YourSiteName Mobile</em>. If you list only one domain on the <a href="/manual/domains.html">Domains</a> page, we link your header to this domain. See the sample default mobile header below for <a href="http://www.howto.gov">HowTo.gov</a>.</p>
<p><img src="http://f22818b4dfc10241d8a3-f1564c64756a8cfee25b6b19953b1d23.r31.cf2.rackcdn.com/tumblr_meazaml0781qid15q.png"/></p>
<p><strong>Custom mobile header</strong></p>
<p>You can customize your mobile header to include a logo. You can also edit or add your mobile homepage URL.</p>
<p>The logo must be less than 56&#160;KB. We recommend it be no wider than 320 pixels.</p>
<p>You can link to your classic homepage (e.g., <a href="http://www.agency.gov">http://www.agency.gov</a>) or to your specific mobile homepage (e.g., <a href="http://m.agency.gov">http://m.agency.gov</a>). If you use device detection on your website, we recommend that you link to your classic homepage for a more seamless mobile experience. </p>
<p>See the sample custom mobile header below for the <a href="http://m.usa.gov">m.USA.gov</a> results page.</p>
<p><img src="http://f22818b4dfc10241d8a3-f1564c64756a8cfee25b6b19953b1d23.r31.cf2.rackcdn.com/tumblr_meazs7WsWk1qid15q.png"/></p>
<blockquote>
<p><em><strong>Troubleshooting tip:</strong> </em>You can implement a drop-down menu using CSS (and without using JavaScript). For more information, read tips at <a href="http://www.alistapart.com/articles/horizdropdowns/"><a href="http://www.alistapart.com/articles/horizdropdowns">http://www.alistapart.com/articles/horizdropdowns</a></a>.</p>
</blockquote>
<p><a href="http://usasearch.howto.gov">USASearch</a> &gt; [Admin Center](http://search.usa.gov/affiliates/home) &gt; YourSite &gt; Header and Footer</p>
