# Residential Juvenile Justice Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/residential-juvenile-justice-facilities) |
| Metadata | [Link](https://data.ny.gov/api/views/jn2j-7x6a) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/jn2j-7x6a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/jn2j-7x6a/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | jn2j-7x6a |
| Name | Residential Juvenile Justice Facilities |
| Attribution | Office of Children and Family Services |
| Category | Human Services |
| Tags | juvenile justice, residential, facility |
| Created | 2014-01-08T20:58:57Z |
| Publication Date | 2016-02-22T16:04:56Z |

## Description

This provides information on the location, phone and fax numbers, security level and video conference capacity of each of the Juvenile Justice facilities operated by Office for Children and Family Services (OCFS).

## Columns

```ls
| Included | Schema Type | Field Name    | Name           | Data Type | Render Type |
| ======== | =========== | ============= | ============== | ========= | =========== |
| No       | time        | :updated_at   | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | facility      | Facility       | text      | text        |
| No       |             | address       | Street Address | text      | text        |
| No       |             | address_1     | Address 1      | text      | text        |
| Yes      | series tag  | city          | City           | text      | text        |
| Yes      | series tag  | state         | State          | text      | text        |
| Yes      | series tag  | zip           | Zip            | text      | text        |
| Yes      | series tag  | phone         | Phone          | text      | text        |
| Yes      | series tag  | fax           | Fax            | text      | text        |
| Yes      | series tag  | county        | County         | text      | text        |
| Yes      | series tag  | security      | Security       | text      | text        |
| Yes      | series tag  | vc_capability | VC Capability  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,address_1
```

## Data Commands

```ls
series e:jn2j-7x6a d:2016-02-22T07:59:26.000Z t:zip=12153 t:phone="(518) 851-3211" t:fax="(518) 851-2403" t:facility="Columbia Secure Center" t:county=Columbia t:vc_capability=Yes t:state=NY t:security=Secure t:city=Claverack m:row_number.jn2j-7x6a=1

series e:jn2j-7x6a d:2016-02-22T07:59:41.000Z t:zip=13471 t:phone="(315) 245-0084" t:fax="(315) 245-0088" t:facility="Taberg Limited Secure Center" t:county=Oneida t:vc_capability=Yes t:state=NY t:security="Limited Secure" t:city=Taberg m:row_number.jn2j-7x6a=2

series e:jn2j-7x6a d:2016-02-22T07:59:41.000Z t:zip=14882 t:phone="(607) 533-4262" t:fax="(607) 533-7309" t:facility="Lansing Residential Center" t:county=Tompkins t:vc_capability=Yes t:state=NY t:security=Non-Secure t:city=Lansing m:row_number.jn2j-7x6a=3
```

## Meta Commands

```ls
metric m:row_number.jn2j-7x6a p:long l:"Row Number"

entity e:jn2j-7x6a l:"Residential Juvenile Justice Facilities" t:attribution="Office of Children and Family Services" t:url=https://data.ny.gov/api/views/jn2j-7x6a

property e:jn2j-7x6a t:meta.view v:id=jn2j-7x6a v:category="Human Services" v:attributionLink=http://ocfs.ny.gov/main/rehab/ v:averageRating=0 v:name="Residential Juvenile Justice Facilities" v:attribution="Office of Children and Family Services"

property e:jn2j-7x6a t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:jn2j-7x6a t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:jn2j-7x6a t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | facility                      | address                     | address_1    | city            | state | zip   | phone          | fax            | county   | security       | vc_capability | 
| =========== | ============================= | =========================== | ============ | =============== | ===== | ===== | ============== | ============== | ======== | ============== | ============= | 
| 1456127966  | Columbia Secure Center        | 419 Spook Rock Rd.          | P.O. Box 265 | Claverack       | NY    | 12153 | (518) 851-3211 | (518) 851-2403 | Columbia | Secure         | Yes           | 
| 1456127981  | Taberg Limited Secure Center  | 10011 Taberg-Florence Rd.   |              | Taberg          | NY    | 13471 | (315) 245-0084 | (315) 245-0088 | Oneida   | Limited Secure | Yes           | 
| 1456127981  | Lansing Residential Center    | 270 Auburn Rd.              |              | Lansing         | NY    | 14882 | (607) 533-4262 | (607) 533-7309 | Tompkins | Non-Secure     | Yes           | 
| 1456127981  | Ella McQueen Reception Center | 41 Howard Avenue            |              | Brooklyn        | NY    | 11221 | (718) 574-2063 | (718) 574-2930 | Kings    | Reception      | Yes           | 
| 1456127981  | Youth Leadership Academy      | 57081 State Highway 10      | P.O. Box 132 | South Kortright | NY    | 13842 | (607) 538-1401 | (607) 538-1403 | Delaware | Limited Secure | Yes           | 
| 1456127981  | Highland Residential Center   | 629 North Chodikee Lake Rd. | P.O. Box 970 | Highland        | NY    | 12528 | (845) 691-6006 | (845) 691-6042 | Ulster   | Limited Secure | Yes           | 
| 1456127981  | Red Hook Residential Center   | 531 Turkey Hill Rd.         |              | Red Hook        | NY    | 12571 | (845) 758-4151 | (845) 758-4508 | Dutchess | Non-Secure     | Yes           | 
| 1456127981  | Middletown Residential Center | 393 County Route 78         |              | Middletown      | NY    | 10940 | (845) 342-3936 | (845) 342-1468 | Orange   | Non-Secure     | Yes           | 
| 1456127981  | GoshenSecure Center           | 97 Cross Rd.                |              | Goshen          | NY    | 10924 | (845) 615-3000 | (845) 615-3016 | Orange   | Secure         | Yes           | 
| 1456127981  | MacCormick Secure Center      | 300 South Rd.               |              | Brooktondale    | NY    | 14817 | (607) 539-7121 | (607) 539-6588 | Tompkins | Secure         | Yes           | 
```