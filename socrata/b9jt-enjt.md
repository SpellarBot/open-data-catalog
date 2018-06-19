# Available contracts in King County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/term-contract-log) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/b9jt-enjt) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/b9jt-enjt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/b9jt-enjt/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | b9jt-enjt |
| Name | Available contracts in King County |
| Category | Operations |
| Tags | procurement, contracts |
| Created | 2016-02-18T23:27:45Z |
| Publication Date | 2017-04-07T18:34:43Z |

## Description

Piggyback on a King County contract. Local government may cooperate with other localities on a basis of mutual advantage in providing services and facilities in a manner that will accord best with geographic, economic, population and other factors influencing the needs and development of local communities.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| Yes      | series tag  | vendor_name    | VENDOR NAME    | text      | text        |
| Yes      | series tag  | cpa_number     | CPA NUMBER     | text      | text        |
| Yes      | series tag  | last_updated   | LAST UPDATED   | text      | text        |
| Yes      | time        | expirationdate | EXPIRATIONDATE | text      | text        |
| Yes      | series tag  | commodity      | COMMODITY      | text      | text        |
| Yes      | series tag  | agency         | AGENCY         | text      | text        |
| Yes      | series tag  | contract       | CONTRACT       | text      | text        |
| Yes      | series tag  | green          | Green          | checkbox  | checkbox    |
```

## Time Field

```ls
Value = expirationdate
Format & Zone = MM/dd/yyyy
```

## Data Commands

```ls
series e:b9jt-enjt d:2019-12-14T00:00:00.000Z t:commodity="REFLECTIVE SIGN SHEETING; ROAD SIGN MATERIALS" t:contract=http://www.kingcounty.gov/~/media/depts/finance/procurement/termlog/5824594.pdf t:agency=UNIVERSAL t:last_updated=1/19/2016 t:cpa_number=5824594 t:vendor_name="3M COMPANY" m:row_number.b9jt-enjt=1

series e:b9jt-enjt d:2019-12-14T00:00:00.000Z t:commodity="SIGN SHEETING MATERIALS" t:contract=http://www.kingcounty.gov/~/media/depts/finance/procurement/termlog/5831776.pdf t:agency=DOT-FLEET t:last_updated=2/12/2016 t:cpa_number=5831776 t:vendor_name="3M COMPANY" m:row_number.b9jt-enjt=2

series e:b9jt-enjt d:2017-04-30T00:00:00.000Z t:commodity="CRANE RENTAL SERVICES WITH OPERATOR" t:contract=http://www.kingcounty.gov/~/media/depts/finance/procurement/termlog/5438905.pdf t:agency=UNIVERSAL t:last_updated=1/29/2016 t:cpa_number=5438905 t:vendor_name="A MILLICAN CRANE SERVICE INC" m:row_number.b9jt-enjt=3
```

## Meta Commands

```ls
metric m:row_number.b9jt-enjt p:long l:"Row Number"

entity e:b9jt-enjt l:"Available contracts in King County" t:url=https://data.kingcounty.gov/api/views/b9jt-enjt

property e:b9jt-enjt t:meta.view v:id=b9jt-enjt v:category=Operations v:averageRating=0 v:name="Available contracts in King County"

property e:b9jt-enjt t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:b9jt-enjt t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| vendor_name                     | cpa_number | last_updated | expirationdate | commodity                                                     | agency      | contract                                                                        | green | 
| =============================== | ========== | ============ | ============== | ============================================================= | =========== | =============================================================================== | ===== | 
| 3M COMPANY                      | 5824594    | 1/19/2016    | 12/14/2019     | REFLECTIVE SIGN SHEETING; ROAD SIGN MATERIALS                 | UNIVERSAL   | http://www.kingcounty.gov/~/media/depts/finance/procurement/termlog/5824594.pdf |       | 
| 3M COMPANY                      | 5831776    | 2/12/2016    | 12/14/2019     | SIGN SHEETING MATERIALS                                       | DOT-FLEET   | http://www.kingcounty.gov/~/media/depts/finance/procurement/termlog/5831776.pdf |       | 
| A MILLICAN CRANE SERVICE INC    | 5438905    | 1/29/2016    | 4/30/2017      | CRANE RENTAL SERVICES WITH OPERATOR                           | UNIVERSAL   | http://www.kingcounty.gov/~/media/depts/finance/procurement/termlog/5438905.pdf |       | 
| A.G.A. DISTRIBUTION SPECIALISTS | 5839682    | 4/8/2016     | 3/2/2021       | SURE POWER VDC CONVERTERS                                     | TRANSIT     | http://www.kingcounty.gov/~/media/depts/finance/procurement/termlog/5839682.pdf |       | 
| AAA FIRE AND SAFETY, INC.       | 5485632    | 1/29/2016    | 8/31/2017      | ANSUL BRAND PARTS AND SERVICES                                | DNRP        | http://www.kingcounty.gov/~/media/depts/finance/procurement/termlog/5485632.pdf |       | 
| ABACUS SERVICE CORPORATION      | 5889152    | 2/17/2017    | 10/2/2017      | TEMPORARY STAFFING SERVICES, INFORMATION TECHNOLOGY PERSONNEL | UNIVERSAL   | http://www.kingcounty.gov/~/media/depts/finance/procurement/termlog/5889152.pdf |       | 
| ABRA INC                        | 5580621    | 1/29/2016    | 5/31/2018      | AUTOBODY REPAIR SERVICES ON VANPOOL VEHICLES                  | DOT-TRANSIT | http://www.kingcounty.gov/~/media/depts/finance/procurement/termlog/5580621.pdf |       | 
| ACADEMY OF LANGUAGES LLC        | 5491417    | 1/29/2016    | 9/16/2017      | TRANSLATION SERVICES                                          | UNIVERSAL   | http://www.kingcounty.gov/~/media/depts/finance/procurement/termlog/5491417.pdf |       | 
| ACF WEST INC                    | 5542042    | 1/29/2016    | 2/5/2018       | SAND BAGS, UNFILLED                                           | UNIVERSAL   | http://www.kingcounty.gov/~/media/depts/finance/procurement/termlog/5542042.pdf |       | 
| ACF WEST INC                    | 5906730    | 12/23/2016   | 12/31/2018     | GEOSYNTHETIC & EROSION CONTROL MATERIALS                      | UNIVERSAL   | http://www.kingcounty.gov/~/media/depts/finance/procurement/termlog/5906730.pdf |       | 
```