# gcp_ege
The raw data was taken and uploaded to the Cloud Storage bucket using console
There was a function trigger as soon as Bucket receives data to get processed data
The data is then uploaded to Pub/Sub
The data is cleaned using a cloud function.
The data is then sent to BigQuery.
The analysis is done quering the database and analysis is shown in Data Studio.
