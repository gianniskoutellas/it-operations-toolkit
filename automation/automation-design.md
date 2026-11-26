# Request Intake Automation

## Business problem
Requests arrive through email or chat and can be missed, duplicated, or lack key information.

## Proposed workflow
1. Employee submits a structured request through a form.
2. The automation creates a tracker record.
3. The relevant recipient receives a notification.
4. Operations reviews, prioritises, and resolves or escalates the request.

## Trigger
New form response.

## Actions
- Create tracker record.
- Send notification email.

## Data captured
- Requester
- Department
- Request type (IT support / Office / Access / Equipment)
- Urgency (Low / Medium / High)
- Description
- Submission timestamp

## Limitations
- This is a design document; no live automation is claimed.
- Human review is required before access, spending, or security decisions.
- No credentials, personal data, or sensitive attachments should be collected.

## Future improvements
- Add automatic categorisation.
- Add SLA reminders.
- Add an approval workflow for purchases.
- Integrate with Google Workspace or a CRM.
