---
audience: user
user-guide-title: Adobe Experience Platform Source Connectors Help
breadcrumb-title: Source Connectors Guide
user-guide-description: Ingest data from a variety of sources or structure, label, and enhance already ingested data.
feature: Sources
---

# Source connectors {#sources}

- [Source connectors overview](home.md)
- Available source connectors {#connectors}
  - Adobe applications {#adobe-applications}
    - [Analytics Classifications source connector](connectors/adobe-applications/classifications.md)
    - [Analytics source connector](connectors/adobe-applications/analytics.md)
    - [Audience Manager source connector](connectors/adobe-applications/audience-manager.md)
    - [Customer attributes source connector](connectors/adobe-applications/customer-attributes.md)
    - Field mappings {#mapping}
      - [Analytics field mappings](connectors/adobe-applications/mapping/analytics.md)
      - [Audience Manager field mappings](connectors/adobe-applications/mapping/audience-manager.md)
      - [Target field mappings](connectors/adobe-applications/mapping/target.md)
      - [Marketo Engage field mappings](connectors/adobe-applications/mapping/marketo.md)
      - [Salesforce field mappings](connectors/adobe-applications/mapping/salesforce.md)
    - Marketo {#marketo}
      - [Marketo Engage connector](connectors/adobe-applications/marketo/marketo.md)
      - [Marketo Engage authentication guide](connectors/adobe-applications/marketo/marketo-auth.md)
      - [B2B namespaces and schemas](connectors/adobe-applications/marketo/marketo-namespaces.md)
  - Advertising {#advertising}
    - [Google AdWords connector](connectors/advertising/ads.md)
  - Cloud storage {#cloud-storage}
    - [Amazon Kinesis connector](connectors/cloud-storage/kinesis.md)
    - [Amazon S3 connector](connectors/cloud-storage/s3.md)
    - [Apache HDFS connector](connectors/cloud-storage/hdfs.md)
    - [Azure Data Lake Storage Gen2 connector](connectors/cloud-storage/adls-gen2.md)
    - [Azure Blob connector](connectors/cloud-storage/blob.md)
    - [Azure Event Hubs connector](connectors/cloud-storage/eventhub.md)
    - [Azure File Storage connector](connectors/cloud-storage/azure-file-storage.md)
    - [Data Landing Zone](connectors/cloud-storage/data-landing-zone.md)
    - [FTP connector](connectors/cloud-storage/ftp.md)
    - [Google Cloud Storage connector](connectors/cloud-storage/google-cloud-storage.md)
    - [Google PubSub](connectors/cloud-storage/google-pubsub.md)
    - [Oracle Object Storage](connectors/cloud-storage/oracle-object-storage.md)
    - [SFTP connector](connectors/cloud-storage/sftp.md)
    - [Amazon S3 and Azure Blob connector](connectors/cloud-storage/blob-s3.md)
  - CRM {#crm}
    - [Microsoft Dynamics connector](connectors/crm/ms-dynamics.md)
    - [Salesforce connector](connectors/crm/salesforce.md)
    - [Veeva CRM connector](connectors/crm/veeva.md)
    - [Zoho CRM connector](connectors/crm/zoho.md)
  - Customer success {#customer-success}
    - [Salesforce Service Cloud connector](connectors/customer-success/salesforce-service-cloud.md)
    - [ServiceNow connector](connectors/customer-success/servicenow.md)
  - Databases {#databases}
    - [Amazon Redshift connector](connectors/databases/redshift.md)
    - [Apache Hive on Azure HDInsights connector](connectors/databases/hive.md)
    - [Apache Spark on Azure HDInsights connector](connectors/databases/spark.md)
    - [Azure Data Explorer connector](connectors/databases/data-explorer.md)
    - [Azure Synapse Analytics connector](connectors/databases/synapse-analytics.md)
    - [Azure Table Storage connector](connectors/databases/ats.md)
    - [Couchbase connector](connectors/databases/couchbase.md)
    - [Google BigQuery connector](connectors/databases/bigquery.md)
    - [GreenPlum connector](connectors/databases/greenplum.md)
    - [HP Vertica connector](connectors/databases/hp-vertica.md)
    - [IBM DB2 connector](connectors/databases/ibm-db2.md)
    - [MariaDB connector](connectors/databases/mariadb.md)
    - [Microsoft SQL Server connector](connectors/databases/sql-server.md)
    - [MySQL connector](connectors/databases/mysql.md)
    - [Oracle connector](connectors/databases/oracle.md)
    - [Phoenix connector](connectors/databases/phoenix.md)
    - [PostgreSQL connector](connectors/databases/postgres.md)
    - [Snowflake connector](connectors/databases/snowflake.md)
  - eCommerce {#ecommerce}
    - [Shopify connector](connectors/ecommerce/shopify.md)
  - Local system {#local-system}
    - [Local file upload connector](connectors/local-system/local-file-upload.md)  
  - Marketing automation {#marketing-automation}
    - [HubSpot connector](connectors/marketing-automation/hubspot.md)
    - [Mailchimp connector](connectors/marketing-automation/mailchimp.md)
    - [Salesforce Marketing Cloud](connectors/marketing-automation/salesforce-marketing-cloud.md)
  - Payments {#payments}
    - [PayPal connector](connectors/payments/paypal.md)
  - Protocols {#protocols}
    - [Generic OData connector](connectors/protocols/odata.md)
    - [Generic REST API connector](connectors/protocols/generic-rest.md)
  - Streaming {#streaming}
    - [HTTP API connector](connectors/streaming/http.md)
- API tutorials {#api-tutorials}
  - Create a base connection {#create}
    - Advertising {#advertising}
      - [Google AdWords](tutorials/api/create/advertising/ads.md)
    - Cloud storage {#cloud-storage}
      - [Amazon Kinesis](tutorials/api/create/cloud-storage/kinesis.md)
      - [Amazon S3](tutorials/api/create/cloud-storage/s3.md)
      - [Apache HDFS](tutorials/api/create/cloud-storage/hdfs.md)
      - [Azure Blob](tutorials/api/create/cloud-storage/blob.md)
      - [Azure Data Lake Storage Gen2](tutorials/api/create/cloud-storage/adls-gen2.md)
      - [Azure Event Hubs](tutorials/api/create/cloud-storage/eventhub.md)
      - [Azure File Storage](tutorials/api/create/cloud-storage/azure-file-storage.md)
      - [Data Landing Zone](tutorials/api/create/cloud-storage/data-landing-zone.md)
      - [FTP](tutorials/api/create/cloud-storage/ftp.md)
      - [Google Cloud Storage](tutorials/api/create/cloud-storage/google.md)
      - [Google PubSub](tutorials/api/create/cloud-storage/google-pubsub.md)
      - [Oracle Object Storage](tutorials/api/create/cloud-storage/oracle-object-storage.md)
      - [SFTP](tutorials/api/create/cloud-storage/sftp.md)
    - CRM {#crm}
      - [Microsoft Dynamics](tutorials/api/create/crm/ms-dynamics.md)
      - [Salesforce](tutorials/api/create/crm/salesforce.md)
      - [Veeva CRM](tutorials/api/create/crm/veeva.md)
      - [Zoho CRM](tutorials/api/create/crm/zoho.md)
    - Customer success {#customer-success}
      - [Salesforce Service Cloud](tutorials/api/create/customer-success/salesforce-service-cloud.md)
      - [ServiceNow](tutorials/api/create/customer-success/servicenow.md)
    - Databases {#databases}
      - [Amazon Redshift](tutorials/api/create/databases/redshift.md)
      - [Apache Hive on Azure HDInsights](tutorials/api/create/databases/hive.md)
      - [Apache Spark on Azure HDInsights](tutorials/api/create/databases/spark.md)
      - [Azure Data Explorer](tutorials/api/create/databases/data-explorer.md)
      - [Azure Synapse Analytics](tutorials/api/create/databases/synapse-analytics.md)
      - [Azure Table Storage](tutorials/api/create/databases/ats.md)
      - [Couchbase](tutorials/api/create/databases/couchbase.md)
      - [Google BigQuery](tutorials/api/create/databases/bigquery.md)
      - [GreenPlum](tutorials/api/create/databases/greenplum.md)
      - [HP Vertica](tutorials/api/create/databases/hp-vertica.md)
      - [IBM DB2](tutorials/api/create/databases/ibm-db2.md)
      - [MariaDB](tutorials/api/create/databases/mariadb.md)
      - [MySQL](tutorials/api/create/databases/mysql.md)
      - [Oracle](tutorials/api/create/databases/oracle.md)
      - [Phoenix](tutorials/api/create/databases/phoenix.md)
      - [PostgreSQL](tutorials/api/create/databases/postgres.md)
      - [Snowflake](tutorials/api/create/databases/snowflake.md)
      - [SQL Server](tutorials/api/create/databases/sql-server.md)
    - eCommerce {#ecommerce}
      - [Shopify](tutorials/api/create/ecommerce/shopify.md)
    - Marketing automation {#marketing-automation}
      - [HubSpot](tutorials/api/create/marketing-automation/hubspot.md)
      - [MailChimp Campaign](tutorials/api/create/marketing-automation/mailchimp-campaign.md)
      - [MailChimp Members](tutorials/api/create/marketing-automation/mailchimp-members.md)
      - [Salesforce Marketing Cloud](tutorials/api/create/marketing-automation/salesforce-marketing-cloud.md)
    - Payments {#payments}
      - [PayPal](tutorials/api/create/payments/paypal.md)
    - Protocols {#protocols}
      - [Generic OData](tutorials/api/create/protocols/odata.md)
      - [Generic REST API](tutorials/api/create/protocols/generic-rest.md)
    - Streaming {#streaming}
      - [HTTP API](tutorials/api/create/streaming/http.md)
  - Explore data {#explore}
    - [Explore advertising data](tutorials/api/explore/advertising.md)
    - [Explore cloud storage data](tutorials/api/explore/cloud-storage.md)
    - [Explore CRM data](tutorials/api/explore/crm.md)
    - [Explore customer success data](tutorials/api/explore/customer-success.md)
    - [Explore database data](tutorials/api/explore/database-nosql.md)
    - [Explore eCommerce data](tutorials/api/explore/ecommerce.md)
    - [Explore marketing automation data](tutorials/api/explore/marketing-automation.md)
    - [Explore payment data](tutorials/api/explore/payments.md)
    - [Explore protocol data](tutorials/api/explore/protocols.md)
  - Collect data {#collect}
    - [Collect advertising data](tutorials/api/collect/advertising.md)
    - [Collect cloud storage data](tutorials/api/collect/cloud-storage.md)
    - [Collect CRM data](tutorials/api/collect/crm.md)
    - [Collect customer success data](tutorials/api/collect/customer-success.md)
    - [Collect database data](tutorials/api/collect/database-nosql.md)
    - [Collect eCommerce data](tutorials/api/collect/ecommerce.md)
    - [Collect marketing automation data](tutorials/api/collect/marketing-automation.md)
    - [Collect payment data](tutorials/api/collect/payments.md)
    - [Collect protocol data](tutorials/api/collect/protocols.md)
    - [Collect streaming data](tutorials/api/collect/streaming.md)
  - [Monitor dataflows](tutorials/api/monitor.md)
  - [Update accounts](tutorials/api/update.md)
  - [Update dataflows](tutorials/api/update-dataflows.md)
  - [Delete accounts](tutorials/api/delete.md)
  - [Delete dataflows](tutorials/api/delete-dataflows.md)
- UI tutorials {#ui-tutorials}
  - Create a source connection {#create}
    - Adobe applications {#adobe-applications}
      - [Adobe Analytics (report-suite data)](tutorials/ui/create/adobe-applications/analytics.md)
      - [Adobe Analytics (classifications data)](tutorials/ui/create/adobe-applications/classifications.md)
      - [Adobe Audience Manager](tutorials/ui/create/adobe-applications/audience-manager.md)
      - [Adobe Campaign Managed Services](tutorials/ui/create/adobe-applications/campaign.md)
      - [Customer attributes](tutorials/ui/create/adobe-applications/customer-attributes.md)
      - [Marketo Engage](tutorials/ui/create/adobe-applications/marketo.md)
    - Advertising {#create}
      - [Google AdWords](tutorials/ui/create/advertising/ads.md)
    - Cloud storage {#cloud-storage}
      - [Amazon Kinesis](tutorials/ui/create/cloud-storage/kinesis.md)
      - [Amazon S3](tutorials/ui/create/cloud-storage/s3.md)
      - [Apache HDFS](tutorials/ui/create/cloud-storage/hdfs.md)
      - [Azure Data Lake Storage Gen2](tutorials/ui/create/cloud-storage/adls-gen2.md)
      - [Azure Blob](tutorials/ui/create/cloud-storage/blob.md)
      - [Azure Event Hubs](tutorials/ui/create/cloud-storage/eventhub.md)
      - [Azure File Storage](tutorials/ui/create/cloud-storage/azure-file-storage.md)
      - [Data Landing Zone](tutorials/ui/create/cloud-storage/data-landing-zone.md)
      - [FTP](tutorials/ui/create/cloud-storage/ftp.md)
      - [Google Cloud Storage](tutorials/ui/create/cloud-storage/google-cloud-storage.md)
      - [Google PubSub](tutorials/ui/create/cloud-storage/google-pubsub.md)
      - [Oracle Object Storage](tutorials/ui/create/cloud-storage/oracle-object-storage.md)
      - [SFTP](tutorials/ui/create/cloud-storage/sftp.md)
      - [Amazon S3 and Blob](tutorials/ui/create/cloud-storage/blob-s3.md)
    - CRM {#crm}
      - [Microsoft Dynamics](tutorials/ui/create/crm/dynamics.md)
      - [Salesforce](tutorials/ui/create/crm/salesforce.md)
      - [Veeva CRM](tutorials/ui/create/crm/veeva.md)
      - [Zoho CRM](tutorials/ui/create/crm/zoho.md)
    - Customer Success {#customer-success}
      - [Salesforce Service Cloud](tutorials/ui/create/customer-success/salesforce-service-cloud.md)
      - [ServiceNow](tutorials/ui/create/customer-success/servicenow.md)
    - Databases {#databases}
      - [Amazon Redshift](tutorials/ui/create/databases/redshift.md)
      - [Apache Hive on Azure HDInsights](tutorials/ui/create/databases/hive.md)
      - [Apache Spark on Azure HDInsights](tutorials/ui/create/databases/spark.md)
      - [Azure Data Explorer](tutorials/ui/create/databases/data-explorer.md)
      - [Azure Synapse Analytics](tutorials/ui/create/databases/synapse-analytics.md)
      - [Azure Table Storage](tutorials/ui/create/databases/ats.md)
      - [Couchbase](tutorials/ui/create/databases/couchbase.md)
      - [Google Big Query](tutorials/ui/create/databases/bigquery.md)
      - [GreenPlum](tutorials/ui/create/databases/greenplum.md)
      - [HP Vertica](tutorials/ui/create/databases/hp-vertica.md)
      - [IBM DB2](tutorials/ui/create/databases/ibm-db2.md)
      - [MariaDB](tutorials/ui/create/databases/mariadb.md)
      - [Microsoft SQL Server](tutorials/ui/create/databases/sql-server.md)
      - [MySQL](tutorials/ui/create/databases/mysql.md)
      - [Oracle](tutorials/ui/create/databases/oracle.md)
      - [Phoenix](tutorials/ui/create/databases/phoenix.md)
      - [PostgreSQL](tutorials/ui/create/databases/postgres.md)
      - [Snowflake](tutorials/ui/create/databases/snowflake.md)
    - eCommerce {#ecommerce}
      - [Shopify](tutorials/ui/create/ecommerce/shopify.md)
    - Local system {#local-system}
      - [Local file upload](tutorials/ui/create/local-system/local-file-upload.md)  
    - Marketing automation {#marketing-automation}
      - [HubSpot](tutorials/ui/create/marketing-automation/hubspot.md)
      - [Mailchimp Campaigns](tutorials/ui/create/marketing-automation/mailchimp-campaigns.md)
      - [Mailchimp Members](tutorials/ui/create/marketing-automation/mailchimp-members.md)
      - [Salesforce Marketing Cloud](tutorials/ui/create/marketing-automation/salesforce-marketing-cloud.md)
    - Payments {#payments}
      - [PayPal](tutorials/ui/create/payments/paypal.md)
    - Protocols {#protocols}
      - [Generic OData](tutorials/ui/create/protocols/odata.md)
    - Streaming {#streaming}
      - [HTTP API](tutorials/ui/create/streaming/http.md)
  - Configure a dataflow {#dataflow}
    - [Advertising connection dataflow](tutorials/ui/dataflow/advertising.md)
    - [Batch cloud storage connection dataflow](tutorials/ui/dataflow/batch/cloud-storage.md)
    - [Streaming cloud storage connection dataflow](tutorials/ui/dataflow/streaming/cloud-storage-streaming.md)
    - [CRM connection dataflow](tutorials/ui/dataflow/crm.md)
    - [Customer success connection dataflow](tutorials/ui/dataflow/customer-success.md)
    - [Database connection dataflow](tutorials/ui/dataflow/databases.md)
    - [Ecommerce connection dataflow](tutorials/ui/dataflow/ecommerce.md)
    - [Marketing automation connection dataflow](tutorials/ui/dataflow/marketing-automation.md)
    - [Payment connection dataflow](tutorials/ui/dataflow/payments.md)
    - [Protocol connection dataflow](tutorials/ui/dataflow/protocols.md)
  - [Activate inbound data to populate customer profiles](tutorials/ui/profile.md)
  - [Monitor batch dataflows](tutorials/ui/monitor.md)
  - [Monitor streaming dataflows](tutorials/ui/monitor-streaming.md)
  - [Update accounts](tutorials/ui/update.md)
  - [Update dataflows](tutorials/ui/update-dataflows.md)
  - [Delete accounts](tutorials/ui/delete-accounts.md)
  - [Delete dataflows](tutorials/ui/delete.md)
  - [Subscribe to sources alerts](tutorials/ui/alerts.md)
- Sources SDK {#sdk}
  - [Overview](sources-sdk/overview.md)
  - [Configuration options](sources-sdk/config/config.md)
  - [Configure authentication specification](sources-sdk/config/authspec.md)
  - [Configure source specification](sources-sdk/config/sourcespec.md)
  - [Configure explore specification](sources-sdk/config/explorespec.md)
  - [Sources SDK API overview](sources-sdk/api/api-overview.md)
  - [Getting started](sources-sdk/api/getting-started.md)
  - [Create a connection specification](sources-sdk/api/create.md)
  - [Update a connection specification](sources-sdk/api/update-connection-specs.md)
  - [Update a flow specification](sources-sdk/api/update-flow-specs.md)
  - [Submit your source](sources-sdk/api/submit.md)
  - [Document your source in Adobe Experience Platform](sources-sdk/documentation/doc-overview.md)
  - [Use the GitHub web interface to create a sources documentation page](sources-sdk/documentation/github.md)
  - [Use a text editor in your local environment to create a sources documentation page](sources-sdk/documentation/text-editor.md)
  - [Documentation self-service template](sources-sdk/documentation/template.md)
- [Flow run notifications](notifications.md)
- [IP address allow list](ip-address-allow-list.md)
- [Frequently asked questions](./troubleshooting.md)
- [API reference](https://www.adobe.io/experience-platform-apis/references/flow-service/)
- [Platform release notes](https://www.adobe.com/go/platform-release-notes-en)
