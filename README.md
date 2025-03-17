# Load Oracle Fusion Cloud ERP data into Snowflake

You can load data from Oracle Fusion Cloud Enterprise Resource Planning (ERP) or other Oracle Fusion Cloud Applications into various cloud storage solutions, such as Snowflake, using intermediaries like Amazon S3, Azure Blob, or Google Cloud Storage. You can implement a multicloud strategy and have the flexibility to utilize any data warehouse or cloud service provider for your organizational needs.

In this solution, you consider the advantages and disadvantages of three architecture options, and identify and implement the architecture with the least tradeoffs in your organization.

## Installation

This solution playbook uses the following Services:

[Oracle Autonomous Data Warehouse](https://www.oracle.com/autonomous-database/autonomous-data-warehouse/)
Oracle Autonomous Data Warehouse is the world’s first and only autonomous database optimized for analytic workloads, including data marts, data warehouses, data lakes, and data lakehouses.

[Oracle Cloud Infrastructure GoldenGate](https://docs.oracle.com/en/cloud/paas/goldengate-service/druyg/index.html)
Oracle Cloud Infrastructure GoldenGate is a fully managed, native cloud service that moves data in real-time, at scale. OCI GoldenGate processes data as it moves from one or more data management systems to target databases. 

[OCI Data Integration](https://docs.oracle.com/en-us/iaas/data-integration/home.htm)
Data Integration is a fully managed, multi-tenant service that helps data engineers and developers with data movement and data loading tasks. Powered by Spark ETL or ELT processes, a large volume of data can be ingested from a variety of data assets; cleansed; transformed and reshaped; and efficiently loaded to Oracle Cloud Infrastructure target data assets.

[OCI Data Science](https://www.oracle.com/artificial-intelligence/data-science/)
Oracle Cloud Infrastructure (OCI) Data Science is a fully managed platform for teams of data scientists to build, train, deploy, and manage machine learning (ML) models using Python and open source tools. Use a JupyterLab-based environment to experiment and develop models.

[OCI Data Flow](https://www.oracle.com/big-data/data-flow/)
Oracle Cloud Infrastructure (OCI) Data Flow is a fully managed Apache Spark service that performs processing tasks on extremely large datasets—without infrastructure to deploy or manage. Developers can also use Spark Streaming to perform cloud ETL on their continuously produced streaming data. 

[Vault](https://docs.oracle.com/en-us/iaas/Content/KeyManagement/Tasks/managingvaults.htm)

[Business Intelligence Cloud Connector](https://docs.oracle.com/en/cloud/saas/applications-common/24c/biacc/overview-of-business-intelligence-cloud-connector.html#u00180685)

You can use Oracle Business Intelligence Cloud Connector (BICC) to extract business intelligence and other data in bulk and load it into designated external storage areas.

BICC is available as part of the Oracle Applications Cloud subscription. Additional access provisioning is required and you must sign into BICC to perform all tasks related to the data extraction. Details about access provisioning are provided in the Provision Access section.

[Python](https://www.python.org/)
  - [Oracle Cloud Infrastructure SDK for Python](https://docs.oracle.com/en-us/iaas/Content/API/SDKDocs/pythonsdk.htm)

Please, check the Documentation section for a step by step.

## Documentation

Please, navigate to [Oracle Architecture Center](https://docs-uat.us.oracle.com/en/solutions/load-fusion-erp-data-snowflake/index.html#GUID-1C007BD1-370C-4147-887C-DB3B19AEF036) to follow the step by step to load data into Snowflake.

## Examples

You can find some examples in this repository unde Code folder and [Oracle Architecture Center](https://docs-uat.us.oracle.com/en/solutions/load-fusion-erp-data-snowflake/index.html#GUID-1C007BD1-370C-4147-887C-DB3B19AEF036)

## Help
If you need help with this sample, please log an issue within this repository and the code owners will help out where we can.

## Security

Oracle takes security seriously and has a dedicated response team for [reporting security vulnerabilities](./SECURITY.md) and to answer any security and vulnerability related questions.

## Contributing
We welcome all contributions to this sample and have a [contribution guide](./CONTRIBUTING.md) for you to follow if you'd like to contribute.

## Distribution
Developers choosing to distribute a binary implementation of this project are responsible for obtaining and providing all required licenses and copyright notices for the third-party code used in order to ensure compliance with their respective open source licenses.


## Help

If you need help with this sample, please log an issue within this repository and the code owners will help out where we can.

## License

Copyright (c) 2025 Oracle and/or its affiliates. 

Licensed under the Universal Permissive License v 1.0 as shown at 
https://oss.oracle.com/licenses/upl.
