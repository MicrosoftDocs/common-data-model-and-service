---
title: "Customer service reference"
description: ""
author: ""
manager: "robinarh"
ms.date: "08/24/2016"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataModel"
ms.technology: "CommonDataModel"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "ddd9b0a1-bd9e-46a9-bea0-ba021cf2f219"
---

# Customer Service
## Case (Case) Entity 
An incident that your customers face for a product, service, or interaction. 

Field | Description
---|---
Account | Lookup: Account
ArrivalDate | Data: DateTime<br>Required
CaseId<br>Primary key | Number sequence: <br>Unique
Category | Data: Picklist<br>Required
CloseDate | Data: DateTime
Comment | Data: MultilineText
CurrentAssignedSupportWorker | Lookup: Worker
CurrentContact | Lookup: Contact<br>Required
CustomerSatisfactionCode | Data: Picklist
Description | Data: Text<br>Maximum length: 255
Name | Data: Text<br>Required, Maximum length: 60<br>Description: Case name
OriginCode | Data: Picklist<br>Required<br>Description: Origin
ParentCase | Lookup: Case
Severity | Data: Picklist<br>Required
SolutionType | Data: Picklist
Status | Data: Picklist<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Name<br>Category<br>Status<br>Severity<br>ArrivalDate<br>Description<br>OriginCode<br>CurrentContact<br>ParentCase<br>Account<br>CustomerSatisfactionCode
DefaultList|Auto generated DefaultList field group|CaseId<br>Name<br>Category<br>Status<br>Severity<br>ArrivalDate
DefaultCard|Auto generated DefaultCard field group|CaseId<br>Name<br>Status<br>Severity
DefaultDetails|Auto generated DefaultDetails field group|CaseId<br>Name<br>Category<br>Status<br>Severity<br>ArrivalDate<br>Description<br>OriginCode<br>CurrentContact<br>ParentCase<br>Account<br>CustomerSatisfactionCode<br>CloseDate<br>SolutionType<br>Comment
DefaultLookup|Auto generated DefaultLookup field group|CaseId<br>Name<br>Category<br>Status<br>Severity
DefaultReport|Auto generated DefaultReport field group|CaseId<br>Name<br>Category<br>Status<br>Severity<br>ArrivalDate<br>Description<br>OriginCode<br>CurrentContact<br>ParentCase<br>Account<br>CustomerSatisfactionCode<br>CloseDate<br>SolutionType
DefaultIdentification|Auto generated DefaultIdentification field group|CaseId<br>Name
## CaseActivity (Case activity) Entity 
Any step that is taken on a case: creation of a case, escalation of a case, or resolution or closing of a case, including all state transitions of the case. 

Field | Description
---|---
BeginDate | Data: DateTime<br>Required
CaseSeverity | Data: Picklist<br>Required<br>Description: Current case severity
CaseStatus | Data: Picklist<br>Required<br>Description: Current case status
Comment | Data: MultilineText
Contact | Lookup: Contact
ContactType | Data: Picklist
Description | Data: Text<br>Maximum length: 255
EndDate | Data: DateTime
HasKBArticle | Data: Boolean<br>Required<br>Description: Has KB article(s)
IsReassignment | Data: Boolean<br>Required
IsSeverityChange | Data: Boolean<br>Required<br>Description: Is severity changed
IsStatusChange | Data: Boolean<br>Required<br>Description: Is status changed
PriorCaseSeverity | Data: Picklist
PriorCaseStatus | Data: Picklist
ReassignedComment | Data: Text<br>Maximum length: 255
ReassignedFromCaseWorker | Lookup: Worker
ReassignedReason | Data: Picklist<br>Description: Case reassigned reason
Sequence | Data: Integer<br>Required
SupportCase<br>Primary key | Lookup: Case<br>Required
SupportWorker | Lookup: Worker
Type | Data: Picklist<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|SupportCase<br>Sequence<br>Type<br>BeginDate<br>Description<br>Contact<br>ContactType<br>CaseSeverity<br>CaseStatus<br>HasKBArticle<br>IsReassignment<br>IsSeverityChange<br>IsStatusChange
DefaultList|Auto generated DefaultList field group|SupportCase<br>Sequence<br>Type<br>BeginDate<br>Description<br>CaseSeverity<br>CaseStatus
DefaultCard|Auto generated DefaultCard field group|SupportCase<br>Sequence<br>Type<br>BeginDate
DefaultDetails|Auto generated DefaultDetails field group|SupportCase<br>Sequence<br>Type<br>BeginDate<br>Description<br>Contact<br>ContactType<br>CaseSeverity<br>CaseStatus<br>Comment
DefaultLookup|Auto generated DefaultLookup field group|SupportCase<br>Sequence<br>Type<br>BeginDate<br>Description
DefaultReport|Auto generated DefaultReport field group|SupportCase<br>Sequence<br>Type<br>BeginDate<br>Description<br>Contact<br>ContactType<br>CaseSeverity<br>CaseStatus<br>HasKBArticle<br>IsReassignment<br>IsSeverityChange<br>IsStatusChange
DefaultIdentification|Auto generated DefaultIdentification field group|SupportCase<br>Sequence<br>Description
## CaseActivityKBArticle (Case activity KB article) Entity 
A KB article that is released as part of a case. 

Field | Description
---|---
ArticleValue | Data: Integer<br>Required
CaseActivity<br>Primary key | Lookup: CaseActivity<br>Required
Description | Data: Text<br>Maximum length: 255
KBArticle | Lookup: KBArticle<br>Required
KBArticleName | Data: Text<br>Maximum length: 60

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|CaseActivity<br>KBArticle<br>Description<br>KBArticleName<br>ArticleValue
DefaultList|Auto generated DefaultList field group|CaseActivity<br>KBArticle<br>Description<br>KBArticleName
DefaultCard|Auto generated DefaultCard field group|CaseActivity<br>KBArticle<br>KBArticleName
DefaultDetails|Auto generated DefaultDetails field group|CaseActivity<br>KBArticle<br>Description<br>KBArticleName<br>ArticleValue
DefaultLookup|Auto generated DefaultLookup field group|CaseActivity<br>KBArticle<br>Description
DefaultReport|Auto generated DefaultReport field group|CaseActivity<br>KBArticle<br>Description<br>KBArticleName<br>ArticleValue
DefaultIdentification|Auto generated DefaultIdentification field group|CaseActivity<br>KBArticle
## KBArticle (KB article) Entity 
A KB document that contains reusable steps to solve a case. 

Field | Description
---|---
ArticleScore | Data: Integer
Author | Lookup: Worker<br>Required
Description | Data: Text<br>Maximum length: 255
KBArticleId<br>Primary key | Number sequence: <br>Unique
LinkToArticle | Data: WebsiteUrl
Synopsis | Data: MultilineText

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Description<br>Author<br>ArticleScore<br>LinkToArticle<br>Synopsis
DefaultList|Auto generated DefaultList field group|KBArticleId<br>Description<br>Author<br>ArticleScore
DefaultCard|Auto generated DefaultCard field group|KBArticleId<br>Author<br>ArticleScore
DefaultDetails|Auto generated DefaultDetails field group|KBArticleId<br>Description<br>Author<br>ArticleScore<br>LinkToArticle<br>Synopsis
DefaultLookup|Auto generated DefaultLookup field group|KBArticleId<br>Description<br>Author
DefaultReport|Auto generated DefaultReport field group|KBArticleId<br>Description<br>Author<br>ArticleScore<br>LinkToArticle<br>Synopsis
DefaultIdentification|Auto generated DefaultIdentification field group|KBArticleId<br>Description
