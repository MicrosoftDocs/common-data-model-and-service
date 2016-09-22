---
title: "Person, organization, and group reference"
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
ms.assetid: "cb6723ce-88d9-4e54-81a0-2f532965d3be"
---

# Person, Organization, or Group
## Alumnus (Alumnus) Entity
A graduate of a school.

Field | Description
---|---
AlumniClass | Data: Text<br>Maximum length: 128
AlumnusId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
BusinessPhone | Data: Phone
CellPhone | Data: Phone
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FirstName | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
HomePhone | Data: Phone
LastName | Data: Text<br>Required, Maximum length: 128
Linkedin | Data: Text<br>Maximum length: 128
MiddleName | Data: Text<br>Maximum length: 128
PostalAddress | Data: Address
Status | Enumeration: AlumnusStatusValues: Current, Inactive, Past
Thumbnail | Data: Image
Twitter | Data: Text<br>Maximum length: 128
## Company (Company) Entity
An organization that conducts business.

Field | Description
---|---
BusinessPhone | Data: Phone
CellPhone | Data: Phone
CompanyId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
Description | Data: Text<br>Maximum length: 128
DUNSNumber | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Required, Maximum length: 128
Linkedin | Data: Text<br>Maximum length: 128
ParentCompany | Lookup: Company
PostalAddress | Data: Address
SatoriID | Data: Text<br>Maximum length: 128
StockExchange | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
Thumbnail | Data: Image
Ticker | Data: Text<br>Maximum length: 128
Twitter | Data: Text<br>Maximum length: 128
## Constituent (Constituent) Entity
A member of a group.

Field | Description
---|---
BusinessPhone | Data: Phone
CellPhone | Data: Phone
ConstituentId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FirstName | Data: Text<br>Maximum length: 128<br>Description: Type the constituent first name
FullName | Data: Text<br>Maximum length: 128<br>Description: Type the constituent full name
HomePhone | Data: Phone
LastName | Data: Text<br>Required, Maximum length: 128<br>Description: Type the constituent last name
Linkedin | Data: Text<br>Maximum length: 128
MiddleName | Data: Text<br>Maximum length: 128<br>Description: Type the constituent middle name
PostalAddress | Data: Address
Status | Enumeration: ConstituentStatusValues: Active, InActive
Thumbnail | Data: Image
Twitter | Data: Text<br>Maximum length: 128
## Contact (Contact) Entity
An individual that a company has a relationship with, such as a customer, a supplier, or a colleague, and the related attributes - postal, electronic, social - for that individual.

Field | Description
---|---
BusinessPhone | Data: Phone
CellPhone | Data: Phone
ContactId<br>Primary key | Number sequence: <br>Unique
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FirstName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
FullName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
HomePhone | Data: Phone
LastName | Data: Text<br>Required, Maximum length: 128<br>Description: Type the company or business name.
Linkedin | Data: Text<br>Maximum length: 128
MiddleName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
ParentContact | Lookup: Contact
PartyRole | Enumeration: PartyRoleValues: Alumnus, Company, Constituent, Contractor, Customer, Donor, Employee, Fan, Member, NonProfit, Supplier, Tenant, Vendor, Volunteer
PostalAddress | Data: Address
SatoriId | Data: Text<br>Maximum length: 128
SocialScore | Data: Integer
Thumbnail | Data: Image
Ticker | Data: Text<br>Maximum length: 10
Twitter | Data: Text<br>Maximum length: 128
WebSite | Data: WebsiteUrl
## Contractor (Contractor) Entity
A contractor that a company hires.

Field | Description
---|---
BusinessPhone | Data: Phone
CellPhone | Data: Phone
Company | Lookup: Company
ContractorId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
CostCenter | Lookup: CostCenter
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FirstName | Data: Text<br>Maximum length: 128<br>Description: Type the first name of the contractor
FullName | Data: Text<br>Maximum length: 128<br>Description: Type the full name of the contractor
HomePhone | Data: Phone
LastName | Data: Text<br>Maximum length: 128<br>Description: Type the last name of the contractor
Linkedin | Data: Text<br>Maximum length: 128
Manager | Lookup: Employee
MiddleName | Data: Text<br>Maximum length: 128<br>Description: Type the middle name of the contractor
PartyType | Enumeration: PartyTypeValues: Group, Organization, Person<br>Required
PostalAddress | Data: Address
Status | Enumeration: ContractorStatusValues: Active, InActive
Supplier | Lookup: Supplier
Thumbnail | Data: Image
Twitter | Data: Text<br>Maximum length: 128
## Donor (Donor) Entity
An individual or organization that contributes to an organization for a cause of its interest.

