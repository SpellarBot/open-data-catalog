# Green Light Program - Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/green-light-program-fiscal-year-2012-2f803) |
| Metadata | [Link](https://data.oregon.gov/api/views/5chb-zqsr) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/5chb-zqsr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/5chb-zqsr/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 5chb-zqsr |
| Name | Green Light Program - Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2013-02-07T18:16:50Z |
| Publication Date | 2013-02-07T18:17:59Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | time           | effective_date   | Effective Date   | text      | text        |
| Yes      | series tag     | vendor_name      | Vendor Name      | text      | text        |
| Yes      | numeric metric | amount_of_rebate | Amount of Rebate | money     | money       |
| Yes      | series tag     | outcomes         | Outcomes         | text      | text        |
| No       |                | address          | Address          | text      | text        |
```

## Time Field

```ls
Value = effective_date
Format & Zone = MM/dd/yy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:5chb-zqsr d:2012-03-05T00:00:00.000Z t:outcomes="At Large spent over $1million in Oregon on television commercial production in 2011.  Of that amount, over $450,00 was spent on Oregon Qualified Labor." t:vendor_name="AT LARGE FILMS INC" m:amount_of_rebate=27713.11

series e:5chb-zqsr d:2012-02-17T00:00:00.000Z t:outcomes="Bent Image Lab spent over $3.5million on Oregon Qualified Labor Expenses in 2011." t:vendor_name="BENT IMAGE LAB LLC" m:amount_of_rebate=218412.35

series e:5chb-zqsr d:2012-03-13T00:00:00.000Z t:outcomes="Central Planning spent over $1million in Oregon on television production in 2011.  Of that amount, $104,649 was spent on Oregon Qualified Labor." t:vendor_name="CENTRAL PLANNING LLC" m:amount_of_rebate=6455.82
```

## Meta Commands

```ls
metric m:amount_of_rebate p:double l:"Amount of Rebate" t:dataTypeName=money

entity e:5chb-zqsr l:"Green Light Program - Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/5chb-zqsr

property e:5chb-zqsr t:meta.view v:id=5chb-zqsr v:category="Revenue & Expense" v:averageRating=0 v:name="Green Light Program - Fiscal Year 2012"

property e:5chb-zqsr t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:5chb-zqsr t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| effective_date | vendor_name                  | amount_of_rebate | outcomes                                                                                                                                                                   | address                                                                   | 
| ============== | ============================ | ================ | ========================================================================================================================================================================== | ========================================================================= | 
| 3/5/12         | AT LARGE FILMS INC           | 27713.11         | At Large spent over $1million in Oregon on television commercial production in 2011. Of that amount, over $450,00 was spent on Oregon Qualified Labor.                     | 807 NE Couch Street, Portland, OP, 97232                                  | 
| 2/17/12        | BENT IMAGE LAB LLC           | 218412.35        | Bent Image Lab spent over $3.5million on Oregon Qualified Labor Expenses in 2011.                                                                                          | 2729 SE Division Street, Portland, OR, 97202                              | 
| 3/13/12        | CENTRAL PLANNING LLC         | 6455.82          | Central Planning spent over $1million in Oregon on television production in 2011. Of that amount, $104,649 was spent on Oregon Qualified Labor.                            | 3800 NE Sandy Blvd., #207 Portland, OR 90232                              | 
| 9/13/11        | ELECTRIC BT PRODUCTIONS INC  | 2766.08          | Electric BT Productions Inc. spent over $1million in Oregon on the production "Brain Trust". This payment was a residual amount left over from previous fiscal year audit. | 940 N. Highland Ave, Suite A, LA, CA, 90038                               | 
| 3/13/12        | FUNNELBOX INC                | 74097.39         | Funnelbox Inc. spent over $1.3 million on Oregon Qualified Labor in 2011.                                                                                                  | 712 Main Street, Oregon City, OR                                          | 
| 4/27/12        | LEVERAGE 4 PRODUCTIONS INC   | 682517.00        | Leverage 4 Productions spent over $11million on Oregon Qualified Labor in 2011.                                                                                            | 940 N. Highland Ave, Suite A, LA, CA, 90038                               | 
| 6/5/12         | LEVERAGE 5 PRODUCTIONS INC.  | 100131.60        | Leverage 5 Productions spent over $1.65million on Oregon Qualified Labor in 1st Quarter 2012.                                                                              | 940 N. Highland Ave, Suite A, LA, CA, 90038                               | 
| 3/13/12        | LAIKA INC                    | 2693283          | LAIKA Inc. spent over $43.4million on Oregon Qualified Labor Expenses in 2011 and the first six months of 2012.                                                            | 22990 NW Bennett Street, Hillsboro, OR,97124                              | 
| 3/20/12        | RESPOND2 COMMUNICATIONS INC  | 172354.86        | Respond 2 spent over $3.6million on Oregon Qualified Labor.                                                                                                                | 207 NW Park, Portland, OR, 97209                                          | 
| 3/21/12        | SIDESTREET ENTERTAINMENT INC | 54649.41         | Sidestreet spent over $1million in Oregon on the television series "Portlandia". Of that amount over $850,000 was spent on Oregon Qualified Labor.                         | 100 Universal City Plaza, Bld. 5166, 3rd Floor, Universal City, CA, 91608 | 
```