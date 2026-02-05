# workato-mock-data

**Use case: Sentiment-Based Escalation**

**Story / How the Agent Works:** Imagine a regional operations manager receives dozens of store messages daily. Some are urgent, some are minor. The agent reads each message, understands the tone, and decides whether it needs human attention. It learns that angry, frustrated messages require escalation, while neutral messages can be handled automatically.

**Mock Input Example:** 
**Message Text:**
“This shipment is delayed again! Our shelves are empty, and customers are angry!” Store ID: 143 Channel: Email Timestamp: 2026-01-30 09:15

**AI Agent Decision:** Sentiment: Negative Severity: High

**Human-in-the-Loop:** Confidence 0.6 → Human approval triggered

**Output Example:** Action: Escalate to regional manager Notes: Urgent stock issue, immediate attention required

