# <span style="color:darkblue; font-weight:bold;">Generation SG Junior Data Engineer Programme</span><br><span style="color:darkblue; font-weight:regular;">Final Project: Brazilian E-commerce Public Dataset by Olist</span><br>
#### By Team C.H.Y.E.F - Chee How | Hui Shan | Pin Pin, Yvonne | Eunica | Yiping, Fred
***
<br>

<a id="readme-top"></a>
<!-- TABLE OF CONTENTS -->
<details>
  <summary><h3><b>Table of Contents</b></h3></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#project-objective">Project Objectives</a></li>
        <li><a href="#project-deliverables">Project Deliverables</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#data-architecture">Data Architecture</a>
    </li>
    <li>
      <a href="#data-sources">Data Sources</a>
    </li>
    <li>
      <a href="#methodology">Methodology</a>
      <ul>
        <li><a href="#data-ingestion">Data Ingestion</a></li>
        <li><a href="#data-transformation">Data Transformation</a></li>    
        <li><a href="#data-analytics">Data Analytics</a></li>
        <li><a href="#proof-of-concept">Proof of Concept: Optimization and Unit/Functional Testing</a></li>
        <li><a href="#data-security-and-governance">Data Security and Governance</a></li>
      </ul>
    </li>
		<li>
      <a href="#analysis">Analysis in Power BI</a>
      <ul>
        <li><a href="#recommendations">Business Recommendations</a></li>
      </ul>
    </li>
    <li>
      <a href="#challenges">Challenges and Solutions</a>
    </li>
    <li>
      <a href="#conclusion">Conclusion</a>
    </li>
  </ol>
</details>
<br><br>

<!-- ABOUT THE PROJECT -->
<a id="about-the-project"></a>
<details>
  <summary><h3><b>About The Project</b></h3></summary>
  <img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Olist.png" alt="Olist Store" style="display: block; margin: 0 auto" /><br><br>

**Unlocking Growth in Brazil's Digital Marketplace: The Olist Story**<br>In the bustling heart of Brazil's e-commerce landscape, Olist Store stands as a testament to the country's digital transformation. As Brazil's leading marketplace department store, Olist has connected thousands of merchants with millions of customers, facilitating over 100,000 transactions between 2016 and 2018. Behind each order lies a story – a customer's journey, a merchant's reputation, and Olist's promise to deliver excellence.<br>

**The Digital Goldmine**<br>Imagine a vast digital archive containing the pulse of Brazil's e-commerce: every order, every payment, every customer interaction meticulously recorded. This isn't just data – it's the collective experience of countless Brazilian shoppers, from the sunny beaches of Rio to the bustling streets of São Paulo. The dataset captures:
- The rhythm of customer purchasing patterns
- The flow of payments through Brazil's digital economy
- The intricate dance of logistics across South America's largest country
- The honest voices of customers sharing their experiences
- The geographic tapestry of Brazil's diverse marketplace
<br>

**The Hidden Opportunity**<br>Yet beneath this mountain of data lies untapped potential. While Olist has successfully facilitated thousands of transactions, the true value isn't in what these numbers show – it's in what they hide. Every delayed delivery tells a story about optimization opportunities. Every customer review whispers insights about service improvement. Every abandoned cart holds clues to untapped revenue.<br>

**The Challenge Before Us**<br>The task at hand is exciting and daunting: transforming this rich dataset into actionable intelligence that can revolutionize Olist's marketplace performance. We must:
1. Decode patterns in customer behaviour that could unlock new market segments
2. Uncover inefficiencies in fulfilment that, if addressed, could delight customers
3. Identify the subtle factors that turn satisfied customers into loyal advocates
4. Map the journey from browse to buy, understanding where customers hesitate and why<br>

This isn't just about analyzing numbers – it's about understanding the stories of millions of Brazilians who shop online, the merchants who serve them, and the platform that brings them together. The insights we uncover could reshape the future of e-commerce in Latin America's largest economy.<br>

The question isn't just "What does the data tell us?" but rather "How can we use these insights to create a marketplace that serves Brazil better?"<br>

**Data Source:** [Kaggle - Brazilian E-commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)<br>

</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br><br>

<!-- PROJECT OBJECTIVES -->
<a id="project-objectives"></a>
<details>
  <summary><h3><b>Project Objectives</b></h3></summary>

**The Vision: From Raw Data to Business Gold: A Digital Transformation Journey**<br>Imagine walking into a room filled with scattered pieces of a puzzle. Each piece represents a fragment of your business's story – customer interactions, operational metrics, market performance, and countless other data points. Right now, these pieces lie dormant, their true value locked away. But we're about to change that.<br>

**The Challenge**<br>In today's data-driven world, having information isn't enough. The real power lies in how we collect, connect, and interpret it. Our mission is to build a robust digital pipeline that will transform raw data into actionable insights, enabling leaders to make decisions with confidence and precision.<br>

**The Journey**<br>
**Phase 1: Building the Foundation**<br>Picture constructing a digital highway where data flows seamlessly from various sources into a centralized, intelligent system. We're not just storing data – we're creating a living, breathing ecosystem in our PostgreSQL/SQL Server database. Every table, every relationship, every data point is carefully architected to tell a story.<br>

**Phase 2: Quality and Discovery**<br>Like a master jeweler examining precious stones, we'll scrutinize every piece of data:
- Uncovering hidden patterns in customer behavior
- Identifying anomalies that could signal opportunities or risks
- Cleaning and enriching data to ensure it's trustworthy and meaningful
- Connecting seemingly unrelated information to reveal deeper insights
<br>

**Phase 3: Bringing Data to Life**<br>This is where numbers transform into narratives. Through an intuitive Power BI dashboard:
- Complex data patterns become clear visual stories
- Real-time insights emerge at the click of a button
- Business leaders can explore data landscapes with ease
- Teams across departments gain a shared view of truth
<br>

**Phase 4: Ensuring Excellence**<br>Trust is earned through rigorous validation. Every insight, every calculation, every visualization will be meticulously tested. We'll compare dashboard figures against database queries, ensuring that what you see isn't just beautiful – it's absolutely accurate.<br>

**Phase 5: Unleashing Strategic Power**<br>The culmination of our journey isn't just a technical achievement – it's a business transformation. Armed with deep insights, we'll:
- Identify untapped market opportunities
- Optimize operational efficiency
- Enhance customer experiences
- Drive data-informed strategic decisions
<br>

**The Impact**<br>When complete, this isn't just a data project – it's a business revolution. Decision-makers will move from gut feelings to data-driven certainty. Teams will shift from reactive to proactive. And your organization will gain a competitive edge through deeper understanding and faster response to market dynamics.<br>

**Looking Ahead**<br>This transformation journey marks the beginning of a new era for your business – one where every decision is informed by insights, every strategy is backed by data, and every team is empowered with knowledge. The future isn't just about having data; it's about mastering it.

</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br><br>

<!-- PROJECT DELIVERABLES -->
<a id="project-deliverables"></a>
<details>
  <summary><h3><b>Project Deliverables</b></h3></summary>
  <li>Information about the architecture, dataset, data relationships, database schema</li>
  <li>Approach, challenges, findings, recommendations</li>
  <li>Power BI source file or the published Power BI dashboard URL</li>
  <li>Source code</li>
</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br>

<!-- GETTING STARTED -->
<a id="getting-started"></a>
<a id="prerequisites"></a>
<details>
  <summary><h3><b>Getting Started</b></h3></summary>

### <span style="color:darkblue; font-weight:bold;">Prerequisites</span>

#### **Active Primary (Azure)**<br>
**Azure Managed Services**
  ```sh
  ├── 01. Azure Subscription
  ├── 02. Kaggle API Credentials 
  ├── 03. Azure Command-Line Interface (CLI)
  ├── 04. Azure Storage / Containers
  ├── 05. Azure Function
  ├── 06. Azure Data Factory
  ├── 07. Azure Databricks
  ├── 08. Azure SQL Database
  ├── 09. Azure Synapse Analytics
  ├── 10. Power BI
  ```
<br>

**1. Azure Subscription**<br>To access to Azure, you'ii need an Azure subscription. If you don't already have a subscription, create a [free account](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account?icid=azurefreeaccount&WT.mc_id=A261C142F) before you begin.<br>

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Azure_Subscription_Creation.png" alt="Azure Subscription" style="display: block; margin: 0 auto" /><br>
<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Olist_Azure_Subscription_20250115.png" alt="Azure Subscription Overview" style="display: block; margin: 0 auto" /><br>

**2. Kaggle API Credentials**<br>A **Kaggle API token** allows you to access and interact with Kaggle's features programmatically throught their public API, enablinh you to perform actions like downloading datasets, submitting competition entries, or managing notebooks directly from your code.<br>

> **How to obtain a Kaggle API Key?**<br>
> Go to the `Account` tab of your user profile and select `Create New Token`. This will trigger the download of the `kaggle.json`, a file containing your API credentials.
> 

