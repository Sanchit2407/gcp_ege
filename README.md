# gcp_ege
1. The raw data was taken and uploaded to the Cloud Storage bucket using console.
2. There was a function trigger as soon as Bucket receives data to get processed data
3. The data is then uploaded to Pub/Sub
4. The data is cleaned using a cloud function.
5. The data is then sent to BigQuery.
6. The analysis is done quering the database and analysis is shown in Data Studio.
