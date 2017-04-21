# Libraries Annual Statistics Comparison 2010-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-annual-statistics-comparison-2010-2011-386b4) |
| Metadata | [Link](https://data.hawaii.gov/api/views/utt5-rg7n) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/utt5-rg7n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/utt5-rg7n/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | utt5-rg7n |
| Name | Libraries Annual Statistics Comparison 2010-2011 |
| Attribution | Hawaii State Public Library System |
| Category | Formal Education |
| Tags | library, books, holdings |
| Created | 2012-07-26T19:08:56Z |
| Publication Date | 2012-07-26T19:11:56Z |

## Description

Annual Statistics for Circulation, borrowers, holdings and holds

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | series tag     | island                         | Island                         | text      | text        |
| Yes      | series tag     | library                        | Library                        | text      | text        |
| Yes      | series tag     | code                           | Code                           | text      | text        |
| Yes      | numeric metric | holdings_fy_2010               | Holdings FY 2010               | number    | number      |
| Yes      | numeric metric | holdings_fy_2011               | Holdings FY 2011               | number    | number      |
| Yes      | series tag     | percent_difference_holdings    | Percent Difference Holdings    | text      | text        |
| Yes      | numeric metric | registered_borrowers_fy_2010   | Registered Borrowers FY 2010   | number    | number      |
| Yes      | numeric metric | registered_borrowers_fy_2011   | Registered Borrowers FY 2011   | number    | number      |
| Yes      | series tag     | percent_difference_borrowers   | Percent Difference Borrowers   | text      | text        |
| Yes      | numeric metric | circulation_activity_fy_2010   | Circulation Activity FY 2010   | number    | number      |
| Yes      | numeric metric | circulation_activity_fy_2011   | Circulation Activity FY 2011   | number    | number      |
| Yes      | series tag     | percent_difference_circulation | Percent Difference Circulation | text      | text        |
| Yes      | numeric metric | holds_fy_2010                  | Holds FY 2010                  | number    | number      |
| Yes      | numeric metric | holds_fy_2011                  | Holds FY 2011                  | number    | number      |
| Yes      | series tag     | percent_difference_holds       | Percent Difference Holds       | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:utt5-rg7n d:2010-01-01T00:00:00.000Z t:percent_difference_holds=8 t:library=Aiea t:percent_difference_holdings=(5) t:code=OAA t:percent_difference_borrowers=3 t:island=Oahu t:percent_difference_circulation=(3) m:registered_borrowers_fy_2010=23053 m:registered_borrowers_fy_2011=23709 m:circulation_activity_fy_2011=170657 m:holds_fy_2010=2869 m:holds_fy_2011=3095 m:circulation_activity_fy_2010=176469 m:holdings_fy_2010=82718 m:holdings_fy_2011=78370

series e:utt5-rg7n d:2010-01-01T00:00:00.000Z t:percent_difference_holds=5 t:library="Aina Haina  1/" t:percent_difference_holdings=(5) t:code=OAH t:percent_difference_borrowers=3 t:island=Oahu t:percent_difference_circulation=(1) m:registered_borrowers_fy_2010=15374 m:registered_borrowers_fy_2011=15901 m:circulation_activity_fy_2011=161298 m:holds_fy_2010=2665 m:holds_fy_2011=2788 m:circulation_activity_fy_2010=162701 m:holdings_fy_2010=70180 m:holdings_fy_2011=66364

series e:utt5-rg7n d:2010-01-01T00:00:00.000Z t:percent_difference_holds=15 t:library="Ewa Beach P/S Lib.  2/" t:percent_difference_holdings=(12) t:code=OEW t:percent_difference_borrowers=1 t:island=Oahu t:percent_difference_circulation=7 m:registered_borrowers_fy_2010=20928 m:registered_borrowers_fy_2011=21057 m:circulation_activity_fy_2011=98047 m:holds_fy_2010=2006 m:holds_fy_2011=2316 m:circulation_activity_fy_2010=91858 m:holdings_fy_2010=91196 m:holdings_fy_2011=80317
```

## Meta Commands

```ls
metric m:holdings_fy_2010 p:integer l:"Holdings FY 2010" t:dataTypeName=number

metric m:holdings_fy_2011 p:integer l:"Holdings FY 2011" t:dataTypeName=number

metric m:registered_borrowers_fy_2010 p:integer l:"Registered Borrowers FY 2010" t:dataTypeName=number

metric m:registered_borrowers_fy_2011 p:integer l:"Registered Borrowers FY 2011" t:dataTypeName=number

metric m:circulation_activity_fy_2010 p:integer l:"Circulation Activity FY 2010" t:dataTypeName=number

metric m:circulation_activity_fy_2011 p:integer l:"Circulation Activity FY 2011" t:dataTypeName=number

metric m:holds_fy_2010 p:integer l:"Holds FY 2010" t:dataTypeName=number

metric m:holds_fy_2011 p:integer l:"Holds FY 2011" t:dataTypeName=number

entity e:utt5-rg7n l:"Libraries Annual Statistics Comparison 2010-2011" t:attribution="Hawaii State Public Library System" t:url=https://data.hawaii.gov/api/views/utt5-rg7n

property e:utt5-rg7n t:meta.view v:id=utt5-rg7n v:category="Formal Education" v:attributionLink=http://www.librarieshawaii.org/ v:averageRating=0 v:name="Libraries Annual Statistics Comparison 2010-2011" v:attribution="Hawaii State Public Library System"

property e:utt5-rg7n t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:utt5-rg7n t:meta.view.owner v:id=4hgi-fxu8 v:screenName="Paola Saibene" v:displayName="Paola Saibene"

property e:utt5-rg7n t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| island | library                | code | holdings_fy_2010 | holdings_fy_2011 | percent_difference_holdings | registered_borrowers_fy_2010 | registered_borrowers_fy_2011 | percent_difference_borrowers | circulation_activity_fy_2010 | circulation_activity_fy_2011 | percent_difference_circulation | holds_fy_2010 | holds_fy_2011 | percent_difference_holds | 
| ====== | ====================== | ==== | ================ | ================ | =========================== | ============================ | ============================ | ============================ | ============================ | ============================ | ============================== | ============= | ============= | ======================== | 
| Oahu   | Aiea                   | OAA  | 82718            | 78370            | (5)                         | 23053                        | 23709                        | 3                            | 176469                       | 170657                       | (3)                            | 2869          | 3095          | 8                        | 
| Oahu   | Aina Haina 1/          | OAH  | 70180            | 66364            | (5)                         | 15374                        | 15901                        | 3                            | 162701                       | 161298                       | (1)                            | 2665          | 2788          | 5                        | 
| Oahu   | Ewa Beach P/S Lib. 2/  | OEW  | 91196            | 80317            | (12)                        | 20928                        | 21057                        | 1                            | 91858                        | 98047                        | 7                              | 2006          | 2316          | 15                       | 
| Oahu   | Hawaii Kai 3/          | OHK  | 79327            | 78925            | (1)                         | 18919                        | 19468                        | 3                            | 156970                       | 148851                       | (5)                            | 3807          | 4197          | 10                       | 
| Oahu   | HSL 4/ - 6/            | OHS  | 571114           | 571271           | 0                           | 89591                        | 90724                        | 1                            | 467636                       | 440722                       | (6)                            | 11387         | 10649         | (6)                      | 
| Oahu   | Kahuku Total           |      | 49650            | 49521            | (0)                         | 8977                         | 9223                         | 3                            | 55318                        | 55914                        | 1                              | 885           | 1125          | 27                       | 
| Oahu   | Kahuku P/S Lib. 7/, 8/ | OKA  | 48784            | 48496            | (1)                         | 8977                         | 9223                         | 3                            | 54378                        | 54241                        | (0)                            | 876           | 1091          | 25                       | 
| Oahu   | Bookmobile             | OB7  | 866              | 1025             | 18                          | 0                            | 0                            | 0                            | 940                          | 1673                         | 78                             | 9             | 34            | 278                      | 
| Oahu   | Kailua 9/ - 12/        | OKI  | 86433            | 87547            | 1                           | 42190                        | 43194                        | 2                            | 280766                       | 283959                       | 1                              | 4755          | 4816          | 1                        | 
| Oahu   | Kaimuki 13/, 14/       | OKK  | 121201           | 114132           | (6)                         | 32190                        | 33149                        | 3                            | 362865                       | 347405                       | (4)                            | 7498          | 7289          | (3)                      | 
```