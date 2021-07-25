# DataLake-On-Premises
Implementing a Data Lake On-Premises


## About the project

We will implement a Project of a Data Lake On-premises. Understanding your concept and difference from a Data Warehouse.

##Why?

why Data Lake is a concept not a platform !!!

-This project is part of my personal portfolio, so I'll be happy if you could provide me with any feedback on the project, code, structure or anything you can report that could make me a better data engineer!

Email-me: henricao_7@yahoo.com.br

Connect with me at LinkedIn

## Roadmap For a Successful Data Lake

Companies today are exploding from data, including database dataexisting, application outputs, ecommerce streaming data, social media, apps and devices connected to the Internet of Things (IoT). We are all well versed in the Data Warehouse, designed to capture the core of the business of other business systems, such as ERP systems and CRM, inventory and sales transactions that allow analysts and users of gain insights and make important business decisions from the of this data. But new technologies, including mobile, social and IoT platforms, areboosting much higher volumes of data, higher expectations of users and a rapid globalization of economies. Organizations are realizing that traditional technologies do not meet new business needs. As a result, many organizations are turning to architectures such as Data Lakes, using Apache Hadoop and other technology of Big Data. However, despite the growing investment in Data Lakes and Big Data technology - $150.8 billion in 2017, a 12.4% increase on compared to 2016 - only 14% of organizations report implementing their project proof of concept (PoC) of Big Data, in production. One reason for this discrepancy is that many organizations do not see a return on your initial investment in big data technology and infrastructure. This is usually because these organizations fail to do the right thing, falling short when it comes to designing the data correctly. In (many) in other cases, there is no data-driven culture. Ultimately, these organizations create "swamps" of data (Data Swamps) that are really useful only in cases of exploratory ad-hoc use (something still unusual in many companies, although it is used in research and development). For organizations that move beyond a PoC, many are uniting the flexibility of a Data Lake with good practices of the governance and data control. That's the key to getting a significant ROI technology investments for Big Data.

If you (Data Engineer) ask your Analysts and Scientists of Given what data they want to use in the future they will probably say "Everything available." But we really need all the data we canor just of what is relevant to solve certain business problem? In general, we use Data Lake to store: • Raw transactional data • Semi-structured and unstructured data • Streaming data • Historical data that has not been migrated to production systems • Data that may be useful for analysis in the future

![12](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/12.png)

Data Lakes become data marshes if they are not managedcorrectly. Make sure that your Data Lake has the following Features:

• Architecture to meet the company's business goals 

• Management to protect data 

• Integration to be fed with data from different sources

• Accessibility for "self-service" and to offer Data Scientists the opportunity to apply Real-Time Analytics

#The Scripts for installation and configuration of our Data Lake Follows in Annex!!!

![1](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/1.png)

## Data Warehouse

Data > Structured and Processed Data Before Load on Database 

Processing > data schema generated at the time of writing. 

High > storage for large volumes of data. 

Agility > Little agile, fixed configuration. 

Security > mature security strategies. 

Users > Business Analyst, BI and Data Scientist.

## Data Lake

Structured > Structured, Semi-Structured and Unstructured Data. Raw data. 

Processing > data schema generated at the time of reading. 

Storage > designed to be low cost, regardless of data volume. 

Agility > Very agile. Can be configured and reconfigured as needed. 

Security > You still need to improve your data security and access model. 

Users > Scientist and Data Analyst.

![2](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/2.png)

## What is Corporate Data ?

Corporate Data means any and all data held by any of the companies, including, but not limited to, data related to your finances, taxes, employees, customers, suppliers, and products or services.

## Building the right infrastructure is key
Therefore, it should be:

• Agile

• Hold on

• Compatible

• Manageable

What is the Cost of Implementing a Data Lake On-Premise?

![3](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/3.png)

What is the cost of deploying a Data Lake in the Cloud?

![4](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/4.png) 

![5](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/5.png)

That's an overview but has other costs other issues like if you want to stop using Data Lake and just click a button is ready. No problem with burning HD or depreciation of equipment and etc... and even has a VPN to ensure greater security.

