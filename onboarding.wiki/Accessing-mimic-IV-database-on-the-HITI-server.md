### Summary Code

![](https://github.com/Emory-HITI/onboarding/blob/master/Screen%20Shot%202021-01-21%20at%2012.38.49%20PM.png)

### Code

`!pip install --user psycopg2`

`import psycopg2`

`import pandas as pd`

`conn = psycopg2.connect("dbname=mimic user=mimic password=Mimic@4@plhi")`

`cur = conn.cursor()`

`def create_pandas_table(sql_query, database = conn):` <br>
    `table = pd.read_sql_query(sql_query, database)`<br>
    `return table`

`df = create_pandas_table("select * from mimic_core.patients")`

`df`