Field | Description
---|---
BusinessPhone | Data: Phone
CellPhone | Data: Phone
Description | Data: Text<br>Maximum length: 128
DonorId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
DonorSince | Data: Date
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FirstName | Data: Text<br>Maximum length: 128<br>Description: Type the first name of the donor
FullName | Data: Text<br>Maximum length: 128<br>Description: Type the full name of the donor
HomePhone | Data: Phone
LastName | Data: Text<br>Required, Maximum length: 128<br>Description: Type the last name of the donor
Linkedin | Data: Text<br>Maximum length: 128
MiddleName | Data: Text<br>Maximum length: 128<br>Description: Type the middle name of the donor
PostalAddress | Data: Address
Status | Enumeration: DonorStatusValues: Active, InActive
Thumbnail | Data: Image
Twitter | Data: Text<br>Maximum length: 128
## Employee (Employee) Entity
An employee of a business interest, company, or organization.

Field | Description
---|---
BusinessPhone | Data: Phone
CellPhone | Data: Phone
Company | Lookup: Company
CostCenter | Lookup: CostCenter
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
EmployeeId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
Facebook | Data: Text<br>Maximum length: 128
FirstName | Data: Text<br>Maximum length: 128<br>Description: Type the employee first name
FullName | Data: Text<br>Maximum length: 128<br>Description: Type the employee full name
HireDate | Data: Date
HomePhone | Data: Phone
LastName | Data: Text<br>Required, Maximum length: 128<br>Description: Type the employee full name
Linkedin | Data: Text<br>Maximum length: 128
Manager | Lookup: Employee
MiddleName | Data: Text<br>Maximum length: 128<br>Description: Type the employee middle name
PostalAddress | Data: Address
Status | Enumeration: EmploymentStatusValues: Employed, None, OnLeave, Resigned, Retired<br>Description: Employee Status
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
Thumbnail | Data: Image
Twitter | Data: Text<br>Maximum length: 128
## Family (Family) Entity
A group of related people. Individual family members are described in the FamilyMember entity.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FamilyId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
FullName | Data: Text<br>Required, Maximum length: 128<br>Description: Type the full name of the family
Linkedin | Data: Text<br>Maximum length: 128
Phone | Data: Phone
PostalAddress | Data: Address
Status | Enumeration: FamilyStatusValues: Active, Inactive
Twitter | Data: Text<br>Maximum length: 128
## FamilyMember (Family Member) Entity
A person who is a member of a family.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Family | Lookup: Family<br>Required
FamilyMemberId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
Member | Lookup: Member<br>Required
MemberFirstName | Data: Text<br>Maximum length: 128<br>Description: Type the family member first name
MemberLastName | Data: Text<br>Maximum length: 128<br>Description: Type the family member last name
MemberMiddleName | Data: Text<br>Maximum length: 128<br>Description: Type the family member middle name
PrimaryRole | Enumeration: FamilyRoleValues: ElderSiblings, Father, GrandParents, Mother, YoungerSiblings
## Fan (Fan) Entity
A fan of a person, organization, or group.

Field | Description
---|---
BusinessPhone | Data: Phone<br>Description: Business phone number
CellPhone | Data: Phone<br>Description: Cell phone number
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FanId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
FanSince | Data: Date
FavoritePlayer | Data: Text<br>Maximum length: 128
FirstName | Data: Text<br>Maximum length: 128<br>Description: Type the fan first name
FullName | Data: Text<br>Maximum length: 128<br>Description: Type the fan full name
HomePhone | Data: Phone<br>Description: Home phone number
LastName | Data: Text<br>Required, Maximum length: 128<br>Description: Type the fan last name
Linkedin | Data: Text<br>Maximum length: 128
MiddleName | Data: Text<br>Maximum length: 128<br>Description: Type the fan middle name
PostalAddress | Data: Address
Status | Enumeration: FanStatusValues: Bronze, Club, Gold, Platinum, PreferenceTicket, SeasonTicketHolder, Silver
Thumbnail | Data: Image
Twitter | Data: Text<br>Maximum length: 128
## Household (Household) Entity
A group of individuals who share a living space. Individual household members are described in the HouseholdMember entity.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Email | Data: Email<br>Description: Email for Household
Facebook | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Required, Maximum length: 128<br>Description: Type the company or business name.
HouseholdId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
Linkedin | Data: Text<br>Maximum length: 128
Phone | Data: Phone<br>Description: Phone number for household
PostalAddress | Data: Address
Status | Enumeration: HouseholdStatusValues: Active, Inactive
Twitter | Data: Text<br>Maximum length: 128
## HouseholdMember (Household Member) Entity
A person who is a member of a household.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Household | Lookup: Household<br>Required
HouseholdMemberId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
Member | Lookup: Member<br>Required
MemberFirstName | Data: Text<br>Maximum length: 128<br>Description: Type the member first name
MemberLastName | Data: Text<br>Maximum length: 128<br>Description: Type the member last name
MemberMiddleName | Data: Text<br>Maximum length: 128<br>Description: Type the member middle name
PrimaryRole | Enumeration: HouseholdRoleValues: ElderSiblings, Father, GrandParents, Mother, YoungerSiblings
## Member (Member) Entity
A member of a group, interest, or cause.