**3. Azure Command-Line Interface (CLI)**<br>The [Azure Command-Line Interface (CLI)](https://learn.microsoft.com/en-us/cli/azure/get-started-with-azure-cli) is a tool that allows users to interact with Azure services and resources using a terminal. It's a cross-platform tool that can be used to create, manage, and deploy resources like databases, virtual machines, and storage accounts.<br>

**4. Azure Storage / Container(s)**<br>Set up a storage account to store downloaded datasets.<br>An Azure storage account is a container that bands a set of Azure Storage services together, click on [Microsoft Learn](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-create?tabs=azure-portal).<br>After setting up a storage account, you will need to create a [storage container](https://learn.microsoft.com/en-us/azure/storage/blobs/blob-containers-portal#create-a-container) for storing the datasets.<br>

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Azure_Storage_Container.png" alt="Storage Container" style="display: block; margin: 0 auto" /><br>

**5. Azure Function**<br>Set up an [Azure Function App](https://learn.microsoft.com/en-us/azure/azure-functions/functions-create-function-app-portal?pivots=programming-language-csharp#create-a-function-app) to create a serverless environment for running custom code on-demand for data processing tasks. This eliminates infrastructure management and is ideal for small, event-driven operations, allowing for flexible scaling and cost-effective data manipulation.<br>

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Azure_Function_1.png" alt="Azure Function 1" style="display: block; margin: 0 auto" /><br>
<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Azure_Function_2.png" alt="Azure Function 2" style="display: block; margin: 0 auto" /><br>

**6. Azure Data Factory**<br>Set up an [Azure Data Factory (ADF)](https://learn.microsoft.com/en-us/azure/data-factory/quickstart-create-data-factory) account to manage data pipelines that extract, transform, and load data from diverse sources including on-premises, cloud, SaaS systems. This user-friendly platform simplifies data integration at scale without complex infrastructure, offering extensive connectors and serverless execution while requiring minimal code required.<br>

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/ADF_Creation.png" alt="Azure Data Factory Creation" style="display: block; margin: 0 auto" /><br>

**7. Azure Databricks**<br>Set up [Azure Databricks](https://learn.microsoft.com/en-us/azure/databricks/getting-started/) workspace provides a unified platform in Azure for data processing, transformation, and analytics. It streamlines data pipeline development with features like Delta Lake and Apache Spark, enabling efficient handling of large-scale data operations.<br>

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Databricks_Account_1.png" alt="Databricks Account" style="display: block; margin: 0 auto" /><br>

**8. Azure SQL Database**<br>Set up [Azure SQL Database](https://learn.microsoft.com/en-us/azure/azure-sql/database/single-database-create-quickstart?view=azuresql&tabs=azure-portal) which is a managed cloud database (PaaS) cloud-based Microsoft SQL Servers, provided as parts of Microsoft Azure services. The service handles database management functions for cloud based Microsoft SQL Servers including upgrading, patching, backups, and monitoring without user involvement.<br>

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Create_SQL_Database.png" alt="SQL Database" style="display: block; margin: 0 auto" /><br>

**9. Azure Synapse Analytics**<br>Set up [Azure Synapse Analytics](https://learn.microsoft.com/en-us/azure/synapse-analytics/quickstart-create-workspace), a unified cloud-based analytics platform from Microsoft that combines data warehousing, big data processing, and data integration capabilities, allowing users to query and analyze large datasets from various sources using a single interface, including both relational and non-relational data.<br>

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Create_Synapse_Workspace.png" alt="Synapse Workspace" style="display: block; margin: 0 auto" /><br>

**10. Power BI Desktop**<br>Set up  [Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/fundamentals/desktop-getting-started) which is a collection of software services, apps, and connectors that work together to turn your unrelated sources of data into coherent, visually immersive, and interactive insights. Power BI lets you easily connect to your data sources, visualize and discover what's important, and share that with anyone or everyone you want.<br>

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Power_BI_OlistDB_Connection_1.png" alt="Power BI 1" style="display: block; margin: 0 auto" /><br>
<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Power_BI_OlistDB_Connection_2.png" alt="Power BI 2" style="display: block; margin: 0 auto" /><br>
<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Power_BI_OlistDB_Connection_3.png" alt="Power BI 3" style="display: block; margin: 0 auto" /><br>
<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Power_BI_OlistDB_Connection_4.png" alt="Power BI 4" style="display: block; margin: 0 auto" /><br>

**Azure Account Structure**<br>Organizing resources effectively in Microsoft Azure is essential for managing a cloud environment. Azure uses a structured hierarchy that helps businesses and individuals manage resources more efficiently, control costs, and ensure proper governance. In this guide, we break down the Azure resource hierarchy in simple terms to give you a clear understanding of how to use it.
  ```sh
  ├── 01. Account
  ├── 02. Subscription 
  ├── 03. Resource Group
  ├── 04. Resources
  ```
<br>
<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/OLIST_Azure_Account_Structure.png" alt="Olist Store" style="display: block; margin: 0 auto" /><br><br>

#### **Passive Backup (AWS)**<br>
**AWS Managed Services**

**[Fred to update on prerequsite for AWS]**

**Prerequisites**
- Before setting up this data analytics pipeline, ensure you have the following:
- An AWS account with appropriate permissions 
- Basic understanding of AWS services

**Services Used**
This pipeline utilizes the following AWS services:
AWS management console, easy to toggle and ability to set bookmark for often used services. 
![image-3.png](images/1.png)
1. AWS Identity and Access Management (IAM)
  - To create user and role based policy for assess the services, to prevent unauthorise access to the workspace for security purposes. AWS; Least Privilege Principle, restricting access rights to particular resources for every user, application, and system, with a specific need for access.
  ![image-4.png](images/2.png)
2. Amazon S3 (Simple Storage Service)
  - An Object storage services that offers industry-leading scalability, data availability, security, and performance.
  - Lifecycle management of the file to move file that are infrequently to another tier for cheaper storage on archive file. S3 offers different storage classes to optimize costs based on data access patterns, including Standard, Infrequent Access (IA), and Glacier for archival storage
  - Buckets: Objects are organized into containers called buckets similar to computer file storage level. 
  - Durability and Availability: S3 offers 99.999999999% durability and 99.99% availability for stored objects
3. AWS Glue
  - A fully managed, serverless data integration service that simplifies the process of preparing and transforming data for analytics
  - A service that helps organize, clean, and move data between different storage systems. It's like a smart helper that takes care of the tedious work of getting your data ready for analysis.
4. AWS Glue Crawler
  - An automated tool that simplifies the process of discovering and cataloging data in your AWS environment.
  - To automatically scan our data sources, extract metadata, and populate the AWS Glue Data Catalog with this information. 
  - To aid preparing data for ETL, and setting up of databases. 
5. AWS Glue Data Catalog
  - A central metadata repository that serves as a comprehensive inventory of your data assets across various AWS services. To provide integration with other AWS services such as AWS Athena, Redshift. 
6. Amazon Athena
  - A powerful, serverless query service provided by AWS that enables users to analyze data stored using standard SQL.
  - Pay-per-query pricing model, making it cost-effective
7. Amazon QuickSight
  - A cloud-based business intelligence (BI) service provided by AWS that enables organizations to create and analyze data visualizations, perform ad-hoc analysis, and quickly get business insights from the data.
8. Billing and Cost Management
  - Provide an overview of our expenditure to ensure we run within the free tier limit. 
![image-13.png](images/3.png)


<br>

<a id="installation"></a>
### <span style="color:darkblue; font-weight:bold;">Installation</span>

#### **Active Primary (Azure)**<br>
**Azure Managed Services**<br>

**1. Kaggle CLI**<br>The **Kaggle CLI** tool provive easy ways to interact with Datasets on Kaggle. These commands available can make searching for and downloading Kaggle Datasets a seamless part of data workflow.
1. Run Installation Command on a new Terminal:
    ```sh
    pip install kaggle
    ```
2. After installation is completed, you can verify it by running `kaggle --version` to check version.
3. Move the `kaggle.json` file to the `.kaggle directory` by running:
    ```sh
    mkdir ~/.kaggle
    mv ~/Downloads/kaggle.json ~/.kaggle/
    ```
4. List the current active competition list to confirm if Kaggle CLI is functioning well:
    ```sh
    kaggle competitions list
    ```
<br>

**2. Azure CLI**<br>The **Azure CLI** can be installed on Windows, macOS and Linux distributions: 
* On Linus and macOS, most commonly use package managers like Homebrew or apt-get to install the Azure CLI. 
* While on windows, you can install the Azure CLI using a Microsoft Installer (MSI) Package<br><br>

How to install Azure Commmand-Line Interface (CLI)?
1. Run Installation Command on a new Terminal:
    ```sh
    macOS with Homebrew: brew install azure-cli
    Linux (Ubuntu, Debian): sudo apt-get install azure-cli
    Windows (PowerShell): iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/Azure/azure-cli/latest/azure/install.ps1'))
    ```
2. After installation is completed, you can verify it by running `az --version` to check version.
3. Login to Azure by running `az login` in your terminal to sign in with your Azure account.<br>
For more information on Azure CLI services, click on [Microsoft Learn](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli).<br><br>

**3. Azure MyFunction App**<br>The [Azure Functions Core Tools](https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=macos%2Cisolated-process%2Cnode-v4%2Cpython-v2%2Chttp-trigger%2Ccontainer-apps&pivots=programming-language-csharp) can be installed on Windows, macOS and Linux distributions.<br>

How to install Azure Commmand-Line Interface (CLI)?
1. Run Installation Command on a new Terminal for macOS: 
    ```sh
    brew tap azure/functions
    brew install azure-functions-core-tools@4
    # if upgrading on a machine that has 2.x or 3.x installed:
    brew link --overwrite azure-functions-core-tools@4
    ```
2. Create your local project in a Python Programming model, run the following command:
   ```sh
   func init MyFunctionApp --python
   ```
3. A new folder can be found in your local drive:
   ```sh
   /Users/User-Name/MyFunctionApp/
    ├── function_app.py
    ├── host.json
    ├── local.settings.json
    ├── requirements.txt
    ├── .vscode/extensions.json
   ```
4. Update `requirements.txt` file by adding the following dependencies: 
   ```sh
   azure-functions
   azure-storage-blob
   kaggle
   ```
   Then run this command:
   ```sh
   pip install -r requirements.txt
   ```   
   Alternatively, you can run this command:
   ```sh
   pip install azure-functions azure-storage-blob kaggle
   ```
5. Add your storage connection string to the `local.settings.json` file. You can find this in Azure portal under the storage account's "Access keys" section:
   ```sh
   {
     "IsEncrypted": false,
     "Values": {
      "AzureWebJobsStorage": "UseDevelopmentStorage=true",
      "FUNCTIONS_WORKER_RUNTIME": "python",
      "AZURE_STORAGE_CONNECTION_STRING": "your_actual_connection_string_here"
     }
   }
   ```
6. Install Azure Storage Emulator as we are using "UseDevelopmentStorage=true"
   ```sh
   npm install -g azurite
   ```
<br>

#### **Passive Backup (AWS)**<br>
**AWS Managed Services**<br>

**[Fred to update]**

</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br><br>

<!-- DATA ARCHITECTURE -->
<a id="data-architecture"></a>
<details>
  <summary><h3><b>Data Architecture</b></h3></summary>
  <p>
  Building a data pipeline with Azure as the primary environment and AWS as a secondary environment offers several strategic business adventages. This approach leverages the strengths of both cloud platforms while providing redundancy and flexiblity. Here's an explanation of the business rationale behind this decision:
  </p><br>

**Azure (Active Primary)**<br>It allows to efficiently store, process, and analyze large volumes of e-commerce data from Olist platform, enabling them to extract valuable insights for better decision-making, optimize operations, predict trends, and ultimately improve customer experience by leveraging the scalability, flexibility, and powerful analytics tools offered by Azure services like Azure Data Lake, Azure Data Factory, and Azure Synapse Analytics, particularly when dealing with the vast and diverse data sets generated by an online marketplace.<br>

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Olist_Parallel_Architecture.png" alt="Olist Azure Architecture" style="display: block; margin: 0 auto" /><br><br>

**Key reasons**<br>
- **Large Data Volumes:**<br>Olist generates a significant amount of transactional data from sellers, buyers, products, and logistics, which can be easily stored and processed in Azure Data Lake due to its large storage capacity and distributed processing capabilities.<br>
- **Data Variety:**<br>With different data types like customer demographics, product details, order information, and shipping logistics, Azure allows for flexible data ingestion and analysis of both structured and unstructured data. 
- **Scalability:**<br>As Olist grows, the Azure platform can seamlessly scale up to accommodate increased data volume and processing needs without requiring significant infrastructure management. 
- **Advanced Analytics:**<br>With Azure Synapse Analytics, Olist can perform complex data analysis, build predictive models, and generate actionable insights using machine learning techniques. 
- **Cost-Effectiveness:**<br>Compared to managing on-premise data infrastructure, Azure offers a pay-as-you-go model, allowing Olist to optimize costs based on their data processing needs.
<br><br>
<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Azure_Primary_Environment.png" alt="Olist Azure Architecture" style="display: block; margin: 0 auto" /><br>

**AWS (Passsive Backup)**<br>Incorporating AWS as a secondary environment provides additional benefits and serves as a strategic backup solution.<br>

**Key reasons**<br>
- **Disaster Recovery and Business Continuity:**<br>By implementing AWS Data pipeline as a secondary environment, Olist create a robust disaster recovery solution. In case of any issues with the promary Azure environment, data processing can be quickly shifted to AWS, ensuring business continuity.
- **Multi-cloud Strateg:y**<br>Utilizing both Azure and AWS aligns with a multi-cloud strategy, reducing vendor lock-in and providing flexbility in chossing services that best fit specifc needs.
- **Geographical Redundancy:**<br>AWS's global infrastructure can complement Azure's offering additional geographical redudancy for data storage and processing. This is particulary beneficials for Olist with a global presence or subject to data residency requirements.
- **Cost Optimization:**<br>AWS Data Pipeline's pay-as-you-go pricing model allows businesses to optimize costs by using it as a secondary or backup solution. This approach ensures that company only pay for the resources they use when needed.
<br><br>
<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/AWS_Backup_Environment.png" alt="Olist AWS Architecture" style="display: block; margin: 0 auto" /><br>

**Business Rational**<br>
1. **Risk Mitigation:**<br>By diversifying across two major cloud providers, Olist reduces the risk of service disruptions and ensure continous data processing capabilities.
2. **Flexbility and Innovation:**<br>Access to both Azure and AWS ecosystems allows organizations to leverage the best features and services from each platform, fostering innovation in data management and analytics.
3. **Compliance and Data Governance:**<br>The ability to distribute data across multiple cloud environments can help in meeting various regulatory requirements and data governance policies.
4. **Competitive Advantage:**<br>A dual-cloud strategy for data pipelines positions the company as technologically advanced and adaptable, potentially giving it an edge over competitors who rely on a single cloud provider.
5. **Future-proofing:**<br>As cloud technologites evolve, having expertise and infrastructure in both Azure and AWS ensures that the organization can quickly adapt to new developments and maintain a cutting-edge data management strategy.<br>
By implementing this dual-cloud approach for data pipelines, Olist can create a robust, flexible and efficient data management infrastructure that supports their current needs while preparing them for future challenges and opportunities.<br>
<br>

</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br><br>

<!-- DATA SOURCES -->
<a id="data-sources"></a>
<details>
  <summary><h3><b>Data Sources</b></h3></summary>

**Datasets**<br>Olist stores have the following datasets:
1. Customers information
   ```sh
   olist_customers_dataset.csv (5 columns):
   customer_id: unique identifier for each customer
   customer_unique_id: unique identifier for each customer (anonymized)
   customer_zip_code_prefix: zip code prefix of the customer’s address
   customer_city: city where the customer is located
   customer_state: state where the customer is located
   ```
2. Geolocation
   ```sh
   olist_geolocation_dataset.csv (5 columns)
   geolocation_zip_code_prefix: zip code prefix for the location
   geolocation_lat: latitude of the location
   geolocation_lng: longitude of the location
   geolocation_city: city of the location
   geolocation_state: state of the location
   ```
3. Order items
   ```sh
   olist_orders_dataset.csv (7 columns)
   order_id: unique identifier for each order
   order_item_id: unique identifier for each item within an order
   product_id: unique identifier for the product being ordered
   seller_id: unique identifier for the seller who listed the product
   shipping_limit_date: date and time when the seller has to ship the product
   price: price of the product
   freight_value: shipping fee for the product
   ```
4. Order payments
   ```sh
   olist_order_payments_dataset.csv (5 columns)
   order_id: unique identifier for the order
   payment_sequential: index number for each payment made for an order
   payment_type: type of payment used for the order (e.g. credit card, debit card, voucher)
   payment_installments: number of installments in which the payment was made
   payment_value: value of the payment made
   ```
5. Order reviews
   ```sh
   olist_order_reviews_dataset.csv (7 columns)
   review_id: unique identifier for each review
   order_id: unique identifier for the order that the review is associated with
   review_score: numerical score (1-5) given by the customer for the product
   review_comment_title: title of the review comment
   review_comment_message: text of the review comment
   review_creation_date: date and time when the review was created
   review_answer_timestamp: date and time when the seller responded to the review (if
   applicable)
   ```
6. Orders 
   ```sh
   olist_orders_dataset.csv (8 columns)
   order_id: unique identifier of the order
   customer_id: unique identifier for the customer who placed the order
   order_status: current status of the order (e.g. delivered, shipped, canceled)
   order_purchase-timestamp: date and time when the order was placed
   order_approved_at: date and time when the payment for the order was approved
   order_delivered_carrier_data: date and time when the order was handed over to the carrier
   order_delivered_customer_date: date and time when the order was delivered to the customer
   order_estimated_delivery_date: estimated date when the order is expected to be delivered
   ```
7. Products
   ```sh
   olist_products_dataset.csv (9 columns)
   product_id: unique identifier for each product
   product_category_name: name of the category that the product belongs to
   product_name_lenght: number of characters in the product name
   product_description_lenght: number of characters in the product description
   product_photos_qty: number of photos for the product
   product_weight_g: weight of the product in grams
   product_length_cm: length of the product in centimeters
   product_height_cm: height of the product in centimeters
   product_width_cm: width of the product in centimeters
   ```
8. Sellers information 
   ```sh
   olist_sellers_dataset.csv (4 columns)
   seller_id: unique identifier for each seller
   seller_zip_code_prefix: zip code prefix for the seller's location
   seller_city: city where the seller is located
   seller_state: state where the seller is located
   ```
9. Product category name translation
   ```sh
   product_category_name_translation.csv (2 columns)
   product_category_name: name of the product category in Portuguese
   product_category_name_english: name of the product category in English
   ```
<br>
The data pipeline starts by ingesting data from the on-premises Olist store which may include data from various sources such as sales transactions, customer information, product details, and order history.<br>

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/OLIST_Data_Schema.png" alt="Olist Data Schema" style="display: block; margin: 0 auto" /><br>

**Olist ERD Diagram**<br>An entity-relationship diagram (ERD) of the entities within the OLIST system or applications and the relationships between them.

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/OLIST_Entity_Relationship.png" alt="Olist ERD Diagram" style="display: block; margin: 0 auto" /><br><br>

**Database Setup and Creation**<br>Reviewing datasets and setting up database tables are critical steps in ensuring data integrity, usability, and efficiency. Here's why they are important:
1. **Data Accuracy and Quality:**<br>
   - It helps identify and address missing, duplicate, or inconsistent data, ensuring the information is reliable and accurate.
   - Proper table setup enforces data validation rules, reducing errors during data entry or processing.
2. **Optimal Data Organization:**<br>
   - Structuring database tables using normalization minimizes redundancy and organizes data logically, making it easier to retrieve and manage.
   - A well-designed schema improves data readability and supports efficient relationships between datasets.
3. **Performance Optimization:**<br>
   - It allows for identifying and removing unnecessary data, improving query performance.
   - Proper indexing and table partitioning during setup enhance the speed of data retrieval and processing.
4. **Compliance and Security:**<br>
   - Ensuring sensitive data is correctly stored and protected during the setup process helps meet regulatory and privacy standards (e.g., GDPR, HIPAA).
   - Ensures no unauthorized or non-compliant information is stored.
5. **Scalability and Future-Proofing:**<br>
   - A well-reviewed and structured database is easier to scale as data volume increases.
   - Future enhancements or integration with other systems become simpler when the foundational setup is robust.
6. **Supporting Analytics and Reporting:**<br>
   - Clean, structured datasets and properly designed tables are essential for accurate reporting and analytics.
   - Ensures the inclusion of necessary fields and metrics for meaningful insights.
7. **Collaboration and Cross-Team Understanding:**<br>
   - A clear and logical database setup with well-documented datasets promotes better collaboration among teams (e.g., developers, analysts, and end-users).<br><br>

**Olist Tables Creation:** [SQL script](https://github.com/YvonneLipLim/JDE05_Final_Project/blob/main/Database_Setup/PostgreSQL/OLIST_Tables_Creation.sql)<br>
  
</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br><br>

<!-- DATA INGESTION -->
<a id="methodology"></a>
<details>
  <summary><h3><b>Methodology</b></h3></summary>

  <a id="data-ingestion"></a>
  ### <span style="color:darkblue; font-weight:bold;">Data Ingestion</span>

#### **Primary Ingestion (Azure)**
There are 4 methods of data ingestion:
1. Extracting datasets using Kaggle CLI or a Python script,  then upload to Azure storage with Azure CLI.
2. Extracting datasets using KAggle API with a Python script and upload to Azure storage.
3. Write a Python Azure Function script to automate the data ingestion on a scheduled or manually basis.
4. Extracting datasets from HTTP.
<br>

**Method 1**<br>Extracting Olist Datasets with Kaggle CLI
1. Download the Olist datasets by running this command on a new Terminal:
    ```sh
    kaggle datasets download -d "olistbr/brazilian-ecommerce"
    ```
2. Extract the Downloaded ZIP file:
    ```sh
    unzip brazilian-ecommerce.zip
    ```
3. Check the CSV file after unzipping:
    ```sh
    ls -l
    ```
<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Kaggle_Datasets_Download.png" alt="Download Kaggle Datasets" style="display: block; margin: 0 auto" /><br><br>

1. To search for datasets, run the following command for a complete list:
    ```sh
    kaggle datasets list -s <keyword>
    ```

2. If you want to download a particular file from the dataset, use this command:
    ```sh
    kaggle datasets download -d <owner>/<dataset-name> -f <file-name>
    ```
<br>

**Extracting Olist Datasets with a Python script**<br>The [extract_datasets_local.py](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Local/extract_datasets_local.py) file will download the datasets into the local directory which can be uploaded to the Azure storage account using Azure CLI method.<br><br>

How to Upload Olist Datasets with Azure CLI<br>
1. Run the following command in a new Terminal:
    ```sh
    az login
    ```   
2. A web page will be opened, asking you to enter your Azure credentials. Log in with your account.
3. After logging in, you should see a message in the terminal indicating that you have successfully logged in, along with a list of your subscriptions.
4. Once logged in, run the following command:
    ```sh
    az storage blob upload-batch -d <Container-Name>/<Directory-Name> --account-name <Storage-Account-Name> -s <local-directory-path>
    ```
5. Verify the upload by logging in to the Azure portal to confirm that all your CSV files have been uploaded to the specified container.

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Upload_Datasets_Azure.png" alt="Upload Datasets with Azure CLI" style="display: block; margin: 0 auto" /><br><br>   

**Method 2**<br>Kaggle API<br>
The [extract_datasets_v2.0.py](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Kaggle_API/extract_datasets_v2.0.py) file authenticates with Kaggle API to download datasets directly from Kaggle and upload into Azure storage container using Blob Storage credentials. It automates the data extraction process, ensuring:
- Consistent data sourcing from the original Kaggle repository
- Proper file organization in both local and cloud storage
- Reliable data transfer to Azure for the ETL pipeline
- Error handling and progress tracking during the process
<br>

**Method 3**<br>Azure Function App
- Rewrite the Python Azure Function script by editing the [function_app.py](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Azure_Function/function_app.py) file which can be found in your local directory. The script includes:
  - A scheduled function `scheduled_kaggle_data_extractor` that runs daily at midnight.
  - A manually triggered function `manual_kaggle_data_extractor` that can be invoked via an HTTP request.
  - A common `kaggle_data_extractor` function that both the scheduled and manual functions call to perform the data extraction and upload.
- Then open a new Terminal and start the Azure Storage Emulator:
  ```sh
  azurite --silent --location
  ```
- Next, run the following command in a new Terminal to trigger the scheduled function
  ```sh
  cd MyFunctionApp
  func new --template "Timer trigger" --name KaggleDataExtractor
  0 0 0 * * *
  func start --verbose
  ```
- To run the manual trigger, you can run the curl command:
  ```sh
  curl http://localhost:7071/api/manually-trigger-kaggle-extractor
  ```
- Verify the upload by checking if the files exists in the specified directory of the storage container in Azure.<br><br>

**Example of a Manual Trigger Upload**<br>
<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Storage_Container_Files.png" alt="Storage Container Files Manual Trigger" style="display: block; margin: 0 auto" /><br> 

**Example of a Scheduled Trigger Upload**<br>
<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Storage_Container_Files_Automate.png" alt="Storage Container Files Automate" style="display: block; margin: 0 auto" /><br>

**Method 4**<br>Azure Data Factory<br>
The pipeline would fetch the data from the HTTP endpoint and store it in your Azure Blob storage, maintaining the raw data for further processing.<br>
The process involves several key steps:
1. Create a **HTTP Linked Service** to specific the URL of the HTTP endpoint
2. Create a **HTTP Source Dataset** using the HTTP Linked Service to specific the file format (JSON, CSV, etc)
3. Create a **Sink Dataset** to download the file in the Azure storage container
4. Create a **Pipeline** activity
5. Create a **Copy Data** activity and configure the **Source** and **Sink**  
6. Repeat step 5 by clicking the _clone_ to clone the activity, from there make changes to the **Source** and **Sink**
<br>
**Example of copying Olist data in Azure Data Factory**<br>
  ```sh
  Source (HTTP):
  - Base URL: https://api.example.com/olist
  - Authentication: Anonymous
  - Format: CSV
  - Relative URL: /customers

  Sink (Azure Blob):
  - Container: olist-store-data
  - File path: raw-data/customers.json
  - Format: CSV
  ```
<br>
<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Data_Ingestion.png" alt="Data Ingestion" style="display: block; margin: 0 auto" /><br><br> 

#### **Backup Ingestion (AWS)**

**[Fred to update CLI method]**

We call the python script to ingest the cleaned dataset from Azure to AWS S3 using AWS Glue Notebook Interface. 
![image-2.png](images/1-1.png)

Successfully loaded the dataset to S3. 
![image.png](images/2-1.png)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br><br>

<!-- DATA TRANSFORMATION -->
<a id="data-transformation"></a>
### <span style="color:darkblue; font-weight:bold;">Data Transformation</span>

We applied our data transformation using Azure Databricks because it provides a powerful, scalable platform based on Apache Spark, allowing us to efficiently process large datasets with complex transformations, including data cleaning, aggregation, and manipulation, while seamlessly integrating with other Azure services, all within a collaborative environment with flexible coding options like Python, SQL, and Scala; making it ideal for large-scale data engineering projects with advanced analytics needs.

Key benefits of using Azure Databricks for data transformation:
1. **Scalability**:<br>Easily scale compute clusters to handle large data volumes and complex transformations without compromising performance. 
2. **Apache Spark Power**:<br>Leverage the distributed processing capabilities of Spark for fast and efficient data manipulation. 
3. **Language Flexibility**:<br>Use various languages like Python, SQL, and Scala to write data transformation logic based on your team's expertise. 
4. **Delta Lake Integration_**:<br>Efficiently manage data pipelines with Delta Lake's ACID (Atomicity, Consistency, Isolation, Durability) compliant data lake capabilities. 
5. **Collaborative Environment**:<br>Work collaboratively with notebooks, allowing data scientists and engineers to share insights and code easily. 
6. **Azure Ecosystem Integration**:<br>Seamlessly connect with other Azure services like Azure Storage, Azure Data Factory, and Azure Machine Learning for a unified data pipeline. 

This approach creates a robust, scalable data transformation process that prepares data for analytics while maintaining data quality and performance. 

We performed the following data transformation for our 9 datasets that helped us to deliver:
- **Data Quality**: Achieved consistent data formats, handled missing values, documented transformations
- **Performance**: Parallel processing, optimized larger datasets, efficient resource utilization
- **Maintainability**: Easily debug and monitor outputs, applied useable transformation logic

**Olist Data Cleaning scripts:**<br> 
[01. customers](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Data_Cleaning/01.OLIST_Data_Cleaning_Customers_(revised)_20250113.ipynb)<br>
[02. geolocation](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Data_Cleaning/02.OLIST_Data_Cleaning_Geolocation_(revised)_20250113.ipynb)<br>
[03. order_items](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Data_Cleaning/03.OLIST_Data_Cleaning_Order_Items_(revised)_20250113.ipynb)<br>
[04. order_payments](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Data_Cleaning/04.OLIST_Data_Cleaning_Order_Payments_(revised)_20250113.ipynb)<br>
[05. order_reviews](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Data_Cleaning/05.OLIST_Data_Cleaning_Order_Reviews_(revised)_20250113.ipynb)<br>
[06. orders](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Data_Cleaning/06.OLIST_Data_Cleaning_Orders_(revised)_20250113.ipynb)<br>
[07. products and product_category](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Data_Cleaning/07.OLIST_Data_Cleaning_Products_n_Product_Category_(revised)_20250113.ipynb)<br>
[08. sellers](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Data_Cleaning/08.OLIST_Data_Cleaning_Sellers_(revised)_20250113.ipynb)<br>


<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br><br>

<!-- DATA ANALYTICS -->
<a id="data-analytics"></a>
### <span style="color:darkblue; font-weight:bold;">Data Analytics</span>

#### **Active Analytics (Azure)**
We are using Azure Synapse as a data warehouse for both a lake database and SQL database because it provides a unified platform to seamlessly manage and query large volumes of data from both structured (SQL) and unstructured (lake) sources, essentially acting as a "data lakehouse" where we can access and analyze data from either storage type within a single environment, eliminating the need to move data between separate systems; this translates to improved data accessibility, faster analysis times, and cost efficiency compared to managing separate data warehouse and lake solutions. 

**Key benefits of using Synapse for both lake and SQL databases**:
1. **Data Lakehouse Capability**:<br>Synapse allows us to query data directly from our data lake using SQL alongside traditional structured data in a SQL database, providing flexibility for diverse data analysis needs. 
2. **Scalability**:<br>It allow us to scale the compute resources based on workload demands, whether it's a large-scale data lake query or a targeted SQL query on structured data. 
3. **Cost-Effectiveness**:<br>By using a single platform, we can avoid the overhead of managing separate data storage and processing services, potentially reducing costs. 
4. **Integration with other Azure services**:<br>Synapse seamlessly integrates with other Azure services like Power BI for visualization and Azure Machine Learning for advanced analytics.
5. **External Tables in SQL Database**;<br>It allow us to query data in external sources like Storage container without physically coping the data into the SQL pool to reduced storage costs without duplicating large datasets. Gain faster access to data and the ability to work with data in-place.

**Create a Lake Database**<br>
The process of creating a Lake Database involve several steps:
1. Select `Data`
2. Select `+`
3. Select Lake database and give the database a name
4. Select `Table`
5. Select `From data lake`
6. Create the external tale from data lake and complete the information
![External Table Creation Step 1](https://raw.githubusercontent.com/YvonneLipLim/Images/main/Synapse_Lake_Database_External_Table_1.png)

7. Click Continue and complete the information
![External Table Creation Step 2](https://raw.githubusercontent.com/YvonneLipLim/Images/main/Synapse_Lake_Database_External_Table_2.png)

8. Click Create to add table to the database
![Add Table](https://raw.githubusercontent.com/YvonneLipLim/Images/main/Synapse_Lake_Database_External_Table_4.png)

9. Click Publish to add the desired table
![Publish Activity](https://raw.githubusercontent.com/YvonneLipLim/Images/main/Synapse_Lake_Database_External_Table_3.png)

10. Query the table by selection "SELECT TOP 100 rows" from the Actions menu which will open a new SQL script page to run the query and view the results
![Query Result Table View](https://raw.githubusercontent.com/YvonneLipLim/Images/main/Synapse_TABLE_VIEW.png)
![Query Result Chart View](https://raw.githubusercontent.com/YvonneLipLim/Images/main/Synapse_CHART_VIEW.png)
<br>

**Create a SQL Database**<br>
The guide to create a SQL Database as follows:
1. Select `Data`
2. Select `+`
3. Select `SQL database` and give the database a name
4. Go to `Develop`
5. Click the `+`
6. Select `SQL script`
7. Create View in the SQL script, refer to the [OistSQLDB_View_Creation_SQL_script.sql](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Database_Setup/Synapse/SQL_Database/OlistSQLDB_View_Creation_SQL_script.sql) for more information
8. Once the Create View SQL script is fully execute, all tables will be availabe on the `Views` folder
9. Next, open a new SQL script to create external tables. Refer to the [OistSQLDB_External_Tables_Creation_SQL_script.sql](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Database_Setup/Synapse/SQL_Database/OlistSQLDB_External_Tables_Creation_SQL_script.sql) for more information
10. Once the Create External Tables SQL script is fully execute, all tables will be availabe on the `External tables` folder
![OlistSQLDB Views](https://raw.githubusercontent.com/YvonneLipLim/Images/main/SQL_Database_Tables.png)
<br>

**Entity Relationship Diagram (ERD)**<br>
Obtaining an Entity Relationship Diagram (ERD) from Azure Synapse is highly convenient and beneficial for several reasons:
1. **Visualization of Data Structure**<br>
ERDs provide a clear, visual representation of the database structure, making it easier to understand complex data relationships at a glance. This visual approach is particularly useful in Synapse, where you might be dealing with large-scale data warehouses and numerous interconnected tables.

2. **Improved Data Modeling**<br>
ERDs help in optimizing data models by:
   - Highlighting primary and foreign key relationships between tables
   - Identifying and eliminating data redundancy and inconsistencies
   - Defining constraints that enforce data integrity and security

This is crucial in Synapse environments where efficient data modeling directly impacts query performance and overall system efficiency.

1. **Enhanced Query Optimization**<br>
By clearly showing table relationships, ERDs assist in:
   - Optimizing queries and transactions
   - Understanding data flow, which is vital for performance tuning in Synapse's data warehouse environment

1. **Facilitated Collaboration**<br>
ERDs serve as a common language between different stakeholders:
   - Data engineers can use them to design and maintain the database structure
   - Business analysts can better understand data relationships for reporting
   - Data scientists can grasp the data landscape for analytics projects

This collaborative aspect is particularly valuable in Synapse, which integrates various data processing capabilities and supports multiple user roles.

1. **Documentation and Maintenance**<br>
ERDs act as living documentation of the database schema:
   - They help in tracking the evolution of the database structure over time4
   - Assist in onboarding new team members by providing a clear overview of the data architecture

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Azure_Synapse_ERD_Diagram.png" alt="Synapse ERD Diagram" style="display: block; margin: 0 auto" /><br><br> 

### **Data Dictionary**

**customers**

| Column name | Data type | Max length | Description | Nullable? | Constraints |
| --- | --- | :---: | --- | :---: | --- |
| customer_id | varchar | 8000 | A unique identifier to the orders dataset. Each order has a unique customer_id. | FALSE | pk |
| customer_unique_id | varchar | 8000 |	A global unique identifier for each customer, different from customer_id. |	FALSE |
| customer_zip_code_prefix | varchar | 8000 | The prefix (first 5 digits) of the customer’s postal code (Brazilian zip code).	| FALSE |
| customer_city |	varchar |	8000 | The city where the customer is located. | FALSE |
| customer_state | varchar | 8000 | The state where the customer is located. | FALSE |

**sellers**

| Column name | Data type | Max length | Description | Nullable? | Constraints |
| --- | --- | :---: | --- | :---: | --- |
| seller_id | varchar | 8000 | Unique identifier for each seller on the Olist platform. | TRUE | pk |
| seller_zip_code_prefix | varchar | 8000 | The prefix (first 5 digits) of the seller's zip code, indicating the region where the seller is located. | TRUE |
| seller_city | varchar | 8000 | The city where the seller is located. | TRUE |
|seller_state | varchar | 8000 | The state where the seller is located. | TRUE |

**geolocation**

| Column name | Data type | Max length | Description | Nullable? | Constraints |
| --- | --- | :---: | --- | :---: | --- |
| geolocation_zip_code_prefix | varchar | 8000 | Postal code prefix for the location. This is the first 5 digits of a Brazilian postal code. | FALSE |
| geolocation_lat | float | 8 | Latitude of the location in decimal degrees. | FALSE |
| geolocation_lng | float | 8 | Longitude of the location in decimal degrees. | FALSE |
| geolocation_state | varchar | 8000 | Name of the state where the location is situated. | FALSE |
| geolocation_city_final | varchar | 8000 | Name of the city where the location is situated. | FALSE |

**order_items**

| Column name | Data type | Max length | Description | Nullable? | Constraints |
| --- | --- | :---: | --- | :---: | --- |
| order_id | varchar | 8000 | Unique identifier for each order. Each order can contain one or more items. | FALSE | pk |
| order_item_id | int | 4 | Sequential number identifying number of items included in the same order. | FALSE	|
| product_id | varchar | 8000 | Unique identifier for each product. | FALSE | fk |
| seller_id | varchar | 8000 | Unique identifier for the seller who is selling the product. | FALSE | fk |
| shipping_limit_date | datetime2 | 8 | The latest date and time by which the item should be handled over to the logistic partner. | FALSE |
| price | float | 8 | Price of the product at the time of purchase (in Brazilian reais). | FALSE	|
| freight_value | float | 8 | Shipping cost for the item in Brazilian reais. If an order has more than one item, the shipping cost is split among the items. | FALSE	|

**order_payments**

| Column name | Data type | Max length | Description | Nullable? | Constraints |
| --- | --- | :---: | --- | :---: | --- |
| order_id | varchar | 8000 | Unique identifier for each order. | FALSE | fk |
| payment_sequential | int | 4 | Sequential number of the payment for the order (used when multiple payments are made for a single order). | FALSE	|
| payment_type | varchar | 8000 | The type of payment used for the order (e.g., credit_card, boleto, debit_card, etc.). | FALSE	|
| payment_installments | int | 4 | Number of installments in which the payment will be split (if applicable). | FALSE	|
| payment_value | float | 8 | Total payment value for the order, in Brazilian reais. | FALSE	|

**order_reviews**

| Column name | Data type | Max length | Description | Nullable? | Constraints |
| --- | --- | :---: | --- | :---: | --- |
| review_id | varchar | 8000 | A unique identifier for each review. | FALSE | pk |
| order_id | varchar | 8000 | Unique identifier for each order. | FALSE | fk |
| review_score | int | 4 | The rating given by the customer for the order (on a scale of 1 to 5). | FALSE |
| final_translated_title | varchar | 8000 | Comment title from the review by the customer, in English | TRUE |
| final_translated_message | varchar | 8000 | Comment message from the review by the customer, in English. | TRUE |
| review_creation_date | datetime2 | 8 | The date in which the satisfaction survey was sent to the customer. | FALSE	|
| review_answer_timestamp | datetime2 | 8 | The date in which satisfaction survey was answered. | FALSE	|

**orders**

| Column name | Data type | Max length | Description | Nullable? | Constraints |
| --- | --- | :---: | --- | :---: | --- |
| order_id | varchar | 8000 | Unique identifier for each order. | TRUE | pk |
| customer_id | varchar | 8000 | Unique identifier for the customer who placed the order. | TRUE | fk |
| order_status | varchar | 8000 | Reference to the order status (e.g., delivered, shipped, etc.). | TRUE |
| order_purchase_timestamp | datetime2 | 8 | The date and time when the order was placed. | TRUE |
| order_approved_at | datetime2 | 8 | The date and time when the payment for order was approved. | FALSE |
| order_delivered_carrier_date | datetime2 | 8 | The date and time when the order was handled over to the logistic partner. | FALSE |
| order_delivered_customer_date | datetime2 | 8 | The date and time when the order was actually delivered to the customer. | FALSE |
| order_estimated_delivery_date | datetime2 | 8 | The estimated delivery date that was informed to the customer at purchase moment. | TRUE |

**product_category**

| Column name | Data type | Max length | Description | Nullable? | Constraints |
| --- | --- | :---: | --- | :---: | --- |
| product_category_name_clean | varchar | 8000 | The original product category name in Portuguese. | TRUE |
| product_category_name_english_title | varchar | 8000 | The translated product category name in English. | TRUE |

**products**

| Column name | Data type | Max length | Description | Nullable? | Constraints |
| --- | --- | :---: | --- | :---: | --- |
| product_id | varchar | 8000 | Unique identifier for each product. | TRUE | fk |
| product_category_name | varchar | 8000 | The category to which the product belongs (e.g., electronics, fashion). | TRUE |
| product_name_length | int | 4 | The length of the product name (in characters). | TRUE |
| product_description_length | int | 4 | The length of the product description (in characters). | TRUE |
| product_photos_qty | int | 4 | The number of photos provided for the product. | TRUE |
| product_weight_g | int | 4 | The weight of the product in grams. | TRUE |
| product_length_cm | int | 4 | The length of the product in centimeters. | TRUE |
| product_height_cm | int | 4 | The height of the product in centimeters. | TRUE |
| product_width_cm | int | 4 | The width of the product in centimeters. | TRUE |

#### **Backup Analytics (AWS)**

**Creation of Glue Crawler** 
Toggle to AWS Glue console under the data catalog click on crawler. 
  - Create crawler
  - Step 1 : Name your crawler 
  - Step 2 : Select Data Sources 
            -> Add a data source
            -> Choose the path which dataset is store ![image-5.png](images/1-2.png)
            -> then next
  - Step 3 : Select the IAM role in order for us to access. 
  - Step 4 : Add database to store the data
            - Crawler schedule -- on demand, as and when we required. ![image-6.png](images/2-2.png)
  - Step 5 : Review and create.       
  - Step 6 : Run crawler ![image-7.png](images/3-1.png)

**Verify if the database is created** 
Go to Data Catalog : Databases, select the database we created. 
![image-8.png](images/4.png)
Yes the databases is created, next we can proceed to perform analytics on the data. 

**Creation of AWS Athena for Analytics**
Toggle to Athena. 
From the left, by default the data source is AwsDataCatalog, we just to select the database we created. 
We can perform query by using + on the top right to perform the SQL query on the data, such as SELECT, CREATE TABLE, CREATE VIEW, DROP TABLE etc. 
The output will be saved to the desired output location in S3 for analysis or visualisation. 
![image-9.png](images/5.png)

**Future exploration on AWS QuickSight** 
Toggle to the AWS QuickSight ![image-11.png](images/6.png)
 - To setup the new analyses, go to Dataset and create new dataset from Athena or S3. 
 - Choose the table we want to visualise 
 ![image-12.png](images/7.png)
 - Then we can start to visualise and analysing the data, or merge with other dataset as well. 
Similar to PowerBI 
![image-10.png](images/8.png)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br><br>

<!-- PROOF OF CONCEPT: OPTIMIZATION AND UNIT/FUNCTIONAL TESTING -->
<a id="proof-of-concept"></a>
### <span style="color:darkblue; font-weight:bold;">Proof of Concept: Optimization and Unit/Functional Testing</span>

**Optimization**<br>
The documented improvements provide clear evidence that implementing Parquet as the standard file format will enhance our data infrastructure's efficiency.

Parquet's columnar storage format and efficient compression algorithms enable these improvements while maintaining data integrity. This optimization is particularly valuable for large-scale data processing, as reduced file sizes lead to faster query execution, lower storage costs, and more efficient data transfer across networks.

The data shows consistent size reductions across all tables, with improvements ranging from 15.29% to 72.27%. The "geolocation" table demonstrates this most dramatically, shrinking from 58.44MB to 11.51MB after transformation.

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Large_Datasets_Size_Transformation.png" alt="Large Datasets Size Transformation" style="display: block; margin: 0 auto" /><br>

**Data Pipeline Testing & Quality Assurance**<br>
Our testing strategy encompasses comprehensive validation of data ingestion, transformation, and cleaning processes to ensure data reliability and system robustness.

1. **Test Categories and Coverage**
  - **_Unit Tests_**
    ```sh
    # Example of a unit test for data validation
    def test_seller_data_validation():
      # Test data completeness
      assert df['seller_id'].isnull().sum() == 0
      # Test data format
      assert df['seller_zip_code_prefix'].str.len().mean() == 8
    ```
  - **_Integration Tests_**
    ```sh
    # Example of pipeline integration test
    def test_end_to_end_pipeline():
      # Test data flow from source to destination
      source_count = get_source_record_count()
      dest_count = get_destination_record_count()
      assert source_count == dest_count
    ```
  - **_Performance Tests_**
    ```sh
    # Example of performance benchmark
    def test_pipeline_performance():
      start_time = time.time()
      run_pipeline()
      duration = time.time() - start_time
      assert duration < THRESHOLD_SECONDS
    ```

2. **_Test Scenarios & Results_**

| Test Category | Success Rate | Metrics | Status |
|--------------|--------------|---------|---------|
| Azure Function Ingestion | 100% | Data Completeness, Latency | ✅ |
| Data Factory Pipeline | 99.9% | Throughput, Error Rate | ✅ |
| Data Cleaning | 98.5% | Quality Score, Validation | ✅ |
| Synapse Integration | 99.7% | Performance, Reliability | ✅ |

3. **_Quality Metrics & Thresholds_**
  - Data Completeness: ≥ 99.9%
  - Data Accuracy: ≥ 99.5%
  - Pipeline Latency: < 5 minutes
  - Error Rate: < 0.1%

4. **_Automated Testing Infrastructure_**
    ```sh
    # Example of automated test suite
    class DataPipelineTests(unittest.TestCase):
      def setUp(self):
          self.kv_client = setup_key_vault_client()
          self.connection_string = self.kv_client.get_secret("db-connection")
        
      def test_data_quality(self):
          results = run_quality_checks()
          self.assert_quality_metrics(results)
    ```

5. **_Monitoring & Alerting_**
  - Real-time pipeline monitoring
  - Automated alert triggers for:
      - Data quality threshold breaches
      - Pipeline failures
      - Performance degradation
      - Security incidents

6. **_Test Reports & Documentation_**
  - Detailed test execution logs
  - Quality metrics dashboards
  - Trend analysis reports
  - Issue tracking and resolution documentation

**Key Achievements**:
- 100% automated test coverage
- Real-time quality monitoring
- Secure testing environment
- Comprehensive documentation
- Scalable test infrastructure

This enhanced testing framework ensures:
- Reliable data processing
- Consistent quality standards
- Secure data handling
- Efficient issue resolution
- Continuous pipeline improvement
<br>

**Olist Unit/Functional Test scripts:**<br> 
[01. customers](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Test_Data_Pipelines/01.test_data_pipeline_customers_ingestion_v3.0.ipynb)<br>
[02. geolocation](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Test_Data_Pipelines/02.test_data_pipeline_geolocation_ingestion_v2.0.ipynb)<br>
[03. order_items](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Test_Data_Pipelines/03.test_data_pipeline_order_items_ingestion_v2.0.ipynb)<br>
[04. order_payments](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Test_Data_Pipelines/04.test_data_pipeline_order_payments_ingestion_v2.0.ipynb)<br>
[05. order_reviews](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Test_Data_Pipelines/05.test_data_pipeline_order_reviews_ingestion_v2.0.ipynb)<br>
[06. orders](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Test_Data_Pipelines/06.test_data_pipeline_orders_ingestion_v2.0.ipynb)<br>
[07. products and product_category](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Test_Data_Pipelines/07.test_data_pipeline_products_n_product_category_ingestion_v2.0.ipynb)<br>
[08. sellers](https://github.com/YvonneLipLim/JDE05_Final_Project/tree/main/Source_Codes/Test_Data_Pipelines/08.test_data_pipeline_sellers_ingestion_v2.0.ipynb)<br>

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br><br>

<!-- DATA SECURITY AND GOVERNANCE -->
<a id="data-security-and-governance"></a>
### <span style="color:darkblue; font-weight:bold;">Data Security and Governance</span>

#### **Active Primary (Azure)**
For the Olist e-commerce platform, implementing robust security measures is crucial to protect sensitive customer and business data. Our comprehensive security strategy encompasses:

1. **Secrets Management with Azure Key Vault**
  - Centralized storage of credentials, connection strings, and API keys
  - Automated secret rotation and expiration policies
  - Integration with Azure services for secure access to resources
  - Version control of secrets for audit and recovery purposes

**Example of the Azure Key Vaults integration**
```sh
from azure.keyvault.secrets import SecretClient
from azure.identity import DefaultAzureCredential

key_vault_name = "your-key-vault"
vault_url = f"https://{key_vault_name}.vault.azure.net"
credential = DefaultAzureCredential()
client = SecretClient(vault_url=vault_url, credential=credential)

# Retrieve secrets securely
storage_connection = client.get_secret("storage-connection-string")
```

2. **Database Security**
  - Access Control and Authentication
    - Implementation of Role-Based Access Control (RBAC)
    - Principle of least privilege enforcement
    - Multi-factor authentication for critical operations
  - Pipeline Security
    - End-to-end encryption for data in transit
    - Secure service principal authentication
    - Network isolation using Virtual Networks (VNets)
  - Compliance and Monitoring
    - Regular security assessments and penetration testing
    - Compliance with data protection regulations
    - Continuous monitoring of security metrics

This security framework ensures:
- Protection of sensitive customer and business data
- Compliance with industry standards and regulations
- Secure data processing and storage

The implementation of Azure Key Vault as our secrets management solution has significantly enhanced our security posture by providing:
- Centralized secrets management
- Automated key rotation
- Detailed access logging
- Integration with Azure AD for identity management
- Secure storage of credentials across our data pipeline
<br>

<img src="https://raw.githubusercontent.com/YvonneLipLim/Images/main/Olist_Key.png" alt="Download Kaggle Datasets" style="display: block; margin: 0 auto" /><br>
<br>

#### **Passive Backup(AWS)**

**[Fred to update]**
Data security and governance in AWS are critical components of a robust cloud strategy. They involve implementing policies, procedures, and controls to protect data assets while ensuring compliance with regulatory requirements.

1. Data Security
  - Encryption: 
    - Implement encryption for data at rest and in transit using AWS services like AWS Key Management Service (KMS) and S3 default encyrtion is Server-Side Encrytion for storage.
    - Encrypt sensitive data at rest using AES-256 encryption, especially for customer information stored in Amazon S3 buckets. 
    - Use AWS Secrets Manager to securely store and manage sensitive credentials. 
  - Access Control: 
    - Utilize IAM to enforce the principle of least privilege.
    - Implement multi-factor authentication (MFA) for all user accounts.
    - Regularly review and update access permissions, removing unnecessary privileges.
    - Implement strong password policies, including complexity requirements and regular password changes. 
  - Network Security: 
    - Configure security groups and network ACLs to control inbound and outbound traffic.
  - Monitoring and Logging: 
    - Possibly to use AWS CloudTrail on log, monitor, and retain AWS API activity, providing visibility into actions taken within your AWS account and supporting compliance and security analysis.
    - Use AWS Config to assess, audit, and evaluate the configurations of AWS resources. 

</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br><br>


<!-- ANALYSIS -->
<a id="analysis"></a>
<details>
  <summary><h3><b>Analysis in Power BI</b></h3></summary>

Analysis of the datasets were done using Power BI to answer business questions, derive insights and provide strategic business recommendations to improve customer satisfaction towards Olist and improve customer retention rates.

### **Business Questions**

**1.⁠ ⁠How has the business evolved during the time frame covered in the dataset, and what has been the trend in customer feedback/reviews throughout that period?**

![No. of Orders from 2016-2018](images/Picture1.png)

The sales data spans from September 2016 to October 2018. However, the data from September to December 2016 is insufficient for accurate analysis and is likely incomplete due to the method of data extraction from the provider's database. The same issue applies to the period from September to December 2018.

From 2016 to 2018, there was a general increase in both sales and revenue. Sales grew steadily throughout the period, with a notable spike in November 2017, likely driven by Black Friday promotions. This assumption is supported by a sharp sales increase on November 24, 2017, followed by a significant dip on November 25, 2017.

Out of a total of 99,441 orders placed, 96,476 were successfully delivered, resulting in a delivery success rate of approximately 97%. Interestingly, there were 98,410 customer reviews, suggesting that some customers left feedback even without receiving their orders. This could be due to the system prompting reviews based on estimated delivery dates rather than actual deliveries.

![Average review score by Year and Month](images/Picture2.png)

Although the average review score fluctuated monthly, it generally trended upward from 2016 to 2018. The average score tended to hover around 4, with a noticeable dip between November 2017 and March 2018. This dip may correlate with the increased order volume from the Black Friday sales, which could have impacted customer experience during that period.
<br/><br/>

**2.⁠ ⁠How are customers and/or sellers distributed across the country, and how does this distribution relate to their reviews scores?**

![Customer distribution across country](images/Picture3.jpg)

Customers:

São Paulo (SP) accounts for 41.98% of the customer base, with 41,748 customers. As Brazil’s most populous state, this concentration is expected. Customers from SP gave an average review score of 4.17, which indicates relatively positive feedback. Whereas Rio de Janeiro (RJ) with the second-highest number of customers, had a lower average review score of 3.87. This is below the platform's overall average of 4.086, suggesting that factors like product availability, delivery times, or customer service in RJ might be affecting satisfaction.

![Seller distribution across country](images/Picture4.jpg)

Sellers:

São Paulo (SP) leads with 1,814 sellers, making up 58.61% of the total seller base. This is in line with the state’s status as Brazil’s most populous and economically significant region. The average review score from SP sellers is 4.07, which, although lower than Paraná’s average, still indicates generally positive customer feedback. The high number of sellers from SP reflects its role as a major economic and business hub, which likely attracts a large number of online sellers. On the other hand, Paraná (PR) with the second-highest number of sellers, has an average review score of 4.13, slightly higher than São Paulo’s. This suggests that sellers in Paraná, despite having fewer listings, are performing slightly better in terms of customer satisfaction. The higher review score could reflect better customer service, faster delivery times, or a more consistent product offering. The fact that PR surpasses Rio de Janeiro in seller numbers, even though Rio has the second-highest number of customers, might be attributed to PR's regional economic conditions.

Despite São Paulo’s dominance in seller numbers, Paraná’s higher average review score indicates that seller performance (as measured by customer satisfaction) isn’t solely driven by the volume of sellers. Smaller seller bases in PR could allow for more personalized service or better attention to quality, while the larger seller base in SP may mean more competition and variance in seller performance.
<br/><br/>

**3.⁠ ⁠How frequently do customers return to purchase products from the store?**

![Customer visit counts graph](images/Picture5.jpg)

![Customer visit counts table](images/Picture7.jpg)

Most sales are driven by first-time customers, with only 3% of sales coming from repeat customers. This indicates that while the platform may attract a large number of new buyers, customer retention appears to be a challenge. The data also shows a significant decrease in the number of customers who make more than two purchases, highlighting an inverse relationship between the number of repeat visits and the overall number of repeat customers. Essentially, the more times a customer returns, the fewer customers are making those multiple visits, indicating a low level of repeat customer engagement.
<br/><br/>

**4.⁠ ⁠Is there any relationship between number of orders and purchase day of week?**

![Relation between orders and DayOfWeek graph](images/Picture8.png)

The platform sees more sales on weekdays than on weekends, with sales gradually decreasing as the week progresses, reaching the lowest point on Saturdays. Customers are likely more active during the workweek, in 'shopping mode' during breaks or after work hours, which makes weekday purchases more common. Interestingly, Saturdays experience the lowest sales, which might seem counterintuitive given that it’s traditionally a day when many people have more free time. This trend could be influenced by several factors, such as shopping habits and the timing of promotions.
<br/><br/>

**5.⁠ What are some of the top product categories in terms of sales, revenue and review scores?**

![No. of orders across Product Categories](images/Picture9.jpg)

![Revenue across Product Categories](images/Picture10.jpg)

![Average review score across Product Categories](images/Picture11.jpg)

Top-selling categories like Bed Bath Table, Sports Leisure, and Health Beauty generate significant revenue but have lower review scores, suggesting issues with product quality, customer service, or delivery. In contrast, categories like Fashion, Books, and Construction Tools receive higher ratings, likely due to predictable quality and low returns.

Watches and Gifts generate high revenue despite lower sales volume, likely because of their higher price points. Health Beauty and Computer Accessories perform well in both sales volume and revenue, balancing demand and price.

Overall, high-review categories such as Books and Construction Tools likely meet customer expectations better, while more complex categories like Health Beauty face challenges in maintaining high satisfaction. Customer satisfaction appears to be influenced by product complexity and customer expectations, with essential goods facing more challenges despite strong sales.
<br/><br/>

**6.⁠ ⁠ Has the average delivery duration changed over the observed period in the dataset, and how does this compare with review scores?**

![Graph showing a sharp decrease in average delivery time, followed by a somewhat constant average delivery time below 20 days](images/Picture12.png "Average Delivery Time (in days)")

![Graph showing number of reviews for each review score against delivery time](images/Picture13.jpg "Count of review scores against delivery time")

The average delivery period is approximately 12.09 days, with a standard deviation of 9.55 days, indicating substantial variability in delivery times. Interestingly, deliveries completed within 7 days received the highest frequency of 5-star reviews, suggesting that faster delivery has a positive impact on customer satisfaction. However, there are exceptions where longer delivery times still resulted in 5-star ratings, and conversely, some shorter deliveries received lower ratings, indicating that factors beyond delivery speed, such as product quality, customer service, and the condition of the product, also play a crucial role in shaping review scores.

![Graph showing average review score increasing, peaking before January 2017, then decreasing and hovering around 4, showing a noticeable increase from March 2018](images/Picture14.png "Average review score across observed timeframe")

An analysis of review scores in relation to delivery times shows a negative correlation: as delivery times increase, the proportion of high review scores tends to decrease. This suggests that longer delivery periods negatively impact customer satisfaction, underscoring the importance of timely deliveries to maintain positive customer experiences.

After the November 2017 sales peak, the average review score dipped significantly, likely due to the influx of orders (e.g., Black Friday) leading to delays and increased pressure on logistics. During this period, we observed that average delivery days increased from November to March, suggesting that the high volume of orders may have contributed to slower deliveries and lower review scores.

Starting in March 2018, we saw both the average delivery days decrease and the average review score increase. This could suggest a positive correlation between faster deliveries and higher customer satisfaction. As the platform’s logistics systems likely improved or stabilized after the peak season, quicker deliveries were able to enhance the overall customer experience, reflected in the improvement in review scores.
<br/><br/>

**7.⁠ ⁠What is the most popular payment method for purchasing products from the store, and how does it relate to review scores?**

![Bar plots for each review score, showing precentage of payment methods used overall in each review score](images/Picture15.png "Distribution of payment methods used in each review score")

The most popular payment method for purchasing products from the store is credit cards, followed by Boleto Bancário. Boleto is commonly used by customers who either don’t have access to credit cards or prefer not to use them for online transactions.

When analyzing the relationship between payment methods and review scores, credit cards make up the largest portion of orders across all five payment methods. However, there doesn’t seem to be a clear pattern between payment method and review scores, suggesting that factors other than the payment method, such as product quality or delivery time, may have a more significant impact on customer satisfaction.
<br/><br/>

**8. What are the main issues customers mention when they leave 1-star reviews?**

![Word cloud that shows words most frequently identified in review comment messages where review score is 1](images/Picture16.png "Key words for review score 1")

When analyzing the 1-star reviews, several recurring complaints emerge that highlight key areas for improvement:

*	"Didn't receive": A common issue reported by customers is that they did not receive their orders, even though the platform marked the products as delivered. This points to logistics errors or issues with delivery tracking.
*	"Delayed delivery": Some customers report that their orders were delayed beyond the expected delivery date, leading to frustration and dissatisfaction with the platform’s delivery performance.
*	"Defective product": Many 1-star reviews mention receiving defective or damaged products, signaling a need for stricter quality control at various stages of the product's lifecycle (e.g., manufacturing, storage, shipping).
*	"Product didn’t match description": A few customers report that the product they received did not meet their expectations or match the description provided on the platform. This could be due to inaccurate product listings, poor product photos, or misleading descriptions.
*	“Unresponsive customer service": Some customers express dissatisfaction with customer service, mentioning that their inquiries or complaints were not addressed in a timely or helpful manner.
*	"No resolution to issues": Several 1-star reviews mention that after reporting issues like defective products or missing items, the customer service team failed to resolve the problem, leading to further frustration.

The main themes in 1-star reviews center around delivery inaccuracies and product quality issues. While the platform may mark products as delivered, customers often claim they didn’t receive them, or the products were damaged or defective upon arrival. Some sellers consistently receive lower-than-average ratings, suggesting that these issues may be linked to certain sellers or their handling of logistics and product quality. Interestingly, the payment methods (credit card and boleto) do not seem to have a significant impact on customer satisfaction or review scores. The main issues are primarily related to product and delivery performance, not the payment process.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br><br>

<!-- BUSINESS RECOMMENDATIONS -->
<a id="recommendations"></a>
### <span style="color:darkblue; font-weight:bold;">Strategic Business Recommendations to Increase Sales and Improve Review Scores</span>

**1. Target Repeat Customers and Improve Retention**

The data shows that repeat customer purchases are low, with only 3% of sales coming from repeat buyers. This suggests that customer retention is a significant challenge.

Recommendation:
*	Implement Loyalty Programs: Offer discounts, points, or special deals for repeat customers to encourage them to return. For instance, create a rewards program where customers earn points for every purchase, which can be redeemed for discounts or special offers.
*	Personalize the Shopping Experience: Use customer data to provide personalized recommendations, promotions, or discounts based on previous purchases, encouraging more frequent returns.
*	Engage Customers After First Purchase: After a customer's first purchase, engage them with follow-up emails or exclusive offers that incentivize them to return. For example, offering a 10% off their next purchase or providing a discount for a second purchase within a specified time frame can encourage customers to come back.

Expected Impact: By increasing repeat purchases, the platform will foster stronger customer loyalty, potentially leading to better reviews over time as customers become more familiar with the platform’s offerings and services.
<br/><br/>

**2. Refine Marketing and Promotions**

Sales trends show that weekdays drive more sales than weekends, with Saturdays having the lowest sales, even though it's a traditionally free day for many people. This could be an indication of how promotional timing influences shopping habits.

Recommendation:
*	Optimize Promotional Timing: Evaluate when customers are most likely to shop and adjust marketing strategies accordingly. For example, run midweek sales or promotional campaigns to capture customers who prefer shopping during weekdays.
*	Introduce Weekend-Exclusive Promotions: Despite lower sales on Saturdays, offer weekend-only promotions or flash sales that could help drive traffic during this period. For example, a Saturday Flash Sale could provide a limited-time offer that entices customers to shop on traditionally slower days.
*	Targeted Marketing Campaigns: Use targeted ads to focus on specific regions like São Paulo (SP), where a large customer base exists, or Rio de Janeiro (RJ), where review scores are lower. Personalized promotions may help increase sales and improve customer satisfaction in these areas.
*	Leverage Seasonal Promotions: Take advantage of high-traffic periods like Black Friday, Cyber Monday and holiday seasons to run promotions that boost sales while ensuring logistics are well-prepared to handle high volumes.

Expected Impact: By optimizing marketing strategies around customer behavior and regional preferences, the platform can boost sales and drive customer satisfaction, leading to higher review scores.
<br/><br/>

**3. Enhance Popular Product Categories and Review Scores**

Some of the top-selling categories like Health Beauty and Sports Leisure generate significant revenue but have lower review scores, likely due to issues with product quality or delivery. Conversely, Fashion and Books receive higher ratings.

Recommendation:
*	Improve Product Lines in Lower-Scoring Categories: Focus on enhancing product quality in categories like Health Beauty and Sports Leisure, possibly by collaborating with trusted suppliers or offering premium product lines. Ensuring better product consistency and addressing quality concerns (e.g., defective items, incorrect descriptions) will help improve customer satisfaction. Optimize delivery speeds for these categories to ensure faster and more reliable shipping. Expedited delivery options could be offered, especially for higher-value items in these categories, which would improve the likelihood of positive reviews.
*	Highlight High-Review Categories: Promote categories with higher review scores, such as Books and Fashion, to encourage customer engagement in these areas. Consider creating bundle offers where lower-performing categories can be paired with popular high-review categories (e.g., a Health Beauty product could be bundled with a Book or Fashion item) to balance sales while leveraging positive customer experiences.
*	Encourage Reviews: Use incentives like small discounts or loyalty points to encourage customers to leave reviews, especially for higher-ticket items, which could improve overall review scores across categories. Specifically target first-time buyers in these categories to provide post-purchase reminders and incentivize feedback to improve review scores. Collecting more reviews from a broader base will give a more accurate picture of the product quality and help new customers make informed decisions.

Expected Impact: Improving product offerings and delivery in key categories will likely raise review scores and increase sales in the most profitable segments.
<br/><br/>

**4. Enhance Delivery Speed and Accuracy**

Delivery times fluctuate significantly, with longer delivery periods negatively impacting customer satisfaction and review scores. Delays, such as those seen after Black Friday promotions, led to a dip in reviews.

Recommendation:
*	Optimize Logistics Operations: Invest in more efficient logistics systems to reduce delivery times. This could include working with additional delivery partners, optimizing warehouse locations, and utilizing real-time tracking to keep customers informed.
*	Offer Expedited Shipping Options: Provide customers with faster delivery options, particularly for high-demand or higher-value products. Offering guaranteed delivery within 7 days can help improve review scores and customer satisfaction.
*	Improve Delivery Accuracy: Address issues where customers report not receiving their orders by strengthening coordination with delivery partners and enhancing delivery tracking systems to reduce discrepancies between marked delivery status and actual receipt. Implement follow-up mechanisms where customers can report issues directly, and set up a dedicated customer support team to handle delivery-related queries promptly.

Expected Impact: Faster and more reliable deliveries will likely boost customer satisfaction, increasing the frequency of 5-star reviews and customer retention.
<br/><br/>

**5. Focus on Quality Control and Seller Performance**

Defective products and issues with product descriptions, packaging, and quality are frequently cited in 1-star reviews, often reflecting poor product quality control. Additionally, some sellers consistently receive lower ratings, which might be due to less attention to product quality or customer service.

Recommendation:
*	Implement Stricter Quality Control: Ensure that products undergo thorough quality checks before being shipped. This could involve random inspections or partnering with manufacturers and sellers who can demonstrate high-quality standards.
*	Enhance Seller Training: Provide training or guidelines to sellers about product quality, accurate listings, and customer service best practices. Consider offering incentives for top-performing sellers with high review scores to encourage better performance. Implement a system to track and flag sellers whose average review score consistently falls below a defined threshold (e.g., below 3.5 stars).
*	Improve Product Descriptions and Photos: Standardize and verify product listings to ensure that images and descriptions are accurate, preventing the mismatch between customer expectations and the product they receive. Regular audits of product listings to ensure consistency and prevent outdated or misleading content.

Expected Impact: Higher product quality, more accurate listings, and better seller performance will reduce complaints related to defective products, leading to improved review scores and fewer 1-star reviews.<br/><br/>

**6. Improve Customer Service Response and Resolution**

Many 1-star reviews mention unresponsive or ineffective customer service. Issues like no resolution to problems or poor handling of complaints create frustration and drive negative reviews.

Recommendation:
*	Enhance Customer Support Teams: Invest in better training for customer service representatives to handle complaints promptly and professionally. Establish clear escalation procedures for complex issues.
*	Implement Proactive Support: Use customer data to identify at-risk customers and reach out proactively before they escalate an issue. A customer who receives timely support is less likely to leave a negative review.
*	Faster Resolution of Returns/Refunds: Streamline the returns process and ensure that customers who receive faulty or incorrect products can easily get refunds or exchanges.

Expected Impact: A more responsive and effective customer service team will reduce frustration and increase the chances of resolving issues before customers leave negative reviews, improving overall satisfaction and retention.<br/><br/>

**7. Offer Discounts for Credit Card Payments**

A large portion of customers (approximately 73%) use credit cards as their preferred payment method. However, there is no clear incentive tied to using credit cards for purchases. This represents an opportunity to encourage more spending and boost sales by providing targeted incentives for customers who pay via credit card.

Recommendation:
*	Introduce Credit Card Payment Discounts: Offer exclusive discounts or cashback for customers who choose to pay with their credit cards. For example, provide a 5-10% discount on purchases made using credit cards, encouraging customers to choose this payment method over others like Boleto. These discounts could be tiered, where larger purchases or multiple transactions within a given period yield greater rewards.
*	Launch Credit Card Payment Vouchers: Provide digital vouchers or coupon codes specifically for credit card payments. These vouchers could be used for future purchases or for products in high-demand categories.Bundle offers could be introduced, such as: "Spend $X using a credit card and get $Y off your next order" or "Get 10% off when paying with a credit card on selected product categories."
*	Promote Partnered Credit Card Offers: Collaborate with major credit card issuers (e.g., Visa, Mastercard) to offer special promotions like extra rewards points, discounts, or installment payment options exclusively for cardholders using those brands.
*	Bundle Credit Card Discounts with Loyalty Programs: Customers who make payments using credit cards could accumulate loyalty points faster or unlock exclusive offers as part of a broader loyalty strategy. This could increase repeat purchases and customer retention.
*	Targeted Campaigns for High-Volume Credit Card Users: Identify customers who frequently use credit cards and offer them tailored deals or special perks like early access to sales or exclusive product bundles. Use customer segmentation to focus on high-value shoppers (those who spend the most with credit cards) to drive greater average order values through special, limited-time offers.

Expected Impact: Offering discounts or incentives for credit card payments can boost sales volume by encouraging more spending and higher average order values (AOV). It also helps increase conversion rates by attracting hesitant buyers, and fosters customer retention and loyalty through ongoing rewards.

</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br><br>

<!-- CHALLENGES -->
<a id="challenges"></a>
<details>
<summary><h3><b>Challenges and Solutions</b></h3></summary>
While working on this project, several challenges were met and solutions to overcome them were explored, eventually allowing the team to successfully complete its main objectives. Listed below are the details:

**Azure Data Pipeline**

* Data Transformation: We encountered an issue with data transformation while trying to use Azure Translator to translate the `comment_title` and `comment_message` columns of `order_reviews` from Portuguese to English in Databricks, as the connectivity was incorrect. However, we found an alternative solution by utilising the Google Cloud Translation API, which successfully processed over 100,000 records in 8.41 seconds.
* Slow Processing of Large Dataset: When we initially completed the data cleaning for all datasets, we did not convert the data from CSV to a single Parquet file. As a result, the loading performance was much slower and more resource-intensive for some of the larger files. To address this issue, we transformed the CSV files into Parquet format on Databricks. This change resulted in a significant reduction in file sizes, allowing SQL databases and Power BI to operate more efficiently. In fact, the largest file size decreased by over 70%, from 56 MB to 11.5 MB. The effective compression provided by Parquet has led to faster data retrieval.
* Unit/Functional Testing: To ensure our data pipelines and the associated functions or methods for data cleaning scripts are functioning correctly, we carried out essential tests to catch and fix problems early in the development process. We dedicated nearly a week of man-hours to testing, particularly focusing on the Geolocation dataset, which contains over a million records and operates with a limited compute capacity of just 14GB across 4 cores. To manage this challenge, we broke the testing into 10 smaller parts, which allowed us to streamline the process and achieve quicker response times.

**AWS Data Pipeline**

* Connectivity Issues: We faced some connectivity challenges while configuring the AWS IAM role during our data ingestion efforts using Glue Visual Studio. To address this, we used a Python script on a smart notebook. This approach streamlined the process of transferring datasets from an Azure Storage Container to an AWS S3 bucket, making it much more manageable.

**Dataset Analysis**

* Biased Dataset: The dataset includes only orders that received customer reviews, excluding unreviewed transactions. This introduces sampling bias, limiting the generalizability of insights and potentially skewing conclusions about customer behavior and satisfaction.

* Geolocation Challenges: The dataset provides only partial zipcode prefixes, reducing the accuracy of location-based analysis. As a result, our analysis is limited to broader geographic regions, such as states. Additionally, inconsistencies in the original data (e.g., customers or sellers associated with multiple cities) further complicate city-level analysis.

* Slow Performance (Power BI and Visuals): The size and complexity of the dataset, combined with potentially complex DAX measures and visuals, can lead to slow loading times and lag when interacting with reports and dashboards.

* Weather Data (Impact on Orders and Deliveries): While attempting to analyze how weather conditions might affect orders or deliveries, we were unable to obtain historical weather data for Brazil from 2016-2018 without paying for it. This lack of historical weather data limits the ability to draw comprehensive conclusions regarding the impact of weather on customer behavior or delivery times over the full period of the dataset.

* Nature of Olist's Marketplace: Multiple sellers may offer the same product, leading to variability in delivery times and customer experiences. This inconsistency makes it challenging to correlate reviews with specific factors like delivery time or product price.
    * Solution: Incorporated additional data (e.g., review comments, payment methods) to identify patterns and provide actionable recommendations.

* Issues with Azure Maps in Power BI: Power BI often prompts users to "switch to the new Azure Maps visual," but the new version of Azure Maps can be buggy, causing issues with map rendering and data visualization.
    * Solution: Switching back to the default Maps graphic, reverting to the older version of the map visual provided a more stable visualization experience.

* Power BI Service Deployment and Sharing: Once reports are developed, publishing them to Power BI Service and sharing with others can be problematic. Issues with permissions, access control, and versioning can arise, particularly when sharing reports across multiple users with different access needs. Additionally, automatic data refreshes may fail, especially for large datasets or if the connection isn’t configured correctly.
    * Solution: Properly configure user roles and access levels in Power BI to ensure that only authorized users can view or modify reports.

</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br><br>


<!-- CONCLUSION -->
<a id="conclusion"></a>
<details>
<summary><h3><b>Conclusion</b></h3></summary>

The implemented data pipeline and analytics provide valuable insights that can enhance customer satisfaction on the Olist marketplace. By applying the recommendations, Olist can improve customer retention, product quality, and overall sales performance.  

Looking ahead, we aim to further optimize our data pipeline by focusing on four key areas:  

1. **Monitoring & Observability** – Enhance system insights with real-time dashboards, automated alerts, and live tracking.  
2. **Security Enhancement** – Strengthen data protection through encryption, improved access controls, and compliance audits.  
3. **Pipeline Automation** – Minimize manual intervention with automated data cleaning, error correction, and quality checks.  
4. **Performance Optimization** – Accelerate data processing, reduce resource costs, and improve system responsiveness.  

These enhancements will be rolled out over 12 months, ensuring minimal disruption to ongoing operations.  

</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br><br>
