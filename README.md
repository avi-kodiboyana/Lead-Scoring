# OList-Lead-Scoring

## Lead Scoring Model for the public OList Marketing Funnel dataset from Kaggle - https://www.kaggle.com/olistbr/marketing-funnel-olist

- The dataset has information of 8k Marketing Qualified Leads (MQLs) that requested contact between Jun. 1st 2017 and Jun 1st 2018.
- This data has been further enhanced using the Seller data from OList (https://www.kaggle.com/olistbr/brazilian-ecommerce)
 
## Question: What insights can be determined by the data (Summarized in the Tableau Workbook)

- Dataset has 8000 unique leads, out of which 842 MQLs have closed the deal. Conversion Rate - 10.5%

### Sources of Traffic
- Origin has 10 unique categories, with 60 leads missing their source of origin
- **Organic Search** is the most popular category generating **29%** of the leads to the store
- **Top three sources** (Oragnic Search, Paid Search & Social) of traffic generate close to **66%** of the leads to the store
- Of the customers who closed the deal, **56%  came to the site via Organic Search and Paid Search**

### Landing Pages
- **495** unique landing pages in the dataset
- **b76ef37428e6799c421989521c0e5077** is the most popular landing page with almost **11.5%** of the overall lead visits 
- **Top 10** pages landing pages account for **55%** of the leads visits, and **top 25** pages account for **67%** of the leads visits to the OList site
- **Top 2** landing pages account for **41%** of customers who closed the deal

### Contact Day of Week
- Most of the leads are signing up to be contacted during the **weekdays**
- **88%** of the leads who ended up converting have requested to be contacted during weekdays


## Question: Build a model to predict the top MQLs for the Sales Development Representatives (SDRs) to follow up on
