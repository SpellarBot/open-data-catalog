# Austintexas.gov - Community Registry - Updated once a Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austintexas-gov-community-registry-updated-once-a-month) |
| Metadata | [Link](https://data.austintexas.gov/api/views/u3yy-shmz) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/u3yy-shmz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/u3yy-shmz/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | u3yy-shmz |
| Name | Austintexas.gov - Community Registry - Updated once a Month |
| Attribution | City of Austin, Texas |
| Tags | community registry, neighborhood registry, community, neighborhood |
| Created | 2013-05-09T21:21:54Z |
| Publication Date | 2017-04-07T20:49:07Z |

## Description

This is a monthly upload of the Community Registry. Neighborhood groups register with the City of Austin to receive notices of developments within their specified boundaries.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| No       | time        | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag  | association_name          | Association Name          | text      | text        |
| Yes      | series tag  | association_category      | Association Category      | text      | text        |
| Yes      | series tag  | association_email         | Association Email         | text      | text        |
| Yes      | series tag  | association_zip_code      | Association Zip Code      | text      | text        |
| Yes      | series tag  | association_id            | Planning ID #             | text      | text        |
| Yes      | series tag  | primary_contact_name      | Primary Contact Name      | text      | text        |
| Yes      | series tag  | primary_contact_phone     | Primary Contact Phone     | text      | text        |
| No       |             | primary_address           | Primary Address           | text      | text        |
| Yes      | series tag  | primary_contact_zipcode   | Primary Contact Zipcode   | text      | text        |
| Yes      | series tag  | primary_contact_email     | Primary Contact Email     | text      | text        |
| Yes      | series tag  | secondary_contact_name    | Secondary Contact Name    | text      | text        |
| Yes      | series tag  | secondary_contact_phone   | Secondary Contact Phone   | text      | text        |
| No       |             | secondary_contact_address | Secondary Contact Address | text      | text        |
| Yes      | series tag  | secondary_contact_zipcode | Secondary Contact Zipcode | text      | text        |
| Yes      | series tag  | secondary_contact_email   | Secondary Contact Email   | text      | text        |
| Yes      | series tag  | members                   | Number of Households      | text      | text        |
| Yes      | series tag  | meeting_information       | Meeting Information       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = primary_address,secondary_contact_address
```

## Data Commands

```ls
series e:u3yy-shmz d:2017-04-07T20:48:02.000Z t:secondary_contact_phone=512-345-1776 t:association_id=425 t:secondary_contact_zipcode=78755 t:primary_contact_email=N/A t:primary_contact_name="Peter Torgrimson" t:association_category="Neighborhood Association" t:association_name="2222 Coalition of Neighborhood Associations Inc." t:association_zip_code="78726; 78730; 78731; 78750; 78759" t:primary_contact_phone=512-338-4722 t:secondary_contact_email=N/A t:meeting_information="The organization typically meets at River Place Country Club. The organization meets monthly or more frequently as necessary." t:primary_contact_zipcode=78755 t:secondary_contact_name="Lisette Schmidli" t:members=2000 t:association_email=2222CONA(at)gmail.com m:row_number.u3yy-shmz=1

series e:u3yy-shmz d:2017-04-07T20:48:02.000Z t:secondary_contact_phone=565-8798 t:association_id=1194 t:secondary_contact_zipcode=78731 t:primary_contact_email=dan(at)digiclaim.com t:primary_contact_name="Daniel King" t:association_category="Neighborhood Association" t:association_name="45th St. Concerned Citizens" t:primary_contact_phone=632-7724 t:secondary_contact_email=N/A t:meeting_information="We'll be meeting at 2611 W. 45th St. twice a year or as needed. Next meeting is in early December '12 to elect our officers. Thanks in advance." t:primary_contact_zipcode=78731 t:secondary_contact_name="Donna Lund" t:members=N/A t:association_email=N/A m:row_number.u3yy-shmz=2

series e:u3yy-shmz d:2017-04-07T20:48:02.000Z t:primary_contact_zipcode=78757 t:association_id=769 t:primary_contact_email=N/A t:association_name="5702 Wynona Neighbors" t:primary_contact_name="John Keohane" t:secondary_contact_name=N/A t:association_email=Keohane(at)prodigy.net t:primary_contact_phone=512-371-3853 m:row_number.u3yy-shmz=3
```

## Meta Commands

```ls
metric m:row_number.u3yy-shmz p:long l:"Row Number"

entity e:u3yy-shmz l:"Austintexas.gov - Community Registry - Updated once a Month" t:attribution="City of Austin, Texas" t:url=https://data.austintexas.gov/api/views/u3yy-shmz

property e:u3yy-shmz t:meta.view v:id=u3yy-shmz v:attributionLink=http://www.austintexas.gov/cr v:averageRating=0 v:name="Austintexas.gov - Community Registry - Updated once a Month" v:attribution="City of Austin, Texas"

property e:u3yy-shmz t:meta.view.owner v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:displayName=AustinGo

property e:u3yy-shmz t:meta.view.tableauthor v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:roleName=publisher v:displayName=AustinGo
```

## Top Records

```ls
| :updated_at | association_name                                                 | association_category     | association_email                        | association_zip_code              | association_id | primary_contact_name                                    | primary_contact_phone | primary_address                   | primary_contact_zipcode | primary_contact_email    | secondary_contact_name | secondary_contact_phone | secondary_contact_address   | secondary_contact_zipcode | secondary_contact_email | members | meeting_information                                                                                                                                                                               | 
| =========== | ================================================================ | ======================== | ======================================== | ================================= | ============== | ======================================================= | ===================== | ================================= | ======================= | ======================== | ====================== | ======================= | =========================== | ========================= | ======================= | ======= | ================================================================================================================================================================================================= | 
| 1491598082  | 2222 Coalition of Neighborhood Associations Inc.                 | Neighborhood Association | 2222CONA(at)gmail.com                    | 78726; 78730; 78731; 78750; 78759 | 425            | Peter Torgrimson                                        | 512-338-4722          | PO Box 28397                      | 78755                   | N/A                      | Lisette Schmidli       | 512-345-1776            | PO Box 28397                | 78755                     | N/A                     | 2000    | The organization typically meets at River Place Country Club. The organization meets monthly or more frequently as necessary.                                                                     | 
| 1491598082  | 45th St. Concerned Citizens                                      | Neighborhood Association | N/A                                      |                                   | 1194           | Daniel King                                             | 632-7724              | 2611 W. 45th St.                  | 78731                   | dan(at)digiclaim.com     | Donna Lund             | 565-8798                | 2611 W. 45th St             | 78731                     | N/A                     | N/A     | We'll be meeting at 2611 W. 45th St. twice a year or as needed. Next meeting is in early December '12 to elect our officers. Thanks in advance.                                                   | 
| 1491598082  | 5702 Wynona Neighbors                                            |                          | Keohane(at)prodigy.net                   |                                   | 769            | John Keohane                                            | 512-371-3853          | 5702 Wynona Ave                   | 78757                   | N/A                      | N/A                    |                         |                             |                           |                         |         |                                                                                                                                                                                                   | 
| 1491598082  | 6ixth Street Austin Association                                  | Other PID                | info(at)6thstreetaustin.com              |                                   | 751            | Certified Management of Austin 6ixth Street Association | 512-339-6962          | 9600 Great Hills Trail Suite 100E | 78759                   | N/A                      | David Morrison         | 512-203-7280            | 211 E. 7th Street Suite 818 | 78701                     | N/A                     | N/A     | Second Wednesday of each month.                                                                                                                                                                   | 
| 1491598082  | A.N.T Artists and Neighbors Together                             | Neighborhood Association | artistsandneighborstogether(at)gmail.com |                                   | 1399           | King Mahon                                              | 2143364035            | 1010 e 7th                        | 78702                   | N/A                      | Maggie Lea             | 512-656-2429            | 1108 East 6th Street        | 78702                     | N/A                     | 12      | Locations within the Boundry Headquarters at 1104 E 6th                                                                                                                                           | 
| 1491598082  | Acres West Homeowners Assn.                                      | Neighborhood Association | N/A                                      |                                   | 2              | Cindy Barron                                            | 512-258-2142          | 13602 Caldwell                    | 78750                   | Biotx69(at)hotmail.com   | Bleeker Morse          | 512-258-2455            | 13601 Caldwell Drive        | 78750                     | kity(at)texas.net       | 24      | As needed                                                                                                                                                                                         | 
| 1491598082  | African American Cultural Heritage District Business Association | Civic                    | N/A                                      |                                   | 1344           | Darrell Pierce                                          | 5124778788            | 901 East 12th Street              | 78702                   | snapmgt(at)sbcglobal.net | Stuart King            | 5124769128              | 1300 East 12th              | 78702                     | N/A                     | N/A     | Once a quarter. Location TBD. Businesses will rotate meeting at their respective locations.                                                                                                       | 
| 1491598082  | Agave Neighborhood Association                                   | Neighborhood Association | agaveneighborhood(at)gmail.com           |                                   | 1414           | Erin Knox                                               | 808-227-4477          | PO Box 141532                     | 78710                   | N/A                      | Sarah Glasscock        | 512-809-7704            | PO Box 141532               | 78710                     | N/A                     | 40      | The second Saturday of every other month beginning in February at 5805 Pinon Vista.                                                                                                               | 
| 1491598082  | Alicante Townhomes                                               | Neighborhood Association | N/A                                      | 78730                             | 1576           | Terry Purdy                                             | 832-257-5277          | 11203 RR 2222#808                 | 78730                   | N/A                      | Lauren Hawthorne       | 512-266-6771            | PO Box 34258511203 RR 2222  | 78734                     | N/A                     | N/A     | Alicante Townhomes Clubhouse Dates TBD                                                                                                                                                            | 
| 1491598082  | Allandale Neighborhood Association                               | Neighborhood Association | allandale.neighborhood(at)gmail.com      |                                   | 3              | Kata Carbone                                            | 512-454-6571          | P.O. Box 10886                    | 78766                   | N/A                      | Marshall Thompson      | N/A                     | P.O. Box 10886              | 78766                     | N/A                     | 4500    | The Executive Committee meets the first Wednesday of every month 7:00-9:00 p.m. at Northwest Recreation Center 2913 Northland Drive. General membership meetings are held in March and September. | 
```