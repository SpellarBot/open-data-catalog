# Runaway And Homeless Youth Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/runaway-and-homeless-youth-programs) |
| Metadata | [Link](https://data.ny.gov/api/views/q88j-j2mi) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/q88j-j2mi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/q88j-j2mi/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | q88j-j2mi |
| Name | Runaway And Homeless Youth Programs |
| Attribution | New York State Office of Children and Family Services |
| Category | Human Services |
| Tags | runaway youth, homeless youth |
| Created | 2014-03-31T17:45:56Z |
| Publication Date | 2016-01-14T17:28:46Z |

## Description

Included in this data set are data elements that will help the public identify agencies that are certified to operate programs for runaway and homeless youth. These programs are available to assist runaway and homeless youth in emergency situation and provide independent living skills for youth in transition. Data elements include the agency name, agency business address, phone number, website and type of program offered.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                                  | Data Type | Render Type |
| ======== | =========== | =================== | ===================================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at                            | meta_data | meta_data   |
| Yes      | series tag  | agency              | Agency                                | text      | text        |
| Yes      | series tag  | street_address      | Agency Business Street Address        | text      | text        |
| Yes      | series tag  | city                | City                                  | text      | text        |
| Yes      | series tag  | state               | State                                 | text      | text        |
| Yes      | series tag  | zip                 | Zip                                   | text      | number      |
| Yes      | series tag  | url                 | URL                                   | url       | url         |
| Yes      | series tag  | phone               | Phone                                 | text      | text        |
| Yes      | series tag  | phone_extension     | Phone Extension                       | text      | text        |
| Yes      | series tag  | crisis_shelter      | Crisis Shelter                        | text      | text        |
| Yes      | series tag  | tilp                | Transition Independent Living Program | text      | text        |
| Yes      | series tag  | interim_family      | Interim Family                        | text      | text        |
| Yes      | series tag  | supported_residence | Supported Residence                   | text      | text        |
| Yes      | series tag  | group_residence     | Group Residence                       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:q88j-j2mi d:2016-01-11T05:34:39.000Z t:crisis_shelter=Y t:zip=11542 t:tilp=N t:phone=516-671-1253 t:interim_family=N t:state=NY t:group_residence=N t:agency="SCO Family of Services" t:street_address="1 Alexander Place 5th Floor" t:supported_residence=Y t:url=http://sco.org t:city="Glen Cove" m:row_number.q88j-j2mi=1

series e:q88j-j2mi d:2016-01-11T05:34:39.000Z t:crisis_shelter=N t:zip=13901 t:tilp=N t:phone=607-739-9166 t:interim_family=N t:state=NY t:group_residence=N t:agency="Catholic Charities of Broome County" t:street_address="232 Main St" t:supported_residence=Y t:url=http://www.catholicharitiesbc.org t:city=Binghamton m:row_number.q88j-j2mi=2

series e:q88j-j2mi d:2016-01-11T05:34:39.000Z t:crisis_shelter=Y t:zip=10509 t:tilp=N t:phone=845-279-2378 t:interim_family=N t:state=NY t:group_residence=N t:agency="Green Chimneys Children's Services" t:street_address="400 Doansburg Road - Caller Box 719" t:supported_residence=N t:url=http://www.greenchimneys.org t:city=Brewster m:row_number.q88j-j2mi=3
```

## Meta Commands

```ls
metric m:row_number.q88j-j2mi p:long l:"Row Number"

entity e:q88j-j2mi l:"Runaway And Homeless Youth Programs" t:attribution="New York State Office of Children and Family Services" t:url=https://data.ny.gov/api/views/q88j-j2mi

property e:q88j-j2mi t:meta.view v:id=q88j-j2mi v:category="Human Services" v:attributionLink=http://ocfs.ny.gov/main/youth v:averageRating=0 v:name="Runaway And Homeless Youth Programs" v:attribution="New York State Office of Children and Family Services"

property e:q88j-j2mi t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:q88j-j2mi t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:q88j-j2mi t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | agency                                       | street_address                                | city          | state | zip   | url                                               | phone        | phone_extension | crisis_shelter | tilp | interim_family | supported_residence | group_residence | 
| =========== | ============================================ | ============================================= | ============= | ===== | ===== | ================================================= | ============ | =============== | ============== | ==== | ============== | =================== | =============== | 
| 1452490479  | SCO Family of Services                       | 1 Alexander Place 5th Floor                   | Glen Cove     | NY    | 11542 | [http://sco.org, null]                            | 516-671-1253 |                 | Y              | N    | N              | Y                   | N               | 
| 1452490479  | Catholic Charities of Broome County          | 232 Main St                                   | Binghamton    | NY    | 13901 | [http://www.catholicharitiesbc.org, null]         | 607-739-9166 |                 | N              | N    | N              | Y                   | N               | 
| 1452490479  | Green Chimneys Children's Services           | 400 Doansburg Road - Caller Box 719           | Brewster      | NY    | 10509 | [http://www.greenchimneys.org, null]              | 845-279-2378 |                 | Y              | N    | N              | N                   | N               | 
| 1452490479  | The Center For Youth Services, Inc.          | 905 Monroe Ave.                               | Rochester     | NY    | 14620 | [http://centerforyouth.net, null]                 | 585-473-2464 |                 | Y              | N    | Y              | N                   | N               | 
| 1452490479  | Project Hospitality                          | 100 Park Ave                                  | Staten Island | NY    | 10302 | [http://projecthospitality.org, null]             | 718-448-1544 |                 | N              | N    | N              | Y                   | N               | 
| 1452490479  | Oswego County Opportunities                  | 75 East First St., Midtown Plaza, Lower-Level | Oswego        | NY    | 13126 | [http://www.oco.org, null]                        | 315-342-7532 |                 | N              | N    | Y              | Y                   | N               | 
| 1452490479  | Family and Childrens Association             | 100 East Old Country Rd                       | Mineola       | NY    | 11501 | [http://www.familyandchildrens.org/Home, null]    | 516-221-1310 |                 | Y              | N    | N              | N                   | Y               | 
| 1452490479  | WAIT House                                   | P.O. Box 3252                                 | Glens Falls   | NY    | 12801 | [http://www.hycwaithouse.org, null]               | 518-798-2077 |                 | Y              | Y    | N              | N                   | N               | 
| 1452490479  | Catholic Charites of Oneida/Madison Counties | 1408 Genesee Street                           | Utica         | NY    | 13502 | [http://www.catholiccharitiesom.org, null]        | 315-724-2158 |                 | N              | N    | Y              | N                   | N               | 
| 1452490479  | The Franciscan Center                        | 1910 Seneca St.                               | Buffalo       | NY    | 14210 | [http://franciscancenterinc.org/wordpress/, null] | 716-822-8017 |                 | N              | N    | N              | N                   | Y               | 
```