# Griddy Prompt Library

Public prompt examples for Griddy, the AI spreadsheet assistant for Excel and Google Sheets.

This repo is a task-first library of prompts, sample datasets, and expected outcomes. It is designed to help people understand how to ask for spreadsheet work in plain English, and to showcase the kinds of jobs Griddy handles well.

## What is in this repo

- Category-based prompt examples for finance, sales, marketing, project management, HR, and personal workflows
- Small CSV datasets you can open in Excel, Google Sheets, or Griddy
- Expected-result notes so each prompt is concrete instead of hand-wavy
- Demo media links that point to the live Griddy product footage and screenshots

## Who this is for

- Spreadsheet users who want better prompts
- Teams evaluating Griddy for real spreadsheet work
- Content creators, analysts, operators, and founders looking for repeatable spreadsheet task patterns

## Best starting points by role

- Finance: budget variance analysis, expense cleanup, invoice aging, cash runway
- Sales: pipeline forecast, follow-up priority board, lead source conversion, stalled-deal review
- Marketing: content calendar, campaign review, UTM cleanup, content refresh prioritization
- Project management: task risk report, Gantt plan, sprint board, resource capacity
- HR: vacation coverage, shift conflict check, hiring pipeline, headcount plan
- Personal: wedding budget, meal planning, subscription audit, trip budget

## How to use it

1. Open one of the CSV files in `datasets/`.
2. Open the matching prompt file in `prompts/`.
3. Paste the prompt into Griddy.
4. Adjust column names if your sheet differs from the sample data.

## Categories

- `finance`
- `sales`
- `marketing`
- `project-management`
- `hr`
- `personal`

## Repo layout

```text
griddy-prompt-library/
├── prompts/
│   ├── finance/
│   ├── sales/
│   ├── marketing/
│   ├── project-management/
│   ├── hr/
│   └── personal/
├── docs/
│   └── demo-media.md
└── datasets/
    ├── finance/
    ├── sales/
    ├── marketing/
    ├── project-management/
    ├── hr/
    └── personal/
```

## Griddy links

- Website: https://getgriddy.ai
- Use cases: https://getgriddy.ai/use-cases/
- Templates: https://getgriddy.ai/templates/
- Excel add-in: https://appsource.microsoft.com/en-us/product/office/wa200008745?tab=overview
- Google Sheets add-on: https://workspace.google.com/marketplace/app/griddy/206105793696
- Blog: https://getgriddy.ai/blog/
- Copilot comparison: https://getgriddy.ai/vs/copilot/

## Quality bar

The goal is not to dump generic prompts into GitHub. Each prompt should:

- map to a real spreadsheet job
- use clear, testable language
- point to sample data or a realistic table shape
- describe the expected output

## Notes

- These prompts are examples, not magic phrases. Good spreadsheet prompting depends on clear data structure and a clear outcome.
- If you publish new prompts, validate them in the product before treating them as final.

## License

MIT. See [LICENSE](./LICENSE).
