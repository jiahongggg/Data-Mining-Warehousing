# E-commerce Data Warehouse with Featuretools

This repository demonstrates the use of [Featuretools](https://docs.featuretools.com/) to create an optimized data model for an e-commerce dataset. The data model is designed for data warehousing and includes entities, relationships, and deep feature synthesis. The goal is to facilitate efficient data analysis and reporting for business intelligence.

## Installation

You can install Featuretools using pip:

```bash
pip install featuretools
```

## Implementation
The following steps outline the implementation of the data model:

1. Sample Data: Sample data for customers, products, orders, and order details is provided in Python dictionaries.
2. Data Conversion: The data is converted into pandas DataFrames.
3. EntitySet Creation: An EntitySet, named 'ecommerce_data,' is created to store entities and relationships.
4. Entity Addition: Entities for customers, products, orders, and order details are added to the EntitySet.
5. Relationship Definition: Relationships between entities are defined to establish connections. These include customer-order, order-order details, and product-order details relationships.
6. Deep Feature Synthesis: Deep feature synthesis is performed on the 'orders' entity to create new features using aggregation and transformation primitives. The result is a feature matrix with enriched features.
7. Displaying New Features: The generated features are displayed as a DataFrame.

## Usage
You can use this code as a reference to design and implement a data model for your own e-commerce dataset using Featuretools. Modify the sample data and relationships to suit your specific dataset.

To run the code, simply execute the Python script provided.
