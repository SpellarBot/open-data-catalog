# Missouri Law Enforcement Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-law-enforcement-agencies) |
| Metadata | [Link](https://data.mo.gov/api/views/cgbu-k38b) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/cgbu-k38b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/cgbu-k38b/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | cgbu-k38b |
| Name | Missouri Law Enforcement Agencies |
| Attribution | Missouri Department of Public Safety - Peace Officer Standards and Training |
| Category | Public Safety |
| Tags | police, sheriff, university police, department |
| Created | 2012-03-02T18:01:16Z |
| Publication Date | 2017-02-21T03:00:42Z |

## Description

List of Active law enforcement agencies (Sheriff, Municipal, University, Court, etc)

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | name             | Agency Name      | text      | text        |
| Yes      | series tag  | ceo_name         | Contact Name     | text      | text        |
| Yes      | series tag  | ceo_title        | CEO Title        | text      | text        |
| Yes      | series tag  | street_address   | Street Address   | text      | text        |
| Yes      | series tag  | street_address_2 | Street Address 2 | text      | text        |
| Yes      | series tag  | city             | City             | text      | text        |
| Yes      | series tag  | zip              | Zip              | text      | text        |
| Yes      | series tag  | county_name      | County Name      | text      | text        |
| Yes      | series tag  | voice_number     | Voice Number     | text      | text        |
| Yes      | series tag  | fax_number       | Fax Number       | text      | text        |
| Yes      | series tag  | agency_type      | Agency_Type      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cgbu-k38b d:2017-04-17T13:31:16.000Z t:agency_type=County t:fax_number=6607853224 t:zip=63501 t:ceo_name="Robert Hardwick" t:name="Adair County Sheriff's Office" t:ceo_title=Sheriff t:voice_number=6606654644 t:street_address="215 N Franklin" t:county_name=ADAIR t:city=Kirksville m:row_number.cgbu-k38b=1

series e:cgbu-k38b d:2017-04-17T13:31:16.000Z t:agency_type=Municipal t:fax_number=8162972888 t:zip=64720 t:ceo_name="Christopher Dillon" t:street_address_2="16 E 5th Street" t:name="Adrian Police Dept." t:ceo_title=Chief t:voice_number=8162972106 t:street_address="PO Box 246" t:county_name=BATES t:city=Adrian m:row_number.cgbu-k38b=2

series e:cgbu-k38b d:2017-04-17T13:31:16.000Z t:agency_type=Municipal t:fax_number=5737225487 t:zip=63730 t:ceo_name="Donnie Bohnsack" t:name="Advance Police Dept." t:ceo_title=Chief t:voice_number=5737223603 t:street_address="308 W Gabriel Street" t:county_name=STODDARD t:city=Advance m:row_number.cgbu-k38b=3
```

## Meta Commands

```ls
metric m:row_number.cgbu-k38b p:long l:"Row Number"

entity e:cgbu-k38b l:"Missouri Law Enforcement Agencies" t:attribution="Missouri Department of Public Safety - Peace Officer Standards and Training" t:url=https://data.mo.gov/api/views/cgbu-k38b

property e:cgbu-k38b t:meta.view v:id=cgbu-k38b v:category="Public Safety" v:attributionLink=http://dps.mo.gov/dir/programs/post/ v:averageRating=0 v:name="Missouri Law Enforcement Agencies" v:attribution="Missouri Department of Public Safety - Peace Officer Standards and Training"

property e:cgbu-k38b t:meta.view.license v:name="Public Domain"

property e:cgbu-k38b t:meta.view.owner v:id=hxwx-y8az v:profileImageUrlMedium=/api/users/hxwx-y8az/profile_images/THUMB v:profileImageUrlLarge=/api/users/hxwx-y8az/profile_images/LARGE v:screenName="Missouri Department of Public Safety" v:profileImageUrlSmall=/api/users/hxwx-y8az/profile_images/TINY v:displayName="Missouri Department of Public Safety"

property e:cgbu-k38b t:meta.view.tableauthor v:id=hxwx-y8az v:profileImageUrlMedium=/api/users/hxwx-y8az/profile_images/THUMB v:profileImageUrlLarge=/api/users/hxwx-y8az/profile_images/LARGE v:screenName="Missouri Department of Public Safety" v:profileImageUrlSmall=/api/users/hxwx-y8az/profile_images/TINY v:roleName=editor v:displayName="Missouri Department of Public Safety"
```

## Top Records

```ls
| :updated_at | name                           | ceo_name           | ceo_title    | street_address             | street_address_2 | city          | zip   | county_name | voice_number | fax_number | agency_type | 
| =========== | ============================== | ================== | ============ | ========================== | ================ | ============= | ===== | =========== | ============ | ========== | =========== | 
| 1492435876  | Adair County Sheriff's Office  | Robert Hardwick    | Sheriff      | 215 N Franklin             |                  | Kirksville    | 63501 | ADAIR       | 6606654644   | 6607853224 | County      | 
| 1492435876  | Adrian Police Dept.            | Christopher Dillon | Chief        | PO Box 246                 | 16 E 5th Street  | Adrian        | 64720 | BATES       | 8162972106   | 8162972888 | Municipal   | 
| 1492435876  | Advance Police Dept.           | Donnie Bohnsack    | Chief        | 308 W Gabriel Street       |                  | Advance       | 63730 | STODDARD    | 5737223603   | 5737225487 | Municipal   | 
| 1492435876  | Alma Police Dept.              | Nick Boehmer       | Chief        | 205 S County Rd            |                  | Alma          | 64001 | LAFAYETTE   | 6606742475   | 6606742491 | Municipal   | 
| 1492435876  | Alton Police Dept.             | Rusty Warren       | Chief        | PO Box 247                 |                  | Alton         | 65606 | OREGON      | 4177787115   | 4177787941 | Municipal   | 
| 1492435876  | Anderson Police Dept.          | GERALD HATFIELD    | Acting Chief | 713 Business 71 Highway    | PO Box 397       | Anderson      | 64831 | MCDONALD    | 4173550198   | 4178456565 | Municipal   | 
| 1492435876  | Andrew County Sheriff's Office | Bryan Atkins       | Sheriff      | 400 E Main Street          |                  | Savannah      | 64485 | ANDREW      | 8163245801   | 8163240574 | County      | 
| 1492435876  | Annapolis Police Dept          | Jeffery Burkett    | Chief        | 204 School Street          |                  | Annapolis     | 63620 | IRON        | 5735983531   | 5735983631 | Municipal   | 
| 1492435876  | Appleton City Police Dept.     | Karol Stephan      | Mayor        | 114 E Fourth St PO Box 134 |                  | Appleton City | 64724 | ST. CLAIR   | 6604762631   | 6604762651 | Municipal   | 
| 1492435876  | Arbyrd Police Dept.            | Jerry Gentry       | Chief        | 200 Broadway               | P.O. Box 338     | Arbyrd        | 63821 | DUNKLIN     | 5736543834   | 5736543507 | Municipal   | 
```