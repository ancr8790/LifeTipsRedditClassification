# LifeTipsRedditClassification
Categorization of Life tip posts on reddit via Unsupervised Learning

I will be using the following dataset [Helpful Life Tips from Reddit](https://kaggle.com/datasets/asaniczka/helpful-life-tips-from-reddit-dataset-13k-tips) taken from Kaggle.com to either build a recommendation system that suggests relevant tips based on specific life situations or topics OR analyze popular life topics and their corresponding tips to uncover patterns and common themes.

The following description of the dataset was taken directly from the website:

About the Dataset:
Reddit is a treasure trove of genuine life experiences from millions of people. Subreddits like r/lifeProTips and r/YouShouldKnow are well-known for containing some of the best and most practical tips that anyone can apply to their life.

This dataset is a cleaned version of the split reddit dump by u/Watchful1.

The dataset has the following attributes:

"id" - Post id given by reddit. (type:str)

"author" - Creator of the post. (type:str)

"isOver18" - Whether the post is NSFW or not. (type:bool)

"postUrl"- URL for the actual reddit post. (type:str)

"subreddit" - Name of the subreddit the post was created on. (type:str)

"postTitle" - Title of the post. (type:str)

"hasPostBody" - Whether the post has a post body or not. (type:bool)

"postBody" - Body of the post. If null, post doesn't contain a body. (type:str)

"score" - Score of the post given by users. (type:int)

"numComments"- Number of comments in the original reddit post. (type:int)
