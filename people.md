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
   {% include myPhotoGallery.html %}
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
<!-- Select people using a filter: https://jekyllrb.com/docs/liquid/filters/
 if member.graduated 
 -->
{% assign oldMembers = site.data.group | where:'graduated', true %}
{% assign oldMembersPhoto = oldMembers | where_exp:"members", "members.photo != null" %}
{% assign oldMembersNoPhoto = oldMembers | where_exp:"members", "members.photo == null" %}
{% for member in oldMembersPhoto %}
    {% include myPhotoGallery.html %}
{% endfor %}
</ul>

<!-- And former members without a photo -->
<ul style="columns: 2; list-style: none; list-style-type: none; margin-left: 0;">
{% for member in oldMembersNoPhoto %}
  {% include myPhotoGallery.html %}
{% endfor %}

</ul>