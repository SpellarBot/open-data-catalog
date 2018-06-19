# All Live Births In Illinois, 1989-2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/all-live-births-in-illinois-1989-2009-1f7b2) |
| Metadata | [Link](https://data.illinois.gov/api/views/9e74-xdvk) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/9e74-xdvk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/9e74-xdvk/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 9e74-xdvk |
| Name | All Live Births In Illinois, 1989-2009 |
| Attribution | Illinois Department of Public Health, Office of Policy, Planning, and Statistics, Illinois Center for Health Statistics |
| Category | Health |
| Tags | health, birth, baby, vital statistics, population |
| Created | 2014-08-12T14:31:24Z |
| Publication Date | 2014-08-12T14:33:49Z |

## Description

Data provided by IL Center for Health Statistics.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | county_name | COUNTY NAME | text      | text        |
| Yes      | numeric metric | 1989        | 1989        | number    | number      |
| Yes      | numeric metric | 1990        | 1990        | number    | number      |
| Yes      | numeric metric | 1991        | 1991        | number    | number      |
| Yes      | numeric metric | 1992        | 1992        | number    | number      |
| Yes      | numeric metric | 1993        | 1993        | number    | number      |
| Yes      | numeric metric | 1994        | 1994        | number    | number      |
| Yes      | numeric metric | 1995        | 1995        | number    | number      |
| Yes      | numeric metric | 1996        | 1996        | number    | number      |
| Yes      | numeric metric | 1997        | 1997        | number    | number      |
| Yes      | numeric metric | 1998        | 1998        | number    | number      |
| Yes      | numeric metric | 1999        | 1999        | number    | number      |
| Yes      | numeric metric | 2000        | 2000        | number    | number      |
| Yes      | numeric metric | 2001        | 2001        | number    | number      |
| Yes      | numeric metric | 2002        | 2002        | number    | number      |
| Yes      | numeric metric | 2003        | 2003        | number    | number      |
| Yes      | numeric metric | 2004        | 2004        | number    | number      |
| Yes      | numeric metric | 2005        | 2005        | number    | number      |
| Yes      | numeric metric | 2006        | 2006        | number    | number      |
| Yes      | numeric metric | 2007        | 2007        | number    | number      |
| Yes      | numeric metric | 2008        | 2008        | number    | number      |
| Yes      | numeric metric | 2009        | 2009        | number    | number      |
```

## Time Field

```ls
Value = 1989
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9e74-xdvk d:1989-01-01T00:00:00.000Z t:county_name="ILLINOIS TOTAL" m:2008=176634 m:2009=171077 m:2006=180503 m:2007=180530 m:2004=180665 m:2005=178872 m:2002=180555 m:2003=182393 m:1990=195499 m:1995=185801 m:1996=183079 m:1997=180649 m:1998=182503 m:1991=194066 m:1992=190923 m:1993=190709 m:1994=189182 m:1989=190247 m:1999=182027 m:2001=184022 m:2000=185003

series e:9e74-xdvk d:1989-01-01T00:00:00.000Z t:county_name=ADAMS m:2008=817 m:2009=804 m:2006=805 m:2007=890 m:2004=802 m:2005=883 m:2002=760 m:2003=794 m:1990=960 m:1995=828 m:1996=830 m:1997=812 m:1998=862 m:1991=971 m:1992=881 m:1993=893 m:1994=865 m:1989=928 m:1999=843 m:2001=866 m:2000=825

series e:9e74-xdvk d:1989-01-01T00:00:00.000Z t:county_name=ALEXANDER m:2008=120 m:2009=114 m:2006=112 m:2007=136 m:2004=126 m:2005=122 m:2002=129 m:2003=141 m:1990=192 m:1995=140 m:1996=147 m:1997=132 m:1998=140 m:1991=164 m:1992=189 m:1993=152 m:1994=158 m:1989=175 m:1999=117 m:2001=138 m:2000=132
```

## Meta Commands

```ls
metric m:1989 p:integer l:1989 t:dataTypeName=number

metric m:1990 p:integer l:1990 t:dataTypeName=number

metric m:1991 p:integer l:1991 t:dataTypeName=number

metric m:1992 p:integer l:1992 t:dataTypeName=number

metric m:1993 p:integer l:1993 t:dataTypeName=number

metric m:1994 p:integer l:1994 t:dataTypeName=number

metric m:1995 p:integer l:1995 t:dataTypeName=number

metric m:1996 p:integer l:1996 t:dataTypeName=number

metric m:1997 p:integer l:1997 t:dataTypeName=number

metric m:1998 p:integer l:1998 t:dataTypeName=number

metric m:1999 p:integer l:1999 t:dataTypeName=number

metric m:2000 p:integer l:2000 t:dataTypeName=number

metric m:2001 p:integer l:2001 t:dataTypeName=number

metric m:2002 p:integer l:2002 t:dataTypeName=number

metric m:2003 p:integer l:2003 t:dataTypeName=number

metric m:2004 p:integer l:2004 t:dataTypeName=number

metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

entity e:9e74-xdvk l:"All Live Births In Illinois, 1989-2009" t:attribution="Illinois Department of Public Health, Office of Policy, Planning, and Statistics, Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/9e74-xdvk

property e:9e74-xdvk t:meta.view v:id=9e74-xdvk v:category=Health v:averageRating=0 v:name="All Live Births In Illinois, 1989-2009" v:attribution="Illinois Department of Public Health, Office of Policy, Planning, and Statistics, Illinois Center for Health Statistics"

property e:9e74-xdvk t:meta.view.license v:name="Public Domain"

property e:9e74-xdvk t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:9e74-xdvk t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county_name    | 1989   | 1990   | 1991   | 1992   | 1993   | 1994   | 1995   | 1996   | 1997   | 1998   | 1999   | 2000   | 2001   | 2002   | 2003   | 2004   | 2005   | 2006   | 2007   | 2008   | 2009   | 
| ============== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | 
| ILLINOIS TOTAL | 190247 | 195499 | 194066 | 190923 | 190709 | 189182 | 185801 | 183079 | 180649 | 182503 | 182027 | 185003 | 184022 | 180555 | 182393 | 180665 | 178872 | 180503 | 180530 | 176634 | 171077 | 
| ADAMS          | 928    | 960    | 971    | 881    | 893    | 865    | 828    | 830    | 812    | 862    | 843    | 825    | 866    | 760    | 794    | 802    | 883    | 805    | 890    | 817    | 804    | 
| ALEXANDER      | 175    | 192    | 164    | 189    | 152    | 158    | 140    | 147    | 132    | 140    | 117    | 132    | 138    | 129    | 141    | 126    | 122    | 112    | 136    | 120    | 114    | 
| BOND           | 187    | 195    | 195    | 185    | 206    | 200    | 202    | 194    | 193    | 201    | 188    | 184    | 196    | 172    | 239    | 209    | 189    | 215    | 185    | 173    | 198    | 
| BOONE          | 445    | 462    | 464    | 462    | 497    | 538    | 566    | 529    | 531    | 545    | 595    | 587    | 629    | 629    | 668    | 646    | 744    | 737    | 736    | 676    | 622    | 
| BROWN          | 57     | 68     | 72     | 72     | 50     | 58     | 58     | 58     | 64     | 41     | 51     | 63     | 57     | 54     | 76     | 56     | 54     | 57     | 60     | 64     | 65     | 
| BUREAU         | 425    | 449    | 448    | 414    | 389    | 429    | 417    | 417    | 389    | 417    | 396    | 434    | 420    | 434    | 458    | 396    | 409    | 392    | 413    | 409    | 381    | 
| CALHOUN        | 41     | 53     | 54     | 55     | 75     | 48     | 48     | 49     | 37     | 57     | 47     | 51     | 49     | 48     | 58     | 51     | 58     | 55     | 49     | 59     | 53     | 
| CARROLL        | 207    | 222    | 179    | 201    | 202    | 189    | 173    | 175    | 163    | 185    | 193    | 170    | 147    | 191    | 154    | 151    | 160    | 140    | 163    | 142    | 123    | 
| CASS           | 166    | 187    | 211    | 161    | 183    | 171    | 166    | 150    | 185    | 188    | 191    | 181    | 215    | 185    | 208    | 181    | 199    | 177    | 195    | 200    | 164    | 
```