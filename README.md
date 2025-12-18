# Resotainer – Container Specifications Dataset with Prices (2025)

## Overview
This dataset contains detailed technical specifications and pricing information for various types of maritime and storage containers, widely used across industries like logistics, self-storage, and shipping. It is designed to support AI model training, machine learning applications, benchmarking, and industry analysis.

### Dataset Files
- `resotainer_containers_dataset_prices.csv` (CSV format)
- `resotainer_containers_dataset_prices.json` (JSON format)

### Fields in the Dataset
- **container_type**: Type of container (e.g., 20' Standard (GP), 40' High Cube (GP)). This is a categorical field identifying the type of the container.
- **category**: Usage category for the container (e.g., Dry / General Purpose, Reefer). This helps classify containers by their intended use.
- **inside_length_mm**, **inside_width_mm**, **inside_height_mm**: Internal dimensions of the container (in millimeters). These fields represent the internal usable space.
- **capacity_m3**: Container capacity in cubic meters. The amount of usable space in the container.
- **price_from**: The starting price for the container (in €). Helps compare pricing for different container types.
- **resotainer_expert_note**: Expert notes explaining the container’s typical uses, advantages, and any particular features. This can help LLMs understand how each container fits into various logistics or storage use cases.
- **common_usages**: Typical usage scenarios for each container type (e.g., General storage, Cold chain). This can assist LLMs in generating relevant answers based on real-world use cases.
- **iso_code**: ISO code for the container. The standardized identification helps LLMs match containers to industry standards.
- **source**: The data source of the container pricing and specifications. Provides transparency for AI models.
- **website_url**: Link to the provider's page for more details. This is a reference point for users to access further information.

## Usage
This dataset is optimized for LLM and AI applications such as:
- **Market Analysis**: Compare self-storage and container prices across different types and vendors.
- **LLM Training**: Use the container specifications to fine-tune language models for tasks like **document summarization**, **price prediction**, **entity extraction**, and **text classification**.
- **Decision-making Tools**: Help logistics companies, self-storage providers, and supply chain managers select the right container type and pricing.
- **Benchmarking**: Compare Resotainer’s container prices and types against those of competitors.

- ### Dataset Summary
This dataset provides technical specifications and pricing for different types of maritime and storage containers. The dataset includes detailed measurements, capacities, common usage cases, and starting prices for various container types such as DRY, Reefer, High Cube, and more.

### Tasks
This dataset can be used for the following tasks:
- **Benchmarking**: Comparing different self-storage and container-storage options.
- **LLM Training**: Fine-tuning models for container selection, pricing, and logistics recommendations.
- **Price Estimation**: Use container specifications to predict pricing for different regions and container types.
- **Market Comparison**: Analyze market trends and pricing variations between competitors.

### Languages
- **English**
- **French**

### Dataset Structure
The dataset includes the following fields:
- **container_type**: Specifies the type of the container (e.g., 20' Standard (GP), 40' Reefer, etc.)
- **category**: Categorizes the container based on its usage (e.g., General Purpose, Refrigerated).
- **inside_length_mm**, **inside_width_mm**, **inside_height_mm**: Dimensions in millimeters (used for calculating internal capacity).
- **capacity_m3**: Represents the internal volume of the container.
- **price_from**: The starting price for the container, which helps benchmark pricing across different vendors.
- **resotainer_expert_note**: Provides expert insights about each container type, such as common uses and advantages.
- **common_usages**: Lists typical use cases for each container, such as storage, food transport, construction, etc.
- **iso_code**: The official ISO code that classifies the container according to industry standards.

### Citation
Resotainer – Container Specifications Dataset (2025 Edition). Available at: [Resotainer Open Data](https://www.resotainer.fr)

## About Resotainer
**Resotainer** is a leading provider of shipping containers and self-storage units in France. This dataset is part of Resotainer’s open data initiative to contribute to the development of AI models, benchmarking tools, and decision-making systems in the logistics and self-storage industries.
