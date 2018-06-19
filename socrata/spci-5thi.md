# Iowa School Building Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-school-building-directory) |
| Metadata | [Link](https://data.iowa.gov/api/views/spci-5thi) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/spci-5thi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/spci-5thi/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | spci-5thi |
| Name | Iowa School Building Directory |
| Attribution | Iowa Department of Education, Bureau of Information and Analysis |
| Category | Education |
| Tags | schools, buildings, school administrators |
| Created | 2015-01-23T15:43:45Z |
| Publication Date | 2015-01-23T16:20:21Z |

## Description

This dataset contains a directory of both public and nonpublic school buildings for the current school year.  Mailing addresses, phone and fax numbers, physical location, grades at school, and school administrator names and titles can be found in the dataset.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                        | Data Type | Render Type |
| ======== | =========== | =================== | =========================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | district_school_id  | School ID                   | text      | text        |
| Yes      | series tag  | co_name             | County Name                 | text      | text        |
| Yes      | series tag  | aea                 | AEA                         | text      | text        |
| Yes      | series tag  | school_type_name    | School Type                 | text      | text        |
| Yes      | series tag  | district_name       | Public School District Name | text      | text        |
| Yes      | series tag  | school_name         | School Building Name        | text      | text        |
| Yes      | series tag  | grade_start         | Grade Start                 | text      | text        |
| Yes      | series tag  | grade_end           | Grade End                   | text      | text        |
| Yes      | series tag  | administrator       | Administrator               | text      | text        |
| Yes      | series tag  | administrator_title | Administrator Title         | text      | text        |
| No       |             | mailing_address     | Mailing Address             | text      | text        |
| Yes      | series tag  | po_box              | PO Box                      | text      | text        |
| Yes      | series tag  | mailing_city        | Mailing City                | text      | text        |
| Yes      | series tag  | mailing_state       | Mailing State               | text      | text        |
| Yes      | series tag  | mailing_zip_code    | Mailing Zip Code            | text      | number      |
| Yes      | series tag  | phone_number        | Phone Number                | text      | number      |
| Yes      | series tag  | fax_number          | Fax Number                  | text      | number      |
| Yes      | series tag  | email_address       | Email Address               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = mailing_address
```

## Data Commands

```ls
series e:spci-5thi d:2015-01-23T08:12:19.000Z t:fax_number=6414732913 t:phone_number=6414732842 t:school_name="Gladbrook-Reinbeck Middle School" t:school_type_name="Public Middle School" t:grade_end=08 t:district_school_id=25020209 t:po_box="PO Box 370" t:grade_start=05 t:co_name=Tama t:aea=07 t:district_name="Gladbrook-Reinbeck Comm School District" t:administrator="Scot Aen" t:mailing_state=Iowa t:mailing_city=Gladbrook t:mailing_zip_code=50635 t:email_address=scot.aden@gr-rebels.net t:administrator_title=Principal m:row_number.spci-5thi=1

series e:spci-5thi d:2015-01-23T08:12:19.000Z t:fax_number=7122432120 t:phone_number=7122431370 t:school_name="Schuler Elementary School" t:school_type_name="Public Elementary School" t:grade_end=05 t:district_school_id=03870427 t:grade_start=04 t:co_name=Cass t:aea=13 t:district_name="Atlantic Comm School District" t:administrator="James Northwick" t:mailing_state=Iowa t:mailing_city=Atlantic t:mailing_zip_code=50022 t:email_address=jnorthwick@atlanticiaschools.org t:administrator_title=Principal m:row_number.spci-5thi=2

series e:spci-5thi d:2015-01-23T08:12:19.000Z t:fax_number=3196955130 t:phone_number=3196953707 t:school_name="Pekin Middle School" t:school_type_name="Public Middle School" t:grade_end=08 t:district_school_id=51630209 t:grade_start=06 t:co_name=Jefferson t:aea=15 t:district_name="Pekin Comm School District" t:administrator="JoAnne Morenz" t:mailing_state=Iowa t:mailing_city=Packwood t:mailing_zip_code=525808542 t:email_address=joanne.morenz@pekincsd.org t:administrator_title=Principal m:row_number.spci-5thi=3
```

## Meta Commands

```ls
metric m:row_number.spci-5thi p:long l:"Row Number"

entity e:spci-5thi l:"Iowa School Building Directory" t:attribution="Iowa Department of Education, Bureau of Information and Analysis" t:url=https://data.iowa.gov/api/views/spci-5thi

property e:spci-5thi t:meta.view v:id=spci-5thi v:category=Education v:averageRating=0 v:name="Iowa School Building Directory" v:attribution="Iowa Department of Education, Bureau of Information and Analysis"

property e:spci-5thi t:meta.view.license v:name="Public Domain"

property e:spci-5thi t:meta.view.owner v:id=hthm-474y v:profileImageUrlMedium=/api/users/hthm-474y/profile_images/THUMB v:profileImageUrlLarge=/api/users/hthm-474y/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/hthm-474y/profile_images/TINY v:displayName="Iowa Department of Education"

property e:spci-5thi t:meta.view.tableauthor v:id=hthm-474y v:profileImageUrlMedium=/api/users/hthm-474y/profile_images/THUMB v:profileImageUrlLarge=/api/users/hthm-474y/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/hthm-474y/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Education"
```

## Top Records

```ls
| :updated_at | district_school_id | co_name     | aea | school_type_name            | district_name                           | school_name                      | grade_start | grade_end | administrator       | administrator_title | mailing_address    | po_box     | mailing_city | mailing_state | mailing_zip_code | phone_number | fax_number | email_address                         | 
| =========== | ================== | =========== | === | =========================== | ======================================= | ================================ | =========== | ========= | =================== | =================== | ================== | ========== | ============ | ============= | ================ | ============ | ========== | ===================================== | 
| 1422000739  | 25020209           | Tama        | 07  | Public Middle School        | Gladbrook-Reinbeck Comm School District | Gladbrook-Reinbeck Middle School | 05          | 08        | Scot Aen            | Principal           | 509 Washington St. | PO Box 370 | Gladbrook    | Iowa          | 50635            | 6414732842   | 6414732913 | scot.aden@gr-rebels.net               | 
| 1422000739  | 03870427           | Cass        | 13  | Public Elementary School    | Atlantic Comm School District           | Schuler Elementary School        | 04          | 05        | James Northwick     | Principal           | 501 East 11th St.  |            | Atlantic     | Iowa          | 50022            | 7122431370   | 7122432120 | jnorthwick@atlanticiaschools.org      | 
| 1422000739  | 51630209           | Jefferson   | 15  | Public Middle School        | Pekin Comm School District              | Pekin Middle School              | 06          | 08        | JoAnne Morenz       | Principal           | 1062 Birch Ave.    |            | Packwood     | Iowa          | 525808542        | 3196953707   | 3196955130 | joanne.morenz@pekincsd.org            | 
| 1422000739  | 67000109           | Henry       | 15  | Public High School          | Waco Comm School District               | WACO High School                 | 07          | 12        | Jeff Nance          | Principal           | 706 N Pearl        | PO Box 158 | Wayland      | Iowa          | 52654            | 3192566200   | 3192566211 | jeff.nance@wacocsd.org                | 
| 1422000739  | 06098204           | Benton      | 10  | Nonpublic Elementary School |                                         | Central Lutheran School          | PK          | 08        | Janet S. Doellinger | Principal           | 310 3rd St W       | PO Box 190 | Newhall      | Iowa          | 523150190        | 3192235271   | 3192235257 | jdoellinger@centrallutheranschool.org | 
| 1422000739  | 41310209           | Cerro Gordo | 07  | Public Middle School        | Mason City Comm School District         | John Adams Middle School         | 07          | 08        | Jerrold Siglin      | Principal           | 29 S Illinois Ave  |            | Mason City   | Iowa          | 50401            | 6414214420   | 6414214476 | jsiglin@masoncityschools.org          | 
| 1422000739  | 02610445           | Polk        | 11  | Public Elementary School    | Ankeny Comm School District             | Westwood Elementary School       | PK          | 05        | Amy Dittmar         | Principal           | 2920 NW 9th        |            | Ankeny       | Iowa          | 50023            | 5159659690   | 5159659693 | amy.dittmar@ankenyschools.org         | 
| 1422000739  | 14310109           | Adams       | 13  | Public High School          | Corning Comm School District            | Corning High School              | 09          | 12        | Kent Jorgensen      | Principal           | 904 8th St         |            | Corning      | Iowa          | 50841            | 6413224245   | 6413225149 | kjorgensen@corningcsd.org             | 
| 1422000739  | 32040427           | Buchanan    | 07  | Public Elementary School    | Jesup Comm School District              | Prairie Grove Elementary School  | K           | 08        | Brian Pottebaum     | Principal           | 531 Prospect       | PO Box 287 | Jesup        | Iowa          | 506480287        | 3198271700   | 3198273905 | bpottebaum@jesup.k12.ia.us            | 
| 1422000739  | 07478305           | Sioux       | 12  | Nonpublic Elementary School |                                         | Hull Christian School            | PK          | 08        | Randy Ten Pas       | Principal           | 1301 5th St        | Box 550    | Hull         | Iowa          | 51239            | 7124392273   | 8889900581 | rtenpas@hullchristian.com             | 
```