# Libraries Outreach Programs FY2009 - FY2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-outreach-programs-fy2009-fy2011-9d81e) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ekm4-ugtg) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ekm4-ugtg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ekm4-ugtg/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ekm4-ugtg |
| Name | Libraries Outreach Programs FY2009 - FY2011 |
| Attribution | Hawaii State Public Library System |
| Category | Formal Education |
| Tags | library |
| Created | 2012-07-26T22:49:38Z |
| Publication Date | 2012-07-26T22:52:49Z |

## Description

Statistics regarding the Outreach Programs conducted by the Hawaii State Public Library System

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | island             | Island             | text      | text        |
| Yes      | series tag     | library            | Library            | text      | text        |
| Yes      | numeric metric | outreach_fy_2009   | Outreach FY 2009   | number    | number      |
| Yes      | numeric metric | attendance_fy_2009 | Attendance FY 2009 | number    | number      |
| Yes      | numeric metric | outreach_fy_2010   | Outreach FY 2010   | number    | number      |
| Yes      | numeric metric | attendance_fy_2010 | Attendance FY 2010 | number    | number      |
| Yes      | numeric metric | outreach_fy_2011   | Outreach FY 2011   | number    | number      |
| Yes      | numeric metric | attendance_fy_2011 | Attendance FY 2011 | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ekm4-ugtg d:2009-01-01T00:00:00.000Z t:library=Aiea t:island=Oahu m:attendance_fy_2011=510 m:attendance_fy_2010=1797 m:outreach_fy_2011=19 m:outreach_fy_2010=21 m:attendance_fy_2009=1386 m:outreach_fy_2009=51

series e:ekm4-ugtg d:2009-01-01T00:00:00.000Z t:library="Aina Haina" t:island=Oahu m:attendance_fy_2011=304 m:attendance_fy_2010=1329 m:outreach_fy_2011=6 m:outreach_fy_2010=4 m:attendance_fy_2009=899 m:outreach_fy_2009=12

series e:ekm4-ugtg d:2009-01-01T00:00:00.000Z t:library="Ewa Beach" t:island=Oahu m:attendance_fy_2011=222 m:attendance_fy_2010=0 m:outreach_fy_2011=9 m:outreach_fy_2010=0 m:attendance_fy_2009=3175 m:outreach_fy_2009=23
```

## Meta Commands

```ls
metric m:outreach_fy_2009 p:integer l:"Outreach FY 2009" t:dataTypeName=number

metric m:attendance_fy_2009 p:integer l:"Attendance FY 2009" t:dataTypeName=number

metric m:outreach_fy_2010 p:integer l:"Outreach FY 2010" t:dataTypeName=number

metric m:attendance_fy_2010 p:integer l:"Attendance FY 2010" t:dataTypeName=number

metric m:outreach_fy_2011 p:integer l:"Outreach FY 2011" t:dataTypeName=number

metric m:attendance_fy_2011 p:integer l:"Attendance FY 2011" t:dataTypeName=number

entity e:ekm4-ugtg l:"Libraries Outreach Programs FY2009 - FY2011" t:attribution="Hawaii State Public Library System" t:url=https://data.hawaii.gov/api/views/ekm4-ugtg

property e:ekm4-ugtg t:meta.view v:id=ekm4-ugtg v:category="Formal Education" v:attributionLink=http://www.librarieshawaii.org/ v:averageRating=0 v:name="Libraries Outreach Programs FY2009 - FY2011" v:attribution="Hawaii State Public Library System"

property e:ekm4-ugtg t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:ekm4-ugtg t:meta.view.owner v:id=4hgi-fxu8 v:screenName="Paola Saibene" v:displayName="Paola Saibene"

property e:ekm4-ugtg t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| island | library    | outreach_fy_2009 | attendance_fy_2009 | outreach_fy_2010 | attendance_fy_2010 | outreach_fy_2011 | attendance_fy_2011 | 
| ====== | ========== | ================ | ================== | ================ | ================== | ================ | ================== | 
| Oahu   | Aiea       | 51               | 1386               | 21               | 1797               | 19               | 510                | 
| Oahu   | Aina Haina | 12               | 899                | 4                | 1329               | 6                | 304                | 
| Oahu   | Ewa Beach  | 23               | 3175               | 0                | 0                  | 9                | 222                | 
| Oahu   | Hawaii Kai | 9                | 193                | 12               | 343                | 13               | 408                | 
| Oahu   | HSL        | 103              | 9377               | 70               | 6655               | 74               | 7680               | 
| Oahu   | Kahuku     | 45               | 926                | 50               | 1231               | 55               | 748                | 
| Oahu   | Kailua     | 9                | 153                | 12               | 1495               | 5                | 204                | 
| Oahu   | Kaimuki    | 11               | 420                | 12               | 279                | 6                | 145                | 
| Oahu   | Kalihi     | 166              | 6744               | 17               | 512                | 97               | 2313               | 
| Oahu   | Kaneohe    | 17               | 1077               | 2                | 42                 | 13               | 861                | 
```