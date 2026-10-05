# Requirements Summary

This summarises the business requirements the dashboard was built against. The source was a BI requirements document for a newly launched e-commerce platform serving the **UK and US** markets.

> **Note:** the dashboard was built on a synthetic, AI-generated dataset aligned to this requirements schema.

## Purpose
Establish a BI and analytics platform from launch day that integrates website, marketing, sales, product catalog and fulfillment data, giving end-to-end visibility and a **single source of truth** for business and customer metrics.

## Goals (SMART, first 6 months)
| Goal | What the analytics must enable |
|---|---|
| Customer retention | Baseline repeat-customer rate; segment loyal vs at-risk customers |
| Sales growth | Spot top-selling and underperforming products |
| Cart abandonment | Find checkout-flow and behaviour insights to reduce abandonment |
| Customer satisfaction | Find root causes of poor satisfaction and returns |
| Customer value | Identify cross-sell and upsell opportunities to lift AOV |
| Reliability | 99.9% uptime; page load under 2 seconds |

## Scope
**In scope:** data integration across sales, catalog, inventory, website and marketing; promotion/upsell/cross-sell analysis; dashboards for executives, marketing and operations; KPI reporting (traffic, revenue, AOV, conversion, fulfillment, returns, CSAT).

**Out of scope:** changes to CRM/ERP; new UIs or mobile apps; any write-back to live transactional systems; languages other than UK/US English; manually maintained spreadsheet reports.

## Journey stages, Key Result Areas and dashboard pages
| Stage | Key Result Areas | Dashboard page |
|---|---|---|
| Product Discovery & Browsing | Efficient discovery; engagement with product/category pages; longer sessions | Product Discovery |
| Cart Engagement & Pre-Checkout | More product interaction; more items per cart; minimal abandonment | Funnel & Cart Analysis |
| Checkout & Transaction | High checkout conversion and AOV; profitable promotions; 99.9% payment success | Checkout & Transactions |
| Fulfillment & Shipping | Accurate, on-time, cost-effective delivery; faster order-to-ship | Fulfillment & Shipping |
| Post-Purchase | Lower return rate; more reviews; stronger loyalty and repeat purchase | Post-Purchase |
| Sales & Financial Performance | Balanced view of revenue, cost and profitability | Executive Summary |

## Key Risk Indicators defined per stage
| Stage | KRIs |
|---|---|
| Discovery | Bounce rate > 70%; high zero-result searches; low page-to-page view ratio |
| Cart | Cart abandonment > 60%; high cart-removal rate; short product view duration; low cross-sell/upsell click rate |
| Checkout | Payment failure > 5%; low promotion ROI; high drop-off at payment; low revenue per session |
| Fulfillment | Rising late-delivery rate; high delivery-failure rate |
| Post-Purchase | Spike in return volume; surge in negative reviews |
| Financial | Declining net margin; excessive discounting |

## Known data limitations (from the requirements)
- Marketing spend and CRM retention data were not available in the dataset at design time, so **CAC and CLV** are deferred until those modules are integrated.
- NPS and CSAT were planned as later additions once enough survey data exists.

## Future considerations in the requirements
Fraud & risk analytics (fraud score, chargeback ratio, account takeover) and expanded customer-experience metrics (NPS, CSAT).
