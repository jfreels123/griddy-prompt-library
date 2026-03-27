# Shift Schedule Conflict Check

Catch staffing conflicts in a weekly schedule.

## Prompt

```text
Review this shift schedule and flag double-booked employees, uncovered shifts, and anyone scheduled for more than 40 hours this week. Then create a clean summary by employee.
```

## Sample data

- `../../../datasets/hr/shift-schedule.csv`

## Expected result

- Detects double-bookings
- Flags uncovered shifts
- Totals weekly hours per employee
- Identifies overtime risk

## Related Griddy pages

- https://getgriddy.ai/templates/hr/
- https://getgriddy.ai/blog/how-to-use-countifs-in-excel/
