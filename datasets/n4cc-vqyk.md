# Insurance Producers Licensed in Iowa

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/insurance-producers-licensed-in-iowa) |
| Metadata | [Link](https://data.iowa.gov/api/views/n4cc-vqyk) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/n4cc-vqyk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/n4cc-vqyk/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | n4cc-vqyk |
| Name | Insurance Producers Licensed in Iowa |
| Attribution | Iowa Insurance Division |
| Category | Economy |
| Tags | insurance, producers, licensed, life, variable life, variable annuity, accident and health, crop, casualty, property, personal lines, credit, surety, reciprocal authority |
| Created | 2015-07-02T16:25:24Z |
| Publication Date | 2016-09-02T15:21:51Z |

## Description

This dataset provides a listing of resident and non-resident insurance producers licensed to sell to Iowans.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                            | Data Type     | Render Type   |
| ======== | ============== | ====================== | =============================== | ============= | ============= |
| Yes      | series tag     | npn                    | National Producer Number        | text          | number        |
| Yes      | series tag     | last_name              | Last Name                       | text          | text          |
| Yes      | series tag     | first_name             | First Name                      | text          | text          |
| No       |                | address_line_1         | Mailing Address 1               | text          | text          |
| No       |                | address_line_2         | Mailing Address 2               | text          | text          |
| No       |                | address_line_3         | Mailing Address 3               | text          | text          |
| Yes      | series tag     | city                   | Mailing City                    | text          | text          |
| Yes      | series tag     | state                  | Mailing State                   | text          | text          |
| Yes      | series tag     | zip                    | Mailing Zip                     | text          | text          |
| Yes      | time           | firstactivedate        | Active Date                     | calendar_date | calendar_date |
| No       |                | expirydate             | Date Expire                     | calendar_date | calendar_date |
| Yes      | numeric metric | business_phone         | Business Phone                  | number        | text          |
| Yes      | series tag     | email                  | Business Email                  | text          | text          |
| Yes      | series tag     | ce_compliance          | Continuing Ed Compliance        | text          | text          |
| Yes      | series tag     | iowaresident           | Iowa Resident                   | text          | text          |
| Yes      | series tag     | loa_has_crop           | Crop                            | text          | text          |
| Yes      | series tag     | loa_has_surety         | Surety                          | text          | text          |
| Yes      | series tag     | loa_has_ah             | Accident and Health             | text          | text          |
| Yes      | series tag     | loa_has_life           | Life                            | text          | text          |
| Yes      | series tag     | loa_has_variable       | Variable Life, Variable Annuity | text          | text          |
| Yes      | series tag     | loa_has_personal_lines | Personal Lines                  | text          | text          |
| Yes      | series tag     | loa_has_credit         | Credit                          | text          | text          |
| Yes      | series tag     | loa_has_excess         | Excess and Surplus Lines        | text          | text          |
| Yes      | series tag     | loa_has_property       | Property                        | text          | text          |
| Yes      | series tag     | loa_has_casualty       | Casualty                        | text          | text          |
| Yes      | series tag     | loa_has_reciprocal     | Reciprocal Authority            | text          | text          |
```

## Time Field

```ls
Value = firstactivedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_line_1,address_line_2,address_line_3,expirydate
```

## Data Commands

```ls
series e:n4cc-vqyk d:2017-04-05T00:00:00.000Z t:loa_has_casualty=No t:zip=55344 t:loa_has_personal_lines=No t:loa_has_variable=Yes t:loa_has_life=Yes t:loa_has_ah=Yes t:state=MN t:ce_compliance=Y t:npn=6929780 t:loa_has_reciprocal=No t:city="EDEN PRAIRIE" t:loa_has_property=No t:first_name=ERIK t:loa_has_credit=No t:loa_has_surety=No t:email=erik.c.rosvold@ampf.com t:loa_has_crop=No t:last_name=ROSVOLD t:loa_has_excess=No t:iowaresident=No m:business_phone=9527469458

series e:n4cc-vqyk d:2011-05-03T00:00:00.000Z t:loa_has_casualty=Yes t:zip=90621 t:loa_has_personal_lines=No t:loa_has_variable=No t:loa_has_life=No t:loa_has_ah=No t:state=CA t:ce_compliance=Y t:npn=16137153 t:loa_has_reciprocal=No t:city="BUENA PARK" t:loa_has_property=Yes t:first_name=DARRICK t:loa_has_credit=No t:loa_has_surety=No t:email=darrick.edison@adp.com t:loa_has_crop=No t:last_name=EDISON t:loa_has_excess=No t:iowaresident=No m:business_phone=7142285012

series e:n4cc-vqyk d:2005-11-18T00:00:00.000Z t:loa_has_casualty=Yes t:zip=61615 t:loa_has_personal_lines=No t:loa_has_variable=No t:loa_has_life=Yes t:loa_has_ah=No t:state=IL t:ce_compliance=Y t:npn=8593330 t:loa_has_reciprocal=No t:city=PEORIA t:loa_has_property=Yes t:first_name=JARED t:loa_has_credit=No t:loa_has_surety=No t:email=jared.lister@libertymutual.com t:loa_has_crop=No t:last_name=LISTER t:loa_has_excess=No t:iowaresident=No m:business_phone=3096924009
```

## Meta Commands

```ls
metric m:business_phone p:long l:"Business Phone" t:dataTypeName=number

entity e:n4cc-vqyk l:"Insurance Producers Licensed in Iowa" t:attribution="Iowa Insurance Division" t:url=https://data.iowa.gov/api/views/n4cc-vqyk

property e:n4cc-vqyk t:meta.view v:id=n4cc-vqyk v:category=Economy v:averageRating=0 v:name="Insurance Producers Licensed in Iowa" v:attribution="Iowa Insurance Division"

property e:n4cc-vqyk t:meta.view.license v:name="Public Domain"

property e:n4cc-vqyk t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:n4cc-vqyk t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| npn      | last_name | first_name | address_line_1                | address_line_2             | address_line_3 | city            | state | zip   | firstactivedate     | expirydate          | business_phone | email                          | ce_compliance | iowaresident | loa_has_crop | loa_has_surety | loa_has_ah | loa_has_life | loa_has_variable | loa_has_personal_lines | loa_has_credit | loa_has_excess | loa_has_property | loa_has_casualty | loa_has_reciprocal | 
| ======== | ========= | ========== | ============================= | ========================== | ============== | =============== | ===== | ===== | =================== | =================== | ============== | ============================== | ============= | ============ | ============ | ============== | ========== | ============ | ================ | ====================== | ============== | ============== | ================ | ================ | ================== | 
| 6929780  | ROSVOLD   | ERIK       | 6500 CITY WEST PKWY           | SUITE 400                  |                | EDEN PRAIRIE    | MN    | 55344 | 2017-04-05T00:00:00 | 2020-05-31T00:00:00 | 9527469458     | erik.c.rosvold@ampf.com        | Y             | No           | No           | No             | Yes        | Yes          | Yes              | No                     | No             | No             | No               | No               | No                 | 
| 16137153 | EDISON    | DARRICK    | 7000 VILLAGE DR               |                            |                | BUENA PARK      | CA    | 90621 | 2011-05-03T00:00:00 | 2020-05-31T00:00:00 | 7142285012     | darrick.edison@adp.com         | Y             | No           | No           | No             | No         | No           | No               | No                     | No             | No             | Yes              | Yes              | No                 | 
| 8593330  | LISTER    | JARED      | 5005 W AMERICAN PRAIRIE DR    |                            |                | PEORIA          | IL    | 61615 | 2005-11-18T00:00:00 | 2020-05-31T00:00:00 | 3096924009     | jared.lister@libertymutual.com | Y             | No           | No           | No             | No         | Yes          | No               | No                     | No             | No             | Yes              | Yes              | No                 | 
| 17437566 | KNIGHT    | SUZANNE    | 1000 AAA DR SUITE 150         |                            |                | HEATHROW        | FL    | 32746 | 2014-12-01T00:00:00 | 2017-05-31T00:00:00 | 4078296622     |                                | Y             | No           | No           | No             | No         | No           | No               | Yes                    | No             | No             | No               | No               | No                 | 
| 16021888 | HAMRICK   | CALVIN     | 13520 BALLANTYNE CORPORATE PL |                            |                | CHARLOTTE       | NC    | 28277 | 2014-03-07T00:00:00 | 2019-07-31T00:00:00 | 9805006356     | calvin.hamrick@tiaa.org        | Y             | No           | No           | No             | No         | Yes          | Yes              | No                     | No             | No             | No               | No               | No                 | 
| 17655812 | BIEHL     | KRISTIN    | 114 WHITE STREET              |                            |                | HOWELL          | NJ    | 07731 | 2015-09-25T00:00:00 | 2018-09-30T00:00:00 | 9089075764     | biehl.kristin@yahoo.com        | Y             | No           | No           | No             | Yes        | No           | No               | No                     | No             | No             | No               | No               | No                 | 
| 373599   | GRECO     | MICHAEL    | 100 ILLINOIS ST STE 207       |                            |                | ST CHARLES      | IL    | 60174 | 2012-06-22T00:00:00 | 2018-06-30T00:00:00 | 6305362005     | michael_greco@ajg.com          | Y             | No           | No           | No             | Yes        | Yes          | No               | No                     | No             | No             | No               | No               | No                 | 
| 372094   | KIMBEL    | BRENT      | 2501 W. BELTLINE HWY.         | SUITE 301                  |                | MADISON         | WI    | 53713 | 2003-04-30T00:00:00 | 2018-03-31T00:00:00 | 6088190500     | brent.a.kimbel@ampf.com        | Y             | No           | No           | No             | Yes        | Yes          | Yes              | No                     | No             | No             | No               | No               | No                 | 
| 9034405  | CONWAY    | BRIAN      | INSPRO, INC.                  | 2501 WESTOWN PKWY STE 1104 |                | WEST DES MOINES | IA    | 50266 | 2007-01-11T00:00:00 | 2019-06-30T00:00:00 | 5152269565     | ndetmer@insproins.com          | N             | Yes          | No           | No             | Yes        | Yes          | No               | No                     | No             | No             | Yes              | Yes              | No                 | 
| 17345628 | BEDFORD   | BRITTANY   | 2089 SUFFOLK RD               |                            |                | OSKALOOSA       | IA    | 52577 | 2014-08-14T00:00:00 | 2020-03-31T00:00:00 | 6418569069     | brittany_bedford@us.aflac.com  | N             | Yes          | No           | No             | Yes        | Yes          | No               | No                     | No             | No             | No               | No               | No                 | 
```