#Emmet Django Snippets  

##Overview  

This is a set of snippets for Eclipse Emmet plugin to use in Django templates. At the moment it includes snippets for all standard Django templates tags.

##Installation  

1. Make sure that Emmet Eclipse Zen is installed and working.  
2. Download the emmet-django.xml file.  
3. Open Eclipse preferences (Windows->Preferences) and go Emmet->Snippets  
4. Click Import... button and select the emmet-django.xml.  
5. That's it, you can use the snippets now.  

##Snippets list  

	Abbreviation 	Tag
	autoescape 		{% autoescape %} {% autoescape %}
	block 			{% block %} {% endblock %}
	blocktrans		{% blocktrans %} {% endblocktrans %}
	bt				{% blocktrans %} {% endblocktrans %}
	comment 		{% comment %} {% endcomment %}
	csrf 			{% csrf_token %}
	csrf_token 		{% csrf_token %}
	cycle 			{% cycle %}
	debug 			{% debug %}
	ext 			{% extends "" %}
	extends 		{% extends "" %}
	filter 			{% filter %} {% endfilter %}
	firstof 		{% firstof %}
	for 			{% for in %} {% endfor %}
	fore 			{% for in %} {% empty %} {% endfor %}
	i18n			{% load i18n %}
	if 				{% if %} {% endif %}
	ifch			{% ifchanged %} {% endifchanged %}
	ifchanged 		{% ifchanged %} {% endifchanged %}
	ife 			{% if %} {% else %} {% endif %}
	ifelse 			{% if %} {% else %} {% endif %}
	inc 			{% include "" %}
	include 		{% include "" %}
	load 			{% load %}
	load:i18n		{% load i18n %}
	load:static		{% load static %}
	load:tz			{% load tz %}
	lorem			{% lorem %}
	media-prefix	{% get_media_prefix %}
	now 			{% now "" %}
	regroup 		{% regroup as %}
	sl				{% spaceless %} {% endspaceless %}
	spaceless 		{% spaceless %} {% endspaceless %}
	static			{% static "" %}
	static-prefix	{% get_static_prefix %}
	templatetag 	{% templatetag %}
	tt				{% templatetag %}
	tt:block		{% templatetag openblock %} {% templatetag closeblock %}
	tt:br			{% templatetag openbrace %} {% templatetag closebrace %}
	tt:com			{% templatetag opencomment %} {% templatetag closecomment %}
	tt:var			{% templatetag openvariable %} {% templatetag closevariable %}
	tz				{% load tz %}
	url 			{% url "" %}
	verbatim		{% verbatim %} {% endverbatim %}
	widthratio 		{% widthratio %}
	with 			{% with = %} {% endwith %}

##Hints  

You can use some of these snippets to wrap a text fragment with a tag. To do that select the text and choose Wrap With Abbreviation... from Emmet menu. This works for tags which have an ending tag, like {% if %} {% endif %}.  
You can use the Tab key to move the cursor to next logical position. For example use the for snippet and hit Tab to see how the cursor moves.  

