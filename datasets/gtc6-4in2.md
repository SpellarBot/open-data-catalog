# Table 11.11 SOCIAL SECURITY BENEFICIARIES AND BENEFITS PAID 1991 TO 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-11-11-social-security-beneficiaries-and-benefits-paid-1991-to-2012) |
| Metadata | [Link](https://data.hawaii.gov/api/views/gtc6-4in2) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/gtc6-4in2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/gtc6-4in2/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | gtc6-4in2 |
| Name | Table 11.11 SOCIAL SECURITY BENEFICIARIES AND BENEFITS PAID 1991 TO 2013 |
| Attribution | Department of Economi Davelopment and Tourism |
| Category | Economic Development |
| Tags | social security |
| Created | 2012-08-27T21:09:54Z |
| Publication Date | 2015-10-21T20:49:48Z |

## Description

* December data.  Previous to 2006 based on 10-percent samples, 2006 and after based on Master Beneficiary Record, 100 percent data								
* Previous to 2007 includes special age-72 beneficiaries.								
    Source:  U.S. Social Security Administration, Office of Policy Data, Annual Statistical Supplement,								
Please go to the DBEDT Databook site, http://hawaii.gov/dbedt/info/economic/databook,  for the complete data source.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                     | Data Type | Render Type |
| ======== | ============== | ===================================== | ======================================== | ========= | =========== |
| Yes      | time           | year                                  | Year                                     | number    | text        |
| Yes      | numeric metric | number_of_beneficiaries               | Number of beneficiaries                  | number    | number      |
| Yes      | numeric metric | monthly_benefits_thousand             | Monthly benefits ($thousand)             | money     | money       |
| Yes      | numeric metric | estimated_total_benefits_paid_million | Estimated total benefits paid ($million) | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gtc6-4in2 d:1991-01-01T00:00:00.000Z m:number_of_beneficiaries=151390 m:estimated_total_benefits_paid_million=971 m:monthly_benefits_thousand=85182

series e:gtc6-4in2 d:1992-01-01T00:00:00.000Z m:number_of_beneficiaries=154950 m:estimated_total_benefits_paid_million=1041 m:monthly_benefits_thousand=90840

series e:gtc6-4in2 d:1993-01-01T00:00:00.000Z m:number_of_beneficiaries=158370 m:estimated_total_benefits_paid_million=1106 m:monthly_benefits_thousand=95812
```

## Meta Commands

```ls
metric m:number_of_beneficiaries p:integer l:"Number of beneficiaries" t:dataTypeName=number

metric m:monthly_benefits_thousand p:integer l:"Monthly benefits ($thousand)" t:dataTypeName=money

metric m:estimated_total_benefits_paid_million p:integer l:"Estimated total benefits paid ($million)" t:dataTypeName=money

entity e:gtc6-4in2 l:"Table 11.11 SOCIAL SECURITY BENEFICIARIES AND BENEFITS PAID 1991 TO 2013" t:attribution="Department of Economi Davelopment and Tourism" t:url=https://data.hawaii.gov/api/views/gtc6-4in2

property e:gtc6-4in2 t:meta.view v:id=gtc6-4in2 v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt/info/economic/databook v:averageRating=0 v:name="Table 11.11 SOCIAL SECURITY BENEFICIARIES AND BENEFITS PAID 1991 TO 2013" v:attribution="Department of Economi Davelopment and Tourism"

property e:gtc6-4in2 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:gtc6-4in2 t:meta.view.owner v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:displayName="Yang-Seon Kim"

property e:gtc6-4in2 t:meta.view.tableauthor v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:roleName=editor v:displayName="Yang-Seon Kim"
```

## Top Records

```ls
| year | number_of_beneficiaries | monthly_benefits_thousand | estimated_total_benefits_paid_million | 
| ==== | ======================= | ========================= | ===================================== | 
| 1991 | 151390                  | 85182                     | 971                                   | 
| 1992 | 154950                  | 90840                     | 1041                                  | 
| 1993 | 158370                  | 95812                     | 1106                                  | 
| 1994 | 161840                  | 101506                    | 1169                                  | 
| 1995 | 168020                  | 107600                    | 1243                                  | 
| 1996 | 169300                  | 113990                    | 1317                                  | 
| 1997 | 172050                  | 119266                    | 1385                                  | 
| 1998 | 174850                  | 124320                    | 1453                                  | 
| 1999 | 179150                  | 131387                    | 1517                                  | 
| 2000 | 184140                  | 142159                    | 1628                                  | 
```