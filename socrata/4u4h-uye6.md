# Dhs-training-county-contacts-2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dhs-training-county-contacts-2) |
| Metadata | [Link](https://data.oregon.gov/api/views/4u4h-uye6) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/4u4h-uye6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/4u4h-uye6/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 4u4h-uye6 |
| Name | Dhs-training-county-contacts-2 |
| Created | 2015-04-08T17:03:38Z |
| Publication Date | 2015-04-08T18:23:06Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type      | Render Type    |
| ======== | =========== | =========== | ========== | ============== | ============== |
| No       | time        | :updated_at | updated_at | meta_data      | meta_data      |
| Yes      | series tag  | county      | County     | drop_down_list | drop_down_list |
| Yes      | series tag  | name        | Name       | text           | text           |
| Yes      | series tag  | phone       | Phone      | text           | text           |
| Yes      | series tag  | email       | Email      | email          | email          |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4u4h-uye6 d:2015-04-08T11:03:48.000Z t:phone=971-673-1837 t:email=melissa.masserant@state.or.us t:county=2hiy-qzsa t:name="Melissa Masserant" m:row_number.4u4h-uye6=1

series e:4u4h-uye6 d:2015-04-08T11:04:25.000Z t:phone=971-673-1838 t:email=irene.m.phipps@state.or.us t:county=2hiy-qzsa t:name="Irene Phipps (Espanol)" m:row_number.4u4h-uye6=2

series e:4u4h-uye6 d:2015-04-08T10:55:08.000Z t:phone=503-378-4784 t:email=erma.s.brundidge@state.or.us t:county=5xq3-zteq t:name="Erma Brundidge" m:row_number.4u4h-uye6=3
```

## Meta Commands

```ls
metric m:row_number.4u4h-uye6 p:long l:"Row Number"

entity e:4u4h-uye6 l:Dhs-training-county-contacts-2 t:url=https://data.oregon.gov/api/views/4u4h-uye6

property e:4u4h-uye6 t:meta.view v:id=4u4h-uye6 v:averageRating=0 v:name=Dhs-training-county-contacts-2

property e:4u4h-uye6 t:meta.view.owner v:id=r4w9-b2zg v:profileImageUrlMedium=/api/users/r4w9-b2zg/profile_images/THUMB v:profileImageUrlLarge=/api/users/r4w9-b2zg/profile_images/LARGE v:screenName="Mark Tinsley" v:profileImageUrlSmall=/api/users/r4w9-b2zg/profile_images/TINY v:displayName="Mark Tinsley"

property e:4u4h-uye6 t:meta.view.tableauthor v:id=r4w9-b2zg v:profileImageUrlMedium=/api/users/r4w9-b2zg/profile_images/THUMB v:profileImageUrlLarge=/api/users/r4w9-b2zg/profile_images/LARGE v:screenName="Mark Tinsley" v:profileImageUrlSmall=/api/users/r4w9-b2zg/profile_images/TINY v:roleName=editor v:displayName="Mark Tinsley"
```

## Top Records

```ls
| :updated_at | county    | name                   | phone              | email                           | 
| =========== | ========= | ====================== | ================== | =============================== | 
| 1428491028  | 2hiy-qzsa | Melissa Masserant      | 971-673-1837       | melissa.masserant@state.or.us   | 
| 1428491065  | 2hiy-qzsa | Irene Phipps (Espanol) | 971-673-1838       | irene.m.phipps@state.or.us      | 
| 1428490508  | 5xq3-zteq | Erma Brundidge         | 503-378-4784       | erma.s.brundidge@state.or.us    | 
| 1428490516  | v7gv-5hf9 | Monica Gilbertson      | 541-481-9482 x 224 | monica.l.gilbertson@state.or.us | 
| 1428490521  | 2hiy-qzsa | Robin Blood            | 503-872-5584       | robin.blood@state.or.us         | 
| 1428490531  | xamu-izux | Sue Lissman            | 541-565-3014       | susan.lissman@state.or.us       | 
| 1428490537  | padb-zte7 | Sandra Koops           | 503-842-5571 x 306 | Sandra.D.Koops@state.or.us      | 
| 1428490542  | u2nj-x6ne | Lidwinner Machado      | 541-966-0855       | lidwinner.machado@state.or.us   | 
| 1428490562  | znra-zxe9 | Tracy Gower            | 541-506-5222       | tracy.l.gower@state.or.us       | 
| 1428490567  | m7jt-2hzr | Madeline Hodge         | 503-277-6673       | madeline.hodge@state.or.us      | 
```