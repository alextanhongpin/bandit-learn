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


## References
- https://www.analyticsvidhya.com/blog/2018/09/reinforcement-multi-armed-bandit-scratch-python/
- https://www.offerzen.com/blog/how-to-build-a-product-recommender-using-multi-armed-bandit-algorithms
- https://www.optimizely.com/optimization-glossary/multi-armed-bandit/
- https://stats.stackexchange.com/questions/230523/in-what-kind-of-real-life-situations-can-we-use-a-multi-arm-bandit-algorithm
- https://www.quora.com/In-what-kind-of-real-life-situations-can-we-use-a-multi-arm-bandit-algorithm
http://blog.yhat.com/posts/the-beer-bandit.html
