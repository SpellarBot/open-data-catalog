# Combined Fund Drive Donations 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/combined-fund-drive-donations-2014) |
| Metadata | [Link](https://data.wa.gov/api/views/m5pi-uads) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/m5pi-uads/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/m5pi-uads/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | m5pi-uads |
| Name | Combined Fund Drive Donations 2014 |
| Attribution | Combined Fund Drive Administered by the Washington Secretary of State |
| Tags | combine fund drive, donations, charity, 2014 |
| Created | 2015-05-18T18:36:25Z |
| Publication Date | 2015-05-19T20:17:24Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | charity_code    | Charity Code    | text      | number      |
| Yes      | series tag     | charity_name    | Charity Name    | text      | text        |
| Yes      | numeric metric | donations_total | Donations Total | money     | money       |
| Yes      | series tag     | zip_code        | Zip Code        | text      | number      |
| Yes      | series tag     | contact_email   | Contact Email   | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:m5pi-uads d:2014-01-01T00:00:00.000Z t:charity_name="Planned Parenthood Federation of America" t:charity_code=1481041 m:donations_total=17026.37

series e:m5pi-uads d:2014-01-01T00:00:00.000Z t:charity_name="Injured Marine Semper Fi Fund" t:charity_code=1479167 t:contact_email=theresa@charitystateregistration.org t:zip_code=92055 m:donations_total=1018.63

series e:m5pi-uads d:2014-01-01T00:00:00.000Z t:charity_name="Milgard School of Business Fund for Excellence" t:charity_code=1479537 m:donations_total=1007.67
```

## Meta Commands

```ls
metric m:donations_total p:double l:"Donations Total" t:dataTypeName=money

entity e:m5pi-uads l:"Combined Fund Drive Donations 2014" t:attribution="Combined Fund Drive Administered by the Washington Secretary of State" t:url=https://data.wa.gov/api/views/m5pi-uads

property e:m5pi-uads t:meta.view d:2017-06-09T13:58:48.503Z v:id=m5pi-uads v:attributionLink=http://www.cfd.wa.gov/ v:averageRating=0 v:name="Combined Fund Drive Donations 2014" v:attribution="Combined Fund Drive Administered by the Washington Secretary of State"

property e:m5pi-uads t:meta.view.license d:2017-06-09T13:58:48.503Z v:name="Public Domain"

property e:m5pi-uads t:meta.view.owner d:2017-06-09T13:58:48.503Z v:id=2iur-ynm8 v:profileImageUrlMedium=/api/users/2iur-ynm8/profile_images/THUMB v:profileImageUrlLarge=/api/users/2iur-ynm8/profile_images/LARGE v:screenName=ryan.leisinger v:profileImageUrlSmall=/api/users/2iur-ynm8/profile_images/TINY v:displayName=ryan.leisinger

property e:m5pi-uads t:meta.view.tableauthor d:2017-06-09T13:58:48.503Z v:id=2iur-ynm8 v:profileImageUrlMedium=/api/users/2iur-ynm8/profile_images/THUMB v:profileImageUrlLarge=/api/users/2iur-ynm8/profile_images/LARGE v:screenName=ryan.leisinger v:profileImageUrlSmall=/api/users/2iur-ynm8/profile_images/TINY v:roleName=administrator v:displayName=ryan.leisinger
```

## Top Records

```ls
| charity_code | charity_name                                   | donations_total | zip_code | contact_email                        | 
| ============ | ============================================== | =============== | ======== | ==================================== | 
| 1481041      | Planned Parenthood Federation of America       | 17026.37        |          |                                      | 
| 1479167      | Injured Marine Semper Fi Fund                  | 1018.63         | 92055    | theresa@charitystateregistration.org | 
| 1479537      | Milgard School of Business Fund for Excellence | 1007.67         |          |                                      | 
| 315560       | Civil Air Patrol - Washington Wing             | 426.98          | 98438    | shannon.swick@wawg.cap.gov           | 
| 1480778      | The A21 Campaign                               | 339.09          |          |                                      | 
| 314988       | Land Trust Alliance                            | 311.66          | 20036    | info@lta.org                         | 
| 489795       | Youth Services Of Kittitas County Inc          | 285.12          |          | crystal.church@kccn.org              | 
| 1480493      | Inland Northwest Honor Flight                  | 283.85          |          |                                      | 
| 1480045      | Christ Clinic/Christ Kitchen                   | 282.27          |          |                                      | 
| 1478392      | Food Providers Of America                      | 241.84          |          |                                      | 
```