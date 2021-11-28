# Real-time-streaming-
In power BI streaming, we can stream data and update dashboards in real-time. Any visual or dashboard that can be created in Power BI can also be created to display and update real-time data and visuals. The devices and sources of streaming data can be factory sensors, social media sources, service usage metrics, or many other time-sensitive data collectors or transmitters.
# Need to Implement Power BI Real Time Streaming
Power BI is primarily a decision-making tool that helps to extract valuable insights from the data. In the new age of analytics-driven decision-making, the one who has the latest data typically wins the market. There are also specific IOT based requirements where Real Time data has to be analyzed. In all these cases, Power BI’s Real Time data Streaming capability is a boon for organizations.
# Power BI supports real-time streaming for the following types of datasets::
Push Data
Streaming Dataset
PubNub streaming dataset.

# 1) Push Datasets
Push Datasets are similar to Streaming Datasets except for the fact that they can store data for historical analysis. This ability to store data also helps them to report on the data. They can ingest up to 1 request per second with a maximum payload of 16MB.Streaming Datasets

# 2) Streaming Datasets 
streaming datasets allows external data sources to Push data to Power BI through REST APIs. They help you process the Real Time data as and when it comes in. Streaming Datasets do not store the data anywhere and hence are not suitable for cases where historical data analysis is required. They support data retrieval for up to an hour. They can ingest up to 5 requests per second with a maximum payload of 15KB. A caveat is that you can not build reports using a pure Streaming Dataset. 

# 3) PubNub streaming Datasets
PubNub provides an SDK based on which you can implement Real Time communication platforms. Since this is a separate infrastructure as a service product, Power BI does not ingest any data and only displays the data by accessing the streams. PubNub will allow users to work around the throughput and request data size limits imposed by Power BI.

In here we will be using the pubnub streaming dataset to create a report and dashboard . 
pubnub streaming datasets link - https://www.pubnub.com/developers/realtime-data-streams/
Dashboard link -  https://app.powerbi.com/groups/9a727f96-25dd-415a-8d86-82503e2d7d3e/dashboards/0d74bed4-0c8c-482a-b375-d9c184bada14

so lets rock and roll 
