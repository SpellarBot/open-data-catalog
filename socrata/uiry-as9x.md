# Alcohol Beverage Outlet (ABO) - Active Licenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/alcohol-beverage-outlet-abo-active-licenses) |
| Metadata | [Link](https://data.nola.gov/api/views/uiry-as9x) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/uiry-as9x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/uiry-as9x/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | uiry-as9x |
| Name | Alcohol Beverage Outlet (ABO) - Active Licenses |
| Attribution | City of New Orleans ? Bureau of Revenue |
| Category | Economy and Workforce |
| Tags | new orleans, alcohol, abo |
| Created | 2014-09-17T20:32:35Z |
| Publication Date | 2017-02-15T20:48:49Z |

## Description

Alcohol Beverage Outlet licenses within the City of New Orleans. Data provided by Bureau of Revenue.

## Columns

```ls
| Included | Schema Type | Field Name      | Name         | Data Type | Render Type |
| ======== | =========== | =============== | ============ | ========= | =========== |
| No       | time        | :updated_at     | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | trade_name      | BusinessName | text      | text        |
| No       |             | address         | Address      | text      | text        |
| Yes      | series tag  | suite           | Suite        | text      | text        |
| Yes      | series tag  | city            | City         | text      | text        |
| Yes      | series tag  | state           | State        | text      | text        |
| Yes      | series tag  | zip             | Zip          | text      | text        |
| Yes      | series tag  | occupation_code | BusinessType | text      | text        |
| Yes      | series tag  | owner_name      | OwnerName    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:uiry-as9x d:2017-02-15T20:53:16.000Z t:occupation_code="1105 - FULL SVC RESTAURANTS (TABLE SERVICE)" t:zip=70116 t:owner_name="THE ITALIAN BARREL LLC" t:state=LA t:trade_name="THE ITALIAN BARREL" t:city="NEW ORLEANS" m:row_number.uiry-as9x=1

series e:uiry-as9x d:2017-02-15T20:53:16.000Z t:occupation_code="2802 - BREWERIES" t:zip=70125 t:owner_name="WAYWARD OWL BREWING COMPANY, LLC" t:state=LA t:trade_name="WAYWARD OWL BREWING COMPANY, LLC" t:city="NEW ORLEANS" m:row_number.uiry-as9x=2

series e:uiry-as9x d:2017-02-15T20:53:16.000Z t:occupation_code="1106 - GROCERY (EXC CONVENIENCE) STORES" t:zip=70114-4340 t:owner_name="ALGIERS CENTRAL,INC" t:state=LA t:trade_name="ALGIERS CENTRAL MARKET" t:city="NEW ORLEANS" m:row_number.uiry-as9x=3
```

## Meta Commands

```ls
metric m:row_number.uiry-as9x p:long l:"Row Number"

entity e:uiry-as9x l:"Alcohol Beverage Outlet (ABO) - Active Licenses" t:attribution="City of New Orleans ? Bureau of Revenue" t:url=https://data.nola.gov/api/views/uiry-as9x

property e:uiry-as9x t:meta.view v:id=uiry-as9x v:category="Economy and Workforce" v:averageRating=0 v:name="Alcohol Beverage Outlet (ABO) - Active Licenses" v:attribution="City of New Orleans ? Bureau of Revenue"

property e:uiry-as9x t:meta.view.owner v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:uiry-as9x t:meta.view.tableauthor v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:roleName=administrator v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:uiry-as9x t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| :updated_at | trade_name                       | address               | suite | city        | state | zip        | occupation_code                              | owner_name                       | 
| =========== | ================================ | ===================== | ===== | =========== | ===== | ========== | ============================================ | ================================ | 
| 1487191996  | THE ITALIAN BARREL               | 430 BARRACKS ST       |       | NEW ORLEANS | LA    | 70116      | 1105 - FULL SVC RESTAURANTS (TABLE SERVICE)  | THE ITALIAN BARREL LLC           | 
| 1487191996  | WAYWARD OWL BREWING COMPANY, LLC | 3940 THALIA ST        |       | NEW ORLEANS | LA    | 70125      | 2802 - BREWERIES                             | WAYWARD OWL BREWING COMPANY, LLC | 
| 1487191996  | ALGIERS CENTRAL MARKET           | 840 TECHE ST          |       | NEW ORLEANS | LA    | 70114-4340 | 1106 - GROCERY (EXC CONVENIENCE) STORES      | ALGIERS CENTRAL,INC              | 
| 1487191996  | MONDO                            | 900 HARRISON AVE      |       | NEW ORLEANS | LA    | 70124      | 1105 - FULL SVC RESTAURANTS (TABLE SERVICE)  | MONDO RESTAURANT, LLC            | 
| 1487191996  | PEPPERONI'S CAFE                 | 8123 HAMPSON ST       |       | NEW ORLEANS | LA    | 70118      | 1105 - FULL SVC RESTAURANTS (TABLE SERVICE)  | ESCOHYDE INC                     | 
| 1487191996  | RED EYE GRILL                    | 852 S PETERS ST       |       | NEW ORLEANS | LA    | 70130      | 1126 - DRINKING PLACES (ALCOHOLIC BEVERAGES) | RED EYE GRILL, INC               | 
| 1487191996  | UGLY DOG SALOON & BBQ            | 401 ANDREW HIGGINS ST |       | NEW ORLEANS | LA    | 70130      | 1105 - FULL SVC RESTAURANTS (TABLE SERVICE)  | SALOON PROMOTIONS INC            | 
| 1487191996  | FREY SMOKED MEAT                 | 4141 BIENVILLE ST     |       | NEW ORLEANS | LA    | 70119      | 1105 - FULL SVC RESTAURANTS (TABLE SERVICE)  | FREY SMOKED MEAT                 | 
| 1487191996  | STANLEY                          | 547 SAINT ANN ST      |       | NEW ORLEANS | LA    | 70116      | 1105 - FULL SVC RESTAURANTS (TABLE SERVICE)  | STANLEY OF NEW ORLEANS, LLC      | 
| 1487191996  | BAIE ROUGE                       | 4128 MAGAZINE ST      |       | NEW ORLEANS | LA    | 70115      | 1105 - FULL SVC RESTAURANTS (TABLE SERVICE)  | BAIE ROUGE,LLC                   | 
```