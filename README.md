# Order Shipping Analysis & Product Category Review

## Project Overview
This project builds a data workflow that automates the classification of shipping methods, integrates product category data, and flags high-risk orders for review. The goal is to support operational accuracy and improve decision-making through automated data processing.

---

## Tools Used
- **Alteryx Designer** – Building and automating the data workflow  
- **Excel** – Input and output data files, reference tables, and documentation  
- **Image Export** – Workflow visualization for documentation and presentation  

---

## Workflow Summary

### 1. Shipping Method Assignment
- Mapped each order to the appropriate shipping method based on its **Order Priority**.

### 2. Product Data Integration
- Combined **Product Categories** with **Product Details** using SKU alignment.
- Created a unified product reference table for enrichment.

### 3. Order Flagging Logic
- Merged enriched product data with order data.
- Flagged orders containing **Technology** items shipped via **Freight** with a **“REVIEW”** tag.
- All other orders were left as null.

---

## Outcome
- Delivered a clean, enriched dataset ready for analysis.
- Enabled targeted review of high-risk orders.
- Demonstrated proficiency in:
  - Data blending  
  - Conditional logic  
  - Workflow automation  

---

## Repository Contents

### Data
- **Initial State.xlsx** – Raw input data  
- **Final State.xlsx** – Output after workflow execution  
- **Product Categories.xlsx** – Category labels for each product SKU  
- **Product Details.xlsx** – SKU-based product information used for enrichment  
- **Shipping Method.xlsx** – Reference table mapping order priorities to shipping methods  

### Workflow
This repository includes a complete visual representation of the Alteryx workflow. The workflow section contains screenshots of all tools used and the full end-to-end workflow, illustrating data inputs, transformations, joins, and logic applied throughout the process.

### Documentation
- **Project Objective** – Written summary of project goals and business logic  

---

## Disclaimer
This project was developed using **Alteryx Designer**, a proprietary tool. Alteryx software is not included or distributed as part of this repository.
