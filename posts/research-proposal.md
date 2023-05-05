---
title: Research Proposal
date: 2023-03-21
tags: [posts]
---

# CS580S2023

## Assignment 10

### Final Deliverable: Proposal

### Name

Luke Lacaria

### GitHub Account Name

lukel43

---

### Introduction

My proposed research project is the completion of both an application and a historical analysis centering around sports betting odds. More specifically, my application aims to find, optimize and notify using of arbitrage opportunities. Arbitrage opportunities are defined as a circumstance where a user can place a bet on both sides of a binary betting option and guarentee profit. These opportunities occur when the odds align as such that by betting certain amounts on each side, your winnings will more than total the sum wagered regardless of the outcome. 

#### Motivation

The motivation of my project is two sided. Firstly, I aim to investigate whether an algorithmic approach to sports betting can produce a more profitable experience for users. Secondly, I wish to provide bettors with more information when betting, and provide an opportunity to at the least decrease potential losses and hedge against the risks of betting. This should result in a more profitable, informed, and safe environment for bettors to bet within. Ideally, my research project will successfully provide a tool for bettors to make more profitable bets and decrease the odds of losses and gambling addiction. At the very least, my project certainly will provide a insightful historical data analysis on sports betting odds, and offer insights into what situation placing an arbitrage bet could be useful, and how to take advantage of this.

#### Current State of the Art

Currently, there is little to no research on sports betting, especially in the area of arbitrage. I have found some relative literature, but much of it centers around strategies that are unavailable to users within the U.S., or focuses on algorithmically predicting the outcomes of matches or finding bets with "good" odds. My project differs from this because it does not aim to make any predictions or statements about the outcomes of matches or fairness of odds. It simply will calculate and notify users of the most profitable betting options given their current circumstances using the-odds-api. Additionally, I have not been able to find any historical data analysis on the outcomes of sports betting odds, nor how to optimize profits. All models that I have seen are theoretical statistical models, but not much work has been done concerning historical odds.

#### Goals of the Project

The goals of my project are first to conduct a historical analysis to identify how often arbitrage opportunities are available, and evaluate whether or not they can on average provide more profit than other common betting strategies. Then, I aim to create an application that identifies and notifies users of these opportunities. 

The historical analysis will serve two purposes. First to provide valuable research and literature into what sports betting opportunities and strategies are typically more or less successful. Secondly, it will provide valuable information that I can use to inform and improve my proposed application idea, in which I provide users with an application that can notify them of arbitrage opportunities. The historical data analysis will answer valuable questions such as when an arbitrage bet should be made, and allow me to work this information into the advice offered by my application.

### Related work

My project's related work consists of literature on algorithms that can identify arbitrage opportunities in sports betting, but none that actually scrape real data to identify these opportunities. Additionally, I have found research that evaluates the viability of sports betting arbitrage on betting exchanges, but betting exchanges are not available in the US, nor did this research use live data. There is also plenty of research on arbitrage in a stock market setting, but I feel some of the principles of this type of arbitrage can be applied to sports betting.

### Ethics

The ethics of my project may be of concern to some, given the questionable ethics of gambling as a whole. However, I feel that my application can act as a way to decrease the risks and pitfalls associated with gambling. It will provide valuable information, and if arbitrage proves to be a less than optimal strategy, I will disclaim as much. My research will be a step towards a more informed and fair sports betting environment, equipping bettors with as much information possible in order to decrease the risks of losses and addiction. Additionally, much of the allure associated with gambling addiction centers around chasing winning large sums, but my application and research focuses on the opposite, with the goal being opting out of the potential to win larger sums in favor of less risky smaller sums.

### Prototype

My prototype was a Python script that implemented an arbitrage algorithm to identify arbitrage opportunities. It also pulled in real-world live and future data using the-odds-api. It then used this real data to inform users when their bet has an opportunity for arbitrage and, when this occurs, inform users of how much to bet in order to maximize profits. 

The prototype program was very successful, further motivating me to pursure this research project. The feasibility of the concept was proven through my prototype as it answered many of the major questions surrounding my proposed research project. 

Firstly, the question of the reliability of the-odds-api was answered; the-odds-api's abilities exceeding my expectations providing incredible accurate and detailed odds information covered a huge variety of bets, sports leagues, and sportsbooks.

Secondly the question of whether such an algorithm is even possible was answered with a resounding yes. I was capable of providing a very solid framework for the algorithm and program during the duration of the development of my prototype. Additionally, I was able to prove during the prototype that I can process and compare the data provided by the-odds-api using Python. 

Then, when developing my research project I will have to decide whether or not to continue using Python. As I have the most experience and confidence in using Python, but there may be a more optimal implementation for this specific use case.

### Experiments



#### Experimental Design

My experimental design utilized Python and the-odds-api, which was viable for testing the validity of my application, but may not be optimal for implementing the full project. There still remains a few questions that need to be answered to complete the design of my finished product. First I will need to answer whether or not Python is optimal for processesing and handling the data and algorithm. Secondly, I will need to see which languages, frameworks will be necessary and or optimal for implementing a front-end. Finally I will need to determine whether a web application or mobile applicaiton is optimal, and if a mobile application would be worth the additional effort.

