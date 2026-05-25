# Automation QA Assessment

## Task 1
Performed QA testing on the RealWorld demo application.

Issues identified:
- Weak password validation
- Poor error messaging
- Empty article submission
- Accessibility concerns
- Performance lag with large input

## Task 2
Created an n8n workflow using:
- Schedule Trigger
- CoinGecko API
- HTTP Request Node
- Code Transformation Node
- IF Conditional Node

The workflow fetches cryptocurrency market data every hour, transforms the response, and validates price conditions automatically.

## Error Handling
Workflow designed to avoid silent failures and support stable execution.