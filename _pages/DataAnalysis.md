---
layout: archive
title: "Data Analysis"
permalink: /DataAnalysis/
author_profile: true
---

## [Bank's Debt Collecting Analysis](/files/banks_debt.html)
<p>After a debt has been legally declared "uncollectable" by a bank, the account is considered "charged-off." But that doesn't mean the bank <strong><em>walks away</em></strong> from the debt. They still want to collect some of the money they are owed. The bank will score the account to assess the expected recovery amount, that is, the expected amount that the bank may be able to receive from the customer in the future.</p>
<p>In this project, we'll load the banking dataset and try to inspect regression discontinuity to answer the question: whether it's worth the extra cost spending on debt collecting for the bank? </p>
[![](/images/banks_debt.png)](/files/banks_debt.html)

---




{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
