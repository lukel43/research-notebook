---
title: Experiment
date: 2023-04-04
tags: [posts]
---

Sports betting is a popular activity, and with the rise of online platforms and APIs, it has become increasingly accessible. However, finding profitable betting opportunities can be difficult, especially if you're not familiar with the intricacies of sports betting.

To address this issue, I conducted a senior thesis experiment to determine if it's possible to programmatically gather and analyze data using the-odds-api to calculate and find sports betting arbitrage opportunities. I used Python to extract odds data from the-odds-api and to compare user inputted bets to the bets found using the API. I also developed an algorithm to determine whether or not an arbitrage opportunity is available and what the potential profit would be.

I focused my experiment on NBA Moneyline odds as the bet pool. The program allows users to search for a team and displays the odds for that game on every sportsbook. Finally, it prompts the user for the odds to compare, then determines if an arbitrage opportunity exists.

My findings show that the experiment was successful, and it's possible to use Python and the-odds-api to find profitable sports betting opportunities. By comparing user inputted bets to the API odds, the program was able to identify arbitrage opportunities and potential profits. This can be a valuable tool for anyone interested in sports betting, from casual fans to professional gamblers.

The current implementation to determine arbitrage opportunities is as follows:

```py
def check_arb(bet_odds, api_odds):
    """
    Compares the user inputted bet odds to the odds retrieved from the API and
    calculates whether there is an arbitrage opportunity.
    """
    implied_prob_bet = 1 / bet_odds
    implied_prob_api = 1 / api_odds
    arb_percent = (1 - (implied_prob_bet + implied_prob_api)) * 100

    if arb_percent > 0:
        print(f"\n\nThere is an arbitrage opportunity! You could make a {arb_percent:.2f}% profit.")
    else:
        print("\n\nThere is no arbitrage opportunity.")
```

Thus far, my senior thesis experiment demonstrates the power of using technology to analyze and optimize sports betting strategies. With the right tools and algorithms, it's possible to increase your chances of winning and turn sports betting into a profitable venture.