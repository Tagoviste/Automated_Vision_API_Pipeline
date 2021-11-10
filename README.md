# Automated_Vision_API_Pipeline
Automated Pipeline for Vision API Labelling and Document_Text_Detection using Python Client Library
*   Disclaimer: This is not an official Google script
*   Created by: Public Sector CE

# Table of Contents
- [Dependencies](#dependencies)
- [Capabilities](#capabilities)
- [Installation](#installation)
- [Supported Providers](/docs)
    * Major Cloud
        * [Google Cloud](/docs/gcp.md)


## Dependencies

1.  GCP VPC.
2.  GCS Storage Buckets.
3.  Vision API
4.  Cloud Functions.
5.  Service Accounts.
6.  BigQuery
7.  Data Studio - Optional




## Capabilities

1.  Automated processing of uploaded images from a specified GCS bucket using GCP Vision API.
2.  Save processed output to a designated GCS storage.
3.  Automated upload of results into a designated BigQuery dataset table.


#### Components

1.    2 * GCS Buckets
2.      - Image Upload Bucket <upload_bucket_name>
3.      - Processed Output Bucket <output_bucket_name>
4.    2 * Cloud Function scripts
5.      - Vision API Processing <vision_api_python>
6.      - BigQuery Data Ingestion <bq_data_python>
7.    1 * BigQuery Dataset Table
8.      - Image Data <image_data_table>
9.    2 * Service Accounts
10.     - 


#### Permissions

