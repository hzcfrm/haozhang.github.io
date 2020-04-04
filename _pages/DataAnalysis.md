---
layout: archive
title: "Data Analysis"
permalink: /DataAnalysis/
author_profile: true
---

## [Bank's Debt Collecting Analysis](/files/banks_debt.html)
<p>After a debt has been legally declared "uncollectable" by a bank, it does not <em>walks away</em> from the debt. They still want to collect some of the money they are owed. The bank will implement different levels of debt collecting strategies, advanced collecting strategies, of course, cost more money.</p>
<p>In this project, we'll load the banking dataset and try to inspect regression discontinuity to answer the question: whether it's worth the extra cost spending on debt collecting for the bank? </p>
[![](/images/banks_debt.png)](/files/banks_debt.html)

---

## [Mobile Games Operation A/B Testing](/files/mobile_games.html)
<p>In mobile games design, we want to get users' <em>retention</em>, which means potential profits. In this project, we'll load one of the mobile games' users dataset and conduct A/B tesing, to find out which one of the two different level designs attracts the players more.</p>
[![](/images/mobile_games.png)](/files/mobile_games.html)

---




{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
