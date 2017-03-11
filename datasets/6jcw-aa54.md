# Medical Examiner--2009 Manner Death, by Gender

## Dataset

* [Dataset URL](https://datacatalog.cookcountyil.gov/api/views/6jcw-aa54/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/medical-examiner-2009-manner-death-by-gender-a77be)
* [Metadata URL](https://datacatalog.cookcountyil.gov/api/views/6jcw-aa54)
* Id = 6jcw-aa54
* Name = Medical Examiner--2009 Manner Death, by Gender
* Attribution = Cook County Medical Examiner
* Category = Healthcare
* Created = 2011-09-22T17:22:24Z
* Publication Date = 2014-10-27T16:38:44Z
* Rows Updated = 2014-10-27T16:38:39Z

## Description



## Columns

```ls
| Name            | Field Name      | Data Type | Render Type | Schema Type    | Included | 
| =============== | =============== | ========= | =========== | ============== | ======== | 
| updated_at      | :updated_at     | meta_data | meta_data   | time           | No       | 
| MANNER OF DEATH | manner_of_death | text      | text        | series tag     | Yes      | 
| SEX             | sex_            | text      | text        | series tag     | Yes      | 
| COUNT           | count           | number    | number      | numeric metric | Yes      | 
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
series e:6jcw-aa54 d:2011-09-22T10:22:25.000Z t:manner_of_death=ACCIDENT t:sex_=MALE m:count=995

series e:6jcw-aa54 d:2011-09-22T10:22:25.000Z t:manner_of_death=ACCIDENT t:sex_=FEMALE m:count=439

series e:6jcw-aa54 d:2011-09-22T10:22:25.000Z t:manner_of_death=HOMICIDE t:sex_=MALE m:count=535
```

## Meta Commands

```ls
metric m:count p:integer l:COUNT t:dataTypeName=number

entity e:6jcw-aa54 l:"Medical Examiner--2009 Manner Death, by Gender" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/6jcw-aa54

property e:6jcw-aa54 t:meta.view d:2017-03-07T22:41:39.186Z v:id=6jcw-aa54 v:category=Healthcare v:averageRating=0 v:name="Medical Examiner--2009 Manner Death, by Gender" v:attribution="Cook County Medical Examiner"

property e:6jcw-aa54 t:meta.view.license d:2017-03-07T22:41:39.186Z v:name="Public Domain"

property e:6jcw-aa54 t:meta.view.owner d:2017-03-07T22:41:39.186Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:6jcw-aa54 t:meta.view.tableauthor d:2017-03-07T22:41:39.186Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```