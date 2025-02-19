# Microservices Architecture

## Planned Microservices:
- **Account Service:** Handles account creation, updates, and closures.
- **Transaction Service:** Manages all types of fund transfers and transactions.
- **Loan Service:** Handles loan applications and management.
- **Notification Service:** Manages alerts, emails, and push notifications.

## Design:
- Each service will communicate via RESTful APIs.
- Services will be stateless and use databases specific to their function.
