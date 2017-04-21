# Pari-mutuel Grants To Municipalities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pari-mutuel-grants-to-municipalities) |
| Metadata | [Link](https://data.ct.gov/api/views/59ps-catp) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/59ps-catp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/59ps-catp/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 59ps-catp |
| Name | Pari-mutuel Grants To Municipalities |
| Attribution | CT Dept of Consumer Protection |
| Category | Government |
| Tags | pari-mutuel, otb, teletheater |
| Created | 2014-09-17T14:26:13Z |
| Publication Date | 2014-09-17T14:34:11Z |

## Description

In accordance with the provisions of CGS Section12-575(m), grants to municipalities are paid to towns which host Off-Track Betting and Pari-mutuel operations.

## Columns

```ls
| Included | Schema Type    | Field Name                                             | Name                                                     | Data Type | Render Type |
| ======== | ============== | ====================================================== | ======================================================== | ========= | =========== |
| No       | time           | :updated_at                                            | updated_at                                               | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year                                            | Fiscal Year                                              | text      | text        |
| Yes      | numeric metric | total_otb                                              | Total OTB                                                | money     | money       |
| Yes      | numeric metric | otb_branches_telephone_betting                         | OTB Branches & Telephone Betting                         | money     | money       |
| Yes      | numeric metric | otb_teletheaters                                       | OTB Teletheaters                                         | money     | money       |
| Yes      | numeric metric | total_parimutuel                                       | Total Parimutuel                                         | money     | money       |
| Yes      | numeric metric | pari_mutuel_jai_alai                                   | Pari-mutuel Jai Alai                                     | money     | money       |
| Yes      | numeric metric | pari_mutuel_greyhound_racing                           | Pari-mutuel Greyhound Racing                             | money     | money       |
| Yes      | numeric metric | total_municipal_payments_from_otb_pari_mutuel_wagering | Total Municipal Payments from OTB & Pari-mutuel Wagering | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:59ps-catp d:2014-09-17T07:33:42.000Z t:fiscal_year=1979 m:total_otb=292645 m:otb_branches_telephone_betting=292645 m:total_municipal_payments_from_otb_pari_mutuel_wagering=3163144 m:total_parimutuel=2870499 m:otb_teletheaters=0 m:pari_mutuel_jai_alai=2368389 m:pari_mutuel_greyhound_racing=502110

series e:59ps-catp d:2014-09-17T07:33:42.000Z t:fiscal_year=1980 m:total_otb=410667 m:otb_branches_telephone_betting=278136 m:total_municipal_payments_from_otb_pari_mutuel_wagering=3061722 m:total_parimutuel=2651055 m:otb_teletheaters=132531 m:pari_mutuel_jai_alai=2197692 m:pari_mutuel_greyhound_racing=453363

series e:59ps-catp d:2014-09-17T07:33:42.000Z t:fiscal_year=1981 m:total_otb=445094 m:otb_branches_telephone_betting=263131 m:total_municipal_payments_from_otb_pari_mutuel_wagering=3016648 m:total_parimutuel=2571554 m:otb_teletheaters=181963 m:pari_mutuel_jai_alai=2096112 m:pari_mutuel_greyhound_racing=475442
```

## Meta Commands

```ls
metric m:total_otb p:integer l:"Total OTB" t:dataTypeName=money

metric m:otb_branches_telephone_betting p:double l:"OTB Branches & Telephone Betting" t:dataTypeName=money

metric m:otb_teletheaters p:integer l:"OTB Teletheaters" t:dataTypeName=money

metric m:total_parimutuel p:integer l:"Total Parimutuel" t:dataTypeName=money

metric m:pari_mutuel_jai_alai p:integer l:"Pari-mutuel Jai Alai" t:dataTypeName=money

metric m:pari_mutuel_greyhound_racing p:integer l:"Pari-mutuel Greyhound Racing" t:dataTypeName=money

metric m:total_municipal_payments_from_otb_pari_mutuel_wagering p:integer l:"Total Municipal Payments from OTB & Pari-mutuel Wagering" t:dataTypeName=money

entity e:59ps-catp l:"Pari-mutuel Grants To Municipalities" t:attribution="CT Dept of Consumer Protection" t:url=https://data.ct.gov/api/views/59ps-catp

property e:59ps-catp t:meta.view v:id=59ps-catp v:category=Government v:attributionLink=http://www.ct.gov/dcp/lib/dcp/pdf/gaming/grants_to_municipalities14.pdf v:averageRating=0 v:name="Pari-mutuel Grants To Municipalities" v:attribution="CT Dept of Consumer Protection"

property e:59ps-catp t:meta.view.license v:name="Public Domain"

property e:59ps-catp t:meta.view.owner v:id=ewkk-db5a v:screenName=WilliamR v:displayName=WilliamR

property e:59ps-catp t:meta.view.tableauthor v:id=ewkk-db5a v:screenName=WilliamR v:roleName=editor v:displayName=WilliamR
```

## Top Records

```ls
| :updated_at | fiscal_year | total_otb | otb_branches_telephone_betting | otb_teletheaters | total_parimutuel | pari_mutuel_jai_alai | pari_mutuel_greyhound_racing | total_municipal_payments_from_otb_pari_mutuel_wagering | 
| =========== | =========== | ========= | ============================== | ================ | ================ | ==================== | ============================ | ====================================================== | 
| 1410939222  | 1979        | 292645    | 292645                         | 0                | 2870499          | 2368389              | 502110                       | 3163144                                                | 
| 1410939222  | 1980        | 410667    | 278136                         | 132531           | 2651055          | 2197692              | 453363                       | 3061722                                                | 
| 1410939222  | 1981        | 445094    | 263131                         | 181963           | 2571554          | 2096112              | 475442                       | 3016648                                                | 
| 1410939222  | 1982        | 470236    | 265657                         | 204579           | 2780299          | 2259098              | 521201                       | 3250535                                                | 
| 1410939222  | 1983        | 469034    | 264539                         | 204495           | 2855649          | 2283440              | 572209                       | 3324683                                                | 
| 1410939222  | 1984        | 756795    | 410703                         | 346092           | 2897883          | 2311193              | 586690                       | 3654678                                                | 
| 1410939222  | 1985        | 750577    | 399622                         | 350955           | 2990578          | 2398070              | 592508                       | 3741155                                                | 
| 1410939222  | 1986        | 763615    | 414065                         | 349550           | 3011434          | 2415730              | 595704                       | 3775049                                                | 
| 1410939222  | 1987        | 1382211   | 776311                         | 605900           | 3428091          | 2551119              | 876972                       | 4810302                                                | 
| 1410939222  | 1988        | 2028253   | 1142652                        | 885601           | 2996521          | 2134758              | 861763                       | 5024774                                                | 
```