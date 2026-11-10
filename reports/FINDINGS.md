# Findings and recommendations

The analysis defines sales as rows with positive quantity and unit price whose invoice number does not begin with `C`, after exact duplicate rows are removed.

- Sales-only revenue is **£10,642,110.80** over **524,878 rows**.
- November 2011 is the highest complete month at **£1,503,866.78**. December reaches **£637,790.33**, but the source ends on 9 December.
- The UK contributes **84.6%** of sales-only revenue.
- In the sales-only view, **65.6%** of customers with recorded IDs have more than one distinct invoice.

## Recommended next steps

1. Compare monthly trends with the preceding/following years before making seasonal forecasts.
2. Investigate the autumn increase using campaign and calendar records; the trend alone does not identify a cause.
3. Report returns and cancellation activity separately and reconcile it with sales before describing net revenue.
4. Audit product descriptions to remove postage and other non-merchandise lines from product decisions.
5. Treat customer retention metrics as applying to identified customers only.
