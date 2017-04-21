# Bike Fix It

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bike-fix-it) |
| Metadata | [Link](https://data.austintexas.gov/api/views/cvnz-fq2z) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/cvnz-fq2z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/cvnz-fq2z/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | cvnz-fq2z |
| Name | Bike Fix It |
| Attribution | City of Austin |
| Created | 2015-08-27T15:21:19Z |
| Publication Date | 2015-08-27T15:27:08Z |

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | recreation_centers | Recreation Centers | text      | text        |
| Yes      | series tag  | zip_code           | Zip Code           | text      | text        |
| Yes      | series tag  | phone_number       | Phone Number       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cvnz-fq2z d:2015-08-27T08:21:44.000Z t:phone_number="(512) 974-9011" t:zip_code=78746 t:recreation_centers="Danny G. McBeth Recreation Center" m:row_number.cvnz-fq2z=1

series e:cvnz-fq2z d:2015-08-27T08:21:44.000Z t:phone_number="(512) 453-7765" t:zip_code=78751 t:recreation_centers="Hancock Recreation Center" m:row_number.cvnz-fq2z=2

series e:cvnz-fq2z d:2015-08-27T08:21:44.000Z t:phone_number="(512) 974-5680" t:zip_code=78722 t:recreation_centers="Alamo Recreation" m:row_number.cvnz-fq2z=3
```

## Meta Commands

```ls
metric m:row_number.cvnz-fq2z p:long l:"Row Number"

entity e:cvnz-fq2z l:"Bike Fix It" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/cvnz-fq2z

property e:cvnz-fq2z t:meta.view v:id=cvnz-fq2z v:attributionLink=http://austintexas.gov/fixit v:averageRating=0 v:name="Bike Fix It" v:attribution="City of Austin"

property e:cvnz-fq2z t:meta.view.license v:name="Public Domain"

property e:cvnz-fq2z t:meta.view.owner v:id=wpqw-45f6 v:screenName=Betty v:displayName=Betty

property e:cvnz-fq2z t:meta.view.tableauthor v:id=wpqw-45f6 v:screenName=Betty v:roleName=editor v:displayName=Betty
```

## Top Records

```ls
| :updated_at | recreation_centers                         | zip_code | phone_number   | 
| =========== | ========================================== | ======== | ============== | 
| 1440663704  | Danny G. McBeth Recreation Center          | 78746    | (512) 974-9011 | 
| 1440663704  | Hancock Recreation Center                  | 78751    | (512) 453-7765 | 
| 1440663704  | Alamo Recreation                           | 78722    | (512) 974-5680 | 
| 1440663704  | PARD Annex                                 | 78705    |                | 
| 1440663704  | Metz Recreation Center                     | 78702    | (512) 478-8716 | 
| 1440663704  | Montopolis Recreation Center               | 78741    | (512) 978-2300 | 
| 1440663704  | Austin Recreation Center                   | 78701    | (512) 476-5662 | 
| 1440663704  | Lorraine "Grandma" Camacho Activity Center | 78702    | (512) 391-1863 | 
| 1440663704  | Turner-Roberts Recreation Center           | 78724    | (512) 978-2690 | 
| 1440663704  | Pickfair Community Center                  | 78750    | (512) 401-8119 | 
```