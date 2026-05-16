---
title: Refrigerator Rundown
layout: base
header-image: "/assets/images/book-to-network.png"
header-title: Disruptive Expertise
header-subtitle: When technology questions authority
header-position: 35% center
---

## Who's an expert?
The refrigerator is an everyday appliance that was once controversial and scary to be used. Just like most technology, there was fear and confusion around the different benefits of owning a fridge. 

With some research, it is easy to tell that there were quite a few concerns with the fridge and having it in your home. Some of these concerns included the toxic chemicals that were being used and the environmental concerns of having this in your home. A simple leak from this appliance was fatal, since the chemicals that were combined were both odorless and colorless. Because of this, Einstein invented a leak proof pump to combat this issue, which helped ease a lot of people's minds. 

While these are concerning points, it also brought a lot of good to the average household in regard to food preservation. It allowed for the storage of fresh meat, dairy products, and produce that could follow the food safety rules. The fridge was also a big deal for women in the household, since it advocated for a "servantless society". 

All in all, the refrigerator changed the world even if it was considered scary when it was first introduced.


{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/card-stack.html cards=cards %}

