# food-rec


### Motivation
With the increasing number of health issues among individuals, people are adopting more preventative as compared to remedying health approaches. An important aspect of keeping healthy is consuming a well-balanced diet daily. Identifying nourishing meals is particularly challenging for working individuals as they try to strike a balance between their professional and personal lives. Further, healthy meals seem unappetizing for many, which further lures people towards less health but more tasty and convenient meals.
In this regard, we wish to explore how recommendation systems could tackle this problem haunting the contemporary professionals, by learning about their food preferences and providing a plethora of healthy options to choose from.

### Background
We use clickstream and item attributes from our dataset to experiment with Content-Based, Collaborative and Sequential Recommendation Models. Through this, we aim to recommend meals for users according to the time of day, their cuisine preferences, dietary restrictions and calorie target.

**Personalised Search** &nbsp;&nbsp;&nbsp;   We receive user inputs for maximum calories and a free-form query text. Based on these user criteria, we rank the recipes in our database and prepare a list of candidates for our user.

**Recommendations** &nbsp;&nbsp;&nbsp;  We explore implicit-feedback based matrix factorisation techniques, with latent vectors to represent the user and the recipes, to model the user’s clickstream to provide personalised recommendations models. Additionally, we explore neural network-based models sequence models. We also look at content-based recommender systems by using item attributes in an attempt to solve cold-start problems associated with new recipes.
