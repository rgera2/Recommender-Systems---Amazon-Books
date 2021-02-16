# Recommender-Systems---Amazon-Books

# Introduction and Background
This is hence not surprising that during the most recent couple of years, with the ascent of YouTube, Amazon, Netflix and numerous other such web services, recommender frameworks have assumed increasingly more positions in our lives. From internet business (propose to purchasers’ articles that could intrigue them) to online commercials (propose to clients the correct substance, coordinating their inclinations), recommender frameworks are today unavoidable in our everyday online excursions.

In this project we tried to tackle a similar problem of overburden of choices when selecting books and try to help users by designing some recommendation systems that would suggest books based on the book’s popularity, book’s content and based upon the user’s previous choice and likes and dislikes. We used recommender systems that are too naive to very sophisticated personalized one and try to gauge each system to check their possible merits and demerits.

# Dataset Description:
We used Amazon Dataset which contains 1 million ratings across 10,000 unique books.
In most cases, there are at least 10 books rated by each user and the rating lies between 0 to 5.
The ratings data set provides a list of ratings that users have given to books. It includes 981756 records and 3 fields: user_id, rating, book_id.

# Tools
Google colab, Pyspark

# Recommendor Systems built
1. Popularity based RS
2. Content based RS
3. Collaborative based RS

# Evaluation and Performance
Metric used was RMSE.

Performance improved using 5-fold cross validation (13% improvement from baseline on test data)

# Future scope:
1. A hybrid system using both content-based and collaborative filtering. This would mean incorporating information about the individual items, including features like subject matter, page size, color vs. black and white, creator name, cost, etc.
2. Multi-armed bandit algorithms:
They can recommend products with the highest expected value while still exploring other products. They do not suffer from the cold-start problem and therefore do not require customer preferences or information about products.
