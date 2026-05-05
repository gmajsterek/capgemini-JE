# IC ITem Solver

1. Agentic plane
Business context (eli5)
This process describes the reconciliation done in the IC Reconciliation tool. Blackline is considered as a provider of best in class solution in the market for transaction matching and Intercompany Reconciliation. Intercompany module should be used for this process, in case this module is not implemented, process can be also run using Reconciliation module (as explained in BS Item Solver).
In order to ensure an effective and efficient reconciliation process, it is critical that the period-end closing calendar is strictly adhered to. The process of Intercompany (IC) reconciliation starts on dates set out in the Period End (PE) Close calendar. Objective of this process is to accurately match and reconcile IC transactions and report all Intercompany accounts on a timely basis, before finalization of financial results for a given accounting period.


Agent description (role, measurement, oversight, allowed actions)
Role: to analyze and solve items that are marked by the reconciliation tool as IC reconciling items (Mismatches/incorrect entries/unjustified items)
1. Agent to access list of accounts to be reconciled in Intercompany module.
2. Agent to open the account reconciliation prepared automatically in the Intercompany module.
3. Analyse list of reconciling items, investigate each unreconciled item using source data from ERP, JE workflow, other systems and reports
Item can be reconciled?
4. Yes, Reconcile item in the Intercompany module
5. Complete reconciliation and submit for review
6. No, Item can be explained? Yes, Provide commentaries and go to step 5. If No: Is item an error posting and journal needed? Yes: propose JE, No: open discussion within Intercompany module with relevant stakeholder to solve the item.
7. Escalate if no action/resolution of the open discussion.
8. Update reconciliation based on the discussion results.
Measurement: % of successfully completed IC reconciliation % of first time approved IC reconciliation
Oversight: Human approver to provide feedback on the rejected IC Recocniliation for Agent to learn for the future. Human to correct IC Reconciliation if rejected. Human or other agent to solve unreconciled item on ERP on reconciliation tool.
Allowed actions: Can log to ERP/ Solution/tool(Blackline) to obtain reconciliation list from Intercompany module and to obtain balance details. Can send communication/query from Intercompany module. Can access Intercompany module for approval workflow to submit reconciled item for approval and investigation. Can access process documentation (policies, past postings, booking rules, procedures) in the shared location.
Actions not allowed:
1. Approval and Validation
Ensure IC Reconciliation and journals are reviewed and approved
Follow strict compliance on threshold processing for JEs adjustment for open unreconciled items.
2. System Configuration
No access on system configuration or Agent maintenance
Tools Integration should not be performed by Agent(Blackline, Highradius, etc.)
3. Human or Agent to solve Data error in ERP/Tool/Reconciliation Tool.
4. Cannot change ERP configuration or content - read and edit access
5. Cannot change knowledge source documentation - read and edit access for commentaries and follow-ups"


Industry specificity
Various open reconciling items and IC reconciliation depending on industry specific unique nature of transactions, regulatory requirements, and operational models


Knowledge prerequisites
Accounting rules, accounting standards (IFRS, US GAAP etc.) and company specific policies/guidelines (including IC policy, materiality and audit guidelines), industry specific regulations and accounting rules, desktop procedures and Business Operating Packs, understanding of technology landscape (for system integration for data points) and stakeholders matrix
