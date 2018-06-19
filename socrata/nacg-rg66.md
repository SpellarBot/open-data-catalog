# Total Income And Tax Liability By Place Of Residence: Beginning Tax Year 1999

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-income-and-tax-liability-by-place-of-residence-beginning-tax-year-1999) |
| Metadata | [Link](https://data.ny.gov/api/views/nacg-rg66) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/nacg-rg66/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/nacg-rg66/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | nacg-rg66 |
| Name | Total Income And Tax Liability By Place Of Residence: Beginning Tax Year 1999 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | tax, income, liability, county |
| Created | 2014-05-06T18:48:20Z |
| Publication Date | 2017-02-06T23:00:56Z |

## Description

The Department of Taxation and Finance annually produces a data (study) file and provides a report of statistical information on New York State personal income tax returns that were timely filed. Timely filing means that the tax return was delivered to the Department on or before the due date of the tax return.  The data are from full-year resident, full-year nonresident, and part-year resident returns. This dataset defines individuals filing a resident tax return as full-year residents and individuals filing a nonresident tax return are defined as either a full- year nonresident or a part-year resident.Data presented in this dataset provide the major income tax structure components by size of income.  The components include income, deductions, dependent exemptions, and tax liability. The data also provides this information by size of income and by the filer?s permanent place of residence (county, state or country).  For a more detailed explanation on the determination of residency and components of income see the attachment: NYSTF_PlaceOfResidence_Introduction.Researchers agree to: Use the data for statistical reporting an analysis only. The author will include a disclaimer that states any analyses, interpretations or conclusions were reached by the author and not the New York State Department of Taxation and Finance.

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                                  | Data Type | Render Type |
| ======== | ============== | ================================================ | ===================================================== | ========= | =========== |
| Yes      | time           | tax_year                                         | Tax Year                                              | number    | number      |
| Yes      | series tag     | resident_type                                    | Resident Type                                         | text      | text        |
| Yes      | series tag     | place_of_residence                               | Place of Residence                                    | text      | text        |
| Yes      | series tag     | country                                          | Country                                               | text      | text        |
| Yes      | series tag     | state                                            | State                                                 | text      | text        |
| Yes      | series tag     | county                                           | County                                                | text      | text        |
| Yes      | series tag     | disclosure                                       | Disclosure                                            | text      | text        |
| Yes      | numeric metric | number_of_all_returns                            | Number of All Returns                                 | number    | number      |
| Yes      | numeric metric | ny_agi_of_all_returns_in_thousands               | NY AGI of All Returns (in thousands) *                | number    | number      |
| Yes      | numeric metric | tax_liability_of_all_returns_in_thousands        | Tax Liability of All Returns (in thousands) **        | number    | number      |
| Yes      | numeric metric | number_of_taxable_returns                        | Number of Taxable Returns                             | number    | number      |
| Yes      | numeric metric | ny_agi_of_taxable_returns_in_thousands           | NY AGI of Taxable Returns (in thousands) *            | number    | number      |
| Yes      | numeric metric | tax_liability_of_taxable_returns_in_thousands    | Tax Liability of Taxable Returns (in thousands) **    | number    | number      |
| Yes      | numeric metric | number_of_nontaxable_returns                     | Number of Nontaxable Returns                          | number    | number      |
| Yes      | numeric metric | ny_agi_of_nontaxable_returns_in_thousands        | NY AGI of Nontaxable Returns (in thousands) *         | number    | number      |
| Yes      | numeric metric | tax_liability_of_nontaxable_returns_in_thousands | Tax Liability of Nontaxable Returns (in thousands) ** | number    | number      |
| Yes      | numeric metric | average_ny_agi_of_all_returns                    | Average NY AGI of All Returns                         | number    | number      |
| Yes      | numeric metric | average_tax_of_all_returns                       | Average Tax of All Returns                            | number    | number      |
| Yes      | numeric metric | average_ny_agi_of_taxable_returns                | Average NY AGI of Taxable Returns                     | number    | number      |
| Yes      | numeric metric | average_tax_of_taxable_returns                   | Average Tax of Taxable Returns                        | number    | number      |
| Yes      | numeric metric | average_ny_agi_of_nontaxable_returns             | Average NY AGI of Nontaxable Returns                  | number    | number      |
| Yes      | numeric metric | county_sort_order                                | County Sort Order                                     | number    | number      |
```

## Time Field

```ls
Value = tax_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nacg-rg66 d:2011-01-01T00:00:00.000Z t:place_of_residence="New York City - Bronx" t:resident_type="Full-Year Resident" t:county=Bronx t:state="New York" t:country="United States" m:average_ny_agi_of_nontaxable_returns=10063 m:number_of_all_returns=588674 m:ny_agi_of_all_returns_in_thousands=17626369 m:average_tax_of_all_returns=737 m:ny_agi_of_nontaxable_returns_in_thousands=2906845 m:average_ny_agi_of_all_returns=29942 m:ny_agi_of_taxable_returns_in_thousands=14719525 m:tax_liability_of_nontaxable_returns_in_thousands=-165209 m:tax_liability_of_all_returns_in_thousands=433593 m:number_of_nontaxable_returns=288854 m:county_sort_order=1 m:number_of_taxable_returns=299820 m:average_ny_agi_of_taxable_returns=49095 m:average_tax_of_taxable_returns=1997 m:tax_liability_of_taxable_returns_in_thousands=598802

series e:nacg-rg66 d:2011-01-01T00:00:00.000Z t:place_of_residence="New York City - Kings" t:resident_type="Full-Year Resident" t:county=Kings t:state="New York" t:country="United States" m:average_ny_agi_of_nontaxable_returns=8685 m:number_of_all_returns=1078520 m:ny_agi_of_all_returns_in_thousands=48145626 m:average_tax_of_all_returns=1845 m:ny_agi_of_nontaxable_returns_in_thousands=3841481 m:average_ny_agi_of_all_returns=44640 m:ny_agi_of_taxable_returns_in_thousands=44304145 m:tax_liability_of_nontaxable_returns_in_thousands=-250532 m:tax_liability_of_all_returns_in_thousands=1989456 m:number_of_nontaxable_returns=442320 m:county_sort_order=2 m:number_of_taxable_returns=636200 m:average_ny_agi_of_taxable_returns=69639 m:average_tax_of_taxable_returns=3521 m:tax_liability_of_taxable_returns_in_thousands=2239988

series e:nacg-rg66 d:2011-01-01T00:00:00.000Z t:place_of_residence="New York City - Manhattan" t:resident_type="Full-Year Resident" t:county=Manhattan t:state="New York" t:country="United States" m:average_ny_agi_of_nontaxable_returns=-13802 m:number_of_all_returns=808917 m:ny_agi_of_all_returns_in_thousands=129181676 m:average_tax_of_all_returns=11701 m:ny_agi_of_nontaxable_returns_in_thousands=-3220186 m:average_ny_agi_of_all_returns=159697 m:ny_agi_of_taxable_returns_in_thousands=132401862 m:tax_liability_of_nontaxable_returns_in_thousands=-87257 m:tax_liability_of_all_returns_in_thousands=9465286 m:number_of_nontaxable_returns=233305 m:county_sort_order=3 m:number_of_taxable_returns=575612 m:average_ny_agi_of_taxable_returns=230019 m:average_tax_of_taxable_returns=16595 m:tax_liability_of_taxable_returns_in_thousands=9552543
```

## Meta Commands

```ls
metric m:number_of_all_returns p:integer l:"Number of All Returns" d:"Count of the number of return filings (note: married filing joint returns count as one)" t:dataTypeName=number

metric m:ny_agi_of_all_returns_in_thousands p:double l:"NY AGI of All Returns (in thousands) *" d:"New York Adjusted Gross Income from return filings. * New York Adjusted Gross Income on resident tax forms and Federal source New York Adjusted Gross Income (includes non-New York income) on non-resident tax forms" t:dataTypeName=number

metric m:tax_liability_of_all_returns_in_thousands p:double l:"Tax Liability of All Returns (in thousands) **" d:"Tax Liability from return filings. ** Includes refundable tax credits" t:dataTypeName=number

metric m:number_of_taxable_returns p:integer l:"Number of Taxable Returns" d:"Count of the number of taxable return filings (note: married filing joint returns count as one)" t:dataTypeName=number

metric m:ny_agi_of_taxable_returns_in_thousands p:double l:"NY AGI of Taxable Returns (in thousands) *" d:"New York Adjusted Gross Income from taxable return filings. * New York Adjusted Gross Income on resident tax forms and Federal source New York Adjusted Gross Income (includes non-New York income) on non-resident tax forms" t:dataTypeName=number

metric m:tax_liability_of_taxable_returns_in_thousands p:double l:"Tax Liability of Taxable Returns (in thousands) **" d:"Tax Liability from taxable return filings. Note: for Full-Year Nonresidents the data may not be available." t:dataTypeName=number

metric m:number_of_nontaxable_returns p:integer l:"Number of Nontaxable Returns" d:"Count of the number of non-taxable return filings (note: married filing joint returns count as one)" t:dataTypeName=number

metric m:ny_agi_of_nontaxable_returns_in_thousands p:double l:"NY AGI of Nontaxable Returns (in thousands) *" d:"New York Adjusted Gross Income from non-taxable return filings" t:dataTypeName=number

metric m:tax_liability_of_nontaxable_returns_in_thousands p:double l:"Tax Liability of Nontaxable Returns (in thousands) **" d:"Tax Liability from non-taxable return filings. Note: for tax years prior to 2011 the data may not be available. ** Includes refundable tax credits" t:dataTypeName=number

metric m:average_ny_agi_of_all_returns p:integer l:"Average NY AGI of All Returns" d:"Average New York Adjusted Gross Income from all return filings" t:dataTypeName=number

metric m:average_tax_of_all_returns p:integer l:"Average Tax of All Returns" d:"Average Tax Liability from all return filings" t:dataTypeName=number

metric m:average_ny_agi_of_taxable_returns p:integer l:"Average NY AGI of Taxable Returns" d:"Average New York Adjusted Gross Income from taxable return filings" t:dataTypeName=number

metric m:average_tax_of_taxable_returns p:integer l:"Average Tax of Taxable Returns" d:"Average Tax Liability from taxable return filings. Note: for Full-Year Nonresidents the data may not be available." t:dataTypeName=number

metric m:average_ny_agi_of_nontaxable_returns p:integer l:"Average NY AGI of Nontaxable Returns" d:"Average New York Adjusted Gross Income from non-taxable return filings" t:dataTypeName=number

metric m:county_sort_order p:integer l:"County Sort Order" d:"Sort Order on Place of Residence" t:dataTypeName=number

entity e:nacg-rg66 l:"Total Income And Tax Liability By Place Of Residence: Beginning Tax Year 1999" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/nacg-rg66

property e:nacg-rg66 t:meta.view v:id=nacg-rg66 v:category="Government & Finance" v:attributionLink=http://www.tax.ny.gov/research/stats/stat_pit/analysis_of_state_personal_income_tax_returns_by_place_of_residence.htm v:averageRating=0 v:name="Total Income And Tax Liability By Place Of Residence: Beginning Tax Year 1999" v:attribution="New York State Department of Taxation and Finance"

property e:nacg-rg66 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:nacg-rg66 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:nacg-rg66 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| tax_year | resident_type      | place_of_residence        | country       | state    | county               | disclosure | number_of_all_returns | ny_agi_of_all_returns_in_thousands | tax_liability_of_all_returns_in_thousands | number_of_taxable_returns | ny_agi_of_taxable_returns_in_thousands | tax_liability_of_taxable_returns_in_thousands | number_of_nontaxable_returns | ny_agi_of_nontaxable_returns_in_thousands | tax_liability_of_nontaxable_returns_in_thousands | average_ny_agi_of_all_returns | average_tax_of_all_returns | average_ny_agi_of_taxable_returns | average_tax_of_taxable_returns | average_ny_agi_of_nontaxable_returns | county_sort_order | 
| ======== | ================== | ========================= | ============= | ======== | ==================== | ========== | ===================== | ================================== | ========================================= | ========================= | ====================================== | ============================================= | ============================ | ========================================= | ================================================ | ============================= | ========================== | ================================= | ============================== | ==================================== | ================= | 
| 2011     | Full-Year Resident | New York City - Bronx     | United States | New York | Bronx                |            | 588674                | 17626369                           | 433593                                    | 299820                    | 14719525                               | 598802                                        | 288854                       | 2906845                                   | -165209                                          | 29942                         | 737                        | 49095                             | 1997                           | 10063                                | 1                 | 
| 2011     | Full-Year Resident | New York City - Kings     | United States | New York | Kings                |            | 1078520               | 48145626                           | 1989456                                   | 636200                    | 44304145                               | 2239988                                       | 442320                       | 3841481                                   | -250532                                          | 44640                         | 1845                       | 69639                             | 3521                           | 8685                                 | 2                 | 
| 2011     | Full-Year Resident | New York City - Manhattan | United States | New York | Manhattan            |            | 808917                | 129181676                          | 9465286                                   | 575612                    | 132401862                              | 9552543                                       | 233305                       | -3220186                                  | -87257                                           | 159697                        | 11701                      | 230019                            | 16595                          | -13802                               | 3                 | 
| 2011     | Full-Year Resident | New York City - Queens    | United States | New York | Queens               |            | 1028443               | 41248512                           | 1512781                                   | 627276                    | 37521694                               | 1694491                                       | 401167                       | 3726818                                   | -181709                                          | 40108                         | 1471                       | 59817                             | 2701                           | 9290                                 | 4                 | 
| 2011     | Full-Year Resident | New York City - Richmond  | United States | New York | Richmond             |            | 204587                | 11442144                           | 494959                                    | 140940                    | 11001652                               | 518404                                        | 63647                        | 440492                                    | -23445                                           | 55928                         | 2419                       | 78059                             | 3678                           | 6921                                 | 5                 | 
| 2011     | Full-Year Resident | Total, New York City      | United States | New York | Total, New York City |            | 3709141               | 247644328                          | 13896076                                  | 2279848                   | 239948878                              | 14604228                                      | 1429293                      | 7695450                                   | -708153                                          | 66766                         | 3746                       | 105248                            | 6406                           | 5384                                 | 6                 | 
| 2011     | Full-Year Resident | Albany                    | United States | New York | Albany               |            | 140676                | 7677295                            | 368534                                    | 98199                     | 7362112                                | 385117                                        | 42477                        | 315183                                    | -16584                                           | 54574                         | 2620                       | 74971                             | 3922                           | 7420                                 | 7                 | 
| 2011     | Full-Year Resident | Allegany                  | United States | New York | Allegany             |            | 18197                 | 663809                             | 21063                                     | 11149                     | 594423                                 | 24125                                         | 7048                         | 69387                                     | -3062                                            | 36479                         | 1157                       | 53316                             | 2164                           | 9845                                 | 8                 | 
| 2011     | Full-Year Resident | Broome                    | United States | New York | Broome               |            | 88141                 | 3625446                            | 136304                                    | 57184                     | 3380900                                | 155152                                        | 30957                        | 244546                                    | -18849                                           | 41132                         | 1546                       | 59123                             | 2713                           | 7900                                 | 9                 | 
| 2011     | Full-Year Resident | Cattaraugus               | United States | New York | Cattaraugus          |            | 33328                 | 1188768                            | 37752                                     | 20637                     | 1071691                                | 43722                                         | 12691                        | 117077                                    | -5970                                            | 35669                         | 1133                       | 51931                             | 2119                           | 9225                                 | 10                | 
```