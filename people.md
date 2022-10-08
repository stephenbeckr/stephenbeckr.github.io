---
layout: page
title: People
permalink: /people/
---

## Current members

<!-- ones with photos (including generic photos); TODO: website, orcid, github -->
<ul style="columns: 2; list-style: none; padding: 0; list-style-type: none; margin-left: 0;">
{% for member in site.data.group %}
{% if member.photo != null %}
{% unless member.graduated %}
<!-- <li style = "clear: both; -webkit-column-break-inside: avoid;  page-break-inside: avoid; break-inside: avoid;"> 
<img src="/assets/img-group/{{ member.photo }}" class="img-responsive" width="34%" style="float: left;" /> -->
  <!-- <b>{{ member.name }}</b>  -->
  <!-- Now, member.name is in the include below (so turns it into hyperlink of they have website) -->
   {% include myPhotoGallery.html %}
  <!-- <br>
  <i>{{ member.short }} </i><br>
  {{ member.long }}
  </li> -->
{% endunless %}
{% endif %}
{% endfor %}
</ul>
<!-- ones without photos -->
<ul style="columns: 2; list-style: none; list-style-type: none; margin-left: 0;">
{% for member in site.data.group %}
{% unless member.photo %}
{% unless member.graduated %}
   {% include myPhotoGallery.html %}
{% endunless %}
{% endunless %}
{% endfor %}
</ul>

-------------

Our lab also works with many PhD students from other groups (e.g., Noki Cheng, Liz Strong, Tzu-Chi Yen, Killian Wood, Minah Yang)

-------------

## Former members
<ul style="columns: 2; list-style: none; padding: 0; list-style-type: none; margin-left: 0;">
{% for member in site.data.group %}
{% if member.photo != null %}
{% if member.graduated %}
  {% include myPhotoGallery.html %}
<!-- <li style = "clear: both; -webkit-column-break-inside: avoid;  page-break-inside: avoid; break-inside: avoid;"> 
<img src="/assets/img-group/{{ member.photo }}" class="img-responsive" width="34%" style="float: left;" />
  <b>{{ member.name }}</b> <br>
  <i>{{ member.short }} </i><br>
  {{ member.long }}
  {% if member.linkedin %}
  <a rel="me" href="{{ member.linkedin | cgi_escape | escape }}" target="_blank" title="{{ member.linkedin | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#linkedin' | relative_url }}"></use></svg></a>
  {% endif %}  
  </li> -->
{% endif %}
{% endif %}
{% endfor %}
</ul>


<ul style="columns: 2; list-style: none; list-style-type: none; margin-left: 0;">
{% for member in site.data.group %}
{% unless member.photo %}
{% if member.graduated %}
  {% include myPhotoGallery.html %}
<!-- <li style = "margin: 1rem 0; -webkit-column-break-inside: avoid;  page-break-inside: avoid; break-inside: avoid;"> 
  <b>{{ member.name }}</b> <br>
  <i>{{ member.short }} </i><br>
  {{ member.long }}
  {% if member.linkedin %}
  <a rel="me" href="{{ member.linkedin | cgi_escape | escape }}" target="_blank" title="{{ member.linkedin | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#linkedin' | relative_url }}"></use></svg></a>
  {% endif %}  
  </li> -->
{% endif %}
{% endunless %}
{% endfor %}
</ul>