# Requirements & Planning Documents --- Detailed Exam Notes

## 1. Requirement Gathering

### 1.1 What is Requirement Gathering?

**Requirement Gathering** is the process of **collecting, understanding,
documenting, and analyzing the needs and expectations of users and
stakeholders** for a software system.

It is one of the first major activities in software development because
developers need to know **what the system should do** before designing
and developing it.

### Example

Suppose we are developing a **Hospital Management System**.

During requirement gathering, we may identify:

-   Patient registration
-   Doctor management
-   Appointment booking
-   Medical record management
-   Billing
-   Login for doctors and patients
-   Report generation

### Main Objectives

1.  Understand customer needs.
2.  Identify system functionality.
3.  Identify quality requirements.
4.  Identify stakeholders.
5.  Remove ambiguity and confusion.
6.  Define the scope of the project.
7.  Provide a foundation for the SRS document.

### Requirement Gathering Process

**Identify Stakeholders → Collect Requirements → Analyze Requirements →
Prioritize → Validate → Document**

#### 1. Identify Stakeholders

Find people who are affected by or interested in the system.

Examples:

-   Customers
-   End users
-   Managers
-   Developers
-   Administrators

#### 2. Collect Requirements

Requirements can be collected using:

-   Interviews
-   Questionnaires
-   Surveys
-   Observation
-   Meetings
-   Brainstorming
-   Prototyping
-   Document analysis

#### 3. Analyze Requirements

Check whether requirements are:

-   Clear
-   Complete
-   Consistent
-   Feasible
-   Testable

#### 4. Prioritize Requirements

Requirements are classified according to importance:

-   **High priority** -- must be implemented
-   **Medium priority** -- important but can wait
-   **Low priority** -- optional features

#### 5. Validate Requirements

Stakeholders review the requirements and confirm that they are correct.

#### 6. Document Requirements

Finally, requirements are documented in an **SRS (Software Requirements
Specification)**.

------------------------------------------------------------------------

## 1.2 Functional Requirements

### Definition

**Functional requirements** describe **what the system should do**.

They specify the functions, operations, and services that the software
must provide.

### Examples

For an online shopping system:

-   User can register.
-   User can log in.
-   User can search products.
-   User can add products to the cart.
-   User can place an order.
-   User can make payment.
-   Admin can add or remove products.
-   System can generate invoices.

### Characteristics

Functional requirements describe:

-   Inputs
-   Outputs
-   Processing
-   User interactions
-   Business rules
-   System operations

### Example

**Requirement:**\
"The system shall allow users to reset their password."

Here, the functionality is **password reset**.

------------------------------------------------------------------------

## 1.3 Non-Functional Requirements

### Definition

**Non-functional requirements** describe **how well the system should
perform** rather than what functions it should perform.

They define the **quality attributes and constraints** of a system.

### Major Types

#### 1. Performance

Defines how quickly the system should respond.

**Example:**\
The system should respond to a user request within 2 seconds.

#### 2. Security

Defines protection against unauthorized access.

**Example:**\
Only authorized administrators can access user records.

#### 3. Reliability

Defines how consistently the system operates without failure.

**Example:**\
The system should be available 99.9% of the time.

#### 4. Usability

Defines how easy the system is to learn and use.

**Example:**\
A new user should be able to complete registration easily.

#### 5. Scalability

Defines the ability of the system to handle increasing users or data.

**Example:**\
The system should support 10,000 simultaneous users.

#### 6. Maintainability

Defines how easily the software can be modified or repaired.

#### 7. Availability

Defines how often the system should be available to users.

#### 8. Portability

Defines whether software can run on different platforms.

### Functional vs Non-Functional Requirements

  -----------------------------------------------------------------------
  Functional Requirement              Non-Functional Requirement
  ----------------------------------- -----------------------------------
  Describes **what** the system does  Describes **how well** it does it

  Related to system functions         Related to system quality

  Usually directly visible to users   Often related to system performance

  Example: Login                      Example: Login must complete within
                                      2 seconds

  Example: Generate report            Example: Report must be generated
                                      within 5 seconds
  -----------------------------------------------------------------------

### Easy Trick

**Functional = WHAT**

**Non-functional = HOW WELL**

------------------------------------------------------------------------

## 1.4 Stakeholders

### Definition

A **stakeholder** is a person, group, or organization that has an
interest in the software system or is affected by it.

### Types of Stakeholders

#### 1. Customers

They request and pay for the system.

#### 2. End Users

People who actually use the software.

Examples:

-   Students using a college portal
-   Patients using a healthcare application

#### 3. Project Manager

Responsible for planning, scheduling, and managing the project.

#### 4. Developers

Build the software according to requirements.

#### 5. Testers

Check whether the software works correctly and satisfies requirements.

#### 6. Business Analysts

Collect and analyze business requirements.

#### 7. System Administrators

Manage and maintain the deployed system.

#### 8. Management

Provides business direction, budget, and organizational support.

### Importance of Stakeholders

Stakeholders help to:

