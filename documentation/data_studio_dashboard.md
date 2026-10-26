# NovaMart Retail — Stakeholder Analysis

## 1. Purpose

This document identifies the key stakeholders for the NovaMart Retail Sales and Inventory Performance Analysis project, outlines their information needs, and explains how the analysis can support business decision-making.

The stakeholder analysis is based on a hypothetical retail business scenario created for portfolio purposes. The dataset is synthetic, and the stakeholders described below are illustrative rather than actual project participants.

## 2. Business Context

NovaMart Retail needs a consolidated view of sales performance, profitability, store-level results, product performance, and inventory distribution.

Without a consistent reporting approach, decision-makers may find it difficult to compare performance, identify areas requiring further investigation, and prioritise operational reviews.

The proposed solution combines sales and inventory analysis with an interactive dashboard.

## 3. Stakeholder Identification

| Stakeholder | Primary Interest | Information Required |
|---|---|---|
| Retail Operations Manager | Store performance | Sales by store, transaction volume, performance differences |
| Finance Manager | Financial performance | Total sales, profit, profit margin, average order value |
| Inventory Manager | Stock management | Inventory status, overstock records, stock distribution |
| Category or Product Manager | Product performance | Sales by product, top-selling products, product-level comparisons |
| Senior Management | Overall business performance | High-level KPIs, notable findings, areas requiring investigation |
| Business Analyst | Reliable and actionable reporting | Business requirements, KPI definitions, data quality, validated insights |

## 4. Stakeholder Needs and Business Questions

### 4.1 Retail Operations Manager

**Business need:** Understand differences in sales performance across stores.

Key questions:
- Which stores have the highest and lowest recorded sales?
- Are performance differences associated with transaction volume or average order value?
- Which stores require further operational investigation?

**Expected outcome:** A comparable store-performance view that helps prioritise further analysis.

### 4.2 Finance Manager

**Business need:** Monitor overall financial performance.

Key questions:
- What are the total recorded sales and profit?
- What is the overall profit margin?
- What is the average order value?
- Are sales and profitability moving in the same direction over time?

**Expected outcome:** Consistent financial KPIs supported by documented calculation rules.

### 4.3 Inventory Manager

**Business need:** Understand the distribution of inventory status.

Key questions:
- How many inventory records are classified as healthy or overstock?
- Which products or locations require a stock review?
- What additional information is needed to assess potential stockout risk?

**Expected outcome:** A clear inventory-status summary and a list of areas for further validation.

### 4.4 Category or Product Manager

**Business need:** Understand product-level sales performance.

Key questions:
- Which products have the highest recorded sales value?
- How do products compare by sales and profit?
- Which additional measures would help evaluate product performance?

**Expected outcome:** A product ranking that supports further investigation into product mix and profitability.

### 4.5 Senior Management

**Business need:** Obtain a concise overview of business performance.

Key questions:
- What are the main performance indicators?
- What patterns are visible in the available data?
- What limitations should be considered before making decisions?

**Expected outcome:** A concise dashboard and evidence-based summary of findings.

## 5. Stakeholder Prioritisation

Stakeholders can be prioritised according to their decision-making responsibilities and the information they require.

| Priority | Stakeholder Group | Reason |
|---|---|---|
| High | Senior Management | Requires an overall view of business performance |
| High | Retail Operations Manager | Needs store-level comparisons |
| High | Finance Manager | Requires consistent sales and profit reporting |
| Medium | Inventory Manager | Needs inventory-status visibility and further validation |
| Medium | Category or Product Manager | Needs product-level performance analysis |

These priorities are illustrative and would need confirmation with actual stakeholders in a real project.

## 6. Proposed Reporting Requirements

The following reporting requirements translate stakeholder needs into practical dashboard capabilities.

| Requirement ID | Requirement | Priority |
|---|---|---|
| BR-01 | Display total sales and total profit | Must Have |
| BR-02 | Display transaction count and units sold | Must Have |
| BR-03 | Compare sales performance across stores | Must Have |
| BR-04 | Rank products by recorded sales value | Must Have |
| BR-05 | Display inventory-status distribution | Must Have |
| BR-06 | Document KPI definitions and calculation methods | Must Have |
| BR-07 | Provide time-based sales trends | Future Enhancement |
| BR-08 | Compare product profitability | Future Enhancement |
| BR-09 | Support validated store and product filtering | Future Enhancement |

## 7. Assumptions and Dependencies

- The analysis uses a synthetic dataset.
- Stakeholder roles and priorities are hypothetical.
- KPI calculations depend on the accuracy and consistency of the source data.
- The inventory snapshot is separate from the sales transactions and has not been reconciled with them.
- Additional data may be required to investigate sales trends, stockout risk, and operational causes.
- Actual stakeholder priorities would need to be confirmed during project discovery.

## 8. Risks and Mitigation

| Risk | Potential Impact | Proposed Mitigation |
|---|---|---|
| Inconsistent KPI definitions | Different teams may interpret results differently | Document formulas and aggregation rules |
| Incomplete or inaccurate data | Misleading reporting | Perform data-quality checks |
| Sales treated as a measure of profitability | Poor business decisions | Review profit and margin alongside sales |
| Inventory data not reconciled with sales | Incorrect stock-related conclusions | Validate inventory against sales and replenishment records |
| Descriptive findings interpreted as causal | Unsupported recommendations | Clearly document assumptions and limitations |

## 9. Success Criteria

The proposed reporting solution would be considered successful if:

- Required KPIs are calculated consistently.
- Stakeholders can identify store and product performance patterns.
- Inventory status is presented clearly.
- Metric definitions and data limitations are documented.
- Findings are traceable to the available dataset.
- Recommendations distinguish observed evidence from areas requiring further investigation.

## 10. Conclusion

Stakeholder analysis helps connect data analysis with business decision-making. By identifying stakeholder needs, documenting reporting requirements, and acknowledging data limitations, the NovaMart Retail project demonstrates a structured approach to business analysis.

The analysis provides a foundation for future enhancements, including time-based trend reporting, deeper profitability analysis, and validated inventory monitoring.

---

**Project:** NovaMart Retail — Sales and Inventory Performance Analysis  
**Document Type:** Stakeholder Analysis  
**Prepared for:** Business Analyst Portfolio  
**Data Classification:** Synthetic portfolio data
