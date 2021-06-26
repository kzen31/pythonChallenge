# pythonChallenge
Task python use case from IYKRA

1. Using Dataset A, The table given to you cannot be updated, so if there is a change in the status of a transaction the new data is inserted instead of updating the status of the transaction, it will insert a new row with the same id and insert time based on the time when the row is inserted. You are assigned to create a view that only shows the most updated transactions for each id, so there is no duplicate id inside the view.

2. Using Dataset B, Write a query to get the rolling sum total of sales using the window function!

3. Using Dataset C, Your task is to create an automation (python script preferable) that convert JSON file above into three CSV files below.

`CSV_1 :

    user_id,tx_id

    1,1

    1,3

    1,5

    2,2

    2,4

    2,6


`CSV_2 :

    Id,name,email

    1,agus,agus@example.com

    2,asep,asep@example.com



`CSV_3 :

    Id,tx_date,tx_amount,tx_type

    1,2020-01-01,10,buy

    2,2020-01-01,10,sell

    3,2020-02-01,10,buy

    4,2020-02-01,10,sell

    5,2020-03-01,20,sell

    6,2020-03-01,20,buy
