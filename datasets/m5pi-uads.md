# Combined Fund Drive Donations 2014

## Dataset

* [Dataset URL](https://data.wa.gov/api/views/m5pi-uads/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/combined-fund-drive-donations-2014)
* [Metadata URL](https://data.wa.gov/api/views/m5pi-uads)
* Id = m5pi-uads
* Name = Combined Fund Drive Donations 2014
* Attribution = Combined Fund Drive Administered by the Washington Secretary of State
* [Attribution Link](http://www.cfd.wa.gov/)
* Tags = [combine fund drive, donations, charity, 2014]
* Created = 2015-05-18T18:36:25Z
* Publication Date = 2015-05-19T20:17:24Z
* Rows Updated = 2015-05-19T07:20:57Z

## Description



## Columns

```ls
| Name            | Field Name      | Data Type | Render Type | Schema Type    | Included | 
| =============== | =============== | ========= | =========== | ============== | ======== | 
| updated_at      | :updated_at     | meta_data | meta_data   | time           | No       | 
| Charity Code    | charity_code    | text      | number      | series tag     | Yes      | 
| Charity Name    | charity_name    | text      | text        | series tag     | Yes      | 
| Donations Total | donations_total | money     | money       | numeric metric | Yes      | 
| Zip Code        | zip_code        | number    | number      | numeric metric | Yes      | 
| Contact Email   | contact_email   | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:m5pi-uads d:2015-05-18T11:36:30.000Z t:charity_name="Planned Parenthood Federation of America" t:charity_code=1481041 m:donations_total=17026.37

series e:m5pi-uads d:2015-05-18T11:36:31.000Z t:charity_name="Injured Marine Semper Fi Fund" t:charity_code=1479167 t:contact_email=theresa@charitystateregistration.org m:zip_code=92055 m:donations_total=1018.63

series e:m5pi-uads d:2015-05-18T11:36:31.000Z t:charity_name="Milgard School of Business Fund for Excellence" t:charity_code=1479537 m:donations_total=1007.67
```

## Meta Commands

```ls
metric m:zip_code l:"Zip Code" t:dataTypeName=number

entity e:m5pi-uads l:"Combined Fund Drive Donations 2014" t:attribution="Combined Fund Drive Administered by the Washington Secretary of State" t:url=https://data.wa.gov/api/views/m5pi-uads

property e:m5pi-uads t:meta.view d:2017-03-07T20:16:20.564Z v:id=m5pi-uads v:attributionLink=http://www.cfd.wa.gov/ v:averageRating=0 v:name="Combined Fund Drive Donations 2014" v:attribution="Combined Fund Drive Administered by the Washington Secretary of State"

property e:m5pi-uads t:meta.view.license d:2017-03-07T20:16:20.564Z v:name="Public Domain"

property e:m5pi-uads t:meta.view.owner d:2017-03-07T20:16:20.564Z v:id=2iur-ynm8 v:profileImageUrlMedium=/api/users/2iur-ynm8/profile_images/THUMB v:profileImageUrlLarge=/api/users/2iur-ynm8/profile_images/LARGE v:screenName=ryan.leisinger v:profileImageUrlSmall=/api/users/2iur-ynm8/profile_images/TINY v:roleName=administrator v:displayName=ryan.leisinger

property e:m5pi-uads t:meta.view.tableauthor d:2017-03-07T20:16:20.564Z v:id=2iur-ynm8 v:profileImageUrlMedium=/api/users/2iur-ynm8/profile_images/THUMB v:profileImageUrlLarge=/api/users/2iur-ynm8/profile_images/LARGE v:screenName=ryan.leisinger v:profileImageUrlSmall=/api/users/2iur-ynm8/profile_images/TINY v:roleName=administrator v:displayName=ryan.leisinger
```