#### Evaluation

My experiment was very successful at what I intended it to do, which was give simple, single bet arbitrage opportunities through the CLI using Python. However, for the full project, I would like to introduce many more betting options, as well as a user-friendly interface that allows for notifications to make the application much more user-friendly. During the devlopment of my prototype and experiment, I intentionally limited the scope of my application in terms of the betting event, sports leagues, and other features offered in order to speed up development. This approach was very successful in allowing my to show the validity of my proposal, as well as afforded me the opportunity to conclude the experiment with a fully functional program that already provides value, and showcases the potential of my application.

#### Threats to Validity

The main threat to the validity of my project is determining how often arbitrage opportunities are available and if they provide more profit than other betting strategies. Although my small scale data collection and anecdotal evidence has shown that these opportunities are prevalent, a more thorough historical data analysis is needed to paint a clearer picture of their prevalence and profitability. Another threat to validity is the reliability of the-odds-api, as it is a third-party service that could potentially be unreliable or unavailable at times. Thus far and through my research, I am rather confident in the reliablility and availability of the-odds-api, but as with any software project introducing additional dependencies always increases complexity and risk. So, this will be something to keep an eye on throughout the development of my reasearch project. Additionally, the validity of the results of my historical analysis could be impacted by factors such as changes in odds-setting methods or fluctuations in the sports betting market. These threats can be mitigated by conducting a thorough and robust historical data analysis and implementing multiple fail-safes within the application to ensure reliable and consistent data from the-odds-api.

### Conclusion

#### Summary of Results

In summary, thus far I have conducted research to see who else has covered this topic, created a successful prototype, and planned a roadmap for my project. During each of these steps, I have grown more passionate and optimistic about the future of my project. I feel this application could have many real-world use cases and the historical data analysis could provide key insights that could inform future bettors to make better decisions and improve sports betting strategy.

#### Future Work

My future work will primarily concern expanding the scope of the data collected and arbitrage opportunities offered, conducting a more thorough historical data analysis to test the utility of my application, and building a user-friendly interface to make interacting with my application easy for the common bettor. I plan to offer all betting events provided through the-odds-api on my application, as well as all the sports leagues that are offered. The main limiting factory will be the amount of API requests this will take up, but I'm confident this can be overcome through a crafty and efficient implementation. I will also need to continue to work on my front-end development skills to complete this application. Though I have done some work in web development, and plan to take web applications next spring I will need much more knowledge to accomplish my goals. I plan to overcome this by learning more about front-end development during my free time. Also, I'm sure I will learn more about front-ends this summer during my internship, where I will be creating front-ends and API's for databases with Howmet Aerospace. Lastly I will need to hone in on my data analysis skills, which I have acquired through the database systems and data analytics courses, but I will need to build further on this foundation to complete my project. This is especially true since my project will rely heavily on a thorough and successful historical data analysis of sports betting odds. This data analysis will likely be the most comprehensive and large scale analysis I have ever done, so I am sure that I will need to work harder to improve my data analysis skills to achieve the results that I desire and require.

#### Ethical Implications and Recommendations

The obvious ethical dilemma when it comes to my proposed project is the questionable morality of gambling. However, like many other possibly harmful things, it is much better to provide people with information and tools to combat the plights that can come from these vices. In the case of my project, I feel providing valuable information about the potential benefits and downsides of sports betting through my historical data analysis, as well as providing them with a tool that can help them make more informed, safer bets via my application, is a positive step forward even if it does concern a topic that some may see as unethical.

#### Conclusions

Overall, my project has great potential to provide information and a tool to people that has multiple use cases, as well as the ability to reduce the risks of gambling. I am very passionate about pursuing this project both because I am confident in my ability to produce a tool that is very helpful and useful. Additionally, I am highly fascinated in attempting to confront the largest human-based sportsbook odds through a data-driven and programmatic strategy and I would like to learn more about how odds are created and if there are any trends that can be capitalized upon. Also, I look forward to the opportunity to showcase everything I have learned throughout my time here at the college, and this project gives me the perfect opportunity to do that. First, I will have to utilize my data analysis skills to conduct the historical odds data analysis and draw insightful conclusions. Then I will utilize my programming knowledge to create the algorithm and backbone of my application. Then, I will further develop my front-end skills when completing the user friendly interface. During this process, I will tie everything together using my software engineering skills to ensure my application is developed optimally and using the best practices available. Finally, I will showcase my writing skills through the completion of the final report. All in all, I am very excited to begin developing this proejct and have high hopes for the results. My goal is in the end, have a project that both showcases my knowledge and value to the college and potential employers, but also is able to act as a useful and insightful resource and application on its own. 

#### References

https://core.ac.uk/download/pdf/6576725.pdf
https://pubsonline.informs.org/doi/epdf/10.1287/mnsc.2016.2656
https://www.mdpi.com/2227-9091/8/3/88
https://the-odds-api.com/
