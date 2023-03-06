
# Building-a-Scalable-Data-Warehouse-with-Data-Vault-2.0-CN

Trying to translate the book of "Building a Scalable Data Warehouse with Data Vault 2.0" to Chinese language to better understand this data modelling concept.

说明：此资源库中所有内容均基于Daniel Linstedt及Michael Olschimke联合所著的商业图书：《Building a Scalable Data Warehouse with Data Vault 2.0》，所有翻译内容均由个人贡献，非商业使用。

产品信息如下：

Title: Building a Scalable Data Warehouse with Data Vault 2.0

Author(s): Daniel Linstedt, Michael Olschimke

Release date: September 2015

Publisher(s): Morgan Kaufmann

ISBN: 9780128026489

如果您对原著感兴趣可以通过亚马逊等图书网站购买原著，购买地址：https://www.amazon.com/Building-Scalable-Data-Warehouse-Vault/dp/0128025107

**************************************************************
Translater: Derek.Zhu

Last update datetime: 2023-Mar-6th
**************************************************************

Table of contents

Cover

Title page

Table of Contents

Copyright

Authors Biography

Foreword

Preface

Acknowledgments



Chapter 1: Introduction to Data Warehousing

Abstract

1.1. History of Data Warehousing

1.2. The Enterprise Data Warehouse Environment

1.3. Introduction to Data Vault 2.0

1.4. Data Warehouse Architecture


Chapter 2: Scalable Data Warehouse Architecture

Abstract

2.1. Dimensions of Scalable Data Warehouse Architectures

2.2. Data Vault 2.0 Architecture


Chapter 3: The Data Vault 2.0 Methodology

Abstract

3.1. Project Planning

3.2. Project Execution

3.3. Review and Improvement


Chapter 4: Data Vault 2.0 Modeling

Abstract

4.1. Introduction to Data Vault Modeling

4.2. Data Vault Modeling Vocabulary

4.3. Hub Definition

4.4. Link Definition

4.5. Satellite Definition


Chapter 5: Intermediate Data Vault Modeling

Abstract

5.1. Hub Applications

5.2. Link Applications

5.3. Satellite Applications


Chapter 6: Advanced Data Vault Modeling

Abstract

6.1. Point-in-Time Tables

6.2. Bridge Tables

6.3. Reference Tables


Chapter 7: Dimensional Modeling

Abstract

7.1. Introduction

7.2. Star Schemas

7.3. Multiple Stars

7.4. Dimension Design


Chapter 8: Physical Data Warehouse Design

Abstract

8.1. Database Workloads

8.2. Separate Environments for Development, Testing, and Production

8.3. Microsoft Azure Cloud Computing Platform

8.4. Physical Data Warehouse Architecture on Premise

8.5. Database Options

8.6. Setting up the Data Warehouse


Chapter 9: Master Data Management

Abstract

9.1. Definitions

9.2. Master Data Management Goals

9.3. Drivers for Managing Master Data

9.4. Operational vs. Analytical Master Data Management

9.5. Master Data Management as an Enabler for Managed Self-Service BI

9.6. Master Data Management as an Enabler for Total Quality Management

9.7. Creating a Model

9.8. Importing a Model

9.9. Integrating MDS with the Data Vault and Operational Systems


Chapter 10: Metadata Management

Abstract

10.1. What is Metadata?

10.2. Implementing the Meta Mart

10.3. Implementing the Metrics Vault

10.4. Implementing the Metrics Mart

10.5. Implementing the Error Mart


Chapter 11: Data Extraction

Abstract

11.1. Purpose of Staging Area

11.2. Hashing in the Data Warehouse

11.3. Purpose of the Load Date

11.4. Purpose of the Record Source

11.5. Types of Data Sources

11.6. Sourcing Flat Files

11.7. Sourcing Historical Data

11.8. Sourcing the Sample Airline Data

11.9. Sourcing Denormalized Data Sources

11.10. Sourcing Master Data from MDS


Chapter 12: Loading the Data Vault

Abstract

12.1. Loading Raw Data Vault Entities

12.2. Loading Reference Tables

12.3. Truncating the Staging Area


Chapter 13: Implementing Data Quality

Abstract

13.1. Business Expectations Regarding Data Quality

13.2. The Costs of Low Data Quality

13.3. The Value of Bad Data

13.4. Data Quality in the Architecture

13.5. Correcting Errors in the Data Warehouse

13.6. Transform, Enhance and Calculate Derived Data

13.7. Standardization of Data

13.8. Correct and Complete Data

13.9. Match and Consolidate Data

13.10. Creating Dimensions from Same-As Links


Chapter 14: Loading the Dimensional Information Mart

Abstract

14.1. Using the Business Vault as an Intermediate to the Information Mart

14.2. Materializing the Information Mart

14.3. Leveraging PIT and Bridge Tables for Virtualization

14.4. Implementing Temporal Dimensions

14.5. Implementing Data Quality Using PIT Tables

14.6. Dealing with Reference Data

14.7. About Hash Keys in the Information Mart


Chapter 15: Multidimensional Database

Abstract

15.1. Accessing the Information Mart

15.2. Creating Dimensions

15.3. Creating Cubes

15.4. Accessing the Cube


Subject Index