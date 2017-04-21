# Iowa Property Casualty Insurance Premiums and Losses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-property-casualty-insurance-premiums-and-losses) |
| Metadata | [Link](https://data.iowa.gov/api/views/inub-pueg) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/inub-pueg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/inub-pueg/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | inub-pueg |
| Name | Iowa Property Casualty Insurance Premiums and Losses |
| Attribution | Iowa Department of Commerce, Insurance Division |
| Category | Economy |
| Tags | insurance, premiums, losses, property, casualty |
| Created | 2014-12-02T14:49:35Z |
| Publication Date | 2016-10-05T16:43:50Z |

## Description

Dataset contains information on premiums written, losses paid and taxes paid for property casualty insurance companies licensed to operate in the State of Iowa by year and line of insurance.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name              | Data Type | Render Type |
| ======== | ============== | ================ | ================= | ========= | =========== |
| Yes      | time           | datayear         | Year              | number    | number      |
| Yes      | numeric metric | chapter          | Iowa Code Chapter | number    | number      |
| Yes      | series tag     | cstate           | State             | text      | text        |
| Yes      | series tag     | cname            | Company Name      | text      | text        |
| Yes      | series tag     | description      | Line of Insurance | text      | text        |
| Yes      | numeric metric | premiums_written | Premiums Written  | money     | money       |
| Yes      | numeric metric | losses_paid      | Losses Paid       | money     | money       |
| Yes      | numeric metric | taxes_paid       | Taxes Paid        | money     | money       |
| Yes      | series tag     | cocode           | NAIC Number       | text      | text        |
| Yes      | series tag     | active_code      | Iowa Company Code | text      | text        |
```

## Time Field

```ls
Value = datayear
Format & Zone = yyyy
```

## Data Commands

```ls
series e:inub-pueg d:2015-01-01T00:00:00.000Z t:active_code=2074 t:description=Credit t:cocode=37273 t:cstate=IL t:cname="AXIS Insurance Company" m:chapter=515.48 m:taxes_paid=0 m:losses_paid=0 m:premiums_written=0

series e:inub-pueg d:2015-01-01T00:00:00.000Z t:active_code=1199 t:description=Fire t:cocode=10464 t:cstate=SC t:cname="Canal Insurance Company" m:chapter=515.48 m:taxes_paid=0 m:losses_paid=0 m:premiums_written=0

series e:inub-pueg d:2015-01-01T00:00:00.000Z t:active_code=2961 t:description=Fire t:cocode=33111 t:cstate=MI t:cname="MHA Insurance Company" m:chapter=515.48 m:taxes_paid=0 m:losses_paid=0 m:premiums_written=0
```

## Meta Commands

```ls
metric m:chapter p:double l:"Iowa Code Chapter" d:"State of Iowa Code Chapter that Insurance Company is Licensed Under" t:dataTypeName=number

metric m:premiums_written p:integer l:"Premiums Written" t:dataTypeName=money

metric m:losses_paid p:integer l:"Losses Paid" t:dataTypeName=money

metric m:taxes_paid p:integer l:"Taxes Paid" t:dataTypeName=money

entity e:inub-pueg l:"Iowa Property Casualty Insurance Premiums and Losses" t:attribution="Iowa Department of Commerce, Insurance Division" t:url=https://data.iowa.gov/api/views/inub-pueg

property e:inub-pueg t:meta.view v:id=inub-pueg v:category=Economy v:averageRating=0 v:name="Iowa Property Casualty Insurance Premiums and Losses" v:attribution="Iowa Department of Commerce, Insurance Division"

property e:inub-pueg t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:inub-pueg t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| datayear | chapter | cstate | cname                                 | description               | premiums_written | losses_paid | taxes_paid | cocode | active_code | 
| ======== | ======= | ====== | ===================================== | ========================= | ================ | =========== | ========== | ====== | =========== | 
| 2015     | 515.48  | IL     | AXIS Insurance Company                | Credit                    | 0                | 0           | 0          | 37273  | 2074        | 
| 2015     | 515.48  | SC     | Canal Insurance Company               | Fire                      | 0                | 0           | 0          | 10464  | 1199        | 
| 2015     | 515.48  | MI     | MHA Insurance Company                 | Fire                      | 0                | 0           | 0          | 33111  | 2961        | 
| 2015     | 515.48  | IA     | MyCompass, Inc.                       | Credit                    | 0                | 0           | 0          | 15831  | 3205        | 
| 2015     | 515.48  | IL     | AGCS Marine Insurance Company         | Fire                      | 0                | 0           | 0          | 22837  | 2253        | 
| 2015     | 515.48  | WI     | 1st Auto & Casualty Insurance Company | Fire                      | 0                | 0           | 0          | 44725  | 2894        | 
| 2015     | 515.48  | WI     | 1st Auto & Casualty Insurance Company | Allied Lines              | 0                | 0           | 0          | 44725  | 2894        | 
| 2015     | 515.48  | WI     | 1st Auto & Casualty Insurance Company | Multiple Peril Crop       | 0                | 0           | 0          | 44725  | 2894        | 
| 2015     | 515.48  | WI     | 1st Auto & Casualty Insurance Company | Federal Flood             | 0                | 0           | 0          | 44725  | 2894        | 
| 2015     | 515.48  | WI     | 1st Auto & Casualty Insurance Company | Farmowners Multiple Peril | 74037            | 72263       | 1147       | 44725  | 2894        | 
```