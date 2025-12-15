# Requirements Gathering & Analysis
---

## 1. Requirements Gathering

During the initial phase of the project, requirements were gathered through direct discussions with the client representative, **Mr. Bui Ngoc Le**.

The objective of this phase was to understand the current asset and equipment management process, identify pain points, and clarify business rules.

The key questions used for requirement elicitation included:

1. What is the process for handing over equipment to project teams?
2. What is the process for receiving and returning equipment?
3. How is the condition of equipment assessed?
4. What are the roles and responsibilities of each department?
5. What happens when equipment reaches the end of its depreciation period?

---

## 2. Requirements Analysis

### 2.1 Equipment Handover Process

**Business Description**

When a project is executed, employees contact the Administration and Human Resources Department to request the assets and equipment required for construction or operational activities.

**Process Flow**
- Employees submit an equipment handover request through the system.
- The HR department records which employee receives each asset.
- After receiving the equipment, the employee confirms receipt in the system.
- Once confirmed, the handover process is completed.

**Business Rules**
- Each asset must be associated with a specific employee during handover.
- Asset quantity and status must be updated after handover confirmation.

---

### 2.2 Equipment Return Process

**Business Description**

Employees are required to return equipment when it is no longer needed or upon project completion.

**Process Flow**
1. The employee registers an equipment return request in the system.
2. HR department staff verify the returned asset and update its status.
3. The system records the asset as returned and managed by the HR department.

**Business Rules**
- Returned assets must be inspected before status updates.
- Only HR staff can confirm asset returns.

---

### 2.3 Equipment Condition Assessment

**Business Description**

Equipment condition is assessed during both handover and return processes.

**Assessment Criteria**
- The assessment is based on the condition observed by the receiving party.
- Possible condition statuses include:
  - Usable
  - Damaged
  - Unusable

**Business Rules**
- If equipment is assessed as "Unusable", it cannot be handed over again.
- Condition updates must be recorded in the system.

---

### 2.4 Department Roles and Responsibilities

**Business Description**

The organization consists of multiple departments with clearly defined responsibilities.

**Key Roles**
- **Administration & Human Resources Department**
  - Manage asset and equipment information
  - Confirm handover and return requests
  - Update asset status and quantity

- **Employees**
  - Request asset handover
  - Confirm receipt of assets
  - Register asset return requests

- **Management**
  - View reports and statistics
  - Monitor asset usage and depreciation status

**Business Rules**
- Only authorized departments can edit asset data.
- Employees have read-only access to general asset information.

---

### 2.5 Asset Depreciation Handling

**Business Description**

Each asset is assigned a depreciation period at the time of purchase, based on standard accounting regulations.

**Business Rules**
- When an asset reaches the end of its depreciation period, it is marked as "Fully Depreciated".
- Fully depreciated assets can continue to be used if they remain functional.
- Depreciation status is used for accounting and reporting purposes only.
- Depreciation status does not automatically prevent asset usage.

---

## 3. Summary

This requirements gathering and analysis phase helped define:
- Core asset management processes
- Department responsibilities
- Key business rules related to asset lifecycle and depreciation

The results of this phase serve as the foundation for:
- System requirement specification (SRS)
- Data flow diagrams (DFD)
- Database design
- UI wireframes and prototypes

---

## Keywords
Requirements Gathering · Requirements Analysis · Business Rules · Asset Management · Business Analysis
