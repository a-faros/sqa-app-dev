
# Introduction
## Comparison Table

 ||Business Requirements Specification|Software Requirements Specification|Software Design Specification|
 |-|---|---|---|
 |Referred as|  **BRS**| **SRS**|**SDS**|
|Definition| A formal document that describes the various requirements provided by the business & describes the various requirements provided by the client.|	It specifies the functional and non-functional requirements present in the software. | Describe the actual software, most from a technical perpective.|
|Creation| derived from the client’s requirements and the client’s interaction | derived from the BRS.| exist when a system is developed. Fine difference, to SRS, _refer Note_ **SRS vs SDS.** | 
|Created by|a business analyst.| a system analyst or a system architect. _refer Note_ **SRS Created by.** |Development team.|
|Decribes|	the functional specifications of the software at a very high level.| the technical and functional specification of the software also at a high level.|
|Key terms| Business Function, Business Process & Activity| Module, Sub Module, ERD|

> [!NOTE]
> **_SRS vs SDS._** SDS may contain limitation that is unable to cater to the SRS and/or has features additional that SRS did not have a need.a\
> **_SRS Created by._**  Although, in some companies, the business analyst can also create an SRS. Some companies do not even have an SRS, instead, they make their BRS detailed enough so that it can be used as SRS.


## Visualizing it!

![](./images/Picture1.png)

## Relationships

> [!IMPORTANT]
> It is important to understand that BRS is not neccessarily a 1 to 1 match. There may be intances that the BRS needs to be developed using 2 or more SRS. Or a few BRS can be handled by an SRS.

![](./images/Picture2.png)



# Business Requirement Specification

## Business Case

> [!TIP]
> What is the reason for this need, the need to have this service/system?

## Scope

> [!TIP]
> What is expected to be covered? Also specify what is out of scope to allow better clarity.

## Stakeholder

> [!TIP]
> Who are the persons/groups of people affected by this?

| Stakeholder | Description |
| -------- | ------- |
| Employees  | All persons employee by this company. |
| HR Personnel | Person assigned to manage this system. |
| Operation Managers    | Group of persons, who perform approval functions.|  |

## Business Architecture

> [!TIP]
> In general the organization's setup. What are the mediums use for the service? The users of the service? The main service offering? The existing application systems? The information clusters? Information Providers/Management? The technology and infrastructure?

![](./images/bizArc.png)

## Information Architecture

> [!TIP]
> Specific to the service of the biz case, what information, information provider, business process, users.

![](./images/infoArc.png)

## Business Functions

### Hierarchy of business functions

![](./images/hierBF.png)

### Business Functions Description

![](./images/descBF.png)

### User List

![](./images/userList.png)

## Business Process Needs

### Models and definitions

#### Process Flow

![](./images/procFlow.png)

#### Activity Definition

![](./images/actDef.png)



# System Requirement Specification

## Purpose

> [!TIP]
> What is the reason for this need, the need to have this system?

## Scope

What is expected to be covered? Also specify what is out of scope to allow better clarity.

## User/Actors

Who are the persons/groups of people using this system?

![](./images/actorList.png)

## Systems Functions

### Hierarchy of systems functions

![](./images/hierSF.png)

### User/Actor List mapping

For each module, a map is created.

![](./images/actorMapping.png)

## Model Use Cases

For each module and sub module, use cases are created.

### Module Name

May usually relate to BRS Business Function

### Use Case Diagram

![](./images/uCaseDiag.png)

#### Use Case Description

![](./images/uCaseDesc.png)

### Sub Module Name

May usually relate to BRS Business Process

#### Use Case Diagram

![](./images/uCaseDiag2.png)

#### Use Case Description

![](./images/uCaseDesc2.png)

## Data Model

### Entity Relationship Diagram

![](./images/ERD.png)

### Data Definition

#### Entity Definition

![](./images/entDef.png)

## Process Model

### Contextual Diagram

#### Data Flow Diagram

![](./images/DFDiag.png)

#### Data Flow Definition

![](./images/DFDef.png)

## System Administration

Define module/sub modules that is required to maintain the system. These modules/sub modules does not have **direct** relation to the BRS.