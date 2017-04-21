# Bag Tax

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bag-tax) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/xnjh-vgc4) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/xnjh-vgc4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/xnjh-vgc4/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | xnjh-vgc4 |
| Name | Bag Tax |
| Attribution | Montgomery County, MD |
| Category | Finance/Tax/Property |
| Tags | bag, tax |
| Created | 2016-10-25T22:25:18Z |
| Publication Date | 2016-10-27T21:21:39Z |

## Description

On May 3, 2011 Montgomery County passed legislation (Bill 8-11) that places a five-cent charge on each paper or plastic carryout bag provided by retail establishments in the County to customers at the point of sale, pickup or delivery. Retailers retain 1 cent of each 5 cents for the bags they sell a customer.? This dataset represents information that has been captured since this law went into effect. Update Frequency - Monthly

## Columns

```ls
| Included | Schema Type    | Field Name           | Name             | Data Type     | Render Type   |
| ======== | ============== | ==================== | ================ | ============= | ============= |
| Yes      | numeric metric | filingid             | File ID          | number        | number        |
| Yes      | series tag     | account              | Account          | text          | text          |
| Yes      | time           | datefrom             | Date From        | calendar_date | calendar_date |
| No       |                | dateto               | Date To          | calendar_date | calendar_date |
| Yes      | numeric metric | bagcount             | Bag Count        | number        | number        |
| Yes      | numeric metric | amountcollected      | Amount Collected | money         | money         |
| Yes      | numeric metric | amountdue            | Amount Due       | money         | money         |
| Yes      | numeric metric | amountretained       | Amount Retained  | money         | money         |
| No       |                | createdate           | Create Date      | calendar_date | calendar_date |
| Yes      | series tag     | vendorname           | Vendor Name      | text          | text          |
| Yes      | series tag     | city                 | City             | text          | text          |
| No       |                | physicaladdressstate | State            | text          | text          |
| No       |                | physicaladdresszip   | Zip code         | text          | text          |
```

## Time Field

```ls
Value = datefrom
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = dateto,createdate,physicaladdressstate,physicaladdresszip
```

## Data Commands

```ls
series e:xnjh-vgc4 d:2012-03-01T00:00:00.000Z t:vendorname="Brooklyn Deli Potomac" t:account=000610 t:city=Potomac m:amountcollected=28.35 m:amountretained=5.67 m:bagcount=567 m:filingid=976 m:amountdue=22.68

series e:xnjh-vgc4 d:2012-04-01T00:00:00.000Z t:vendorname="ASADO MD" t:account=000417 t:city=Rockville m:amountcollected=224.7 m:amountretained=44.94 m:bagcount=4494 m:filingid=1859 m:amountdue=179.76

series e:xnjh-vgc4 d:2012-03-01T00:00:00.000Z t:vendorname="ALDO US INC" t:account=000335 m:amountcollected=36.8 m:amountretained=7.36 m:bagcount=736 m:filingid=1073 m:amountdue=29.44
```

## Meta Commands

```ls
metric m:filingid p:integer l:"File ID" d:"Unique transaction number that is generated when a payment is submitted by a vendor." t:dataTypeName=number

metric m:bagcount p:integer l:"Bag Count" d:"The total number of bags that a vendor has issued to a customer." t:dataTypeName=number

metric m:amountcollected p:double l:"Amount Collected" d:"The amount that a vendor has paid for the filing period." t:dataTypeName=money

metric m:amountdue p:double l:"Amount Due" d:"The amount that a vendor is required to pay based on the number of bags that were issued." t:dataTypeName=money

metric m:amountretained p:double l:"Amount Retained" d:"AmountRetained = The amount that a vendor is eligible to retain based on the number of bags that were issued." t:dataTypeName=money

entity e:xnjh-vgc4 l:"Bag Tax" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/xnjh-vgc4

property e:xnjh-vgc4 t:meta.view v:id=xnjh-vgc4 v:category=Finance/Tax/Property v:averageRating=0 v:name="Bag Tax" v:attribution="Montgomery County, MD"

property e:xnjh-vgc4 t:meta.view.license v:name="Public Domain"

property e:xnjh-vgc4 t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:xnjh-vgc4 t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| filingid | account | datefrom            | dateto              | bagcount | amountcollected | amountdue | amountretained | createdate          | vendorname                  | city          | physicaladdressstate | physicaladdresszip | 
| ======== | ======= | =================== | =================== | ======== | =============== | ========= | ============== | =================== | =========================== | ============= | ==================== | ================== | 
| 976      | 000610  | 2012-03-01T00:00:00 | 2012-03-31T00:00:00 | 567      | 28.35           | 22.68     | 5.67           | 2012-04-09T00:00:00 | Brooklyn Deli Potomac       | Potomac       | MD                   | 20854              | 
| 1859     | 000417  | 2012-04-01T00:00:00 | 2012-05-30T00:00:00 | 4494     | 224.7           | 179.76    | 44.94          | 2012-05-25T00:00:00 | ASADO MD                    | Rockville     | MD                   | 20852              | 
| 1073     | 000335  | 2012-03-01T00:00:00 | 2012-03-31T00:00:00 | 736      | 36.8            | 29.44     | 7.36           | 2012-04-13T00:00:00 | ALDO US INC                 |               | DE                   | 19801              | 
| 2332     | 000643  | 2012-05-01T00:00:00 | 2012-05-31T00:00:00 | 2528     | 126.4           | 101.12    | 25.28          | 2012-06-22T00:00:00 | The Finish Line Inc         |               | IN                   | 46235              | 
| 13046    | 000223  | 2014-02-01T00:00:00 | 2014-02-28T00:00:00 | 8848     | 442.4           | 353.92    | 88.48          | 2014-03-19T00:00:00 | Sears Roebuck & Co          |               | IL                   | 60179              | 
| 23558    | 000331  | 2015-11-01T00:00:00 | 2015-11-30T00:00:00 | 5576     | 278.8           | 223.04    | 55.76          | 2015-12-18T00:00:00 | VIE DE FRANCE YAMAZAKI. INC |               | VA                   | 22182              | 
| 17637    | 000448  | 2014-11-01T00:00:00 | 2014-11-30T00:00:00 | 1726     | 86.3            | 69.04     | 17.26          | 2014-12-22T00:00:00 | MARYVALE MARKET INC         | Rockville     | MD                   | 20850              | 
| 10088    | 000643  | 2013-08-01T00:00:00 | 2013-08-31T00:00:00 | 896      | 44.8            | 35.84     | 8.96           | 2013-09-24T00:00:00 | The Finish Line Inc         |               | IN                   | 46235              | 
| 11266    | 000859  | 2013-11-01T00:00:00 | 2013-11-30T00:00:00 | 177      | 8.85            | 7.08      | 1.77           | 2013-12-10T00:00:00 | Candy Man LLC               | Silver Spring | MD                   | 20902              | 
| 5169     | 000204  | 2012-11-01T00:00:00 | 2012-11-30T00:00:00 | 8441     | 422.05          | 337.64    | 84.41          | 2012-12-17T00:00:00 | Eckerd Corporation          |               | PA                   | 17319              | 
```