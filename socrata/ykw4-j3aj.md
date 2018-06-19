# Declared Dangerous Dogs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/declared-dangerous-dogs) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ykw4-j3aj) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ykw4-j3aj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ykw4-j3aj/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ykw4-j3aj |
| Name | Declared Dangerous Dogs |
| Attribution | City of Austin |
| Category | Public Safety |
| Tags | dangerous, dogs, public safety, pets, animals |
| Created | 2012-08-30T18:27:24Z |
| Publication Date | 2016-05-09T19:37:13Z |

## Description

No declared Dangerous Dog in the City of Austin and Travis County should ever be running at large. They are court ordered to be restrained at all times and should be wearing a large tag identifying them as a Dangerous Dog. They have attacked in the past. The owner is required to provide $100,000 in financial responsibility. If they attack again the court could order them put to sleep.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | first_name         | First Name         | text      | text        |
| Yes      | series tag  | last_name          | Last Name          | text      | text        |
| No       |             | address            | Address            | text      | text        |
| Yes      | series tag  | zip_code           | Zip Code           | text      | number      |
| Yes      | series tag  | description_of_dog | Description of Dog | text      | text        |
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
series e:ykw4-j3aj d:2016-05-05T11:53:19.000Z t:first_name=Lorena t:zip_code=78713 t:description_of_dog="?Mulligan,? neutered male, Brindle Bullmastiff" t:last_name=Zuniga m:row_number.ykw4-j3aj=1

series e:ykw4-j3aj d:2016-05-05T11:53:36.000Z t:first_name=Maria t:zip_code=78744 t:description_of_dog="?Tiny,? male, tan and white Boxer mix" t:last_name=Davila m:row_number.ykw4-j3aj=2

series e:ykw4-j3aj d:2016-05-05T11:53:36.000Z t:first_name=Matthew t:zip_code=78739 t:description_of_dog="""Charlie"" neutered male, black and white Labrador Retriever mix" t:last_name=Rafacz m:row_number.ykw4-j3aj=3
```

## Meta Commands

```ls
metric m:row_number.ykw4-j3aj p:long l:"Row Number"

entity e:ykw4-j3aj l:"Declared  Dangerous Dogs" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/ykw4-j3aj

property e:ykw4-j3aj t:meta.view v:id=ykw4-j3aj v:category="Public Safety" v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="Declared  Dangerous Dogs" v:attribution="City of Austin"

property e:ykw4-j3aj t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:ykw4-j3aj t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| :updated_at | first_name | last_name    | address                | zip_code | description_of_dog                                              | 
| =========== | ========== | ============ | ====================== | ======== | =============================================================== | 
| 1462449199  | Lorena     | Zuniga       | 3415 Sweetgum Trc      | 78713    | ?Mulligan,? neutered male, Brindle Bullmastiff                  | 
| 1462449216  | Maria      | Davila       | 4420 Dovemeadow Dr     | 78744    | ?Tiny,? male, tan and white Boxer mix                           | 
| 1462449216  | Matthew    | Rafacz       | 7400 Espira Drive      | 78739    | "Charlie" neutered male, black and white Labrador Retriever mix | 
| 1462449216  | Jeff       | Crawford     | 9321 Bavaria Ln.       | 78749    | "Nala" spayed female, white and brown brindle Pit Bull mix      | 
| 1462449216  | Katherine  | Maloney      | 11504 Murcia Dr        | 78759    | ?Lexie,? female, white and black Pit Bull                       | 
| 1462449216  | Jack       | Barnett      | 13101 Winding Creek Rd | 78736    | "Holly" Spayed female, white Labrador/Pitbull mix               | 
| 1462449216  | Carla      | Ward         | 7128 Mumruffin Ln      | 78754    | ?Lincoln,? male, fawn and white Pit Bull Terrier                | 
| 1462449216  | Melissa    | Spellmann    | 2815 Oak Ridge Dr      | 78669    | ?Sparkles,? spayed female, Brindle Plott Hound mix              | 
| 1462449216  | Ruth       | Delong-Pyron | 903 Vincent Place      | 78660    | "Missy," Spayed Female, red/white Pitbull mix                   | 
| 1462449216  | Ronald     | Vasey        | 4704 Sunridge Ct       | 78741    | ?Rita,? female, brown Australian Shepherd                       | 
```