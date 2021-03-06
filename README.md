# Project Idea
Clickstream analysis for building better websites designed for revenue generation

# Purpose and Use cases
1) Conversion trends - from online marketplaces(clickthrough, basket placement and purchase). Clicking on a product information page means the product has generated interest. If there is not much conversion from click to basket rate, it may be due to poor price point or display.If there is not much conversion from basket to purchase, it may be due to poor checkout experience.
2) Click-path Optimization and effectiveness of ad campaigns- Collect and analyze data to see pages visitors are visiting and in what order.
3) Market basket analysis- what products people buy together, making recommendations and making another sale.
4) Conversion rate from watching third-party content to original content(Netflix lures customers into watching its original content by advertising the more popular third party content).
5) How competitors are making conversions
6) Any online behaviors- favorite cars, searches etc.

# Technologies
![Possible Method](https://qph.fs.quoracdn.net/main-qimg-f6a9510d1b187e8d599124d437fee129-c)

Stream processing is done over a small window
Batch processing takes a whole bulk of data to generate metrics for a larger time frame.

1) Kafka for data ingestion
2) Spark for streaming for real-time computations
3) Run Map-Reduce jobs on HDFS
4) Druid is an open-source data store designed for sub-second queries on real-time and historical data.
 or Cassandra for its high scalability and availability

# Architecture
![Architecture](architecture.jpeg)

#Current Architecture
![CurrentArchitecture](currentarchitecture.jpg)

# Primary engineering challenges
1) Deciding which tool to use and convincing another as to my intentions
2) Currently data size is small. While scaling up, I may end up with more challenges.



# References
1) www.jumpshot.com
2) www.qubole.com
3) www.qurora.com
4) Visualization and Analysis of Clickstream Data of Online Stores for Understanding Web Merchandising
5) https://stackoverflow.com/questions/39196983/clickstream-data-analysis?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa
6) https://www.quora.com/What-are-the-applications-of-clickstream-analysis
7) https://opendata.stackexchange.com/questions/1779/clickstream-sample-dataset
