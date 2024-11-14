# Set up
## Set up Google Cloud Platform (GCP)
### Creating a GCP Account
Creating a Google Cloud Platform (GCP) account is straightforward and free, as it only requires an existing Google or Gmail account. GCP offers both a free tier and a free trial option. The free tier provides ongoing, limited access to core GCP services, including a substantial allowance for processing in BigQuery, which this pipeline uses for creating the main database.

The free trial option grants $300 in credits valid for 90 days after activation. Since this pipeline processes a relatively small amount of data, it can typically run with minimal to no cost, even without the free trial. 

### Creating a GCP Project
Next, create a google cloud project. You could call it something along the lines of "crypto-data-pipeline".
Then enable relevant APIs for the project, including that for Cloud Storage, Compute Engine (if you wish to run the pipeline on a VM), BigQuery and Dataproc.

## Set up Environment 
### Install required packages
### Setup the cloud resources
