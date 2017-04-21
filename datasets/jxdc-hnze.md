# Times Square Entertainment Venues

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/times-square-entertainment-venues-c8ebb) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jxdc-hnze) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jxdc-hnze/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jxdc-hnze/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jxdc-hnze |
| Name | Times Square Entertainment Venues |
| Attribution | Times Square Alliance (TSA) |
| Category | Business |
| Tags | times square alliance, times square, crossroads, crossroads of the world, nyc, new york city, new york, manhattan, theater, food, screens, pedestrian, entertainment, tourism |
| Created | 2011-07-26T20:44:07Z |
| Publication Date | 2013-06-21T19:26:07Z |

## Description

Directory of entertainment venues in the Times Square area Update Schedule: As required

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | company_name    | Company Name    | text      | text        |
| Yes      | series tag  | subindustry     | Subindustry     | text      | text        |
| Yes      | series tag  | sub_subindustry | Sub Subindustry | text      | text        |
| Yes      | series tag  | phone           | Phone           | text      | text        |
| Yes      | series tag  | website         | Website         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jxdc-hnze d:2011-07-26T13:44:08.000Z t:phone="(212) 239-6200" t:company_name="Al Hirschfeld Theater" t:subindustry=Theater t:sub_subindustry=League m:row_number.jxdc-hnze=1

series e:jxdc-hnze d:2011-07-26T13:44:08.000Z t:phone="212-586-7829 x304" t:company_name="The World Famous Laugh Factory" t:subindustry="Comedy Club" m:row_number.jxdc-hnze=2

series e:jxdc-hnze d:2011-07-26T13:44:08.000Z t:phone="(212) 239-2820" t:company_name="Bernard B. Jacobs Theatre" t:subindustry=Theater t:sub_subindustry=League m:row_number.jxdc-hnze=3
```

## Meta Commands

```ls
metric m:row_number.jxdc-hnze p:long l:"Row Number"

entity e:jxdc-hnze l:"Times Square Entertainment Venues" t:attribution="Times Square Alliance (TSA)" t:url=https://data.cityofnewyork.us/api/views/jxdc-hnze

property e:jxdc-hnze t:meta.view v:id=jxdc-hnze v:category=Business v:averageRating=0 v:name="Times Square Entertainment Venues" v:attribution="Times Square Alliance (TSA)"

property e:jxdc-hnze t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jxdc-hnze t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | company_name                                   | subindustry             | sub_subindustry | phone             | website           | 
| =========== | ============================================== | ======================= | =============== | ================= | ================= | 
| 1311687848  | Al Hirschfeld Theater                          | Theater                 | League          | (212) 239-6200    |                   | 
| 1311687848  | The World Famous Laugh Factory                 | Comedy Club             |                 | 212-586-7829 x304 |                   | 
| 1311687848  | Bernard B. Jacobs Theatre                      | Theater                 | League          | (212) 239-2820    |                   | 
| 1311687848  | Music Box Theater                              | Theater                 | League          | 212 239-6200      |                   | 
| 1311687848  | Helen Hayes Theatre                            | Theater                 | League          | (212) 944-9457    |                   | 
| 1311687848  | Touch Nightclub                                | Nightclub               |                 | 212 489-7656      |                   | 
| 1311687848  | Hawthorne Amusement                            | Attractions / Amusement |                 |                   |                   | 
| 1311687848  | Regal Loews Cinemas 42nd Street E-Walk Theater | Movies                  |                 | (212) 840-7761    | www.regmovies.com | 
| 1311687848  | Jujamcyn Theater                               | Theater                 | League          | (212) 840-8181    |                   | 
| 1311687848  | St. James Theatre                              | Theater                 | League          | (212) 239-6200    |                   | 
```