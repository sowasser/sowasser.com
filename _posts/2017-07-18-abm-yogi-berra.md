---
title:  "You Can Observe a Lot by Just Watching: Agent-Based Modelling and Yogi Berra"
date:  2017-07-18 10:00:00
tags: modelling datascience
---


Ahh modelling, providing the computational power to solve real-world problems. Agent-based modelling in particular, is useful for untangling the ephemeral, contradictory, unexplainable phenomena in the physical and social world. The only limit is your imagination. And programming skill, but that's another matter.

For example, the visionary [Yogi Berra][YB] once said, about a popular Italian restaurant, "no one goes there nowadays, it's too crowded", a statement at once nonsense and intuitive. Perhaps we can model it?

Well, yeah we can. There's the El Farol Bar Problem: El Farol is the only bar in Santa Fe that plays Irish music and 100 people want to go. It's great if fewer than 60 people go, and terrible if it's overcrowded. How do you decide whether or not to go? Do you use deductive reasoning: forecasting the attendance and basing your decision on that estimate? What if that's the strategy everyone else uses? Then on nights when everyone else would go, after estimating a low attendance, it'll be crowded and you should skip it.

Brian Arthur came up with this particular problem in his 1994 paper, [Inductive Reasoning and Bounded Rationality (The El Farol Problem)][El Farol]. Instead of having all of the agents act in the same, perfectly rational way, they act on a set of strategies from an "alphabet soup" of predictors of attendance. Over the course of the model, they stick to the strategy that is the most successful. When modelled, the mean attendance hovers around 60, the optimal number of people. 

Of course, in the real world, people might react with greater intelligence and adaptability. But, this theory, where an agent applies "bounded rationality" instead of perfect, deductive reasoning, is still useful. Beyond whether or not to get a pint, similar rationalizations occur in stock-market speculation, when the best time to sell is while everyone else is buying, and vice versa.

It's a fascinating problem and I love that Yogi Berra, in his infinite wisdom, has already encapsulated it. I wonder, what [other Yogi-isms][Yogi-isms] would make great models? If you get any manuscript ideas from this list, I expect to be co-author.

1. When you come to a fork in the road, take it.
2. 90% of baseball is mental; the other half is physical.
3. Always go to other people's funerals, otherwise they won't come to yours.
4. The future ain't what it used to be.
5. It gets late early out here.
6. You've got to be very careful if you don't know where you are going, because you might not get there.
7. It was impossible to get a conversation going, everybody was talking too much.
8. If the world were perfect, it wouldn't be.


And, if you're interested in learning more about agent based modelling, I've been taking an Introduction to Agent-Based Modeling through [Complexity Explorer][CE].

Now pair up in threes and get modelling.



[YB]: https://en.wikipedia.org/wiki/Yogi_Berra#.22Yogi-isms.22
[El Farol]: http://tuvalu.santafe.edu/~wbarthur/Papers/El_Farol.pdf
[Yogi-isms]: http://ftw.usatoday.com/2015/09/the-50-greatest-yogi-berra-quotes
[CE]: https://www.complexityexplorer.org/courses/76-introduction-to-agent-based-modeling-summer-2017