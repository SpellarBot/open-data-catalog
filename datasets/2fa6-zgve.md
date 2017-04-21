# USDA Certified Organic Growers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/usda-certified-organic-growers) |
| Metadata | [Link](https://data.ct.gov/api/views/2fa6-zgve) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/2fa6-zgve/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/2fa6-zgve/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 2fa6-zgve |
| Name | USDA Certified Organic Growers |
| Attribution | Department of Agriculture |
| Category | Environment and Natural Resources |
| Tags | organic, farms, usda, doag |
| Created | 2014-05-09T18:32:13Z |
| Publication Date | 2016-05-16T13:46:34Z |

## Description

The following is a list Certified Organic Farmers in Connecticut. These farms have successfully passed an inspection from a USDA National Organic Program Accredited Inspection Agency. 

For more information please visit the USDA National Organic Program website:  http://www.ams.usda.gov/AMSv1.0/nop

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | certifyingagent  | CertifyingAgent  | text      | text        |
| Yes      | numeric metric | certno           | CertNo           | number    | number      |
| Yes      | series tag     | primaryscope     | Scope            | text      | text        |
| Yes      | series tag     | operationname    | OperationName    | text      | text        |
| No       |                | physicaladdress  | PhysicalAddress  | text      | text        |
| Yes      | series tag     | zipcode          | ZipCode          | text      | text        |
| Yes      | series tag     | county           | Town             | text      | text        |
| Yes      | series tag     | productsproduced | ProductsProduced | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = physicaladdress
```

## Data Commands

```ls
series e:2fa6-zgve d:2016-05-13T10:48:31.000Z t:certifyingagent="Baystate Organic Certifiers" t:operationname="Hamlet Hill Farm" t:productsproduced="Berries, Flowers, Fruit Trees, Herbs, Vegetables" t:county="East Woodstock" t:zipcode=06244 t:primaryscope=CROPS m:certno=15047

series e:2fa6-zgve d:2016-05-13T10:48:31.000Z t:certifyingagent="Baystate Organic Certifiers" t:operationname="Salmon Kill Farm" t:productsproduced="Hay, Vegetables, Herbs, Flowers, Fruit, Seedlings" t:county=Salisbury t:zipcode=16042 t:primaryscope=CROPS m:certno=16042

series e:2fa6-zgve d:2016-05-13T10:48:31.000Z t:certifyingagent="Baystate Organic Certifiers" t:operationname="Wayne's Organic Garden" t:productsproduced="Greenhouse Tomatoes, Herbs, Sedlings, Strawberries, Vegetables" t:county=Oneco t:zipcode=06373-0154 t:primaryscope=CROPS m:certno=2092
```

## Meta Commands

```ls
metric m:certno p:long l:CertNo t:dataTypeName=number

entity e:2fa6-zgve l:"USDA Certified Organic Growers" t:attribution="Department of Agriculture" t:url=https://data.ct.gov/api/views/2fa6-zgve

property e:2fa6-zgve t:meta.view v:id=2fa6-zgve v:category="Environment and Natural Resources" v:attributionLink="http://www.ct.gov/doag/cwp/view.asp?a=3243&Q=522502&PM=1" v:averageRating=0 v:name="USDA Certified Organic Growers" v:attribution="Department of Agriculture"

property e:2fa6-zgve t:meta.view.license v:name="Public Domain"

property e:2fa6-zgve t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:2fa6-zgve t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | certifyingagent                                   | certno  | primaryscope | operationname                 | physicaladdress               | zipcode    | county         | productsproduced                                                                                  | 
| =========== | ================================================= | ======= | ============ | ============================= | ============================= | ========== | ============== | ================================================================================================= | 
| 1463136511  | Baystate Organic Certifiers                       | 15047   | CROPS        | Hamlet Hill Farm              | 40 Hamlet Hill Rd             | 06244      | East Woodstock | Berries, Flowers, Fruit Trees, Herbs, Vegetables                                                  | 
| 1463136511  | Baystate Organic Certifiers                       | 16042   | CROPS        | Salmon Kill Farm              | 317 Salmon Kill Rd.           | 16042      | Salisbury      | Hay, Vegetables, Herbs, Flowers, Fruit, Seedlings                                                 | 
| 1463136511  | Baystate Organic Certifiers                       | 2092    | CROPS        | Wayne's Organic Garden        | 1080 Plainfield Pike          | 06373-0154 | Oneco          | Greenhouse Tomatoes, Herbs, Sedlings, Strawberries, Vegetables                                    | 
| 1463136511  | Oregon Tilth Certified Organic                    |         | HANDLING     | Guida Seibert Dairy Co.       | PO Box 2110                   | 06050      | New Britain    | Cream, Low Fat (1%) Milk, Non Fat (skim) Milk, Reduced Fat (2%) Milk, Whole Milk                  | 
| 1463136570  | Northeast Organic Farming Association of New York | 2014006 | CROPS        | Sub Edge Farm                 | 199 Town Farm Road            | 06032      | Farmington     | Garlic, Hay, Pasture, Slicing Tomatoes, Transplants                                               | 
| 1463136511  | Quality Assurance International                   |         | HANDLING     | Nature's Pure Beverage Co LLC | Two Corporate Drive Suite 136 | 06484      | Shelton        | Cherry Jubilee Cola (8 oz and 16 oz), Cola (8 oz and 16 oz), French Vanilla Cola (8 oz and 16 oz) | 
| 1463136569  | Baystate Organic Certifiers                       | 12142   | CROPS        | Blueberry Hill Organic Farm   | 314 Margaret Henry Rd.        | 06239      | Danielson      | Blueberries, Herbs, Seedlings, Vegetables                                                         | 
| 1463136569  | Baystate Organic Certifiers                       | 8030    | CROPS        | Koster Keunen LLC             | 1021 Echo Lake Rd.            | 06795      | Watertown      | Wax                                                                                               | 
| 1463136569  | Baystate Organic Certifiers                       | 3041    | CROPS        | Starry Night Farm             | 368 Mistuxet Ave.             | 06378      | Stonington     | Vegetables                                                                                        | 
| 1463136569  | Baystate Organic Certifiers                       | 6053    | CROPS        | Valchris Farm                 | 400 Ridge Hill Rd.            | 06370      | Oakdale        | Vegetables                                                                                        | 
```