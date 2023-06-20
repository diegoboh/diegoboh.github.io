---
layout: archive
title: " "
permalink: /publications/
author_profile: true
---

Work in progress
==
<span style="color:blue">some *blue* aaaaa text</span>.

**The dollar blah blah**

<span style="font-size:12pt">
!! This paper explores the macroeconomic implications of the Fed acting as the international lender of last resort to foreign global banks during periods of crisis. To do so, I develop a stylized and tractable model that captures important features of the global financial system in the run-up to the 2008 crisis, such as non-US global banks that invest in US assets but are exposed to dollar liquidity shortages. My model highlights the possibility of multiple equilibria, one of which resembles a global financial crisis with a sharp appreciation of the dollar, tighter financial conditions, weaker aggregate demand, and output losses. Moreover, these episodes may be self-fulfilling due to a feedback loop between the exchange rate and banks’ capacity to raise funds. Given that global banks’ liquidity needs are often denominated in dollars, the Fed is better equipped than other central banks to prevent the “bad” equilibrium when the dollar is strong. However, US incentives to intervene -through dollar swap lines- may not be aligned with the rest of the world.
</span>

Policy papers
==

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
