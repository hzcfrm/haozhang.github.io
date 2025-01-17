---
layout: archive
title: "Quantitative Finance"
permalink: /QuantitativeFinance/
author_profile: true
---

## [Mean-reverting Trading Implementation & Backtesting](/files/mean_reverting.html)
<p>A lot of stocks in the market have some kind of co-movements, which inspire us to investigate the quantitative trading strategy based on the mean-reverting behavior.  In this project, we'll use the standard Johansen test to construct a tradable portfolio using a few stocks from the retail industry, implement the quantitative trading stratgy in Python, and backtest its performance over the last 10 years.</p>
[![](/images/mean_reverting.png)](/files/mean_reverting.html)

---

## [Portfolio Performance Analysis & Benchmarking](/files/portfolio_analysis.html)
<p>Accurate evaluation of the past performance of investments forms the basis for assessing future prospects of the investments. In this project, we'll utilize the R <em>quantmod</em> and <em>PerformanceAnalytics</em> packages to cover fundamental principles and commonly used methods in portfolio evaluation.</p>
[![](/images/portfolio_analysis.png)](/files/portfolio_analysis.html)

---

## [Coca-Cola(KO) Stock Modeling](/files/coca_cola.html)
<p>The Coca-Cola(KO) Company is the producer of the worlds's most popular soft drink. In this project, we'll load the KO stock data using R <em>quantmod</em> package over 10-year span from 2007 to 2018, inspect the log returns and try to fit an adequate statistical model. We'll also look at possible risk premium effect and leverage effect in the stock returns.</p>
[![](/images/coca_cola.png)](/files/coca_cola.html)

---



{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
