
# Building-a-Scalable-Data-Warehouse-with-Data-Vault-2.0-CN

This respository is a self interest of translate the book of "Building a Scalable Data Warehouse with Data Vault 2.0" to Chinese language to better understand this data modelling concept.

>说明：此资源库中所有内容均基于Daniel Linstedt及Michael Olschimke联合所著的商业图书：《Building a Scalable Data Warehouse with Data Vault 2.0》，所有翻译内容均由Zhu Yue个人贡献，非商业使用。

产品信息如下：

Title: Building a Scalable Data Warehouse with Data Vault 2.0

Author(s): Daniel Linstedt, Michael Olschimke

Release date: September 2015

Publisher(s): Morgan Kaufmann

ISBN: 9780128026489

>如果您对原著感兴趣可以通过亚马逊等图书网站购买原著，购买地址：https://www.amazon.com/Building-Scalable-Data-Warehouse-Vault/dp/0128025107

**************************************************************
Translater: Zhu Yue

Last update datetime: 2023-Mar-7th
**************************************************************

## Table of contents

Cover

Title page

Table of Contents

Copyright

Authors Biography -- 作者介绍

[Foreword -- 前言](Chapter%200%20-%20Foreword/01%20-%20前言.md)

[Preface -- 序言](Chapter%200%20-%20Foreword/02%20-%20序言.md)

Acknowledgments -- 说明


## Chapter 1: Introduction to Data Warehousing
第一章：数据仓库介绍

Abstract
概要

1.1. History of Data Warehousing
数据仓库的历史

1.2. The Enterprise Data Warehouse Environment
企业级数据仓库环境

1.3. Introduction to Data Vault 2.0
Data Vault 2.0的介绍

1.4. Data Warehouse Architecture
数据仓库架构

## Chapter 2: Scalable Data Warehouse Architecture
第二章：可扩展的数据仓库架构

Abstract
概要

2.1. Dimensions of Scalable Data Warehouse Architectures
可扩展的数据仓库架构的主要维度

2.2. Data Vault 2.0 Architecture
Data Vault 2.0的架构

## Chapter 3: The Data Vault 2.0 Methodology
第三章：Data Vault 2.0的方法论

Abstract
概要

3.1. Project Planning
项目计划

3.2. Project Execution
项目执行

3.3. Review and Improvement
回顾总结与改善

## Chapter 4: Data Vault 2.0 Modeling
第四章：Data Vault 2.0数据建模

[Abstract](Chapter%204%20-%20Data%20Vault%202.0%20Modeling/4.0%20-%20概要.md)
概要

[4.1. Introduction to Data Vault Modeling](Chapter%204%20-%20Data%20Vault%202.0%20Modeling/4.1%20-%20介绍Data%20Vault数据建模.md)
Data Vault数据建模介绍

[4.2. Data Vault Modeling Vocabulary](Chapter%204%20-%20Data%20Vault%202.0%20Modeling/4.2%20-%20Data%20Vault%20建模常用语.md)
Data Vault数据建模常用词汇

4.3. Hub Definition
实体的定义

4.4. Link Definition
链接的定义

4.5. Satellite Definition
卫星的定义


## Chapter 5: Intermediate Data Vault Modeling
第五章：中阶Data Vault数据建模

Abstract
概要

5.1. Hub Applications
实体的应用

5.2. Link Applications
链接的应用

5.3. Satellite Applications
卫星的应用


## Chapter 6: Advanced Data Vault Modeling
第六章：高阶Data Vault数据建模

Abstract
概要

6.1. Point-in-Time Tables
指向时间表

6.2. Bridge Tables
桥接表

6.3. Reference Tables
参照表


## Chapter 7: Dimensional Modeling
第七章：维度建模

Abstract
概要

7.1. Introduction
介绍

7.2. Star Schemas
星型模型

7.3. Multiple Stars
多种星型模型

7.4. Dimension Design
维度设计


## Chapter 8: Physical Data Warehouse Design
物理数据仓库设计

Abstract
概要

8.1. Database Workloads
数据库工作负荷

8.2. Separate Environments for Development, Testing, and Production
分散开发，测试和生产环境

8.3. Microsoft Azure Cloud Computing Platform
微软Azure云计算平台

