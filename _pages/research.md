---
permalink: /research/
title: "Research"
author_profile: true
---

My fields are international finance and applied econometrics. Dissertation: *Asset Pricing with Structural Breaks and Machine Learning*. Committee: Marcelle Chauvet (chair), Colleen O'Brien, Dongwon Lee.

## Job Market Paper

**Currency-Specific Breaks and Foreign Exchange Puzzles**  
*Draft in preparation*

Textbook theory says a currency should strengthen when its central bank raises interest rates relative to other countries. In the data the link often has the wrong sign, which is the starting point for several long-standing exchange-rate puzzles. These puzzles are usually documented on pooled samples. I estimate break dates separately for each currency pair and re-test the puzzles within regimes. Across 45 G10 currency pairs over 45 years, the rate–currency link moves to the textbook sign at a regime shift in 25 pairs and never moves the other way. The shifts line up with central banks ending the use of interest rates to defend their exchange rate. Reaction functions and daily event studies around policy decisions at the Bank of England, the Bundesbank, the Bank of Canada and the Swiss National Bank support this reading: rate surprises strengthened the currency only after the defense ended. The puzzles are not refuted; they are dated.

Methods: structural-break tests with simulated size checks, Markov switching, bootstrap inference, out-of-sample forecast evaluation with multiple-testing correction. Written in Python and checked against published results.

## Work in Progress

**A News and Central-Bank Text Dataset for Macro-Financial Events**  
*In progress*

A dataset of 9,370 news headlines from 25 outlets and 239 Federal Reserve statements from 1996 to 2026, coded with a large language model and matched to intraday and daily market data. It is built to study how currency and bond markets respond to central-bank announcements and news. Results so far are preliminary.

**Machine Learning and Return Predictability** (dissertation chapter 2)  
*In progress, early stage*

Asks whether text and macro data help predict asset returns and detect changes in how markets move together, with every test designed out of sample. No results to report yet.

## Earlier Work

**LSTM Forecasts of Exchange Rates with a Positioning-Based Sentiment Index** (UC Riverside)

Forecast five major currencies with LSTM networks, combining macro and technical inputs with a sentiment index built from futures traders' positions and weighted for loss aversion. The forecasts did not beat a random walk. That result led to the break-dating approach in the job market paper.

**International Trade and Bilateral ODA: On a Network Basis** (M.S. thesis, Tufts University, 2017; advisor: Sahar Parsa)

A model of how supply shocks pass through trade in intermediate goods, tested on a 1990–2014 donor–recipient panel with pair fixed effects. A higher share of intermediate goods in imports is associated with significantly more bilateral aid.

**Aid and Growth Revisited** (Tufts University, 2016)

Re-estimates the effect of foreign aid on growth by two-stage least squares, instrumenting aid with colonial ties, common language and population, over horizons of 10 to 40 years. I find no significant positive effect.
