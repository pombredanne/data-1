---
layout: post
title: 'Smithsonian Institute EDAN API - PHP Library'
url: http://publicprivatesector.org/news/2013/11/14/smithsonian-institute-edan-api-php-library/
image: https://s3.amazonaws.com/kinlane-productions/php-logo-300.png
---

<a href="https://github.com/si-data/smithsonian-edan"><img src="https://s3.amazonaws.com/kinlane-productions/php-logo-300.png" align="right" width="325" /></a>
<p>To help support the upcoming <a href="http://www.eventbrite.com/e/luce-foundation-center-hackathon-tickets-7945919459">Luce Foundation Center Hackathon</a>, I was asked to help provide a PHP library for developers to use when building web or mobile applications using the Smithsonian Institue EDAN API.</p>

<p>The Smithsonian Institue EDAN API is currently in a private BETA so you have to be participating in the hackathon or invited to work with the API. However, as I do with all my work I wanted to make the library publicly available, and openly licensed so others can use.</p>

<p>The Smithsonian Institue EDAN API allows access to meta data around Smithsonian collections. I started with a main PHP class:</p>

<ul class="mainlist">
<li>edan (edan.php)</li>
</ul>

<p>With one main meta search method:</p>

<ul class="mainlist">
<li>metadataQuery</li>
</ul>

<p>With four tagging methods:</p>

<ul class="mainlist">
<li>addTag</li>
<li>agetTags</li>
<li>amodifyTag</li>
<li>aremoveTag</li>
</ul>

<p>With ten tagging methods:</p>

<ul class="mainlist">
<li>addCollection</li>
<li>modifyCollection</li>
<li>approveCollection</li>
<li>mergeCollection</li>
<li>deleteCollection</li>
<li>addItemToCollection</li>
<li>reviewItemsInCollection</li>
<li>modifyItemInCollection</li>
<li>removeItemFromCollection</li>
<li>getItemDataFromCollection</li>
</ul>

<p>I have made three separate sample files:</p>

<ul class="mainlist">
<li>metadataQuery.php</li>
<li>tags.php</li>
<li>collections.php</li>
</ul>

<p>The <a href="https://github.com/si-data/smithsonian-edan">Smithsonian Institute EDAN API PHP Library</a> is meant to be instructional, teaching you about the EDAN API interface, but also save you time coding.</p>

<p>Its not the best design for production, but will help walk new users through the EDAN API and demostrate what is posssible with search, tagging and building collections.</p>

<p>You can download the The Smithsonian Institute EDAN API PHP Library is available on <a href="https://github.com/si-data/smithsonian-edan">Github</a>. You can leave comments or issues there, or feel free to ping @kinlane.</p>
