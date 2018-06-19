# Missouri Cooling Centers Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-cooling-centers-sites-9243f) |
| Metadata | [Link](https://data.mo.gov/api/views/ks2s-yguy) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/ks2s-yguy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/ks2s-yguy/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | ks2s-yguy |
| Name | Missouri Cooling Centers Sites |
| Attribution | Missouri Department of Health & Senior Services |
| Category | Health |
| Tags | cooling centers, heat |
| Created | 2012-07-05T17:07:44Z |
| Publication Date | 2012-07-05T21:47:54Z |

## Description

Cooling Centers Sites in Missouri

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | facility           | FACILITY           | text      | text        |
| No       |             | address            | ADDRESS            | text      | text        |
| Yes      | series tag  | city               | CITY               | text      | text        |
| Yes      | series tag  | zipcode            | ZIPCODE            | text      | text        |
| Yes      | series tag  | county             | COUNTY             | text      | text        |
| Yes      | series tag  | phone              | PHONE              | text      | text        |
| Yes      | series tag  | hours_of_operation | HOURS OF OPERATION | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:ks2s-yguy d:2012-07-05T14:43:11.000Z t:phone=PHONE t:facility=FACILITY t:county=COUNTY t:hours_of_operation=HOURS_OF_OPERATION t:zipcode=ZIP t:city=CITY m:row_number.ks2s-yguy=1

series e:ks2s-yguy d:2012-07-05T14:43:11.000Z t:phone=618-465-7764 t:facility="The Salvation Army - Alton" t:county=Madison t:hours_of_operation="M-F 9-4:30" t:zipcode=62002 t:city=Alton m:row_number.ks2s-yguy=2

series e:ks2s-yguy d:2012-07-05T14:43:11.000Z t:phone=618-466-3324 t:facility="Godfrey Township General Assistance" t:county=Madison t:zipcode=62035 t:city=Godfrey m:row_number.ks2s-yguy=3
```

## Meta Commands

```ls
metric m:row_number.ks2s-yguy p:long l:"Row Number"

entity e:ks2s-yguy l:"Missouri Cooling Centers Sites" t:attribution="Missouri Department of Health & Senior Services" t:url=https://data.mo.gov/api/views/ks2s-yguy

property e:ks2s-yguy t:meta.view v:id=ks2s-yguy v:category=Health v:averageRating=0 v:name="Missouri Cooling Centers Sites" v:attribution="Missouri Department of Health & Senior Services"

property e:ks2s-yguy t:meta.view.owner v:id=63ti-ur4n v:screenName="Department of Health" v:displayName="Department of Health"

property e:ks2s-yguy t:meta.view.tableauthor v:id=63ti-ur4n v:screenName="Department of Health" v:roleName=editor v:displayName="Department of Health"
```

## Top Records

```ls
| :updated_at | facility                              | address          | city          | zipcode | county   | phone        | hours_of_operation      | 
| =========== | ===================================== | ================ | ============= | ======= | ======== | ============ | ======================= | 
| 1341499391  | FACILITY                              | ADDRESS          | CITY          | ZIP     | COUNTY   | PHONE        | HOURS_OF_OPERATION      | 
| 1341499391  | The Salvation Army - Alton            | 525 Alby St      | Alton         | 62002   | Madison  | 618-465-7764 | M-F 9-4:30              | 
| 1341499391  | Godfrey Township General Assistance   | 6810 Godfrey Rd  | Godfrey       | 62035   | Madison  | 618-466-3324 |                         | 
| 1341499391  | Chouteau Township Hall                | 906 Thorngate Rd | Granite City  | 62040   | Madison  | 618-931-0360 | M-F 9-4                 | 
| 1341499391  | Clyde Jordan Senior Citizens Center   | 6755 State St    | East St Louis | 62203   | St Clair | 618-293-6700 | M-F 8-4                 | 
| 1341499391  | Lessie Bates Davis Neighborhood House | 1200 N 13th St   | East St Louis | 62205   | St Clair | 618-874-0777 | M-Th 8:30-5 F 8:30-4:30 | 
| 1341499391  | The Salvation Army - East St Louis    | 616 N 16th St    | East St Louis | 62205   | St Clair | 618-874-3136 | M-Th 9-3                | 
| 1341499391  | The Salvation Army - Belleville Corps | 20 Glory Pl      | Belleville    | 62226   | St Clair | 618-235-7378 | M-F 10-12 1-2:30        | 
| 1341499391  | Collinsville Senior Citizens Center   | 420 E Main St    | Collinsville  | 62234   | Madison  | 618-344-7787 | M-F 8-4                 | 
| 1341499391  | Faith Countryside Homes               | 1331 26th St     | Highland      | 62249   | Madison  | 618-651-3290 | MWF 8-7:30 T Th 8-4:30  | 
```