---
layout: post
title: Research Assistant @ FutureFinance.AI, WBS Gillmore Center
permalink: /gillmore-center/
---

# What is FutureFinance.AI

The FutureFinance.AI Research Group sits within the WBS Gillmore Centre for Financial Technology. Its mission is to drive innovation in real estate through rigorous research and interdisciplinary collaboration. We seek to develop technologies and methodologies that transform real estate practices, making them more accessible and effective for all stakeholders.

# Projects I worked on

### UK Housing Affordability Tool

My first task was to build developed an interactive map for England and Wales that matches users' financial profiles (savings and income) with property prices across districts, using HM Land Registry data and standard mortgage lending criteria.The user is also able to filter properties according to their housing features.

Design a practical tool for navigating the UK real estate market while enhancing our understanding of housing price patterns.

The website is available at the following address: [https://affordability.gillmore.wbs.ac.uk/](https://affordability.gillmore.wbs.ac.uk/)

#### Future Improvements

Here is a list of additional features and improvement ideas for the tool:

- Use non-conventional data (e.g. floor plans, news articles), to allow for more filtering.
- Add more granularity to the map (post code or city level).
- Assign a “local score”: amenities, commuting times, etc.
- Include Total Cost of Living (maintenance, utilities, groceries, etc.).
- Show projected long-term price trends.
- Return‑On‑Investment Simulator for buy-to-let.
- Implement a property or city sustainability score.

### UK House Price Index (HPI) Replication

The UK House Price Index (HPI) is a key economic indicator produced by the Office for National Statistics (ONS). This index, published monthly, tracks house price changes across England, Wales, Scotland, and Northern Ireland.

The HPI has an impact on policy decisions and financial markets. House prices are closely tied to inflation, interest rates, and economic cycles, making HPI a crucial tool for policy decisions and financial investments

We demonstrate that the UK HPI CAN be reasonably replicated using only publicly available data, unlike the ONS which uses private and expensive data, such as the Acorn geo-demographic segmentation of the UK.

We also found that the method that had the highest correlation with the official HPI was the repeated sales method, employed in the american Case-Shiller Home Price Index, outperforming the Hedonic Regression method, even though the latter is the one officially implemented by the ONS.

### Predicting the UK HPI with LLMs and news articles

Our latest project is the prediction of the UK HPI using only news articles from the Financial Times, and Large Language Models (LLMs)

We collected the news titles from the Financial Times and use LLMs to analyse their potential impact on the housing market. For example a news mentioning a decrease in interest rates or an increase in activity in a certain city could imply an increase in housing prices.

Preliminary results show that a simple linear regression model that uses the ratio of UP to DOWN articles has an $$R^2$$ of about $$20\%$$ when predicting HPI changes 12-20 months in the future ($$p<0.01$$)
