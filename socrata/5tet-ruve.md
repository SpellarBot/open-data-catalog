# Dbedt Tax Credits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-tax-credits) |
| Metadata | [Link](https://data.hawaii.gov/api/views/5tet-ruve) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/5tet-ruve/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/5tet-ruve/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 5tet-ruve |
| Name | Dbedt Tax Credits |
| Category | Economic Development |
| Created | 2015-02-08T04:22:01Z |
| Publication Date | 2015-02-08T04:22:40Z |

## Columns

```ls
| Included | Schema Type | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | =========== | ===================================== | ===================================== | ========= | =========== |
| Yes      | series tag  | progam_id                             | Progam ID                             | text      | text        |
| Yes      | series tag  | agency_name                           | Agency Name                           | text      | text        |
| Yes      | series tag  | tax_credit_name                       | Tax Credit Name                       | text      | text        |
| Yes      | series tag  | hrs_chapter_section                   | HRS Chapter/Section                   | text      | text        |
| Yes      | time        | year_enacted                          | Year Enacted                          | number    | text        |
| Yes      | series tag  | estimated_total_value_claimed_in_2013 | Estimated Total Value Claimed in 2013 | text      | text        |
```

## Time Field

```ls
Value = year_enacted
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:5tet-ruve l:"Dbedt Tax Credits" t:url=https://data.hawaii.gov/api/views/5tet-ruve

property e:5tet-ruve t:meta.view v:id=5tet-ruve v:category="Economic Development" v:averageRating=0 v:name="Dbedt Tax Credits"

property e:5tet-ruve t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:5tet-ruve t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| progam_id | agency_name                                  | tax_credit_name                                                           | hrs_chapter_section          | year_enacted | estimated_total_value_claimed_in_2013                                                         | 
| ========= | ============================================ | ========================================================================= | ============================ | ============ | ============================================================================================= | 
| BED 100   | Business Development & Support Division      | EZ GET Waver                                                              | ?209E-11, HRS                | 1986         |                                                                                               | 
| BED 100   | Business Development & Support Division      | EZ Non-Refundable Tax Credit                                              | ?209E-10, HRS                | 1986         |                                                                                               | 
| BED105    | Creative Industries / Hawaii Film Office     | Act 88/89-Motion Picture, Digital Media Film Production Income Tax Credit | ?235-17, HRS                 | 2006         | $33,906,404                                                                                   | 
| BED 120   | State Energy Office                          | Renewable Energy Technologies Income Tax Credit                           | ?235-12.5, HRS               | 1991         | $174 Million (2012 estimate)                                                                  | 
| BED 143   | High Technology Development Corporation      | Research Activitity Tax Credit                                            | ?235.110.91, HRS             | 2013         | $1.1 Million (reported to be claimed in surveys completed by 10 companies for tax year 2013.) | 
| BED 160   | Hawaii Housing Finance and Development Corp. | State Low Income Housing Tax Credit                                       | ?201H-15 and ?235-110.8, HRS | 1988         | $2,603,673/year with 10 year take down period (Total value awarded* in 2014 tax Year).        | 
|           |                                              |                                                                           |                              |              | *Note: Only DoTax can provide information on when/if State tax credits are actually claimed.  | 
```