---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Working papers


[Non-essential Business Cycles](https://conference.nber.org/conf_papers/f202255.pdf), with Michele Andreolli and Paolo Surico

Using newly constructed time series of consumption, prices and earnings in essential and non-essential sectors, we document three main empirical regularities on post-WWII U.S. data: (i) spending on non-essentials is more sensitive to the business-cycle than spending on essentials; (ii) earnings in non-essential sectors are more cyclical than in essential sectors; (iii) low-earners are more likely to work in non-essential industries. We develop and estimate a structural model with non-homothetic preferences over two expenditure goods, hand-to-mouth consumers and heterogeneity in labour productivity that is consistent with these findings. We use the model to revisit the transmission of monetary policy and find that the interaction of cyclical product demand composition and cyclical labour demand composition greatly amplifies business-cycle fluctuations.

Presented:  PSE Macro Days, Barcelona School of Economics Summer Forum\*, CREi/UPF\*, Boston College\*, LBS, Norges Bank\*, EWMES, SEA\*, RES\*, ECB ChaMP Conference\*, Midwest Macro, NASM of the Econometric Society\*, SED and NBERSI (Monetary Economics)\*

## Projects

[The Green Transition in a Putty-Clay model of Capital], with Simon Gilchrist and Joseba Martinez

Presented: NYU Stern Macro lunch\*, CREi/UPF\*, Imperial\*

[Inequalities in Insurance Climate Risks] (JMP)

Presented: LBS, NYU Student Lunch

\* = Presentations by co-authors

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
