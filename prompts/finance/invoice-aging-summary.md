# Invoice Aging Summary

Turn open invoices into an aging report.

## Prompt

```text
Create an accounts receivable aging summary from this invoice table. Bucket every invoice into Current, 1-30, 31-60, 61-90, and 90+ days past due, then total each bucket and highlight overdue customers.
```

## Sample data

- `../../../datasets/finance/invoices.csv`

## Expected result

- Calculates days past due
- Buckets invoices by aging band
- Totals outstanding receivables by aging bucket
- Highlights customers with overdue balances

## Related Griddy pages

- https://getgriddy.ai/templates/finance/
- https://getgriddy.ai/blog/how-to-use-iferror-in-excel/