![6](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/6.png)
Data Lake is the focal point of a data management strategy. Basically is a central repository is where you will bring the data from the most variable sources store process, analyze and take action with this data they can be discarded can be stored in a second step of what you wanted to keep history, but basically and create the central point of data storage. Allowing what in English is SCV (Single Customer View) that is, a single point of view of the data for the end user and that end user can be with the most varied applications a BI application a machine learning application eventually a tool for creating visualization of reports and dashboards and etc... 6


The volume of data has been increasing significantly over the decades it is clear that previous strategies of storage and data management are no longer enough no longer use Data Marts, Data Warehouse this is not enough because the data changed its characteristics it comes in another format another speed in another volume and we need new strategies is the entry of Data Lake. Data Lake is becoming the focal point of a data management strategy!!!
![7](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/7.png)

One of the world's largest technology companies agrees that vision. Look at this diagram from Microsoft. Look, Azure Data Lake is at the heart of the Microsoft Cloud environment data strategy. You bring the data to Data Lake and there you distribute to other applications or other repositories and then turn that data into information that will be useful for decision making
![8](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/8.png)

##Data Lake Concept


The Term Data Lake can be defined with a vast repository of a variety of raw data across the enterprise, which can be purchased, processed, analyzed, and delivered. Data Lake Is Not a DL Database is a data store!!! A Data Lake acquires data from multiple sources in a company in its native form and therefore has internal shapes modeled on the same data for multiple purposes. Data can be of any type, from structured or semi-structured data to completely unstructured data. A Data Lake is expected to result in business-relevant meanings and insights from the information extracted from the data, using various machine analysis and learning algorithms. Data Lake is not just for storage the DL is built to process and analyze this data either by using a BI tool for example or by using a tool for predictive models. A Data Lake implicitly results in a Business-to-business model, which is good for solving very specific business problems. A Data Lake can represent an entity to the fullest based on information collected from various systems that have this data. With Data Lake we were able to extract information from a single sample entity: When you create a Data Warehouse you collect data from some sources you then organize that data and then you feed into DW I have all the information about each entity there in DW? Can you imagine the client entity i have all the data I need about the client there in my DW? I have registration in my RP system I have the clicks that the user makes on my site I have the emails that my user sends to my company I have the invoices of payment that that customer made I have the invoices and procedure of delivery of the products to that client all this is information of the client entity all this is in the Data Warehouse? Probably not in the vast majority of cases is not because it has a physical limitation for you to mount the DW. When you work with Data Lake I can rather extract everything I have from each entity and store it in my Data Lake, Client Entity, Product, Supplier and any other entity that is interesting for my analysis I extract everything I have every interaction of this user with my company so I store it in the DL and then perform data analysis and create predictive models. Being able to predict what the customer can buy in the next month or what type of product the customer would like to receive!!! A real Game Change!!! This is a lot of work, but the end result may be greater competitive differential profitability among other advantages for the company. Data Lake is not the ideal solution for any company! IMPORTANT TO TAKE THIS INTO CONSIDERATION!! If the company does not have a Data Driven culture, i.e. a data-driven culture and is not even planning to have in the near future then the company will not be able to extract from Data Lake the best it has to offer. Data Lake is the center of a data management strategy so if the company is not concerned with managing its own data the Data Lake will be just another repository. It will only be useful like any technology if the company is prepared to use a technology, so always take that into consideration!!!

![9](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/9.png)

## Benefits For the Company

Unique storage model that describes the representation of data significantly. Centralization of the collection and storage of all data generated by the company. Single point of control Allows a data-driven culture.

## Technical Advantages.

Better data governance. Allows you to work with predictive analytics through Machine Learning and AI. Allows the construction of recommendation systems and other analytical applications. Tracking and consistency of information. Analysis of Historical data.

## Technical Disadvantages

If not well managed, Data Lake results in a Data Swamp

Requires strict security control since ALL data generated by the company will be in a single repository Large amount of storage Need for computer clusters for storage and distributed data processing.

## Architecture of The Data Lake

Always remembering that Data Lake is not a product or a Data Lake tool is a concept just as Data Warehouse is a concept you can implement a DW with Oracle database with SQL Server, Postgre with MySql you can implement a DW in several different ways as well as a Data Lake can be implemented in several different ways with different products and different technologies. 10

