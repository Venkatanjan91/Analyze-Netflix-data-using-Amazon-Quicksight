#  🎬 Netflix Data Analysis Dashboard using Amazon QuickSight.

This project demonstrates the utilization of **Amazon QuickSight**, a **cloud-based Business Intelligence (BI) tool**, for the visualization and analysis of a Netflix dataset. 🚀 The primary objective is to derive actionable insights and identify trends through the creation of an informative dashboard. 💡

##   Project Overview

This project showcases the process of establishing a connection with a data source (Amazon S3), developing effective visualizations, and implementing data filtering techniques within the Amazon QuickSight environment. 🔍 The analysis is centered on gaining a deeper understanding of Netflix content trends and patterns. 📈

##   Project Objectives:

* **Data Visualization**: Design and implement a range of data visualizations 🖼️📊 to effectively represent the Netflix dataset.
* **Data Connection**: Establish a robust connection between the Netflix dataset residing in Amazon S3 🔗🗂️ and the Amazon QuickSight platform.
* **Interactive Analysis**: Leverage QuickSight's filtering capabilities 🎚️🔍 to facilitate dynamic exploration and analysis of specific data subsets.
* **Trend Identification**: Identify and analyze trends 📈📅 within Netflix content releases and other relevant data metrics.
* **Dashboard Development**: Develop an interactive and informative dashboard 🗂️✨ to present key findings and insights in a clear and concise manner.

##   Project Workflow:

1.  **Data Storage on Amazon S3:** 🗄️☁️

    * Amazon S3 is employed for the storage of the core dataset (`netflix_titles.csv`) and a metadata file (`manifest.json`). 📂
    * Proper configuration of the `manifest.json` file, which contains essential connection information (S3 URI), is crucial 📝🔑 to ensure successful data access by QuickSight.

      ![Screenshot 2025-03-23 115253](https://github.com/user-attachments/assets/4dd484ce-74dc-4d7f-aff0-50b8d2dcc6cb)


2.  **Amazon QuickSight Setup:** 🛠️🖥️

    * An Amazon QuickSight account is required for the development of visualizations and the dashboard. ☁️
    * Amazon QuickSight offers a free trial period 🆓🎉 for initial exploration and development.

      ![Screenshot 2025-03-23 121114](https://github.com/user-attachments/assets/f0a1cd18-cd95-41db-90d5-20f30e91b3f1)


3.  **Dataset Integration:** 📥🔗

    * The Netflix dataset is integrated into QuickSight by referencing its storage location within the Amazon S3 bucket. 📥
    * The `manifest.json` file plays a key role 🔑📂 in this process by providing QuickSight with the necessary access details. 📍

      ![Screenshot 2025-03-23 124025](https://github.com/user-attachments/assets/4511b2c4-dd29-4ed2-a3f1-15c412df4153)


4.  **Visualization Development:** 📊📈🎨

    * QuickSight's visualization tools are utilized 📊 to generate a variety of charts and graphs that represent the Netflix data.
    * This involves selecting appropriate chart types 🗺️📍 and mapping data fields to the corresponding visual elements.

5.  **Interactive Filtering Implementation:** ⚙️🔍🎚️

    * Filtering mechanisms are implemented within QuickSight to enable dynamic exploration and focused analysis of specific data subsets. 🔬
    * Example: Filtering Netflix content based on release year 📅 or genre categories. 🎭

6.  **Dashboard Design and Presentation:** 🗂️🎨✨

    * An interactive dashboard is designed and developed 🖼️📊 to present the key findings and visualizations in a clear, concise, and professional manner.
    * QuickSight provides the capability to export dashboards in PDF format 📄📤 for convenient sharing and distribution.

      ![Netflix Data Analysis Dashboard on Amazon Quicksight](https://github.com/user-attachments/assets/2ae6715c-e7a2-4bd8-8798-78d72e01b999)


##   Project Deliverables:

* `netflix_titles.csv`: The core dataset containing Netflix title information. 📀🎬
* `manifest.json`: A metadata file specifying the location and access parameters for the dataset within Amazon S3. ℹ️🔑
* Interactive Data Dashboard: A QuickSight dashboard presenting key insights and visualizations. 🗂️📊✨

##    Tools and Technologies:

* **Amazon S3:** Cloud-based object storage service 🗄️☁️ for housing the dataset.
* **Amazon QuickSight:** Cloud-based business intelligence service 🛠️📊 for data visualization, analysis, and dashboard creation.

##   System Requirements and Installation:


1.  **Amazon S3 Bucket Configuration:** ⬆️🗄️

    * Upload the `netflix_titles.csv` and `manifest.json` files to your designated Amazon S3 bucket. 📂
    * Ensure accurate configuration ✏️ of the `manifest.json` file, including the correct S3 URI, to enable proper data access.

2.  **Amazon QuickSight Account Setup:** ➕☁️

    * Create an Amazon QuickSight account. A free trial option 🆓🎉 is available for initial development and evaluation.

3.  **Data Source Connection:** 🔌🔗

    * Establish a connection between your Amazon S3 bucket and your QuickSight account using the uploaded `manifest.json` file. 📂📍

4.  **Visualization and Dashboard Development:** 📊🎨✨

    * Utilize Amazon QuickSight's features 🎨 to develop the required data visualizations and design your interactive dashboard. 🖼️🗂️

##   Estimated Project Duration

* The estimated time for project completion is approximately 1 hour. ⏱️⏳
