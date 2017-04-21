# CIP Project Phase List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cip-project-phase-list-c4102) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/79k8-wsem) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/79k8-wsem/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/79k8-wsem/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 79k8-wsem |
| Name | CIP Project Phase List |
| Tags | cip, project phase list |
| Created | 2014-05-23T15:29:54Z |
| Publication Date | 2014-10-12T00:49:48Z |

## Description

A list of Project Phases the County employs in managing and tracking its capital projects.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | phase_type             | Phase Type             | text      | text        |
| Yes      | series tag  | phase_step_number      | Phase Step Number      | text      | number      |
| Yes      | series tag  | phase_step_name        | Phase Step Name        | text      | text        |
| Yes      | series tag  | phase_step_description | Phase Step Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:79k8-wsem d:2014-05-23T08:29:56.000Z t:phase_step_description="User departments and DGS identity the needs/scope/goals of project. Usually in-house. POR (Program of Requirements) produced at this stage." t:phase_step_number=1 t:phase_type=1 t:phase_step_name=Planning m:row_number.79k8-wsem=1

series e:79k8-wsem d:2014-05-23T08:29:56.000Z t:phase_step_description="Architects and engineers work from the defined scope and budget to develop the design, and produce construction drawings, etc." t:phase_step_number=2 t:phase_type=1 t:phase_step_name="Preliminary Design" m:row_number.79k8-wsem=2

series e:79k8-wsem d:2014-05-23T08:29:56.000Z t:phase_step_description="Design complete. Construction documents complete. Ready to award contract." t:phase_step_number=3 t:phase_type=1 t:phase_step_name="Final Design" m:row_number.79k8-wsem=3
```

## Meta Commands

```ls
metric m:row_number.79k8-wsem p:long l:"Row Number"

entity e:79k8-wsem l:"CIP Project Phase List" t:url=https://data.montgomerycountymd.gov/api/views/79k8-wsem

property e:79k8-wsem t:meta.view v:id=79k8-wsem v:averageRating=0 v:name="CIP Project Phase List"

property e:79k8-wsem t:meta.view.owner v:id=qzhb-tftn v:screenName="Kathy Luh" v:displayName="Kathy Luh"

property e:79k8-wsem t:meta.view.tableauthor v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"
```

## Top Records

```ls
| :updated_at | phase_type | phase_step_number | phase_step_name    | phase_step_description                                                                                                                      | 
| =========== | ========== | ================= | ================== | =========================================================================================================================================== | 
| 1400833796  | 1          | 1                 | Planning           | User departments and DGS identity the needs/scope/goals of project. Usually in-house. POR (Program of Requirements) produced at this stage. | 
| 1400833796  | 1          | 2                 | Preliminary Design | Architects and engineers work from the defined scope and budget to develop the design, and produce construction drawings, etc.              | 
| 1400833796  | 1          | 3                 | Final Design       | Design complete. Construction documents complete. Ready to award contract.                                                                  | 
| 1400833796  | 1          | 4                 | Bids Let           | Contractor is selected based on several procurement criteria.                                                                               | 
| 1400833796  | 1          | 5                 | Under Construction | Contractors work from the instruction s contained in design documents to complete facility.                                                 | 
| 1400833796  | 1          | 6                 | Ongoing            | Refers to level of effort projects or projects that occur each year (i.e., roof replacement)                                                | 
| 1400833796  | 1          | 7                 | Completed          | All project activities have been completed and paid for.                                                                                    | 
```