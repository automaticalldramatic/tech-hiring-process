Q. A common pattern in real-time data workflows is performing rolling counts of incoming data points, also known as sliding window analysis. A typical use case for rolling counts is identifying trending topics in a user community – such as on Twitter, Instagram or Facebook – where a topic is considered trending when it has been among the top N topics in a given window of time. For this exercise you can listen to an incoming feed of tweets, instagram posts or facebook feed or assume you have a constant stream of updates from a community (create a flat file with data maybe) and stream this into your application. The application should be able to measure, in a particular community what the trending topics are for a given time span; for instance, the most popular topics in the past five minutes or the current day.

The input parameters for this system are :
* a constant feed of updates with topics mentioned with hashtags (#) - lets not reinvent the wheel :P
* a community that subscribes to a subset of this feed
* a time span to get the trending IDs for

As the first part of this exercise, implement a trending topics counter that is always listening to a feed of incoming topics and calculates the trending topic based on a time span provided.

### Assumptions

* assume we have a system that uses some API to pull the latest tweets or a feed of topics 
* assume further that we have a mechanism in place that extracts topical information in the form of words. For instance, we could opt to use a simple pattern matching algorithm that treats #hashtags as topics. 

We design our system so that it considers topic A more popular than topic B (for a given time span) if topic A has been mentioned more often than topic B. This means we only need to count the number of occurrences of topics.

popularity(A) ≥ popularity(B) ⟺ mentions(A) ≥ mentions(B)

* we do not care how the topics are actually derived from user content or user activities as long as the derived topics are represented as textual words. You can assume to get a stream of just topics as well from a system.

### Submission of Results

Please provide the result as a Git repository with this content:

1. The project with all source files and a commit history fit for a king

2. A docker-compose setup

3. A short text document that lists the main steps of building your solution as well as all assumptions/decisions you made in case of unclear requirements or missing information

4. Results could be submitted using any language / framework