---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---
<span style="color:rgb(168, 141, 34); font-size:17pt">
**Work in progress**
</span>

**The Dollar and Global Financial Collapse**

<p style="text-align: justify; font-size:12pt">
This paper explores the macroeconomic implications of the Fed acting as the international lender of last resort to foreign global banks during periods of crisis. To do so, I develop a stylized and tractable model that captures important features of the global financial system in the run-up to the 2008 crisis, such as non-US global banks that invest in US assets but are exposed to dollar liquidity shortages. My model highlights the possibility of multiple equilibria, one of which resembles a global financial crisis with a sharp appreciation of the dollar, tighter financial conditions, weaker aggregate demand, and output losses. Moreover, these episodes may be self-fulfilling due to a feedback loop between the exchange rate and banks’ capacity to raise funds. Given that global banks’ liquidity needs are often denominated in dollars, the Fed is better equipped than other central banks to prevent the “bad” equilibrium when the dollar is strong. However, US incentives to intervene -through dollar swap lines- may not be aligned with the rest of the world.
</p>
<p style="text-align: justify; font-size:12pt">
**Presented at**: 2nd Sailing the Macro Workshop (Sep. 2022), Naples School of Economics PhD Workshop (Sep. 2022), BdF-BoE-BoI International-Macro Workshop (Nov. 2022), SAEe (Dec. 2022), CREi MacroLunch (May 2022/Mar. 2023), Université Paris Nanterre PhD Conference (Apr. 2023), LBS TADC (May 2023), Journal of International Economics Summer School (Poster, Jun. 2023), XXVI Workshop on Dynamic Macro (sched. Jul. 2023), EEA (sched Aug. 2023)
</p>

**Macroprudential rules in a small open economy: a DSGE approach**
<p style="text-align: justify; font-size:12pt">
This paper analyses the interaction between macroprudential instruments using a dynamic stochastic general equilibrium (DSGE) for a small-open economy with financial and nominal frictions. Using different objectives for the monetary authority, we try to find the optimal policy rules involving dynamic capital and reserve requirements. Given the frictions present in the model, the gains from adapting reserve and capital requirements to economic conditions are substantial, especially if financial stability is included as an objective of the Central Bank. Regarding the differences between the two instruments, the most important is that, contrary to capital requirements, an increase in reserve requirements leads to higher inflation and has an ambiguous impact on output. Finally, in the scenario of a financial stability objective and strict separation of tasks by instrument, reserve requirements provide a slightly better response to the exogenous shocks in the economy than capital requirements.
</p>

<span style="color:rgb(168, 141, 34); font-size:17pt">
**Policy papers**
</span>






{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
