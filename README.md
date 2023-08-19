# Recommendation_Systems

## Problem Statement

Build a recommender system by using cosine simillarties score.

# ➳ What is a Recommendation System?

A recommendation system is an algorithm that uses data analysis and machine learning techniques to suggest relevant information (movies, videos, items) to users that they may find interesting. 

These systems analyze large amounts of data about users’ past behavior, preferences, and interests using machine learning algorithms like clustering, collaborative filtering, and deep neural networks to generate personalized recommendations.

# ➳ Types of recommendation systems

There are several types of recommendation systems in machine learning, including :

## Content-based filtering :

Recommends items based on their similarity to items the user has previously liked.

## Collaborative filtering : 

Recommends items based on the preferences of similar users.

## Hybrid : 

combines both content-based and collaborative filtering to make recommendations.

### Hybrid with memory-based and model-based :- 

Memory-based recommendation is a way to make recommendations based on the similarity between items and the users' past behavior, whereas model-based recommendation uses machine learning algorithms to model the user behavior and make recommendations.

### Hybrid with demographic and user-based :- 

Demographic-based recommendation is a way to make recommendations based on user demographic information, and user-based recommendation is a way to make recommendations based on the similarity of users.

### Hybrid with demographic and item-based :- 

Demographic-based recommendation is a way to make recommendations based on user demographic information, and item-based recommendation is a way to make recommendations based on the similarity of items.

# ➳ Content-based Filtering

Content-based filtering is a recommendation system that suggests items to users based on their previous interactions with similar items. This system typically uses the features or attributes of the items to identify similar items.

For example, if a user has previously watched several action movies, a content-based recommendation system would suggest other action movies to the user based on the genre, actors, and other similar attributes of the movies they have previously watched.

![content-based-filtering](https://github.com/yagniksorathiya/Recommendation_Systems/assets/129974278/9f47ae12-e862-470d-8d14-5b8580e87c4d)

One of the key advantages of content-based filtering is that it can recommend items to users even if they have yet to interact with many items in the past. It can also make recommendations to users who have unique tastes and preferences.

However, content-based filtering can also have some drawbacks. For example, if a user's preferences change over time, the system may not be able to adapt and suggest appropriate items. Additionally, the system may only be able to recommend new and diverse items to the user if their tastes are narrower.

Also, a content-based recommendation system requires information about the items. The quality of the recommendations is directly proportional to the quality of the item's features used to make the recommendations.

# ➳ Collaborative Filtering

Collaborative filtering is a recommendation system that suggests items to a user based on similar users' preferences. This system does not use the attributes or features of the items to make recommendations but instead uses the past behavior of users to identify similar users and recommend items that similar users have liked.

**There are two main types of collaborative filtering:**

+ **User-based collaborative filtering:**

This method finds similar users based on their past interactions with items and then recommends items that similar users have liked. For example, if two users have similar viewing histories on Netflix, the system may recommend the same movie to both users.

+ **Item-based collaborative filtering:**

This method finds similar items based on how users have interacted with them and then recommends those similar items to a user. For example, if a user has liked several movies of a particular genre, the system may recommend other movies of that genre to the user.

Collaborative filtering is a powerful technique; it can recommend items to users even if they have not previously interacted with many items. It can also adapt to changes in users' preferences over time. Additionally, it can recommend new and diverse items to users.

However, Collaborative filtering can also have some drawbacks. For example, it may need help with the cold start problem; making recommendations for new users or items with little or no past interactions is difficult. Additionally, if the user base is too small, finding similar users to make recommendations may be difficult.

![collaborative filtering](https://github.com/yagniksorathiya/Recommendation_Systems/assets/129974278/80f8b6c4-1f3c-499b-90e2-076abba71b06)

In summary, Collaborative filtering is a powerful technique that can make accurate recommendations to users. But it requires a large amount of data about users' interactions to work effectively.

![Filtering](https://github.com/yagniksorathiya/Recommendation_Systems/assets/129974278/b5638082-f228-4bd9-9154-da21b41b59bf)

# ➳ Hybrid

## Hybrid with Memory-based and Model-based

Hybrid recommendation systems that combine memory-based and model-based approaches are becoming increasingly popular as they can take advantage of the strengths of both methods while addressing some of their weaknesses.

A memory-based recommendation system is a way to make recommendations based on the similarity between items and the users' past behavior. It typically uses a user-item matrix to store the interactions between users and items, and then uses a similarity measure, such as cosine similarity, to find similar items or users.

On the other hand, a model-based recommendation system uses machine learning algorithms to model user behavior and make recommendations. These algorithms can be used to learn the underlying patterns in the data and make predictions about which items a user may be interested in.

A hybrid recommendation system that combines memory-based and model-based approaches can take advantage of the scalability and interpretability of memory-based methods while addressing some limitations.

For example, a hybrid system can use memory-based methods to make recommendations quickly and easily while using model-based methods to learn the underlying patterns in the data and make recommendations for new users or items.

Additionally, a hybrid system can use memory-based methods to make recommendations for items like those a user has liked in the past while using model-based methods to recommend items that may be different but still of interest to the user.

Overall, hybrid recommendation systems that combine memory-based and model-based approaches have the potential to overcome some of the limitations of each method individually and provide more accurate and diverse recommendations to users.

## Hybrid with Demographic and User-Based

A Hybrid recommendation system that combines demographic and user-based approaches can be useful in situations where demographic information of users is available and can be used to improve the recommendations.

A demographic-based recommendation is a way to make recommendations based on user demographic information, such as age, gender, income, education level, and location. This type of recommendation system can be useful in situations where the demographic information of the users is known and can be used to make recommendations. For example, if a user is a young adult, the system may recommend movies that are popular among young adults. This system seeks to classify users according to traits and provide advice based on demographic groups. As it is not overly complicated and is simple to apply, several industries have adopted this type of strategy.

On the other hand, user-based collaborative filtering is a way to make recommendations based on the similarity of users. This recommendation system finds similar users based on their past interactions with items and then recommends items that similar users have liked. For example, if two users have similar viewing histories on Netflix, the system may recommend the same movie to both users.

A hybrid recommendation system that combines demographic and user-based approaches can take advantage of the strengths of both methods. For example, demographic information can narrow the pool of similar users, making the recommendations more accurate. User-based collaborative filtering can recommend items that similar users have liked.

Additionally, demographic information can be used to make recommendations to users who have yet to interact with many items in the past. For example, if a new user signs up and provides their demographic information, the system can make recommendations based on users' preferences with similar demographic information.

Overall, hybrid recommendation systems combining demographic and user-based approaches can provide more accurate and diverse recommendations to users by using demographic information to narrow down the pool of similar users and recommend items that similar users have liked.

## Hybrid with Demographic and Item-Based

A hybrid recommendation system is a combination of two or more recommendation approaches. A demographic-based and item-based hybrid system would consider the user's characteristics (demographics such as age, gender, income, etc.) and the characteristics of the items being recommended (such as genre, popularity, etc.) to make recommendations. This approach can often lead to more accurate and personalized recommendations than a single approach alone.

![Hybrid Recommendation System](https://github.com/yagniksorathiya/Recommendation_Systems/assets/129974278/86d40194-ccc2-4aaa-99c7-24361a577909)
