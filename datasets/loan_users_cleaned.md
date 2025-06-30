Below is a table description of the loan_users_cleaned.csv features, which is derived from loan_users.csv. This is the dataset that will be used for model development.

| Column                  | Description                                   | Type   |
| -------------           | ------------                                  | ---    |
| Income                  | Income of the user                            | int    |
| Age                     | Age of the user                               | int    |
| Experience              | Professional experience of the user in years  | int    |
| Is_Married              | 1 if the user is married, else 0              | int    |
| House_Ownership_Ordinal | 2 for owned, 1 for rented, else 0             | int    |
| Owns_Car                | 1 if user owns a car, else 0                  | int    |
| CURRENT_JOB_YRS         | Years of experience in the current job        | int    |
| CURRENT_HOUSE_YRS       | Number of years in the current residence      | int    |
| Above_Income_Threshold  | 1 if the user is above the 0.10 quantile in income, given their group of profession, state, and city, else 0 | int |
| Sector_*                | 1 if the user's profession falls in a given sector (e.g., Medical & Health) | int |
| STATE_*                 | 1 if the user's STATE falls in a given STATE (e.g., Bijar) | int |
| Risk_Flag          | 1 if the user has defaulted in the past            | int   |
