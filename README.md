# bandit-learn
A knowledge base for Bandit Algorithm

Implementations here:

- https://github.com/alextanhongpin/node-bandit
- https://github.com/alextanhongpin/go-bandit
- https://github.com/alextanhongpin/go-bandit-server

## Reverse Engineer Microsoft's MultiWorld Testing

Start with a simple bandit experiment, understand the limitation (delayed response). Add real-time graphs and intelligent bot to tell you what can be optimized.

https://www.microsoft.com/en-us/research/project/multi-world-testing-mwt/


## Bandit Server

Bandit algorithm application in recommendations and other things. Not the concurrent issue with some algorithms (greedy epsilon) which requires the values to be updated immediately - imagine many users are pulling the same arm at the same time when the algorithm has not been updated.

Also look into how to apply contextual bandit by using decision tree.

## Contextual Bandit

Learn and apply the contextual bandit algorithm.


## Ad Click Prediction

Can be done through several ways - such as logistic regression. Find out how to implement a working server for that.

## Dynamic Pricing and Price elasticity

Find out how to work with time series data for prices, and the differences between dynamic pricing vs price elasticity algorithms and how to apply them.


## Bandit algorithm use case

What is the goal of bandit algorithm first?
- To dynamically and sequentially choose alternatives, referred to as arms, which will maximise the expected total rewards across the t trials.
- What are the real world use case?
1. To find the best medicine among alternatives
2. To find out the best product to launch among the possible products (versions)
3. Web optimisation, decide how much traffic we need to allocate for each website.
4. Marketing strategy. Find out the best marketing strategy to launch a product.
5. Recommendation system.
    1. Personalised recommendation of songs or books or videos
    2. Recommendation of complementary or substitute products in commerce
    3. Friends suggestions in facebook/linkedin
    4. Recommendation of news articles, based on your interest
6. Investment in stock market
    1. Finding out the best portfolio which maximise your profit
    2. Finding out the best stock to invest
    3. There are many experts in the market which try to predict the stock price. By using bandit algorithm, we can decide the weight for each expert. Weight will tell us indirectly how much we can trust each expert.
7. Combinatorial problem
    1. Helps to figure out the shortest path in the given map
    2. For some disease , we need more than one medicine to cure it . If we are not sure which combination of medicines will cure the disease, the bandit algorithm will help to find out the best combination.
8. Extreme values 
    1. able to find out fraudulent transactions in banking/finance sector (anomaly detection)
    2. Optimistic investment

https://www.quora.com/In-what-kind-of-real-life-situations-can-we-use-a-multi-arm-bandit-algorithm


## References
- https://www.analyticsvidhya.com/blog/2018/09/reinforcement-multi-armed-bandit-scratch-python/
- https://www.offerzen.com/blog/how-to-build-a-product-recommender-using-multi-armed-bandit-algorithms
- https://www.optimizely.com/optimization-glossary/multi-armed-bandit/
- https://stats.stackexchange.com/questions/230523/in-what-kind-of-real-life-situations-can-we-use-a-multi-arm-bandit-algorithm
- https://www.quora.com/In-what-kind-of-real-life-situations-can-we-use-a-multi-arm-bandit-algorithm
http://blog.yhat.com/posts/the-beer-bandit.html
- https://web.stanford.edu/~bvr/pubs/TS_Tutorial.pdf
- https://github.com/lilianweng/multi-armed-bandit/blob/master/solvers.py
- https://lilianweng.github.io/lil-log/2018/01/23/the-multi-armed-bandit-problem-and-its-solutions.html
- https://towardsdatascience.com/solving-multiarmed-bandits-a-comparison-of-epsilon-greedy-and-thompson-sampling-d97167ca9a50?gi=bc17d5acd6f7
- https://jamesmccaffrey.wordpress.com/2017/09/29/thompson-sampling-explained-using-an-example/
- https://www.analyticsvidhya.com/blog/2018/09/reinforcement-multi-armed-bandit-scratch-python/
- https://www.analyticsindiamag.com/thompson-sampling-explained-with-python-code/
- https://towardsdatascience.com/applications-of-reinforcement-learning-in-real-world-1a94955bcd12
