# Early Voting Locations - 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/early-voting-locations-2012-1a758) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/c5zu-3cbe) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/c5zu-3cbe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/c5zu-3cbe/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | c5zu-3cbe |
| Name | Early Voting Locations - 2012 |
| Attribution | Cook County Clerk |
| Created | 2012-10-10T19:48:01Z |
| Publication Date | 2014-10-09T21:26:53Z |

## Columns

```ls
| Included | Schema Type | Field Name | Name    | Data Type | Render Type |
| ======== | =========== | ========== | ======= | ========= | =========== |
| Yes      | series tag  | site       | Site    | text      | text        |
| Yes      | series tag  | hours      | Hours   | text      | text        |
| No       |             | address    | Address | text      | text        |
| Yes      | series tag  | city       | City    | text      | text        |
| Yes      | series tag  | state      | State   | text      | text        |
| Yes      | series tag  | zip        | Zip     | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:c5zu-3cbe d:2012-01-01T00:00:00.000Z t:site="Alsip Village Hall" t:zip=60803 t:hours="Monday-Saturday: 9 a.m.–5 p.m." t:state=IL t:city=Alsip m:row_number.c5zu-3cbe=1

series e:c5zu-3cbe d:2012-01-01T00:00:00.000Z t:site="Arlington Heights Village Hall" t:zip=60005 t:hours="Monday-Saturday: 9 a.m.–5 p.m.; Sunday: 9 a.m. – 3 p.m." t:state=IL t:city="Arlington Heights" m:row_number.c5zu-3cbe=2

series e:c5zu-3cbe d:2012-01-01T00:00:00.000Z t:site="Barrington Township Hall" t:zip=60010 t:hours="Monday-Saturday: 9 a.m.–5 p.m." t:state=IL t:city=Barrington m:row_number.c5zu-3cbe=3
```

## Meta Commands

```ls
metric m:row_number.c5zu-3cbe p:long l:"Row Number"

entity e:c5zu-3cbe l:"Early Voting Locations - 2012" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/c5zu-3cbe

property e:c5zu-3cbe t:meta.view v:id=c5zu-3cbe v:attributionLink=http://cookcountyclerk.com v:averageRating=0 v:name="Early Voting Locations - 2012" v:attribution="Cook County Clerk"

property e:c5zu-3cbe t:meta.view.license v:name="Public Domain"

property e:c5zu-3cbe t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:c5zu-3cbe t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| site                              | hours                                                   | address                      | city              | state | zip    | 
| ================================= | ======================================================= | ============================ | ================= | ===== | ====== | 
| Alsip Village Hall                | Monday-Saturday: 9 a.m.–5 p.m.                          | 4500 W. 123rd St             | Alsip             | IL    | 60803  | 
| Arlington Heights Village Hall    | Monday-Saturday: 9 a.m.–5 p.m.; Sunday: 9 a.m. – 3 p.m. | 33 S. Arlington Heights Road | Arlington Heights | IL    | 60005  | 
| Barrington Township Hall          | Monday-Saturday: 9 a.m.–5 p.m.                          | 602 S. Hough St              | Barrington        | IL    | 60010  | 
| Bellwood Village Hall             | Monday-Saturday: 9 a.m.–5 p.m.                          | 3200 Washington Blvd         | Bellwood          | IL    | 60104  | 
| Berwyn City Hall                  | Monday-Saturday: 9 a.m.–5 p.m.                          | 6700 W. 26th St.             | Berwyn            | IL    | 60402  | 
| Calumet City Public Library--NEW  | Monday-Saturday: 9 a.m.–5 p.m.; Sunday: 9 a.m. – 3 p.m. | 660 Manistee Ave.            | Calumet City      | IL    | 60409  | 
| Calumet Township Community Center | Monday-Saturday: 9 a.m.–5 p.m.                          | 12633 S. Ashland Ave.        | Calumet Park      | IL    | 60827  | 
| Chicago Heights City Hall         | Monday-Saturday: 9 a.m.–5 p.m.                          | 1601 Chicago Road            | Chicago Heights   | IL    | 60411  | 
| Cicero Community Center--NEW      | Monday-Saturday: 9 a.m.–5 p.m.; Sunday: 9 a.m. – 3 p.m. | 2250 S. 49th Ave             | Cicero            | IL    | 60804  | 
| Cicero PSO Building               | Monday-Saturday: 9 a.m.–5 p.m.; Sunday: 9 a.m. – 3 p.m. | 5410 W. 34th St              | Cicero            | IL    | 60804  | 
```