You have two approaches to looking at DL architecture: Split by layers. Look at the services that make up a DL.

##< Metadata Management, Traceability, Hierarchy and Lineage, >

Data acquisition: Data can exist in multiple forms and require different extraction techniques. Data processing: The acquired data may require processing to generate useful information. We can store the raw data and create a replica with processed data. Data analysis: Data is analyzed under demana, real-time, or batch. Data storage: Data is stored before and/or after analysis. This is not a mandatory order is just to stop didactically showing what is done in a Data Lake architecture.

A Data Lake first has to acquire data from somewhere. Once the data has been acquired we have to process it "Remembering that you can store the data and only then process. Yes, you can. Who makes and implements the architecture is you" I'm putting here the ideal depending on the business problems to be solved. I'm going to process this data somehow it can come from streaming (real time) or it can come in batch format, i.e. batchdata depending on how the acquisition step went. Next we have data analysis where we will extract insights from that data that was last stored I have Storage and does not need to be last you can acquire the data process it and store and then analyze you can put the storage at any step. -Many companies choose not to directly store the data because the volume is too large depending on the data is coming in real time if I lose the data in real time depending on the type of analysis I'm trying to do the data no longer serves anything. -Imagine that you are doing a real-time twitter sentiment analysis during a debate for Presidency of the Republic you want to know how are the moods during the debate does not interest me after and not before I want during the Debate why at each interval of the debate the candidates talk to their aides they can according to the return of the public change their behavior during the Debate. So in this case it makes no sense to say that storage will be before depends on the architecture being implemented if the company wants to work with real-time data analysis it acquired processes, that is, transforms that data from some structure applies Machine Learning and then delivers the result

## Data Acquisition

The first point is for the company to define what data will be stored in Data Lake. It's no use saying that you want all the data that's not how managers work a lot and companies they're going to try to say that. What data would you like to have for analysis to solve your business problems? You already know that everything starts in the definition of the problem to be solved

## Data Processing and Management

The definition of what processing and how it will be done is not a technical decision and purely a definition of the business area. Are you building a recommendation system? Are you building a Machine Learning application? Each of these applications will require a different type of processing what many companies normally do is stores the data in its raw state and already applies some ETL during the acquisition faze so you will acquire the data already stores in raw state and in the next step processes and already delivers to an analysis tool because then you speed up the data processing time and consequently deliver your analytical application. In this step and where we basically use the ETL T remembering that ETL will work the same as in the Data Warehouse. Same thing allowing us to extract data from different sources and different formats transform the data as needed and already put in your Data Lake prepares them for analysis. Many people consider that the advantage of Data Lake is that you have given them in raw format. Yes, no doubt it's a big plus, but raw data they're not very useful for analysis I have to process this data somehow if the company is already able to do this during optimal ETL if it doesn't somehow already store in Data Lake and then some tool or a data scientist will look at that data and give some structure to them , process and then prepare for the analysis process in general. THERE IS NO UNSTRUCTURED DATA ANALYSIS you will always give a structure to the data before we analyze. Even when you collect unstructured data before applying to an analytical tool I first give a structure in Data Lake I can writes in the raw state but I have to process at some point or during the acquisition phase or immediately after or later when doing the analysis!!!

## Data analysis

This is the most important part of the entire process you have created a Data Lake exactly to analyze the data and help the company in decision making

## Data Storage

Data Lake has a much larger goal than storing data it can just be part of a pipeline where I acquire, process, analyze, store the result and continue in this cycle so that the company continues to receive the insights from different sources.

