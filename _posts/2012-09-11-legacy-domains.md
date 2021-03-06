---
permalink: /blog/legacy-domains.html
layout: post
title: "Six legacy domains are expiring"
tags: get-code
---
<p><span>As part of the federal <a href="http://www.usa.gov/WebReform.shtml">.gov web reform</a> project, we're eliminating six of our legacy domains. Going forward, our only supported domain is search.usa.gov (or search.yoursite.gov, if you've requested <a href="/manual/get-code.html#cname">DNS masking</a>).</span></p>
<p><span>What do you need to do? I</span><span>f your URL starts with any of the following six legacy domains, </span><span>you must update your HTML form code.</span><span></span></p>
<ol><li><span>firstgovsearch.gov</span></li>
<li><span>searchusa.gov</span></li>
<li><span>usasearch.gov</span></li>
<li><span>(Spanish) buscador.gov</span></li>
<li><span>(Spanish)  buscadorusa.gov</span></li>
<li><span>(Spanish)  usabuscador.gov</span></li>
</ol><p><span>Specifically, you have to update the action of your <a href="/manual/get-code.html">form </a></span><span><a href="/manual/get-code.html">code</a> to call search.usa.gov </span><span>(or search.yoursite.gov)</span><span>.</span></p>
<blockquote>
<p><span>&lt;form method="get" action="http://search.usa.gov/search"&gt;</span></p>
</blockquote>
<p><span></span><span>Note that, if you don't update your form code, your search results </span><span>page will no longer work.</span></p>
