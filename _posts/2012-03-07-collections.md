---
permalink: /manual/collections.html
layout: post
title: "How to Create Collections Within Our Index"
tags: how-to collections
---
[USASearch](http://usasearch.howto.gov) > [Admin Center](http://search.usa.gov/affiliates/home) > YourSite > Collections

<p>Would you like searchers to be able to narrow results to a specific subset of content within your site or on another site?</p>
<p><strong>Step 1. Create a Collection</strong></p>
<p>Create a named collection across any set of domains, subdomains, or subfolders.</p>
<p>Enter a name for the collection (e.g., FAQs).</p>
<p>Enter the URLs that make up this collection. Start each URL prefix with http:// and end it in a trailing slash (/) to avoid unintended matches (e.g., <a href="http://publications.agency.gov/docs/">http://publications.agency.gov/docs/</a> and http://answers.agency.gov/).</p>
<p><img alt="image" src="http://f22818b4dfc10241d8a3-f1564c64756a8cfee25b6b19953b1d23.r31.cf2.rackcdn.com/tumblr_m0j67qCpD31qid15q.png"/></p>
<p><strong>Step 2. Opt to Show in Sidebar</strong></p>
<p>Click on the <a href="/manual/sidebar.html">Sidebar</a> option in the left-hand menu. Check the option, Show in Sidebar, to allow searchers to see navigation options in the left-hand column of the results page.</p>
<p><strong>Step 3. Check Your Search Results Page</strong></p>
<p>Searchers will see an option to narrow their search results to pages in this collection in the left-hand navigation on the results page.</p>
<p><img alt="image" src="http://f22818b4dfc10241d8a3-f1564c64756a8cfee25b6b19953b1d23.r31.cf2.rackcdn.com/tumblr_m0j6jwQoHO1qid15q.png"/></p>
<blockquote>
<div>
<p><em><strong>Did you know?</strong> </em>You can set up a search box on your website that limits results to your collection. </p>
<p>Start with the standard form snippet on the <a href="/manual/get-code.html">Get Code</a> page in the Admin Center. Change the form action to action="http://search.usa.gov/search/docs" and add the following line to limit the results to your collection. </p>
<p>&lt;input type="hidden" name="dc" value="###"&gt;.</p>
<p>The value is the number for your collection ID, which is visible in the URL when you edit your collection in the Admin Center.</p>
<p>See the sample search box below that is limited to news releases in FTC.gov's <a href="http://www.ftc.gov/opa/index.shtml">Newroom</a> for a search on <em>privacy</em>.</p>
<p><img alt="image" src="http://f22818b4dfc10241d8a3-f1564c64756a8cfee25b6b19953b1d23.r31.cf2.rackcdn.com/tumblr_mezhnwedQK1qid15q.png"/></p>
<p><em>Newsroom page with a search box that is limited to news </em></p>
<p><img alt="image" src="http://f22818b4dfc10241d8a3-f1564c64756a8cfee25b6b19953b1d23.r31.cf2.rackcdn.com/tumblr_mezhr7VJZU1qid15q.png"/></p>
<p><em>Search results page that returns news results </em><em>only</em></p>
</div>
</blockquote>
