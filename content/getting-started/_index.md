+++
title = "Getting started"
description = ""
weight = 1
+++

{{< lead >}}
Learn about AgroFIMS, sign up for an account, and navigate the menu. 
{{< /lead >}}
## About AgroFIMS
The Agronomy Field Information Management System (AgroFIMS) allows users to create fieldbooks to collect agronomic data that is already tied to a metadata standard (the CG Core Metadata Schema, aligned with the standard Dublin Core), and semantic standards like <a href="https://bigdata.cgiar.org/resources/agronomy-ontology/" target="_blank"> the Agronomy Ontology (AgrO)</a>, generating data that is Findable, Accessible, Interoperable, and Reusable (FAIR) at collection.
AgroFIMS therefore standardizes data collection and description for easy aggregation and inter-linking across disparate datasets. By December 2020 you will be able to export the fieldbooks you create to the Android-based <a href="http://www.kddart.org/kdsmart.html" target="_blank"> KDSmart</a> or <a href="https://play.google.com/store/apps/details?id=com.fieldbook.tracker&hl=en&gl=US" target="_blank"> Field Book</a> applications for data collection. Collected data can be imported back to AgroFIMS for statistical analysis and reports.
We have also made available the Agronomy API or AgrAPI, which is a RESTful web service API specification to enable access, exchange, and integration of agronomic data across systems and applications. You can use the API to retrieve research management information, experimental designs, crop measurements, and environmental variables from AgroFIMS. The AgrAPI blueprint can be implemented in different programming languages. Currently, AgrAPI is implemented in the R statistical programming language allowing you to analyze your data with the R statistical packages and graphics of your choice.
In 2021 AgroFIMS will allow you to set up agronomic survey questionnaires, for data collection via ODK. It will also allow easy upload of your “born FAIR” data to Dataverse repository platforms with Dublin Core-compliant metadata schemas.
Funding for AgroFIMS was provided by the Bill and Melinda Gates Foundation’s Open Access, Open Data Initiative, and <a href="https://bigdata.cgiar.org/" target="_blank"> the CGIAR Platform for Big Data in Agriculture</a>.
AgroFIMS is under GPL license.


## AgroFIMS workflow
AgroFIMS works in collaboration with the Android applications like KDSmart, ODK Collect and Field Book apps to provide a complete workflow to manage data for the creation of a fieldbook to the data analysis. Below are the different steps to follow to create, collect, analyze and save data using AgroFIMS:
![workflow](https://agrofims.github.io/helpdocs/images/workflow.png)

## Home screen
 ![home_screen](https://agrofims.github.io/helpdocs/images/homescreen.png)

{{< childpages >}}