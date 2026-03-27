# Pipeline Forecast Summary

Turn a raw deals sheet into a forecast and stage summary.

## Prompt

```text
Build a pipeline summary from this deals table. Group deals by stage, total the open pipeline, calculate a weighted forecast using probability, and show which deals are expected to close this month.
```

## Sample data

- `../../../datasets/sales/pipeline.csv`

## Expected result

- Creates a stage-by-stage summary
- Calculates total pipeline value
- Calculates weighted forecast
- Identifies near-term closes

## Related Griddy pages

- https://getgriddy.ai/templates/sales/
- https://getgriddy.ai/use-cases/
