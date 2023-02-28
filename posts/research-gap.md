---
title: Research Gap - Sports Betting Arbitrage/Hedging
date: 2023-02-28
tags: [posts]
---

I have discovered a research gap in the sports betting industry. While the sports betting industry is growing rapidly, tools and strategies surrounding it are as well. A widely discussed, yet rarely researched strategy is one that is referred to as either arbitrage or hedging. 

This concept is that if you place a bet on a binary betting option, then during the course of the game the odds shift so that you can then place a bet on the other option and guarentee profit. This strategy has the benefit of guarenteeing you profit, but risks missing out on additional profit if your original pick was correct.

I plan to use [the-odds-api](https://the-odds-api.com/) to first evaluate how often these circumstances occur by analyzing how often arbitrage opportunities are available on a particular bet, as well as how often they are available within an entire game.

I will then use this data to inform the creation of an application that alerts users when a bet they have placed has an arbitrage opportunity available. I will then track how often the user choses to *capitalize* on the arbitrage opportunity, and what their success rate would have been always and never arbitraging.

This will enable the users to have the information readily available to decreasing the well researched urge to bet emotionally and pick favorites. If an immediate profit is presented to users, my hypothesis is that they will be more willing to seize these opportunities than if they would have had to search for this information on their own. Additionally, I hypothesize that they will be more profitable in the long run using an always arbitrage strategy versus a never arbitrage strategy. The true question will be what level of arbitrage is possible. 

To answer this question my app will allow alerts based on a desired arbitrage profit threshold (ex. 10%, 25%, 50%). Then I will conduct research based on past odds and results to determine which strategy would have been most successful historically. This will result in more information about the viability of arbitrage betting strategies as well as people's willingness to seize these guarenteed profit opportunities at the risk of missing out on possible additional profits.

Sources:
https://core.ac.uk/download/pdf/6576725.pdf
https://pubsonline.informs.org/doi/epdf/10.1287/mnsc.2016.2656
https://www.mdpi.com/2227-9091/8/3/88
https://the-odds-api.com/
