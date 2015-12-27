---
layout: page
title: Phil Rogers
tagline: Some blog about running...
---
{% include JB/setup %}
 
<div class="container">
	
	<div class="col-md-9">
	{% for post in site.posts %}

    	<div class="row">
        	
					<span><a href="{{ BASE_PATH }}{{ post.url }}"  style="text-decoration: none"><h3>{{ post.title }}</h3></span>&nbsp;&nbsp;
                    <br>
					<b> {{ post.date | date_to_string }}</b>
					
					
					<br>
						{{ post.summary }}</a>
					<br><a href="https://twitter.com/share" class="twitter-share-button" data-url="http://philrogers.me{{ BASE_PATH }}{{ post.url }}" data-via="philmonkey">Tweet</a><br>
                    
                    </div>
        	
        {% assign last = 1 %}	
	
	{% endfor %}	

    </div>

</div>


        