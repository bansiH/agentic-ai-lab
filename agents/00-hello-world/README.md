# 00 — No-Code Hello World Agent

## Objective

Build the smallest useful agent loop without writing application code.

**Input → understand → act → observe → respond**

The first version should prove the workflow, not teach infrastructure.

## Recommended implementation

Use **Make + WhatsApp Business Cloud** for the first exercise.

Alternative: use **n8n + WhatsApp Business Cloud** if you want to start directly with the platform that will be used for later low-code exercises.

## First use case

Send a WhatsApp message such as:

> What are my tasks for today?

For the Hello World exercise, do not connect personal email, calendar, banking, or financial accounts yet. Use a small synthetic data source such as Google Sheets.

The agent should:

1. Receive a message.
2. Identify the request.
3. Read a small, approved data source.
4. Produce a concise response.
5. Send the response back to WhatsApp.
6. Log the interaction without storing secrets.

## Definition of done

- A message enters the workflow.
- The workflow identifies the request.
- A tool/data source is queried.
- The result is grounded in retrieved data.
- A response is returned.
- Errors are visible rather than silently swallowed.
- No consequential action is performed.

## Next step

After this works, add LLM-based intent extraction and structured output in:

`agents/01-email-triage/`