An existing question is can I collect all the data from a company? Is this really important for analysis? That's the question to ask. Do I need the logs from the servers to generate a recommendation system for the products of the company's website? If the answer is yes, then I need the data! If the answer is no I don't need to collect that data. Do I need data from social networks to eventually create a sales recommendation system? If the answer is yes I collect otherwise not and go ahead!!! -If you don't have a well-defined strategy to analyze this data you'll store because the data volume is too large and you're going to store it, storing there comes a time when the company is going to have to discard the data to free up some disk space or the data is so old that it doesn't have much use of the application I'm doing
Metadata and Security Management
Where are we going to identify the data that will eventually be stored in Data Lake or analyzed or processed what is this metadata? Date of creation of that data point, date on which that data was stored or entered in your Data Lake, date it was processed, date it was analyzed, the data source that is very important in DW we also include this type of metadata you can put a Column for example there in DW or you can put this in information to the part , i.e. where did this data come from? What was the exact source from which we extracted that content and then did the processing. This information that describes the data is what we call metadata if not, I'm just throwing things inside data lake and completely loses the purpose you need to have an efficient management of how the data is identified that's metadata management!!!

-Traceability: Once you have created some metadata management process now I can track this data within my Data Lake. See the Data Lake may have terabytes, tetabytes in size I need to be able to track the data point as it moves into the Data Lake when it was entered as raw data, when it was processed, when it was parsed, when eventually it was discarded I can write this information and keep it as some kind of metadata history among several other options. There is now virtually a science around metadata management (Metadata Management) that is exactly you control all this is to ensure information about your data. -We also have Hierarchy and lineage that we help define the life cycle of the data within our Data Lake as well as in the Data Warehouse the reasoning is not much different. -Finally, the issue of Security -Although the blue line is not part of the Data Lake architecture it supports the DL architecture.

## Data Quality and Lifecycle


If garbage comes in, there's going to be garbage. Quality is something to be considered throughout the process. How can I establish a criterion a quality standard this is also not easy! Normally during the acquisition and processing phase we can implement some practices with the aim of trying to increase the quality of the data or at least check the quality of the data that is entering the Data Lake we can for example create some kind of filter, establish some rule in the ETL, we can already apply some procedure of cleaning and transformation in the sample data : Imagine that you are collecting data from social networks and this data contains a lot of emoticons(Emoji) that is relevant to your analysis process? Most of the time not so I can already discard these characters before i even enter the data in Data Lake. 11

-Logical Data lake > only point to access the data in every company -Agile> Quickly interactively deliver something -Data Architecture> basically and you model the business concepts -Logical data warehouse > governance of the data for the specific purpose for this I can use a DW -Enterprise Access Point> With a single data control and governance point -Data Virtualization > I need to somehow ensure the systems stable and independent Data Lake is a piece of a larger architecture and the life cycle of the data will depend on the company's objectives the company will create an application with a durability of one year? A year and a half? two? Remember the Lifecycle not and only data lake and all its data architecture!!!

![13](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/13.png)

## The Success Roadmap for a Data Lake should include:

Extensive analytical capabilities 

• Varied sources of data 

• Access from different analytical tools 

• Intensive computing for the execution of Machine algorithms Learning Interoperability 

• Integration with different heterogeneous systems 

• Event and message processing Business Continuity 

• High availability and fault tolerance 

• Disaster Recovery (Backup and Restore) 

• Data Recovery (recovery against data failures and corruption Reduced Cost 

•Use of commodity hardware (low cost) 

• Low overhead administration 

• High performance 

• Resource sharing (virtualization) Multi-tenancy Capabilities 

• Ability to manage various (computational) resources from a single point Being able to gather all these features in a Data Lake is very difficult, but this should be the Roadmap and the goal of any organization interested in getting the most out of Big Data Analytics. And you, as an Engineer is one of those responsible for this.

References: IDC. "Worldwide Semiannual Big Data & Analytics Spending Guide." Gartner. "Market Guide for Hadoop Distributions." Architecting Data Lakes (Free e-book) https://www.oreilly.com/data/free/architecting-data-lakes.csp

How to Build a Successful Data Lake

https://mapr.com/resources/videos/how-build-successful-datalake/assets/how_to_build_a_successful_data_lake_webinar_-_160517.pdf

Here is information from the Cluster/master and the slaves.

![14](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/14.png)

And in this one I follow the execution information of what is happening in the cluster with Yarn. Because you set up a Cluster to run processing jobs you store and then process then here you can monitor

![15](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/15.png)

See that the file is already in our Data Lake!!! We already have a file stored! You just finished building your Data Lake. 16

Running the Job and Checking The Execution
