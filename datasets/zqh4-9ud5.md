# Baltimore City Murals Project 1987 to Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baltimore-city-murals-project-1987-to-present-d7f6f) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/zqh4-9ud5) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/zqh4-9ud5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/zqh4-9ud5/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | zqh4-9ud5 |
| Name | Baltimore City Murals Project 1987 to Present |
| Attribution | The Baltimore Office of Promotion & The Arts |
| Category | Culture & Arts |
| Tags | art, mural, painting |
| Created | 2012-03-30T12:48:03Z |
| Publication Date | 2014-04-03T23:23:40Z |

## Description

Mayor Stephanie Rawlings-Blake and the Baltimore Office of Promotion & The Arts have announced CityPaint 2012: Baltimore Mural Program.  This initiative will decorate Baltimore City with numerous murals this year. As part of the Cleaner, Greener Baltimore program, the city is partnering with neighborhood groups, community organizations, artists and corporations for CityPaint 2012.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| Yes      | series tag  | location        | location        | text      | text        |
| Yes      | series tag  | artistfirstname | artistFirstName | text      | text        |
| Yes      | series tag  | artistlastname  | artistLastName  | text      | text        |
| Yes      | time        | year            | YEAR            | number    | text        |
| Yes      | series tag  | image           | image           | document  | document    |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:zqh4-9ud5 l:"Baltimore City Murals Project 1987 to Present" t:attribution="The Baltimore Office of Promotion & The Arts" t:url=https://data.baltimorecity.gov/api/views/zqh4-9ud5

property e:zqh4-9ud5 t:meta.view v:id=zqh4-9ud5 v:category="Culture & Arts" v:attributionLink=http://www.bop.org v:averageRating=0 v:name="Baltimore City Murals Project 1987 to Present" v:attribution="The Baltimore Office of Promotion & The Arts"

property e:zqh4-9ud5 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:zqh4-9ud5 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:zqh4-9ud5 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| location                              | artistfirstname | artistlastname | year | image                                                                                                                                     | 
| ===================================== | =============== | ============== | ==== | ========================================================================================================================================= | 
| 1731 E. Chase St.                     | Jennifer        | Rattigan       | 2004 | [null, null, null, null]                                                                                                                  | 
| N. Patterson Park Ave. and N. Gay St. | Lyle            | Kissack        | 2004 | [null, null, null, null]                                                                                                                  | 
| 1103 Brentwood Ave.                   | Gary            | Mullen         | 2000 | [null, null, null, null]                                                                                                                  | 
| N. Patterson Park Ave. and N. Gay St. | Alexander       | Martray        | 2004 | [null, null, null, null]                                                                                                                  | 
| 711 N. Carey St.                      | Deborah         | English        | 1989 | [image/jpeg; charset=binary, mav3nMczyXG9llGV1t-ChAblpY5vBRQtdeYKQnMmKo8, English - 711 N. Carey Street.JPG, 181876]                      | 
| 141 S. Central Ave.                   | Donna           | McCullough     | 1989 | [image/jpeg; charset=binary, 3FNrFd_XXQGkMvw0yyJCnL4EzQLBDJ77JG9691u55MU, mccullough-141 s central ave.JPG, 165633]                       | 
| 1611 Carey St.                        | Pontella        | Mason          | 1990 | [image/jpeg; charset=binary, evXoBq6ZlVrYMft4l5cE2HCj4SQorAzOFYkec69WDNg, mason-carey & cumberland.jpg, 3759322]                          | 
| 2229 1/2 W. Pratt St.                 | James           | Voshell        | 1990 | [image/jpeg; charset=binary, SPRvi2RI3Pl15prfuZ80nAlGZ_lgCsCxCSwt7-E9UP4, voshell-2229.5 w pratt st.jpg, 90228]                           | 
| 400 N. Pulaski St.                    | Archie          | Veale          | 1994 | [image/jpeg; charset=binary, pm-WHuygg1Lle38AFItdwpZkBD1fKIY1rZTg3jT3ZxA, veale-400 n pulaski st.JPG, 136416]                             | 
| 2324 McElderry St.                    | Patrick         | Jacobson       | 1995 | [image/jpeg; charset=binary, MT9IQB8HEn1FygD0SAKQgM9bLm0j01zkgHiAlQUXpOo, jacobson-2324 mcelderry st - hope for the children.JPG, 202616] | 
```