-   Identify requirements
-   Define project objectives
-   Identify problems
-   Validate requirements
-   Prioritize features
-   Provide feedback
-   Ensure the final product meets expectations

------------------------------------------------------------------------

## 1.5 Requirement Analysis

### Definition

**Requirement Analysis** is the process of **examining, organizing,
refining, and validating collected requirements**.

The purpose is to ensure that requirements are properly understood
before development begins.

### Activities in Requirement Analysis

1.  **Identify requirements**
2.  **Classify requirements**
3.  **Prioritize requirements**
4.  **Remove ambiguity**
5.  **Identify conflicts**
6.  **Check feasibility**
7.  **Validate requirements**
8.  **Document requirements**

### Example

Suppose one stakeholder says:

> "The application should be very fast."

This is unclear.

During requirement analysis, it can be converted into:

> "The application should respond to normal user requests within 2
> seconds."

Now the requirement is **specific and testable**.

### Characteristics of Good Requirements

A good requirement should be:

-   **Correct**
-   **Complete**
-   **Clear**
-   **Consistent**
-   **Feasible**
-   **Necessary**
-   **Testable**
-   **Unambiguous**
-   **Traceable**

### Exam Point

A requirement should not have multiple possible interpretations.

**Incorrect:**\
"System should load quickly."

**Better:**\
"System should load the dashboard within 3 seconds."

------------------------------------------------------------------------

# 2. BRD --- Business Requirement Document

## 2.1 Definition

**BRD stands for Business Requirement Document.**

A BRD is a document that describes the **high-level business needs,
objectives, goals, and expectations of a project**.

It mainly answers:

> **"Why is the project needed and what does the business want to
> achieve?"**

### Example

For an online college admission system:

> "The college wants to provide an online admission facility to reduce
> manual paperwork and make the admission process faster."

------------------------------------------------------------------------

## 2.2 Purpose of BRD

The main purposes of a BRD are:

1.  Define business objectives.
2.  Explain the reason for developing the system.
3.  Identify business needs.
4.  Define project scope.
5.  Identify stakeholders.
6.  Establish a common understanding between business and technical
    teams.
7.  Provide a foundation for further requirements.
8.  Help estimate project cost and resources.

------------------------------------------------------------------------

## 2.3 Components of BRD

A typical BRD contains:

### 1. Project Overview

Basic information about the project.

### 2. Business Objectives

What the organization wants to achieve.

Examples:

-   Reduce manual work
-   Increase efficiency
-   Improve customer satisfaction

### 3. Business Requirements

High-level requirements of the business.

### 4. Project Scope

Defines what is included and excluded from the project.

### 5. Stakeholders

Identifies people involved in the project.

### 6. Business Processes

Explains how the current and proposed business processes work.

### 7. Assumptions

Conditions assumed to be true.

**Example:**\
Users will have internet access.

### 8. Constraints

Limitations of the project.

Examples:

-   Budget
-   Time
-   Technology
-   Resources

### 9. Risks

Possible problems that may affect the project.

### 10. Success Criteria

Defines how project success will be measured.

------------------------------------------------------------------------

## 2.4 Advantages of BRD

### 1. Clear Business Understanding

Provides a clear understanding of business goals.

### 2. Better Communication

Creates common understanding between stakeholders and development teams.

### 3. Defines Scope

Helps prevent unnecessary features from being added.

### 4. Reduces Misunderstanding

Requirements are documented clearly.

### 5. Helps Planning

Provides a foundation for project planning and estimation.

### 6. Supports Decision Making

Helps management make better project decisions.

### 7. Helps Requirement Validation

Stakeholders can check whether their business needs have been captured
correctly.

------------------------------------------------------------------------

## 2.5 Disadvantages of BRD

### 1. Time Consuming

Preparing a detailed BRD can take significant time.

### 2. Requirement Changes

Business requirements may change after the BRD is prepared.

### 3. Maintenance

The document may need frequent updates.

### 4. Misinterpretation

Poorly written requirements can still create confusion.

### 5. High-Level Nature

BRD generally does not provide detailed technical implementation
information.

------------------------------------------------------------------------

# 3. SRS --- Software Requirements Specification

## 3.1 Definition

**SRS stands for Software Requirements Specification.**

SRS is a detailed document that describes the **functional and
non-functional requirements of a software system**.

It explains **what the software must do and the conditions under which
it must operate**.

### Simple Definition

> **SRS is a complete written description of the requirements of a
> software system.**

### Easy Way to Remember

**BRD → Business wants WHAT and WHY**

**SRS → Software needs to DO WHAT and under WHAT conditions**

------------------------------------------------------------------------

## 3.2 Purpose of SRS

The main purposes are:

1.  Clearly define software requirements.
2.  Provide a basis for software design.
3.  Guide developers during implementation.
4.  Help testers create test cases.
5.  Reduce misunderstandings.
6.  Define system scope.
7.  Support project estimation.
8.  Provide a reference throughout the software lifecycle.
9.  Help maintain and modify the software later.

