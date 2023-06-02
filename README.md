# Python Ship Logbook

This is an implementation of a Ship Logbook Services responsible for receiving, collecting, and processing data from various ship geolocation devices and making it available for further analysis or storage. The primary goal of a Ship Logbook Services is maintaining an precise log of essential ship instruments reading such as GPS, speed, heading, and other data. The secondary goal is to provide a way to access this data in a convenient way. For such a task the services provides a "Data Ingestor Microservice" to receive data from various devices and a "Data Dashboard Microservice" to provide access to the data though an dashboard. The services also provides a "Data Disgestor Microservice" to process the data and make it available for further analysis or storage. 