Field | Description
---|---
BusinessPhone | Data: Phone
CellPhone | Data: Phone
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FirstName | Data: Text<br>Maximum length: 128<br>Description: First name of the member
FullName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
HomePhone | Data: Phone
LastName | Data: Text<br>Required, Maximum length: 128<br>Description: Last name of the member
Linkedin | Data: Text<br>Maximum length: 128
MemberId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
MemberSince | Data: Date
MemberThru | Data: Date
MiddleName | Data: Text<br>Maximum length: 128<br>Description: Middle name of the member
PostalAddress | Data: Address
Status | Enumeration: MemberStatusValues: Active, InActive
Thumbnail | Data: Image
Twitter | Data: Text<br>Maximum length: 128
## Team (Team) Entity
A team in an organization or group. Individual team members are described in the TeamMember entity.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Required, Maximum length: 128<br>Description: Type the company or business name.
Linkedin | Data: Text<br>Maximum length: 128
Phone | Data: Phone
PostalAddress | Data: Address
Status | Enumeration: TeamStatusValues: Active, Inactive
TeamId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
Twitter | Data: Text<br>Maximum length: 128
## TeamMember (Team Member) Entity
A person who is a member of a team.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Member | Lookup: Member<br>Required
MemberFirstName | Data: Text<br>Maximum length: 128<br>Description: Type the first name
MemberLastName | Data: Text<br>Maximum length: 128<br>Description: Type the last name
MemberMiddleName | Data: Text<br>Maximum length: 128<br>Description: Type the middle name
PrimaryRole | Enumeration: TeamRoleValues: Coach, Lead, Manager, Player, Reserve, TeamLeader, TeamMember<br>Description: Team role
Team | Lookup: Team<br>Required
TeamMemberId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
## Tenant (Tenant) Entity
A person, organization, or group that leases space.

Field | Description
---|---
BusinessPhone | Data: Phone
CellPhone | Data: Phone
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FirstName | Data: Text<br>Maximum length: 128<br>Description: Type the tenant first name
FullName | Data: Text<br>Maximum length: 128<br>Description: Type the tenant full name
HomePhone | Data: Phone
LastName | Data: Text<br>Required, Maximum length: 128<br>Description: Type the tenant last name
Linkedin | Data: Text<br>Maximum length: 128
MiddleName | Data: Text<br>Maximum length: 128<br>Description: Type the tenant middle name
PostalAddress | Data: Address
Status | Enumeration: TenantStatusValues: Active, InActive
TenantId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
TenantSince | Data: Date
TenantThru | Data: Date
Thumbnail | Data: Image<br>Description: Default Image
Twitter | Data: Text<br>Maximum length: 128
## Volunteer (Volunteer) Entity
A person who volunteers for an organization or group. This entity tracks contact, management, and skills information.

Field | Description
---|---
BusinessPhone | Data: Phone
CellPhone | Data: Phone
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FirstName | Data: Text<br>Maximum length: 128<br>Description: Type the volunteer first name
FullName | Data: Text<br>Maximum length: 128<br>Description: Type the volunteer full name
HomePhone | Data: Phone
LastName | Data: Text<br>Required, Maximum length: 128<br>Description: Type the volunteer last name
Linkedin | Data: Text<br>Maximum length: 128
Manager | Lookup: Employee
MiddleName | Data: Text<br>Maximum length: 128<br>Description: Type the volunteer middle name
PostalAddress | Data: Address
StartDate | Data: Date<br>Description: Volunteer start date
Status | Enumeration: VolunteerStatusValues: Active, InActive
Thumbnail | Data: Image
Twitter | Data: Text<br>Maximum length: 128
VolunteerId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
