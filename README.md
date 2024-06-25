# Crowdfunding-ETL

__Project Members__
1. Sandy Gergeis
2. Jayce Spiva
3. Adriel Garcia

__Analysis__
* All final analysis is located in the ETL_Mini_Project_Starter_Code_GAdriel_GSandy_SJayce.ipynb
* For our analysis, we decided to complete Option 1: Use Pandas to create the contacts DataFrame
* All DataFrames are located in the Outputs folder
  

_Contacts DataFrame_ : First 5 rows
|contact_id|first_name|last_name|email|
|----------|----------|---------|-----|
|4661|Cecilia|Velasco|cecilia.velasco@rodrigues.fr|
|3765|Mariana|Ellis|mariana.ellis@rossi.org|
|4187|Sofie|Woods|sofie.woods@riviere.com|
|4941|Jeanette|Iannotti|jeanette.iannotti@yahoo.com|
|2199|Samuel|Sorgatz|samuel.sorgatz@gmail.com|


_Catagory DataFrame_ : First 5 rows
|category_id|category|
|-----------|--------|
|cat1|food|
|cat2|music|
|cat3|technology|
|cat4|theater|
|cat5|film & video|


_Campaign DatFrame_ : First 2 rows
|cf_id|contact_id|company_name|description,goal|pledged|outcome|backers_count|country|currency|launched_date|end_date|category_id|subcategory_id|
|-----|----------|------------|----------------|-------|-------|-------------|-------|--------|-------------|--------|-----------|--------------|
|147|4661|"Baldwin, Riley and Jackson"|Pre-emptive tertiary standardization|100.0,0.0|failed|0|CA|CAD|2020-02-13|2021-03-01|cat1|subcat1|
|1621|3765|Odom Inc|Managed bottom-line architecture|1400.0|14560.0|successful|158,US|USD|2021-01-25|2021-05-25|cat2|subcat2|


_Subcategory DataFrame_ : First 5 rows
|subcategory_id|subcategory|
|--------------|-----------|
|subcat1|food trucks|
|subcat2|rock|
|subcat3|web|
|subcat4|plays|
subcat5,documentary
