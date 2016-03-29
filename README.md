# github-project

# Components 
* **mapper-tool-github** - tool for creating elasticsearch mapping your AWS elasticsearch service index
* **sync-github** - batch sync process for downloading repo data and sending in bulk to service-github-data to be saved
* **ui-github** - the application frontend react static app for browsing repos
* **service-github-data** - microservice for handling all data fetching & crud operations for elasticsearch data store
* **service-github-listener** - microservice that listens for pings from github webhooks and sends updated data to service-github-data 

![Image of dataflow]
(http://i.imgur.com/7RfRcH4.png)
