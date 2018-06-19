# CCC Organizations 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccc-organizations-2011-cced7) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/tpag-zk4d) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/tpag-zk4d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/tpag-zk4d/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | tpag-zk4d |
| Name | CCC Organizations 2011 |
| Attribution | The Combined Charity Campaign for Baltimore City (CCC) |
| Category | City Government |
| Tags | charity |
| Created | 2011-09-09T13:24:54Z |
| Publication Date | 2014-04-03T23:43:16Z |

## Description

The Combined Charity Campaign for Baltimore City (CCC) Organizations 2011

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | book_number      | Book_Number      | text      | text        |
| Yes      | series tag  | organizationname | OrganizationName | text      | text        |
| Yes      | series tag  | telephone        | Telephone        | text      | text        |
| Yes      | series tag  | fax              | Fax              | text      | text        |
| Yes      | series tag  | description      | Description      | text      | text        |
| Yes      | series tag  | website          | Website          | url       | url         |
| Yes      | series tag  | streetaddress    | StreetAddress    | text      | text        |
| Yes      | series tag  | city             | City             | text      | text        |
| Yes      | series tag  | zipcode          | ZipCode          | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tpag-zk4d d:2011-01-01T00:00:00.000Z t:organizationname="Give Kids the World, Inc." t:streetaddress="210 South Bass Road" t:fax=407-396-1207 t:website=http://www.gtw.org t:book_number=4797 t:zipcode=34746 t:telephone=407-396-1114 t:city=Kissimmee m:row_number.tpag-zk4d=1

series e:tpag-zk4d d:2011-01-01T00:00:00.000Z t:organizationname="NFB of Maryland" t:streetaddress="1026 East 36th Street" t:website=http://www.nfbmd.org t:description="Provides advocacy, scholarships, education and support to blind residents of Maryland and their families." t:book_number=1678 t:zipcode=21218 t:telephone=410-235-3073 t:city=Baltimore m:row_number.tpag-zk4d=2

series e:tpag-zk4d d:2011-01-01T00:00:00.000Z t:organizationname="Belvedere Assisted Living, Inc." t:streetaddress="32 East 25th Street" t:website=http://www.thebelvedereliving.org t:description="To provide assisted living housing to the aged, ill and handicapped population." t:book_number=4952 t:zipcode=21218 t:telephone=443-570-9064 t:city=Baltimore m:row_number.tpag-zk4d=3
```

## Meta Commands

```ls
metric m:row_number.tpag-zk4d p:long l:"Row Number"

entity e:tpag-zk4d l:"CCC Organizations 2011" t:attribution="The Combined Charity Campaign for Baltimore City (CCC)" t:url=https://data.baltimorecity.gov/api/views/tpag-zk4d

property e:tpag-zk4d t:meta.view v:id=tpag-zk4d v:category="City Government" v:attributionLink=http://www.cccmd.org/ v:averageRating=0 v:name="CCC Organizations 2011" v:attribution="The Combined Charity Campaign for Baltimore City (CCC)"

property e:tpag-zk4d t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:tpag-zk4d t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:tpag-zk4d t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| book_number | organizationname                                   | telephone    | fax           | description                                                                                                                                                                                  | website                                   | streetaddress                                         | city        | zipcode | 
| =========== | ================================================== | ============ | ============= | ============================================================================================================================================================================================ | ========================================= | ===================================================== | =========== | ======= | 
| 4797        | Give Kids the World, Inc.                          | 407-396-1114 | 407-396-1207  |                                                                                                                                                                                              | [http://www.gtw.org, null]                | 210 South Bass Road                                   | Kissimmee   | 34746   | 
| 1678        | NFB of Maryland                                    | 410-235-3073 |               | Provides advocacy, scholarships, education and support to blind residents of Maryland and their families.                                                                                    | [http://www.nfbmd.org, null]              | 1026 East 36th Street                                 | Baltimore   | 21218   | 
| 4952        | Belvedere Assisted Living, Inc.                    | 443-570-9064 |               | To provide assisted living housing to the aged, ill and handicapped population.                                                                                                              | [http://www.thebelvedereliving.org, null] | 32 East 25th Street                                   | Baltimore   | 21218   | 
| 9842        | Art With a Heart, Inc.                             | 410-366-8886 | 410--366-2121 | Dedicated to enhancing the lives of people in need through visual art.                                                                                                                       | [http://www.artwithaheart.net, null]      | 3355 Keswick Road, Hampden Village Centre, Suite #104 | Baltimore   | 21211   | 
| 9739        | Gwynns Falls Elementary School Foundation, Inc.    | 410-396-0638 | 410-545-7853  | Provides activities to Gwynns Falls Elementary School, which directly enhances the educational program of the student body.                                                                  | [null, null]                              | 2700 Gwynns Falls Parkway                             | Baltimore   | 21216   | 
| 4991        | Justice Policy Institute                           | 202-558-7974 | 202-558-7978  | Justice Policy Institute is a research, communications, and technical assistance organization that reduces the use of the justice system and promotes equitable and safe communities.        | [http://www.justicepolicy.org, null]      | 1012 14th Street, NW, Suite 400                       | Washington  | 20005   | 
| 8036        | Leukemia & Lymphoma Society, MD Chapter            | 410-891-1999 | 410-891-1998  | Funds research to cure leukemia, lymphoma, Hodgkin's disease and myeloma; provides patient services, information and referral, financial assistance, education, advocacy and support groups. | [http://www.lls.org/md, null]             | 11350 McCormick Road, Executive Plaza III, Suite 100  | Hunt Valley | 21031   | 
| 5650        | Rape Crisis Intervention Service of Carroll County | 410-857-0900 | 410-876-9147  | Provides free walk-in counseling, hospital/court/police accompaniment services, individual and group therapy and 24-hour hotline for people hurt by sexual violence.                         | [http://www.rapcrisiscc.org, null]        | 224 North Center Street, Room 102, P.O. Box 1563      | Westminster | 21158   | 
| 3153        | Reading Is Fundamental                             | 202-536-3400 | 202-536-3515  | RIF provides free books for children nationwide and engages children, parents, and communities in reading and motivational activities to encourage a lifelong love of reading.               | [http://www.RIF.org, null]                | 1255 23rd Street, N.W., Suite 300                     | Washington  | 20037   | 
| 4259        | The Hole in the Wall Gang Fund, Inc.               | 203-772-0522 | 203-782-1725  | Founded by Paul Newman, this nonprofit serves seriously ill children, bringing hope and healing through camp programs and its outreach program to children in hospitals.                     | [http://www.holeinthewallgang.org, null]  | 555 Long Wharf Drive                                  | New Haven   | 6511    | 
```