# Prompt Library v1 — Customer Support Reply Generator

A reusable prompt template for generating professional, empathetic customer-support replies. Instead of writing a new prompt for every customer issue, one structured template with replaceable variables is adapted to each situation.

Built during my internship at **Neurofive Solutions** · Tested with **ChatGPT**

## How the template works
Every prompt follows the same five components:

| Component | Purpose |
|---|---|
| **Role** | Sets the AI up as a support representative for `{COMPANY_NAME}` |
| **Context** | The `{CUSTOMER_ISSUE}`, the `{CUSTOMER_MESSAGE}` and any `{ADDITIONAL_INFO}` |
| **Task** | What the reply must achieve |
| **Format** | The structure the reply should follow |
| **Constraints** | Tone and length limits |

## Goals
- Reusable across different customer issues
- Consistent response structure
- Easy to swap customer-specific details
- Controlled tone and length
- No rewriting prompts from scratch

## Repository contents
| File | Description |
|---|---|
| [`Prompt_Library_v1.md`](Prompt_Library_v1.md) | The master template, design rationale and usage guide |
| [`prompts_and_outputs.md`](prompts_and_outputs.md) | Five customized prompts built from the template, with the AI-generated replies |

## Usage
1. Open `Prompt_Library_v1.md` and copy the master template.
2. Replace the `{VARIABLES}` with your company and customer details.
3. Paste into your LLM of choice and review the reply before sending.
