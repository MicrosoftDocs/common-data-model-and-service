# Customer Service
## Case (Case) Entity 
An incident that your customers face for a product, service, or interaction. 

Field | Description
---|---
ArrivalDate | Data: DateTime<br>Required
CaseID<br>Primary key | Number sequence: <br>Unique
Category | Enumeration: CaseCategoryValues: Problem, Question, Request<br>Required
CloseDate | Data: DateTime
Comment | Data: MultilineText
Contact | Lookup: Contacts
Customer | Lookup: Customer
CustomerSatisfactionCode | Enumeration: CaseCustomerSatisfactionCodeValues: Dissatisfied, Neutral, Satisfied, VeryDissatisfied, VerySatisfied
Description | Data: Text<br>Maximum length: 255
Name | Data: Text<br>Required, Maximum length: 60<br>Description: Case Name 
OriginCode | Enumeration: CaseOriginCodeValues: Email, Facebook, Other, Phone, Twitter, Web<br>Required
ParentCase | Lookup: Case
Severity | Enumeration: SeverityValues: High, Low, Normal<br>Required
SolutionType | Enumeration: CaseSolutionTypeValues: SolvedByCustomer, SolvedByKBArticle, SolvedBySupportWorker
Status | Enumeration: CaseStatusValues: Active, Cancelled, Closed, OnHold, Resolved, SolvedAnswered<br>Required
## CaseActivity (Case Activity) Entity 
Any step that is taken on a case: creation of a case, escalation of a case, or resolution or closing of a case, including all state transitions of the case. 

Field | Description
---|---
BeginDate | Data: DateTime<br>Required
CaseActivityId<br>Primary key | Number sequence: <br>Unique
Comment | Data: MultilineText
Contact | Lookup: Contacts
ContactType | Enumeration: CaseOriginCodeValues: Email, Facebook, Other, Phone, Twitter, Web
CurrentCaseSeverity | Enumeration: SeverityValues: High, Low, Normal<br>Required
CurrentCaseStatus | Enumeration: CaseStatusValues: Active, Cancelled, Closed, OnHold, Resolved, SolvedAnswered<br>Required
Description | Data: Text<br>Maximum length: 255
Duration | Data: Integer
EndDate | Data: DateTime
HasKBArticle | Data: Boolean<br>Required
IsReassignment | Data: Boolean<br>Required
IsSeverityChange | Data: Boolean<br>Required
IsStatusChange | Data: Boolean<br>Required
ParentCaseActivity | Lookup: CaseActivity
PriorCaseSeverity | Enumeration: SeverityValues: High, Low, Normal
PriorCaseStatus | Enumeration: CaseStatusValues: Active, Cancelled, Closed, OnHold, Resolved, SolvedAnswered
Sequence | Number sequence: 
SupportCase | Lookup: Case
SupportWorker | Lookup: Employee
Type | Enumeration: CaseActivityTypeValues: AssisgReassignCaseWorker, Cancel, ChangeCaseStatus, Close, Contact, CreateSubcase, Intake, MakeKBReference, Open, Research<br>Required
## CaseActivityKBArticle (Case Activity KB Article) Entity 
A KB article that is released as part of a case. 

Field | Description
---|---
ArticleValue | Data: Integer
CaseActivity | Lookup: CaseActivity
CaseActivityKBArticleId<br>Primary key | Number sequence: <br>Unique
Description | Data: Text<br>Maximum length: 255
KBArticle | Lookup: KBArticle
KBArticleName | Data: Text<br>Maximum length: 60
## CaseWorkerAssignment (Case Worker Assignment) Entity 
The assignment of a case worker and a case. 

Field | Description
---|---
AssignFromSupportWorker | Lookup: Employee
AssignToSupportWorker | Lookup: Employee<br>Required
CaseActivity | Lookup: CaseActivity
CaseWorkerAssignmentID<br>Primary key | Number sequence: <br>Unique
Comment | Data: MultilineText
Description | Data: Text<br>Maximum length: 255
Reason | Enumeration: CaseWorkerAssignmentReasonValues: CaseSeverityChange, Initial, Other, Reassign
## KBArticle (KB Article) Entity 
A KB document that contains reusable steps to solve a case. 

Field | Description
---|---
ArticleScore | Data: Integer
Author | Lookup: Employee
Description | Data: Text<br>Maximum length: 255
KBArticleId<br>Primary key | Number sequence: <br>Unique<br>Description: Case Id 
LinkToArticle | Data: WebsiteUrl
Synopsis | Data: MultilineText
