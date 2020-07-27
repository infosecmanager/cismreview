---
title: Information Security Governance
weight: 1
---
# Information Security (IS) Governance

## Information Security (IS) Governance
Information Security (IS) Governance is the act of creating a plan on how company will protect information and making sure everyone will follow the plan. 

We can measure its effectiveness by metrics. 

{{< hint info >}}
Metrics must be **SMART**, where _S = specific, M = measurable, A = attainable, R = relevant and T = timely_.
{{< /hint >}}

IS governance usually uses a framework and an array of supporting processes to ensure IS strategy is aligned with the **business objective**. 

/* diagram of IS hierarchy goes here */

Metrics measured in security policy, and other documents including standards, procedures and guidelines, as well as controls and processes will go back to the IS governance model to make sure all activities are supporting the strategy, which evenatually aligns the **business objective**. 

## Roles and Responsibilities

* Board of Directors
* Executive Management

{{< hint info >}}
They have the business objective in mind, own IS governance and are liable for it, i.e. "Hands-off management". 
{{< /hint >}}

* Functional Management
    * In form of **Security Steering Group**

{{< hint info >}}
They operate according to the business objectives set by senior management. They are to deliver results. 
{{< /hint >}}

* Business Processes Owners

{{< hint info >}}
They grant, revoke, review access and determine what controls have to be configured on the asset. 
{{< /hint >}}

* Custodian roles

{{< hint info >}}
The make sure security controls are configured. 
{{< /hint >}}

{{< hint warning >}}
Data Owners govern the use of data in the business, and they permit and grant access to data in the Information Systems. 
{{< /hint >}}

## How do senior management implement IS governance?

{{< columns >}}

* **Policy** is the high-arch and short statements defining acceptable risk. 
* **Standards** define the "law" that complements policy, they fill in the gaps with technology. 
* **Guidelines** are discretionary. 
* **Procedures** define how business operates. 

<--->

{{< mermaid >}}
graph LR;
    Policy-->Standards;
    Standards-->Guidelines;
    Guidelines-->Procedures;
    Procedures-->Policy;
{{< /mermaid >}}

{{< /columns >}}

## How do senior management manage IS risk?

{{< columns >}}

* **Controls** refer to the mitigation of risk. 
* The purpose of **audit** is to ensure whether controls are in place and configured exactly to the specs
* **Dashboard** is used for reporting the result and findings of audit, and present metrics to measure effectiveness of the security program. 
* **Assurance** gives management an idea on how confident the serviceis up to a certain level of competency. 

<--->

{{< mermaid >}}
graph LR;
    Controls-->Audit;
    Audit-->Dashboard;
    Dashboard-->Assurance;
    Assurance-->Controls;
{{< /mermaid >}}

{{< /columns >}}

## How do we evaluate the effectiveness of IS governance?

* Metrics
    * Strategic Alignment _e.g. process metrics_
    * Risk Management _e.g. risk is reduced to an acceptable level_
    * Performance Mangement _e.g. time/ system metrics (how a process has performed at its desired capacity?)_
    * Value Delivery _e.g. program cost, presence of cost-benefit analysis_
