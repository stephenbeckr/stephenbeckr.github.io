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

Our lab also works with many PhD students from other groups (e.g., [Liz Strong](https://www.linkedin.com/in/elstrong/) -- see [ch 4 of her thesis](https://www.proquest.com/pagepdf/2670031200), [Killian Wood](https://www.linkedin.com/in/killianrwood/), [Minah Yang](https://www.linkedin.com/in/luciaminahyang/), [Noah Francis](https://www.linkedin.com/in/noahfrancis/))

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
