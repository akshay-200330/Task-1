This csv file includes a cleaned version of the marketing_campaign.csv dataset, which has undergone the following preprocessing steps to ensure data quality and prepare it for further analysis and modeling:

Missing Values Handled:
Missing values in the Income column were identified and imputed using the median, as this approach is robust to outliers and better reflects the central tendency for potentially skewed income distributions.

Duplicate Rows Removed:
The dataset was checked for and had any completely duplicate rows removed to ensure each entry represents a unique customer record.

Outliers Addressed in Year_Birth:
Outlier values in the Year_Birth column (e.g., years significantly outside a reasonable human lifespan) were identified and handled. This might involve capping these values to a more plausible range or removing the corresponding rows if they are deemed unrecoverable data entry errors.

Feature Engineering:
Several new features have been engineered to provide richer insights:
* Age: Calculated from Year_Birth to represent the customer's age.
* TotalMntSpendings: Represents the sum of all spending categories (MntWines, MntFruits, MntMeatProducts, MntFishProducts, * * MntSweetProducts, MntGoldProds).
* Children: Represents the total number of children in the household (sum of Kidhome and Teenhome).

  These steps ensure the dataset is clean, consistent, and ready for exploratory data analysis, segmentation, and predictive modeling tasks.
