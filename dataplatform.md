
# **What to consider when building/altering an [Enterprise Data Platform?](#data-platform)**

**TLDR:** Consider developer and customer requirements. Analyze how it can fit into [Enterprise Architecture strategy](#review-existing-ea). Calculate DevOps costs to move and support data from source to analysis. Make sure architecture stays less **frankenstein** over a period of time.

## **Objective**:
Build an enterprise data platform that can help:
- Developers: To build quick, fast, secured, robust and scalable pipelines to increase overall efficiency and effectiveness
- Analysts/Scientists: To perform exploratory and prediction analysis and build insights to make data driven decisions.
- Customers: To find accurate information about their products and/or services.
- Other Groups: To serve other important things like governance, usage stats, catalog, cost, value etc...

</br>

## **Things needed to consider when building/altering data platform:**

### **Review existing EA:**

Enterprise Architecture (EA) can be classified into different domains, each focusing on a specific aspect of the organization's structure and operations. 

Data platform is a collection of tools and technologies that are used to ingest, transform, store, and analyze large volumes of data. It includes both hardware infrastructure and software components. 'Enterprise' in this context refers to non-engineering data and has 1 TB to 999 TB size

Data platform is one of the critical components of EA. It should be designed to be flexible and scalable to adapt changing business needs and data sources listed in EA. We can't simply pick XYZ product because its popular in the market.

EA is classified into sub types. The following sections lists the data platform relevant concerns that needs to be addressed before building or altering data platform.

#### **Business Architecture(BA)**

- Understand company org structure
    * Role hierarchy, locations, responsibilities and relationships.
    * Organize data assets per business architecture
    * Figure out development and support structure globally
    * Make BA flexible and revise till it gets matured
- Link data assets to business processes
    * Define data lineage at 1000 foot view
    * Define ownership using dept email aliases
    * Address data overlap and ownership issues. For example sales and operations planning overlap with supply chain operations

- [orwiki](https://orwiki.org/OR) has standards to example organize business. This site is evolving and it organizes the information like a work flow
- Try using similar methodology to organize and index data assets. When a business requirement comes, one can figure out how new it can affect existing workflow

#### **Data Architecture**

- Decide how current and future data should be handled
    * Centralized
    * Decentralized
    * Hybrid

- Evaluate current and future data processing needs
    * Distributed
    * Monolithic or Traditional
    * Hybrid
    * Batch processing
    * Realtime processing
    * Streaming

- Evaluate current and future data storage requirements
    * Distributed
    * Relational
    * NoSQL
    * File storage
    * Hybrid

- Evaluate data accessing methods for
    * Internal customers
    * External customers
    * Power users, Analysts and Data Scientists
    * North bound systems

- Evaluate data portal or data catalog
    * To organize data assets
    * To ramp up new developers
    * To ramp up new users
    * To search and understand existing data assets

#### **Technology Architecture**

- Figure out the platform hosting environment
    * On-premise
    * Traditional Cloud
    * Cloud Native
    * Hybrid

- Define platform support service model
    * Integrate into existing ticketing management system
    * Auto ticket creation upon failure and resolution
    * Knowledge base with searchable answers
    * L1/L2/L3 support setup

- Cloud
- On-premise
- Hybrid
- Vendor selection and support


#### **Application Architecture**
- Design
- Development
- DevOps

#### **Security Architecture**
- Figure out a strategy for
    * Data Governance
    * Data Catalog
    * Security (default, row, and column level)
    * Encryption
    * Usage Statistics
- Internal auditing : security reports, security viloations, change management, etc
- External auditing : security reports, security viloations, change management, etc
- Business continuity auditing
- Row-level security

<br />