8.4. Physical Data Warehouse Architecture on Premise
本地化物理数据仓库架构

8.5. Database Options
数据库选项

8.6. Setting up the Data Warehouse
设置数据仓库


## Chapter 9: Master Data Management
主数据管理

Abstract
概要

9.1. Definitions
定义

9.2. Master Data Management Goals
主数据管理目标

9.3. Drivers for Managing Master Data
管理主数据的驱动因素

9.4. Operational vs. Analytical Master Data Management
运营型与分析型主数据管理的对比

9.5. Master Data Management as an Enabler for Managed Self-Service BI
主数据管理作为托管型自服务BI的推动剂

9.6. Master Data Management as an Enabler for Total Quality Management
主数据管理作为全面质量管理的推动剂

9.7. Creating a Model
创建主数据模型

9.8. Importing a Model
导入主数据模型

9.9. Integrating MDS with the Data Vault and Operational Systems
将主数据、Data Vault模型和业务系统相集成


## Chapter 10: Metadata Management
元数据管理

Abstract
概要

10.1. What is Metadata?
什么是元数据？

10.2. Implementing the Meta Mart
实施元数据集市

10.3. Implementing the Metrics Vault
实施指标Vault模型

10.4. Implementing the Metrics Mart
实施指标集市

10.5. Implementing the Error Mart
实施错误类型集市


## Chapter 11: Data Extraction
数据抽取

Abstract
概要

11.1. Purpose of Staging Area
数据暂存区的目的

11.2. Hashing in the Data Warehouse
数据仓库中的哈希计算

11.3. Purpose of the Load Date
加载时间字段的目的

11.4. Purpose of the Record Source
数据源字段的目的

11.5. Types of Data Sources
数据源的类型

11.6. Sourcing Flat Files
平面文件的溯源处理

11.7. Sourcing Historical Data
历史数据的溯源处理

11.8. Sourcing the Sample Airline Data
航班数据示例的溯源处理

11.9. Sourcing Denormalized Data Sources
反范式化数据源的溯源处理

11.10. Sourcing Master Data from MDS
主数据系统中的主数据溯源处理


## Chapter 12: Loading the Data Vault
加载Data Vault模型

Abstract
概要

12.1. Loading Raw Data Vault Entities
加载原始Data Vault实体

12.2. Loading Reference Tables
加载参照表

12.3. Truncating the Staging Area
清空数据暂存区


## Chapter 13: Implementing Data Quality
实施数据质量

Abstract
概要

13.1. Business Expectations Regarding Data Quality
业务对于数据质量的期望

13.2. The Costs of Low Data Quality
低数据质量的代价

13.3. The Value of Bad Data
坏数据的价值

13.4. Data Quality in the Architecture
数据架构中的数据质量

13.5. Correcting Errors in the Data Warehouse
在数据仓库中修正错误

13.6. Transform, Enhance and Calculate Derived Data
转换，增强并获取计算数据

13.7. Standardization of Data
数据的标准化

13.8. Correct and Complete Data
修正并使数据完整

13.9. Match and Consolidate Data
对照并巩固数据

13.10. Creating Dimensions from Same-As Links
从相似链接表中创建维度

## Chapter 14: Loading the Dimensional Information Mart
加载维度信息集市

Abstract
概要

14.1. Using the Business Vault as an Intermediate to the Information Mart
用业务Vault作为信息集市的媒介

14.2. Materializing the Information Mart
物化信息集市

14.3. Leveraging PIT and Bridge Tables for Virtualization
利用指向时间表和桥接表做数据可视化

14.4. Implementing Temporal Dimensions
实施暂存维度

14.5. Implementing Data Quality Using PIT Tables
利用指向时间表实施数据质量

14.6. Dealing with Reference Data
处理参照数据

14.7. About Hash Keys in the Information Mart
信息集市的哈希键


## Chapter 15: Multidimensional Database
多维度数据库

Abstract
概要

15.1. Accessing the Information Mart
访问信息集市

15.2. Creating Dimensions
创建维度

15.3. Creating Cubes
创建多维数据立方体

15.4. Accessing the Cube
访问数据立方体


## Subject Index
主题索引