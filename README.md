# Spark
Spark
Data in Scala and Spark
In my first two blog posts of the Spark Streaming and Kafka series - Part 1 - Creating a New Kafka Connector and Part 2 - Configuring a Kafka Connector - I showed how to create a new custom Kafka Connector and how to set it up on a Kafka server. Now it is time to deliver on the promise to analyse Kafka data with Spark Streaming.

When working with Apache Spark, you can choose between one of these programming languages: Scala, Java or Python. (There is also support for Spark querying in R.) Python is admittedly the most popular, largely thanks to Python being the most popular (and easiest to learn) programming language from the selection above. Python's PySpark library is catching up with the Spark features available in Scala, but the fact that Python relies on dynamic typing, poses challenges with Spark integration and in my opinion makes Spark a less natural fit with Python than with Scala.

Spark and Scala - the Basics
Spark was developed in Scala and its look and feel resembles its mother language quite closely. In fact, before diving into Spark Streaming, I am tempted to illustrate that for you with a small example (that also nicely recaptures the basics of Spark usage):
