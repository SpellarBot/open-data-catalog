# Youth Tractor Safety Training in Oregon

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/youth-tractor-safety-training-in-oregon-b2ec9) |
| Metadata | [Link](https://data.oregon.gov/api/views/njpd-rii4) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/njpd-rii4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/njpd-rii4/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | njpd-rii4 |
| Name | Youth Tractor Safety Training in Oregon |
| Attribution | Oregon Department of Agriculture |
| Category | Natural Resources |
| Tags | tractor, training |
| Created | 2013-12-02T15:56:32Z |
| Publication Date | 2014-12-22T22:47:10Z |

## Description

List of tractor safety training providers

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | county            | County            | text      | text        |
| Yes      | series tag  | location_2        | Location          | html      | html        |
| Yes      | series tag  | facility          | Facility          | text      | text        |
| Yes      | series tag  | training_provider | Training provider | text      | text        |
| Yes      | series tag  | contact_name      | Contact name      | text      | text        |
| Yes      | series tag  | contact_phone     | Contact phone     | html      | html        |
| Yes      | series tag  | email_link        | Contact email     | email     | email       |
| Yes      | series tag  | description       | Description       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:njpd-rii4 d:2014-06-18T10:00:23.000Z t:location_2="Harrisburg, Oregon" t:facility="Harrisburg High School" t:county=Linn t:description="Harrisburg has a tractor school each May.  The school has been in operation for 25-30 years and is supported by the area farmers and equipment dealers.  It runs Tuesday through Friday evenings and all day on Saturday.  Sign up is through the High School office." t:contact_phone=<p>541-995-6626</p> t:contact_name="Earl Cavin" t:training_provider="Harrisburg High School" t:email_link=earl.cavin@harrisburg.k12.or.us m:row_number.njpd-rii4=1

series e:njpd-rii4 d:2014-06-18T10:00:24.000Z t:location_2="Imbler, Oregon" t:facility="Imbler High School" t:county=Union t:description="Imbler HS Agriculture Education Program offers the course as a part of the Introductions to Agriculture Mechanics couse in the Spring Term of each year. The Unit of study is conducted from Mid-April to End of May. Offered to any HS (9-12) grade students at no cost. Program utilizes the 4-H Tractor Safety Book, and requires passing all Unit Tests, Driving/Maneuvering Test, and Written Final." t:contact_phone=<p>541-534-5331</p> t:contact_name="Jim Cant" t:training_provider="Imbler High School" t:email_link=jdcant@imbler.k12.or.us m:row_number.njpd-rii4=2

series e:njpd-rii4 d:2014-06-18T10:06:34.000Z t:location_2="St. Helens, Oregon" t:facility=Unknown t:county=Columbia t:description="This class is located at the Columbia County Extension office for class training and at the Fairgrounds for practice." t:contact_name="Woody Davis" t:training_provider=4-H/Extension t:email_link=woody.davis@oregonstate.edu m:row_number.njpd-rii4=3
```

## Meta Commands

```ls
metric m:row_number.njpd-rii4 p:long l:"Row Number"

entity e:njpd-rii4 l:"Youth Tractor Safety Training in Oregon" t:attribution="Oregon Department of Agriculture" t:url=https://data.oregon.gov/api/views/njpd-rii4

property e:njpd-rii4 t:meta.view v:id=njpd-rii4 v:category="Natural Resources" v:attributionLink=http://oregon.gov/ODA v:averageRating=0 v:name="Youth Tractor Safety Training in Oregon" v:attribution="Oregon Department of Agriculture"

property e:njpd-rii4 t:meta.view.owner v:id=hfyt-zc65 v:screenName="Katherine Leamaster" v:displayName="Katherine Leamaster"

property e:njpd-rii4 t:meta.view.tableauthor v:id=hfyt-zc65 v:screenName="Katherine Leamaster" v:displayName="Katherine Leamaster"
```

## Top Records

```ls
| :updated_at | county    | location_2          | facility                    | training_provider      | contact_name              | contact_phone | email_link                          | description                                                                                                                                                                                                                                                                                                                                                                                               | 
| =========== | ========= | =================== | =========================== | ====================== | ========================= | ============= | =================================== | ========================================================================================================================================================================================================================================================================================================================================================================================================= | 
| 1403085623  | Linn      | Harrisburg, Oregon  | Harrisburg High School      | Harrisburg High School | Earl Cavin                | 541-995-6626  | earl.cavin@harrisburg.k12.or.us     | Harrisburg has a tractor school each May. The school has been in operation for 25-30 years and is supported by the area farmers and equipment dealers. It runs Tuesday through Friday evenings and all day on Saturday. Sign up is through the High School office.                                                                                                                                        | 
| 1403085624  | Union     | Imbler, Oregon      | Imbler High School          | Imbler High School     | Jim Cant                  | 541-534-5331  | jdcant@imbler.k12.or.us             | Imbler HS Agriculture Education Program offers the course as a part of the Introductions to Agriculture Mechanics couse in the Spring Term of each year. The Unit of study is conducted from Mid-April to End of May. Offered to any HS (9-12) grade students at no cost. Program utilizes the 4-H Tractor Safety Book, and requires passing all Unit Tests, Driving/Maneuvering Test, and Written Final. | 
| 1403085994  | Columbia  | St. Helens, Oregon  | Unknown                     | 4-H/Extension          | Woody Davis               |               | woody.davis@oregonstate.edu         | This class is located at the Columbia County Extension office for class training and at the Fairgrounds for practice.                                                                                                                                                                                                                                                                                     | 
| 1403086006  | Clackamas | Milwaukie, Oregon   | Unknown                     | North Clackamas        | Wynn Mayfield             | Unknown       | mayfieldw@nclack.k12.or.us          |                                                                                                                                                                                                                                                                                                                                                                                                           | 
| 1403086008  | Yamhill   | McMinnville, Oregon | Unknown                     | 4-H/Extension          | Mike Knutz                | Unknown       | mike.knutz@oregonstate.edu          |                                                                                                                                                                                                                                                                                                                                                                                                           | 
| 1403086009  | Yamhill   | Yamhill, OR         | Yamhill/Carlton High School | Yamhill/Carlton FFA    | Nichole Spearman-Eskelsen | Unknown       | spearmann@ycschools.org             | I sometimes provide one in the spring.                                                                                                                                                                                                                                                                                                                                                                    | 
| 1403086010  | Marion    | Gervais, Oregon     | Unknown                     | Gervais High School    | Mike Williams             | Unknown       | mike_williams@gervais.k12.or.us     |                                                                                                                                                                                                                                                                                                                                                                                                           | 
| 1403086011  | Marion    | Stayton, Oregon     | Unknown                     | Stayton High School    | Cindy Schumacher          | Unknown       | cindy.schumacher@nsantiam.k12.or.us |                                                                                                                                                                                                                                                                                                                                                                                                           | 
| 1403086012  | Malheur   | Ontario, Oregon     | Unknown                     | 4-H/Extension          | Melissa Sherman           | Unknown       | melissa.sherman@oregonstate.edu     |                                                                                                                                                                                                                                                                                                                                                                                                           | 
| 1403086016  | Lake      | Lakeview, Oregon    | Unknown                     | 4-H/Extension          | Pete Schreder             | Unknown       | peter.schreder@oregonstate.edu      |                                                                                                                                                                                                                                                                                                                                                                                                           | 
```