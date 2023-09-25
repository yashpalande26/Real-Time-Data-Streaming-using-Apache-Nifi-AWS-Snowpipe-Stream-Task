# Real-Time-Data-Streaming-using-Apache-Nifi-AWS-Snowpipe-Stream-Task :

In the project titled "Real-Time Data Streaming using Apache Nifi, AWS, Snowpipe, Stream & Task," I embarked on a journey to explore and harness the potential of real-time data streaming. The project's primary objective was to witness the dynamic nature of data in action, from its generation to transformation and storage.

The project workflow unfolded as follows:

1. Data Generation & Upload: To simulate real-time data generation, I created a system that continually produced data. This generated data was promptly uploaded to an Amazon S3 bucket, where it awaited further processing.

2. Snowpipe for Real-Time Ingestion: Leveraging Snowpipe, a powerful tool in the Snowflake ecosystem, I triggered the ingestion process. Snowpipe swiftly loaded the data into a staging area, ensuring a smooth transition from source to destination.

3. Snowflake Streams & Tasks: To track and manage changes at the table level, I implemented Snowflake streams and tasks. Streams kept us informed about any modifications, while tasks played a pivotal role in automation, streamlining various aspects of the data pipeline.

4. Change Data Capture (CDC): Building upon the staging area, I executed Change Data Capture, meticulously capturing insertions, updates, and deletions in the data. This granular level of data monitoring enabled accurate tracking and processing.

5. Slowly Changing Dimensions (SCD): To accommodate evolving data, I applied Slowly Changing Dimension (SCD) techniques, including SCD1 and SCD2. These methods facilitated the management of historical and evolving data, ensuring a comprehensive view of changes over time.

6. Snowflake Data Warehousing: The culmination of this project involved storing the transformed and enriched data in Snowflake's data warehouse. This repository provided a solid foundation for advanced analytics and decision-making.

This project serves as a testament to my expertise in real-time data streaming, ETL (Extract, Transform, Load) automation, and advanced data warehousing techniques. It reflects my ability to manage dynamic data environments efficiently and derive valuable insights from real-time data streams.
