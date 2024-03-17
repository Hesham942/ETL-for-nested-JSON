# Nested JSON ETL

This project provides an ETL (Extract, Transform, Load) framework designed to handle data with nested JSON structures. 

## Installation

This project requires Python 3.x and the following libraries:

* pandas
* json
* pyspark

You can install them using pip:

```bash
pip install pandas json spark pyspark 
```
**4. Usage Instructions:**

* the dataset is nested json format and it can't be read so we needed to change into a readable or structured format. 

  1. **Data Source:** this problem is found a lot you can find it online one of the best providing these datasets is kaggle.
  2. **Transformation:**  we need to explode pivot columns and flattening nested structures to deal with the real data .
  3. **Loading:**  data is being uploaded to postgreSQL using psycopg2 library.