------------------------------------------------------------------------

## 3.3 Components of SRS

A typical SRS contains the following:

### 1. Introduction

Contains:

-   Purpose
-   Scope
-   Definitions
-   References
-   Overview of the document

### 2. Overall Description

Describes the general characteristics of the system.

It may include:

-   Product perspective
-   Product functions
-   User characteristics
-   Operating environment
-   Constraints
-   Assumptions

### 3. Functional Requirements

Describes what the system must do.

**Example:**\
The system shall allow users to register using their email address.

### 4. Non-Functional Requirements

Describes quality requirements such as:

-   Performance
-   Security
-   Reliability
-   Usability
-   Availability
-   Scalability
-   Maintainability

### 5. External Interface Requirements

Describes interaction with:

-   Users
-   Hardware
-   Software
-   APIs
-   Communication systems

### 6. System Constraints

Defines limitations imposed on the system.

Examples:

-   Technology constraints
-   Hardware limitations
-   Budget constraints
-   Legal constraints

### 7. Assumptions and Dependencies

Documents conditions that the system depends upon.

------------------------------------------------------------------------

## 3.4 Advantages of SRS

### 1. Clear Requirements

Provides detailed and structured requirements.

### 2. Reduces Development Errors

Developers have a clear understanding of what needs to be built.

### 3. Helps Testing

Testers can create test cases from SRS requirements.

### 4. Better Communication

Acts as a common reference for:

-   Client
-   Developer
-   Tester
-   Project Manager

### 5. Helps Estimation

Useful for estimating:

-   Cost
-   Time
-   Resources
-   Development effort

### 6. Supports Maintenance

Future developers can understand system requirements.

### 7. Defines Scope

Clearly identifies what the software should and should not provide.

------------------------------------------------------------------------

## 3.5 Disadvantages of SRS

### 1. Time Consuming

Preparing detailed SRS requires considerable effort.

### 2. Difficult to Change

Frequent requirement changes may require updates to the document.

### 3. Requires Skilled Analysis

Poorly written requirements can create problems during development.

### 4. Documentation Overhead

Maintaining large SRS documents can be difficult.

### 5. May Become Outdated

If requirements change but SRS is not updated, it may no longer
represent the actual system.

------------------------------------------------------------------------

# 4. BRD vs SRS

## Comparison Table

  -----------------------------------------------------------------------
  Basis                   BRD                     SRS
  ----------------------- ----------------------- -----------------------
  Full Form               Business Requirement    Software Requirements
                          Document                Specification

  Focus                   Business needs          Software requirements

  Main Question           **Why and what does     **What should the
                          business need?**        software do?**

  Level                   High-level              Detailed

  Audience                Business stakeholders,  Developers, testers,
                          management, client      designers, technical
                                                  team

  Technical Details       Very limited            More detailed

  Functional Requirements Usually high-level      Detailed

  Non-functional          May be mentioned        Clearly specified
  Requirements                                    

  Scope                   Business/project scope  Software/system scope

  Created Mainly By       Business                Business analyst/system
                          analyst/stakeholders    analyst with technical
                                                  input

  Used For                Understanding business  Development and testing
                          goals                   

  Example                 "Provide online         "System shall allow
                          admission facility."    students to submit an
                                                  admission form online."
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 5. BRD and SRS Relationship

The relationship can be understood as:

``` text
Business Problem
      ↓
Business Requirements
      ↓
       BRD
      ↓
Detailed Software Requirements
      ↓
       SRS
      ↓
System Design
      ↓
Development
      ↓
Testing
      ↓
Deployment
```

### Example

**BRD:**

> College wants to automate student admission.

**SRS:**

> The system shall allow students to create an account, fill the
> admission form, upload documents, submit the form, and track
> application status.

Therefore:

-   **BRD = Business perspective**
-   **SRS = Software/technical perspective**

------------------------------------------------------------------------

# 6. Quick Revision

## Requirement Gathering

> Process of collecting and understanding user and stakeholder needs.

## Functional Requirement

> Describes **what the system does**.

**Example:** User can log in.

## Non-Functional Requirement

> Describes **how well the system performs**.

**Example:** Login should complete within 2 seconds.

## Stakeholder

> Anyone who has an interest in or is affected by the project.

## Requirement Analysis

> Process of examining, refining, prioritizing, and validating
> requirements.

## BRD

> Document describing **business needs, goals, and objectives**.

**Main focus: WHY + WHAT business needs**

## SRS

> Detailed document describing **software functional and non-functional
> requirements**.

**Main focus: WHAT software should do + HOW it should perform**

------------------------------------------------------------------------

# 7. Most Important Exam Differences

### Functional vs Non-Functional

**Functional = WHAT**

**Non-functional = HOW WELL**

### BRD vs SRS

**BRD = Business requirements + business goals**

**SRS = Detailed software requirements**

### One-Line Flow to Remember

> **Stakeholders → Requirement Gathering → Requirement Analysis → BRD →
> SRS → Design → Development → Testing**
