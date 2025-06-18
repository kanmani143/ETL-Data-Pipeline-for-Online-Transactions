# ETL-Data-Pipeline-for-Online-Transactions

**Project Summary**

- This project focuses on building a lightweight yet efficient ETL (Extract, Transform, Load) pipeline to automate the extraction of online transactional data from an Amazon Redshift data warehouse, apply necessary transformations, and load the cleaned data into Amazon S3 in CSV format.
- The pipeline ensures clean, deduplicated data is readily available in cloud storage for downstream analytics or reporting.

**Techniques Used**

- ETL Pipeline Design using modular Python scripts
- SQL-based Transformation for data cleaning and deduplication
- Cloud Integration using Amazon Redshift and Amazon S3
- Environment Configuration using .env files and Docker
- Containerization with Docker for reproducibility and easy deployment
- Python Libraries: boto3, psycopg2, pandas, dotenv
  
**Results and Impact**

- Reduced data redundancy by programmatically identifying and removing duplicate records.
- Delivered clean, consistent CSV files directly to S3, improving data accessibility.
- Ensured maintainability and deployment ease via Docker, enabling scalable use in production.
- Created a reusable, modular codebase that supports continuous integration and future enhancements.

**Conclusion**

- This ETL pipeline provides a robust solution for integrating Amazon Redshift with Amazon S3 using Python and Docker.
- The project highlights the importance of clean data pipelines in modern cloud-based architectures and demonstrates practical data engineering skills applicable to real-world enterprise scenarios.
