# SA_billing_api
SLED SA Cloud Billing API Project 


SA Billing Project is a activity for the SLED SA to create a multi API connection ingestion for the Billing API with a guide. 

API Key details you will need to make this billing call. 

1. Deployment API KEY 
2. Oginization ID from the deployment 
3. Ingest Method 


The API call you will be making is as following. 

https://api.elastic-cloud.com/api/v1/billing/costs/{{orgnization_id}}
Auth needs to be the API Key and pass via the Headar of the GET Request

That is all you should need to collect and ingest the Elastic Billing Summary for this Orginization. 




