# prompt-portfolio
# Business Prompt Engineering Portfolio

## Project Overview
This project demonstrates how a business prompt improves — in relevance, structure, and resistance to hallucination — as it moves from a broad instruction to a fully specified one. The portfolio covers **four management functions** (Finance, Marketing, HR, Sales), with **25 prompts each**, structured as 5 real business problems per function, each solved through a 5-step prompt progression (broad → narrow).

## Business Problems Addressed
| Function | Business Problems Covered |
|---|---|
| Finance | Credit risk assessment, fraud detection, financial statement/ratio analysis, investment portfolio allocation, cash flow forecasting |
| Marketing | *(add once completed)* |
| HR | *(add once completed)* |
| Sales | *(add once completed)* |

## Prompt Engineering Framework Used
Every prompt chain follows the course's Role → Context → Task → Constraints → Format → Evidence structure:

```
P1: Task only            → generic, unverifiable answer
P2: + Role                → professional lens, still generic
P3: + Context (real data) → grounded reasoning, no invented numbers
P4: + Constraints/Format   → checkable, structured output
P5: + Evidence rule        → AI must separate Fact / Assumption / Recommendation,
                             or state "information not provided"
```

## Portfolio Structure
```
part-b/business-prompt-engineering/
├── README.md
├── finance/
│   └── finance-prompt-portfolio.md
├── marketing/
│   └── marketing-prompt-portfolio.md
├── hr/
│   └── hr-prompt-portfolio.md
└── sales/
    └── sales-prompt-portfolio.md
```

## Key Learning
- A prompt without context is answered with invented data, not real reasoning.
- Adding a role changes tone, but not accuracy — context is what removes guesswork.
- Constraints and output format turn a vague answer into something a manager can verify line by line.
- The strongest prompts explicitly tell the AI what it does *not* know, so it states an assumption instead of presenting a guess as fact.

## AI Tools Used
Claude (Anthropic)

## Responsible AI Considerations
- All company names, customer data, and figures used are fictional/illustrative — created for classroom practice.
- No real customer, employee, or financial data was used.
- AI-generated calculations and recommendations were independently checked, not accepted as final.

## Limitations
- Business scenarios are simplified for classroom use; real cases involve more variables.
- AI outputs at every stage still require human review before use in an actual business decision.

## Skills Demonstrated
- Prompt engineering (Role–Context–Task–Constraints–Format–Evidence framework)
- Identifying and reducing AI hallucination risk in business use cases
- Applying prompting to Finance, Marketing, HR, and Sales business problems
- Evaluating AI output for business relevance, accuracy, and feasibility
