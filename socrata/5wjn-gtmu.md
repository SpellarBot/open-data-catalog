# Iowa Standardized Medicare Supplement Rate Changes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-standardized-medicare-supplement-rate-changes) |
| Metadata | [Link](https://data.iowa.gov/api/views/5wjn-gtmu) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/5wjn-gtmu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/5wjn-gtmu/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 5wjn-gtmu |
| Name | Iowa Standardized Medicare Supplement Rate Changes |
| Category | Health |
| Created | 2016-10-13T20:10:10Z |
| Publication Date | 2017-04-17T19:58:06Z |

## Description

Over the last several years, the original standardized plans (A ? J) have been updated, and several new plans have been added.

However, for historical rate increase purposes, this data includes all plans whether they are available for sale or not. Only plans with asterisks can

be sold under the MIPPA act: A, B, C, D, F, HD?F, G, K, L, M, and N.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type     | Render Type   |
| ======== | ============== | ============ | ============ | ============= | ============= |
| Yes      | series tag     | company_name | Company Name | text          | text          |
| Yes      | series tag     | form_numbers | Form Numbers | text          | text          |
| Yes      | time           | effective    | Effective    | calendar_date | calendar_date |
| No       |                | a            | A*           | percent       | percent       |
| No       |                | b            | B*           | percent       | percent       |
| No       |                | c            | C*           | percent       | percent       |
| No       |                | d            | D*           | percent       | percent       |
| No       |                | e            | E            | percent       | percent       |
| No       |                | f            | F*           | percent       | percent       |
| No       |                | g            | G*           | percent       | percent       |
| No       |                | h            | H            | percent       | percent       |
| No       |                | i            | I            | percent       | percent       |
| No       |                | j            | J            | percent       | percent       |
| Yes      | numeric metric | hdf          | HD-F*        | percent       | percent       |
| Yes      | numeric metric | hdj          | HD-J         | percent       | percent       |
| No       |                | k            | K*           | percent       | percent       |
| No       |                | l            | L*           | percent       | percent       |
| No       |                | m            | M*           | percent       | percent       |
| No       |                | n            | N*           | percent       | percent       |
| Yes      | series tag     | web_notes    | Web Notes    | text          | text          |
```

## Time Field

```ls
Value = effective
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = a,b,c,d,e,f,g,h,i,j,k,l,m,n
```

## Data Commands

```ls
series e:5wjn-gtmu d:2017-06-01T00:00:00.000Z t:company_name="Continental Life Insurance Company of Brentwood, Tennessee" t:form_numbers="2010 Modernized MIPPA CLIMSP10F IA et al" m:hdf=13.8

series e:5wjn-gtmu d:2017-04-01T00:00:00.000Z t:company_name="Physicians Mutual Insurance Company" t:form_numbers="MIPPA Plans P020, P025, P026, P027" m:hdf=7

series e:5wjn-gtmu d:2017-01-01T00:00:00.000Z t:company_name="Reserve National Insurance Company" t:form_numbers="2010 MIPPA plans:  MCS-10-F et al" m:hdf=0
```

## Meta Commands

```ls
metric m:hdf p:float l:HD-F* t:dataTypeName=percent

metric m:hdj p:float l:HD-J t:dataTypeName=percent

entity e:5wjn-gtmu l:"Iowa Standardized Medicare Supplement Rate Changes" t:url=https://data.iowa.gov/api/views/5wjn-gtmu

property e:5wjn-gtmu t:meta.view v:id=5wjn-gtmu v:category=Health v:averageRating=0 v:name="Iowa Standardized Medicare Supplement Rate Changes"

property e:5wjn-gtmu t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:5wjn-gtmu t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| company_name                                               | form_numbers                                         | effective           | a    | b    | c   | d   | e   | f    | g    | h | i | j   | hdf  | hdj | k | l | m | n    | web_notes                                                                                                                      | 
| ========================================================== | ==================================================== | =================== | ==== | ==== | === | === | === | ==== | ==== | = | = | === | ==== | === | = | = | = | ==== | ============================================================================================================================== | 
| Continental Life Insurance Company of Brentwood, Tennessee | 2010 Modernized MIPPA CLIMSP10F IA et al             | 2017-06-01T00:00:00 | 13.8 | 13.8 |     |     |     | 13.8 | 13.8 |   |   |     | 13.8 |     |   |   |   | 13.8 |                                                                                                                                | 
| Globe Life and Accident Insurance Company                  | GMSA et al                                           | 2017-03-01T00:00:00 | 6.0  | 6.0  | 6.0 |     |     | 6.0  |      |   |   |     |      |     |   |   |   |      | For the 5-26-2004 filing for GGRMSP, the iid approved an age slope change, but the overall rate remained the same.             | 
| Continental General Insurance Company                      | MIPPA plans: CGI-MS-DM-AA-A et al                    | 2017-04-01T00:00:00 |      |      |     |     |     | 0.0  | 2.4  |   |   |     |      |     |   |   |   |      |                                                                                                                                | 
| Washington National Insurance Company                      | IMP-9500, IMP-1950, CIC-1000 and WNIC-1004 All Plans | 2017-06-15T00:00:00 | 7.5  |      | 0.0 | 0.0 | 0.0 | 0.0  | 0.0  |   |   | 3.0 |      |     |   |   |   |      |                                                                                                                                | 
| Combined Insurance Company of America                      | 19500 & 19501                                        | 2017-01-06T00:00:00 |      |      |     | 0.0 |     |      |      |   |   |     |      |     |   |   |   |      | Forms 19500 & 19501 are the "Direct Response" plans                                                                            | 
| Loyal American Life Insurance Company                      | L-5230 et al                                         | 2017-03-01T00:00:00 | 5.6  | 5.6  | 5.6 | 5.6 |     | 5.6  | 5.6  |   |   |     |      |     |   |   |   |      |                                                                                                                                | 
| Physicians Mutual Insurance Company                        | MIPPA Plans P020, P025, P026, P027                   | 2017-04-01T00:00:00 | 9.0  |      |     |     |     | 12.0 | 7.5  |   |   |     | 7.0  |     |   |   |   | 9.0  |                                                                                                                                | 
| Allianz Life Insurance Company of North America            | N-1084-P et al                                       | 2016-12-30T00:00:00 |      |      | 0.0 |     |     | 0.0  |      |   |   |     |      |     |   |   |   |      |                                                                                                                                | 
| USAA Life Insurance Company                                | 2010 MIPPA - Plans A, F, and N)                      | 2017-05-01T00:00:00 | 0.0  |      |     |     |     | 4.0  |      |   |   |     |      |     |   |   |   | 0.0  |                                                                                                                                | 
| Jackson National Life Insurance Company                    | A-4801-P et al                                       | 2016-12-29T00:00:00 |      |      | 0.0 |     |     | 0.0  |      |   |   |     |      |     |   |   |   |      | Purchased Reassure America Life Insurance Company in 2012 Allied Life Insurance Company ceased marketing these plans on 1-1-97 | 
```