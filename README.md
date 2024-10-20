Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors, and concerns of different types of customers.






Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers. 
Customer personality analysis helps a business to modify its product based on its target customers from different types of customer segments. For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment. 
The main objective here is - 
1. What people say about your product: what gives customers’ attitude towards the  product. 
2. What people do: which reveals what people are doing rather than what they are  saying about your product.



1. **Customer Sentiment Analysis**: Understand customers' attitudes towards the product.
2. **Behavior Analysis**: Analyze what customers are doing rather than what they are saying about the product.


1. Python
2. Moduler Programing
3. Used Logging
5. PostgreSQL Database (GCP)
6. GitHub Action (CI/CD)
7. Streamlit (Website)
8. scikit-learn
9. Docker
10. Github
11. AWS ECR (private image)
12. AWS EC2 (VM)



```
│   Dockerfile
│   home.py
│   README.md
│   requirements.txt
│   setup.py
│
├───.github
│   └───workflows
│           main.yaml
│
├───artifacts
│       model.pkl
│       preprocessor.pkl
│
├───docs
│       Architecture_Final.pdf
│       CPA_HLD.pdf
│       Detail project report.pdf
│       Low Level Design.pdf
│       Wireframe Documentation_CPA.pdf
│
├───logs
├───Notebook
│   │   Agglomerative Clustering.ipynb
│   │   KMeans Clustering.ipynb
│   │
│   └───Data
│           marketing_campaign.csv
│
├───pages
│       a_form_page_1.py
│       b_results_page_2.py
│       c_charts_page_3.py
│       d_Make_own_chart.py
│
└───src
    │   exception.py
    │   logger.py
    │   utils.py
    │   __init__.py
    │
    ├───components
    │       data_ingetion.py
    │       data_process.py
    │       data_transformation.py
    │       model_trainer.py
    │       variable.py
    │       __init__.py
    │
    └───pipeline
            prediction_pipeline.py
            training_pipeline.py
            __init__.py
```


- What are the statistical characteristics of the customers?
- What are the spending habits of the customers?
- Are there some products that need more marketing?
- How the marketing can be made effective?

- Exploratory Data Analysis (EDA)
- Data Ingestion
- Data Transformation
- Data Pre-processin
- Model Building
- Training Pipeline
- Prediction pipeline
- Streamlit app
- CI/CD Pipeline Integration with Docker, Amazon ECR, GitHub Actions, and AWS 
EC2
  - Docker Build Integration
  - Amazon Elastic Container Registry (ECR)

- Most of the customers are university graduates.
- Most of the customers are living with partners.
- Those living alone have spent more than those living with partners.
- Most of the customers have only one child.
- Those having no children have spent more.
- Middle Age Adults, aged between 40 and 60, are a famous age group category.
- Middle Age Adults are spending on average, more than the other age groups.
- Most of the customers are earning between 25000 and 85000.
- Wine and Meat products are very famous among the customers.
- On the basis of income and total spending, customers are divided into 4 clusters i.e. Platinum, Gold, Silver, and Bronze.
- Most of the customers fall into the Silver and Gold categories.
- Those who are earning more are also spending more.
- Most of the customers like to buy from stores and then online from the web.
- Platinum customers showed more acceptance towards promotion campaigns while bronze customers had the least interest.



**What are the statistical characteristics of the customers?**

The company's customers are mostly married. There are more Middle Aged Adults, aged between 40 and 60, and most of them like to have one child. Most of the customers hold bachelor degrees and their earnings are mostly between 25,000 and 85,000.

**What are the spending habits of the customers?**

Customers have spent more on wine and meat products. Those without children have spent more than those having children. Singles are spending more than the ones with the partners. Middle-aged adults have spent more than the other age groups. Store shopping is the preferred channel for purchasing among customers. Web and Catalog purchasing also have potential.


**Are there some products that need more marketing?**

Sweets and Fruits need some effective marketing. The company needs to run promotions for these products in order to increase the revenue from these products. Baskets of the least-selling products combined with the most-selling products can be effective.

**How marketing can be made effective?**

As a marketing recommendation give coupons to the old and high-spending customers. Market cheap and on-offer products to low-income and low-spending customers. Web purchasing has some potential. To unlock this give special discounts to the customers who sign up on the company's website.

