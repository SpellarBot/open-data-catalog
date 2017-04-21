# Active Real Estate Salespersons and Brokers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-real-estate-salespersons-and-brokers) |
| Metadata | [Link](https://data.ny.gov/api/views/yg7h-zjbf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/yg7h-zjbf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/yg7h-zjbf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | yg7h-zjbf |
| Name | Active Real Estate Salespersons and Brokers |
| Attribution | New York State Department of State (DOS) |
| Category | Economic Development |
| Tags | real estate, brokers, salespersons |
| Created | 2015-12-10T19:31:42Z |
| Publication Date | 2017-04-20T10:26:45Z |

## Description

This data contains active Real Estate Salesperson and Broker Licenses from New York State Department of State (DOS).  Each line will be either an individual or business licensee which holds business address and license number information.  If the license type is an individual, the business name that the individual works for will be listed.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | business_name           | Business Name           | text          | text          |
| No       |             | business_address_1      | Business Address 1      | text          | text          |
| No       |             | business_address_2      | Business Address 2      | text          | text          |
| Yes      | series tag  | business_city           | Business City           | text          | text          |
| Yes      | series tag  | business_state          | Business State          | text          | text          |
| Yes      | series tag  | business_zip            | Business Zip            | text          | text          |
| Yes      | series tag  | county                  | County                  | text          | text          |
| Yes      | series tag  | license_holder_name     | License Holder Name     | text          | text          |
| Yes      | time        | license_expiration_date | License Expiration Date | calendar_date | calendar_date |
| Yes      | series tag  | license_number          | License Number          | text          | text          |
| Yes      | series tag  | license_type            | License Type            | text          | text          |
```

## Time Field

```ls
Value = license_expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = business_address_1,business_address_2
```

## Data Commands

```ls
series e:yg7h-zjbf d:2018-08-25T00:00:00.000Z t:business_name="COLDWELL BANKER RESIDENTIAL BROKERAGE" t:license_holder_name="ASHBY JO ELLEN" t:license_type="ASSOCIATE BROKER" t:county=NONE t:license_number=10301213690 t:business_zip=10956 t:business_city="NEW CITY" t:business_state=NY m:row_number.yg7h-zjbf=1

series e:yg7h-zjbf d:2019-03-03T00:00:00.000Z t:business_name="COLDWELL BANKER RESIDENTIAL BROKERAGE" t:license_holder_name="AUER JANET" t:license_type="ASSOCIATE BROKER" t:county=NONE t:license_number=30AU0537489 t:business_zip=10570 t:business_city=PLEASANTVILLE t:business_state=NY m:row_number.yg7h-zjbf=2

series e:yg7h-zjbf d:2018-01-08T00:00:00.000Z t:business_name="COLDWELL BANKER RESIDENTIAL BROKERAGE" t:license_holder_name="AVANT YVONNE D" t:license_type="ASSOCIATE BROKER" t:county=NONE t:license_number=30AV0966278 t:business_zip=10605 t:business_city="WHITE PLAINS" t:business_state=NY m:row_number.yg7h-zjbf=3
```

## Meta Commands

```ls
metric m:row_number.yg7h-zjbf p:long l:"Row Number"

entity e:yg7h-zjbf l:"Active Real Estate Salespersons and Brokers" t:attribution="New York State Department of State (DOS)" t:url=https://data.ny.gov/api/views/yg7h-zjbf

property e:yg7h-zjbf t:meta.view v:id=yg7h-zjbf v:category="Economic Development" v:attributionLink=http://www.dos.ny.gov/licensing/ v:averageRating=0 v:name="Active Real Estate Salespersons and Brokers" v:attribution="New York State Department of State (DOS)"

property e:yg7h-zjbf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:yg7h-zjbf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| business_name                         | business_address_1 | business_address_2 | business_city    | business_state | business_zip | county | license_holder_name | license_expiration_date | license_number | license_type     | 
| ===================================== | ================== | ================== | ================ | ============== | ============ | ====== | =================== | ======================= | ============== | ================ | 
| COLDWELL BANKER RESIDENTIAL BROKERAGE | 170 N MAIN ST      |                    | NEW CITY         | NY             | 10956        | NONE   | ASHBY JO ELLEN      | 2018-08-25T00:00:00     | 10301213690    | ASSOCIATE BROKER | 
| COLDWELL BANKER RESIDENTIAL BROKERAGE | 1 WASHINGTON AVE   |                    | PLEASANTVILLE    | NY             | 10570        | NONE   | AUER JANET          | 2019-03-03T00:00:00     | 30AU0537489    | ASSOCIATE BROKER | 
| COLDWELL BANKER RESIDENTIAL BROKERAGE | 278 MAMARONECK AVE |                    | WHITE PLAINS     | NY             | 10605        | NONE   | AVANT YVONNE D      | 2018-01-08T00:00:00     | 30AV0966278    | ASSOCIATE BROKER | 
| COLDWELL BANKER RESIDENTIAL BROKERAGE | 366 UNDERHILL AVE  |                    | YORKTOWN HEIGHTS | NY             | 10598        | NONE   | BALL ADRIAN G       | 2018-07-30T00:00:00     | 30BA0944454    | ASSOCIATE BROKER | 
| COLDWELL BANKER RESIDENTIAL BROKERAGE | 366 UNDERHILL AVE  |                    | YORKTOWN HEIGHTS | NY             | 10598        | NONE   | BARNES SUSAN        | 2017-12-09T00:00:00     | 30BA0959488    | ASSOCIATE BROKER | 
| COLDWELL BANKER RESIDENTIAL BROKERAGE | 170 N MAIN ST      |                    | NEW CITY         | NY             | 10956        | NONE   | BERMAN CAROL C      | 2017-04-29T00:00:00     | 10301211596    | ASSOCIATE BROKER | 
| COLDWELL BANKER RESIDENTIAL BROKERAGE | 170 N MAIN ST      |                    | NEW CITY         | NY             | 10956        | NONE   | BERMAN STELLA       | 2018-08-18T00:00:00     | 30BE0942745    | ASSOCIATE BROKER | 
| COLDWELL BANKER RESIDENTIAL BROKERAGE | 366 UNDERHILL AVE  |                    | YORKTOWN HEIGHTS | NY             | 10598        | NONE   | BODNAR BARBARA E    | 2018-06-29T00:00:00     | 10301201833    | ASSOCIATE BROKER | 
| COLDWELL BANKER RESIDENTIAL BROKERAGE | 170 N MAIN ST      |                    | NEW CITY         | NY             | 10956        | NONE   | BUDOFF DONNA        | 2017-11-19T00:00:00     | 30BU0851856    | ASSOCIATE BROKER | 
| COLDWELL BANKER RESIDENTIAL BROKERAGE | 170 N MAIN ST      |                    | NEW CITY         | NY             | 10956        | NONE   | BUFFA TERESA A      | 2018-04-20T00:00:00     | 30BU0872575    | ASSOCIATE BROKER | 
```