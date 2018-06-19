# Restricted Flavored Tobacco Products

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/restricted-flavored-tobacco-products-eccab) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/5wce-bks2) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/5wce-bks2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/5wce-bks2/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 5wce-bks2 |
| Name | Restricted Flavored Tobacco Products |
| Attribution | City of Chicago |
| Category | Health & Human Services |
| Tags | business, health, regulation, tobacco |
| Created | 2014-05-16T16:00:07Z |
| Publication Date | 2015-12-18T22:55:11Z |

## Description

A list of flavored tobacco products that may not be sold within 500 feet of a school in Chicago. See http://www.cityofchicago.org/content/dam/city/depts/cdph/policy_planning/Board_of_Health/FlavoredTobaccoRules_Final_Dec112015.pdf for the specifics of the regulation. This list will be updated periodically. A list of tobacco flavor terms that may be used to determine if a product is flavored is available at https://data.cityofchicago.org/d/fkci-tsq8.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| Yes      | series tag  | brand          | BRAND          | text          | text          |
| Yes      | series tag  | product        | PRODUCT        | text          | text          |
| Yes      | series tag  | flavor         | FLAVOR         | text          | text          |
| Yes      | series tag  | detail         | DETAIL         | text          | text          |
| Yes      | time        | published_date | PUBLISHED DATE | calendar_date | calendar_date |
```

## Time Field

```ls
Value = published_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:5wce-bks2 d:2014-08-07T00:00:00.000Z t:product="FILTERED CIGAR" t:flavor=BLACKBERRY t:brand=1839 m:row_number.5wce-bks2=1

series e:5wce-bks2 d:2014-08-07T00:00:00.000Z t:product="FILTERED CIGAR" t:flavor=CHERRY t:brand=1839 m:row_number.5wce-bks2=2

series e:5wce-bks2 d:2014-08-07T00:00:00.000Z t:product="FILTERED CIGAR" t:flavor=MENTHOL t:brand=1839 m:row_number.5wce-bks2=3
```

## Meta Commands

```ls
metric m:row_number.5wce-bks2 p:long l:"Row Number"

entity e:5wce-bks2 l:"Restricted Flavored Tobacco Products" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/5wce-bks2

property e:5wce-bks2 t:meta.view v:id=5wce-bks2 v:category="Health & Human Services" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Restricted Flavored Tobacco Products" v:attribution="City of Chicago"

property e:5wce-bks2 t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:5wce-bks2 t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| brand              | product                    | flavor     | detail | published_date      | 
| ================== | ========================== | ========== | ====== | =================== | 
| 1839               | FILTERED CIGAR             | BLACKBERRY |        | 2014-08-07T00:00:00 | 
| 1839               | FILTERED CIGAR             | CHERRY     |        | 2014-08-07T00:00:00 | 
| 1839               | FILTERED CIGAR             | MENTHOL    |        | 2014-08-07T00:00:00 | 
| 1839               | FILTERED CIGAR             | VANILLA    |        | 2014-08-07T00:00:00 | 
| 1839               | MENTHOL-FLAVORED CIGARETTE | MENTHOL    |        | 2014-08-07T00:00:00 | 
| 10/20              | MENTHOL-FLAVORED CIGARETTE | MENTHOL    |        | 2014-08-07T00:00:00 | 
| 10/20 LIGHTS       | MENTHOL-FLAVORED CIGARETTE | MENTHOL    |        | 2014-08-07T00:00:00 | 
| 10/20 ULTRA LIGHTS | MENTHOL-FLAVORED CIGARETTE | MENTHOL    |        | 2014-08-07T00:00:00 | 
| 1839 GREEN         | MENTHOL-FLAVORED CIGARETTE | MENTHOL    |        | 2014-08-07T00:00:00 | 
| 1839 LIGHTS        | MENTHOL-FLAVORED CIGARETTE | MENTHOL    |        | 2014-08-07T00:00:00 | 
```