---
layout: page
title: Phil Rogers
tagline: A blog by a Dartford local
---
{% include JB/setup %}

<div class="container">
	
	<div class="col-md-9">
	{% for post in site.posts %}
	{% assign monkey = forloop.index | modulo:4 %}
	{% case monkey %}
	{% when 1,3 %}
    	<div class="row">
        	<div class="col-md-6">
					<span><a href="{{ BASE_PATH }}{{ post.url }}"><b>{{ post.title }}</b></a></span>
					<br><b> {{ post.date | date_to_string }}</b>
					<a href="https://twitter.com/share" class="twitter-share-button" data-url="http://philrogers.me{{ BASE_PATH }}{{ post.url }}" data-via="philmonkey">Tweet</a>
					
					<br>
						{{ post.summary }}
					<br><br>
 
        	</div>
        {% assign last = 1 %}	
	{% when 0,2 %}
		<div class="col-md-6">
			<span><a href="{{ BASE_PATH }}{{ post.url }}"><b>{{ post.title }}</b></a></span>
			<br><b> {{ post.date | date_to_string }}</b>
			<a href="https://twitter.com/share" class="twitter-share-button" data-url="http://philrogers.me{{ BASE_PATH }}{{ post.url }}" data-via="philmonkey">Tweet</a>
			
			<br>
			{{ post.summary }}
			<br><br>   
	
        </div>

        
        </div>
        {% assign last = 0 %}
		{% if monkey == 5 %}
			<div class="row">
			ad, yo - full width one too!?
			</div>
		{% endif %}        
	{% endcase %}
	{% endfor %}	

	{% case last %}

		
	{% when 1 %}
		
		<div class="col-md-6">
			
		</div>
		</div>

	{% endcase %}
	
    </div>

</div>


        