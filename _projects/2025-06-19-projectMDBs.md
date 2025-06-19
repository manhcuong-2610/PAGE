---
title: "Multilateral Development Banks (MDBs) profitability"
date: 2025-06-19
collection: projects
permalink: /projects/2025-06-19-projectMDBs/
excerpt: "Text analytics project"
notebook_url: "/PAGE/files/MDBs.html"
---
## Overview
This study exploits a dataset on 17 multilateral development banks (MDBs) from 2016 to 2024. The dataset encompasses a comprehensive suite of financial and operational indicators, including capital adequacy ratios (CAR), non-performing loan ratios (NPR), provisioning levels, cost‐income ratios, liquidity coverage, net interest margins, and profitability measures (ROAA, ROAE, NIM). 

To estimate these relationships, we employ a sequence of panel‐econometric models. We begin with Pooled Ordinary Least Squares (OLS) to establish baseline associations, before introducing Fixed Effects (FE) and Random Effects (RE) specifications to control for unobserved heterogeneity across banks and years. Recognising potential endogeneity - particularly between liquidity, capital decisions, and profitability - we then implement a Two‐Stage Least Squares (2SLS) framework using liquidity and capitalisation metrics as instruments. Finally, we adopt a Correlated Random Effects (CRE) approach with a control-function correction, as proposed by Mundlak (1978) and Wooldridge (2010), to jointly address individual effects and residual endogeneity. 


**My work:** [Click here to view the notebook]({{ page.notebook_url }})
