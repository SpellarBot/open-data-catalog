# Mayor?s Office of Housing and Community Development Grants and Loans

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mayors-office-of-housing-and-community-development-grants-and-loans) |
| Metadata | [Link](https://data.sfgov.org/api/views/ez9i-q28j) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ez9i-q28j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ez9i-q28j/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ez9i-q28j |
| Name | Mayor?s Office of Housing and Community Development Grants and Loans |
| Attribution | Data Dictionary Mayor?s Office of Housing and Community Development |
| Category | Housing and Buildings |
| Tags | housing, grants, loans |
| Created | 2016-06-14T19:58:41Z |
| Publication Date | 2016-06-15T19:38:22Z |

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | project_id                | Project ID                | text          | number        |
| Yes      | series tag     | project_name              | Project Name              | text          | text          |
| Yes      | series tag     | loan_id                   | Loan ID                   | text          | number        |
| Yes      | time           | funding_agreement_date    | Funding Agreement Date    | calendar_date | calendar_date |
| Yes      | numeric metric | amount_of_loan_commitment | Amount of Loan Commitment | money         | money         |
```

## Time Field

```ls
Value = funding_agreement_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ez9i-q28j d:1994-05-04T00:00:00.000Z t:project_name="Asian Women's Shelter" t:project_id=1 t:loan_id=451 m:amount_of_loan_commitment=823000

series e:ez9i-q28j d:1990-11-14T00:00:00.000Z t:project_name="Brennan House" t:project_id=2 t:loan_id=657 m:amount_of_loan_commitment=450000

series e:ez9i-q28j d:1993-08-02T00:00:00.000Z t:project_name="Brennan House" t:project_id=2 t:loan_id=2077 m:amount_of_loan_commitment=150000
```

## Meta Commands

```ls
metric m:amount_of_loan_commitment p:double l:"Amount of Loan Commitment" t:dataTypeName=money

entity e:ez9i-q28j l:"Mayor?s Office of Housing and Community Development Grants and Loans" t:attribution="Data Dictionary Mayor?s Office of Housing and Community Development" t:url=https://data.sfgov.org/api/views/ez9i-q28j

property e:ez9i-q28j t:meta.view v:id=ez9i-q28j v:category="Housing and Buildings" v:attributionLink=http://sfmohcd.org/ v:averageRating=0 v:name="Mayor?s Office of Housing and Community Development Grants and Loans" v:attribution="Data Dictionary Mayor?s Office of Housing and Community Development"

property e:ez9i-q28j t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ez9i-q28j t:meta.view.owner v:id=9wvp-x5mw v:screenName="Charlie MacNulty" v:displayName="Charlie MacNulty"

property e:ez9i-q28j t:meta.view.tableauthor v:id=9wvp-x5mw v:screenName="Charlie MacNulty" v:roleName=editor v:displayName="Charlie MacNulty"
```

## Top Records

```ls
| project_id | project_name          | loan_id | funding_agreement_date | amount_of_loan_commitment | 
| ========== | ===================== | ======= | ====================== | ========================= | 
| 1          | Asian Women's Shelter | 451     | 1994-05-04T00:00:00    | 823000.00                 | 
| 2          | Brennan House         | 657     | 1990-11-14T00:00:00    | 450000.00                 | 
| 2          | Brennan House         | 2077    | 1993-08-02T00:00:00    | 150000.00                 | 
| 2          | Brennan House         | 508     | 1996-10-03T00:00:00    | 25000.00                  | 
| 2          | Brennan House         | 552     | 1997-04-15T00:00:00    | 1083854.00                | 
| 3          | Mercy Family Plaza    | 522     | 1989-06-20T00:00:00    | 877000.00                 | 
| 5          | Market Heights        | 43      | 1994-03-03T00:00:00    | 4087151.00                | 
| 6          | San Cristina          | 294     | 1991-07-02T00:00:00    | 2116506.00                | 
| 6          | San Cristina          | 848     | 1994-01-25T00:00:00    | 75000.00                  | 
| 6          | San Cristina          | 1867    | 2011-09-13T00:00:00    | 422424.00                 | 
```