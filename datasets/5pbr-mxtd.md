# IDNYC Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idnyc-locations) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/5pbr-mxtd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/5pbr-mxtd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/5pbr-mxtd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 5pbr-mxtd |
| Name | IDNYC Locations |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | idnyc locations, identification, enrollment, apply, application |
| Created | 2016-04-07T16:27:03Z |
| Publication Date | 2016-07-14T21:22:15Z |

## Description

Locations where people can apply for IDNYC (Not including pop-up enrollment centers).

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| No       |             | id          | ID         | text      | number      |
| Yes      | series tag  | name        | name       | text      | text        |
| No       |             | address1    | address1   | text      | text        |
| No       |             | address2    | address2   | text      | text        |
| Yes      | series tag  | city        | city       | text      | text        |
| Yes      | series tag  | zip         | zip        | text      | text        |
| Yes      | series tag  | hours       | hours      | text      | text        |
| Yes      | series tag  | type        | type       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,address1,address2
```

## Data Commands

```ls
series e:5pbr-mxtd d:2017-02-03T21:35:57.000Z t:zip=11372 t:hours="Open January 18 through January 27, 2016<br>Monday - Friday: 10:00AM - 6:00PM" t:name="Queens- Council Member Daniel Dromm's Office" t:type=temporary t:city="Jackson Height" m:row_number.5pbr-mxtd=1

series e:5pbr-mxtd d:2017-02-03T21:35:57.000Z t:zip=11355 t:hours="Open February 16 through March 2, 2017<br>Monday - Friday: 8:40am - 4pm" t:name="Queens - SelfHelp Innovative Center" t:city=Flushing m:row_number.5pbr-mxtd=2

series e:5pbr-mxtd d:2017-02-03T21:35:57.000Z t:zip=11432 t:hours="Monday - Thursday: 9:00am - 8:00pm<br>Friday: 9:00am - 7:00pm<br>Saturday: 10:00am - 5:00pm<br>Sunda" t:name="Queens - Central Library in Jamaica" t:type=permanent t:city=Queens m:row_number.5pbr-mxtd=3
```

## Meta Commands

```ls
metric m:row_number.5pbr-mxtd p:long l:"Row Number"

entity e:5pbr-mxtd l:"IDNYC Locations" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/5pbr-mxtd

property e:5pbr-mxtd t:meta.view v:id=5pbr-mxtd v:category="Social Services" v:averageRating=0 v:name="IDNYC Locations" v:attribution="Human Resources Administration (HRA)"

property e:5pbr-mxtd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:5pbr-mxtd t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | id   | name                                                               | address1                            | address2                             | city           | zip   | hours                                                                                       | type      | 
| =========== | ==== | ================================================================== | =================================== | ==================================== | ============== | ===== | =========================================================================================== | ========= | 
| 1486157757  | 1915 | Queens- Council Member Daniel Dromm's Office                       | 37-32 75th St, 1st Fl               |                                      | Jackson Height | 11372 | Open January 18 through January 27, 2016
Monday - Friday: 10:00AM - 6:00PM                  | temporary | 
| 1486157757  | 1942 | Queens - SelfHelp Innovative Center                                | 45-25 Kissena Boulevard             |                                      | Flushing       | 11355 | Open February 16 through March 2, 2017
Monday - Friday: 8:40am - 4pm                        |           | 
| 1486157757  | 1059 | Queens - Central Library in Jamaica                                | 89-11 Merrick Blvd                  | (at 89th Ave and Merrick Blvd)       | Queens         | 11432 | Monday - Thursday: 9:00am - 8:00pm
Friday: 9:00am - 7:00pm
Saturday: 10:00am - 5:00pm
Sunda | permanent | 
| 1486157757  | 1941 | Manhattan - Educational Alliance, Center for Recovery and Wellness | 25-29 Avenue D                      |                                      | New York       | 10009 | Open February 6 through February 24, 2017
Monday - Friday: 9:00AM - 5:00PM                  | tempoary  | 
| 1486157757  | 1001 | Bronx - Bronx Library Center                                       | 310 East Kingsbridge Road           | (at Kingsbridge and Briggs)          | Bronx          | 10458 | Mon, Tue, Wed, Thu, Fri: 9:00am - 7:00pm
Sat: 9:00am - 6:00pm
Sun: 12:00pm - 6:00pm         | permanent | 
| 1486157757  | 1000 | Queens - Flushing Library                                          | 41-17 Main Street                   | (at 41st Rd and Main St)             | Flushing       | 11355 | Monday - Thursday: 9:00am - 8:00pm
Friday: 9:00am - 7:00pm
Saturday: 10:00am - 5:00pm
Sunda | permanent | 
| 1486157757  | 1004 | Manhattan - Neighborhood Trust Federal Credit Union                | 1112 St. Nicholas Avenue, 1st Floor | (at W 166th St and St. Nicholas Ave) | New York       | 10032 | Mon, Tue, Fri: 9:00am - 4:00pm
Wed: 9:00am - 1:00pm
Thu: 9:00am - 6:00pm
Sat: 10:00am - 2:0 | permanent | 
| 1486157757  | 1606 | Brooklyn - Asian Americans for Equality                            | 807 48th Street, 2nd Floor          |                                      | Brooklyn       | 11220 | Tue, Wed, Thu, Fri, Sat: 9:00am - 5:00pm                                                    | permanent | 
| 1486157757  | 1613 | Manhattan - East Harlem Health Center                              | 158 East 115 Street                 |                                      | New York       | 10029 | Mon-Fri: 9:00am-5:00pm                                                                      | permanent | 
| 1486157757  | 1002 | Manhattan - Mid-Manhattan Library                                  | 455 5th Avenue, 4th Fl.             | (at E 40th St and 5th Ave)           | New York       | 10016 | Monday - Friday 9:00am - 7:00pm
Saturday and Sunday: 10:00am - 4:00pm                       | permanent | 
```