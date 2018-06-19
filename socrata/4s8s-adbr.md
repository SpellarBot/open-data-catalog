# Chicago Microlending Institute (CMI) Microloans - Summary by Ethnicity and Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chicago-microlending-institute-cmi-microloans-summary-by-ethnicity-and-gender) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/4s8s-adbr) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/4s8s-adbr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/4s8s-adbr/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 4s8s-adbr |
| Name | Chicago Microlending Institute (CMI) Microloans - Summary by Ethnicity and Gender |
| Attribution | City of Chicago |
| Category | Community & Economic Development |
| Tags | community & economic development, small business, business, loans, business loans, microloans, microlenders, capital access centers, finance |
| Created | 2015-02-05T17:44:10Z |
| Publication Date | 2016-02-26T15:24:04Z |

## Description

To improve access to capital, the City of Chicago seeded a $2MM revolving loan fund and partnered with Accion to create the Chicago Microlending Institute (CMI). There is a full list of loans in the https://data.cityofchicago.org/id/dpkg-upyz dataset.  Certain data elements could not be included for privacy reasons but are summarized in this dataset.  Loans without a date are not included in the summary.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | time           | loan_year          | Loan Year          | number    | number      |
| Yes      | series tag     | borrower_ethnicity | Borrower Ethnicity | text      | text        |
| Yes      | series tag     | borrower_gender    | Borrower Gender    | text      | text        |
| Yes      | numeric metric | number_of_loans    | Number of Loans    | number    | number      |
```

## Time Field

```ls
Value = loan_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4s8s-adbr d:2012-01-01T00:00:00.000Z t:borrower_gender=Female t:borrower_ethnicity=Black m:number_of_loans=7

series e:4s8s-adbr d:2012-01-01T00:00:00.000Z t:borrower_gender=Male t:borrower_ethnicity=Black m:number_of_loans=5

series e:4s8s-adbr d:2012-01-01T00:00:00.000Z t:borrower_gender=Female t:borrower_ethnicity=Hispanic m:number_of_loans=2
```

## Meta Commands

```ls
metric m:number_of_loans p:integer l:"Number of Loans" t:dataTypeName=number

entity e:4s8s-adbr l:"Chicago Microlending Institute (CMI) Microloans - Summary by Ethnicity and Gender" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/4s8s-adbr

property e:4s8s-adbr t:meta.view v:id=4s8s-adbr v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Chicago Microlending Institute (CMI) Microloans - Summary by Ethnicity and Gender" v:attribution="City of Chicago"

property e:4s8s-adbr t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:4s8s-adbr t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| loan_year | borrower_ethnicity | borrower_gender | number_of_loans | 
| ========= | ================== | =============== | =============== | 
| 2012      | Black              | Female          | 7               | 
| 2012      | Black              | Male            | 5               | 
| 2012      | Hispanic           | Female          | 2               | 
| 2012      | White              | Female          | 2               | 
| 2012      | White              | Male            | 4               | 
| 2012      | Other              | Female          | 1               | 
| 2013      | Black              | Female          | 34              | 
| 2013      | Black              | Male            | 22              | 
| 2013      | Hispanic           | Female          | 6               | 
| 2013      | Hispanic           | Male            | 6               | 
```