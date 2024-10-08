# 📂 osTicket: Ticket Lifecycle Examples

This project illustrates the typical lifecycle of a ticket in osTicket. It covers how tickets move through different stages, from creation and assignment to resolution, showing the functionality and workflow in real-world scenarios.

## 🚀 Features

- **📝 Ticket Creation**: Submit tickets via email or the osTicket web form.
- **🔄 Ticket Assignment**: Automatically or manually assign tickets to agents or teams.
- **🛠️ Ticket Status Updates**: Update ticket status as agents work on and resolve issues.
- **📅 Ticket Resolution**: Demonstrate how tickets are closed and the resolution process documented.
- **🔔 Notifications**: Show how notifications are sent to users and agents at each step.

## 🛠️ Tech Stack

- **osTicket**: Ticketing system used to manage the lifecycle.
- **Email (SMTP)**: For ticket submission and notification purposes.
- **MySQL**: Database that stores ticket information and statuses.

## ⚙️ Ticket Lifecycle Examples

### Example 1: Simple Support Ticket
1. **Ticket Submission**:
    - A user submits a ticket via the web form.
2. **Ticket Assignment**:
    - The system assigns the ticket to the IT support department.
3. **Status Update**:
    - An agent picks up the ticket and sets it as "In Progress."
4. **Resolution**:
    - The agent resolves the issue and updates the ticket as "Closed."
5. **Notification**:
    - The user receives an email notification confirming the ticket resolution.

### Example 2: Escalation Workflow
1. **Ticket Submission**:
    - A user submits a high-priority ticket via email.
2. **Assignment to Department**:
    - The ticket is assigned to a Tier 1 support team.
3. **Escalation**:
    - The issue is escalated to Tier 2 after being reviewed.
4. **Resolution and Closure**:
    - Tier 2 resolves the issue and marks the ticket as closed.

## 📑 Project Structure

```plaintext
osticket-ticket-lifecycle/
│
├── examples/             # Folder with detailed ticket lifecycle examples
│   ├── example1.md       # Simple ticket lifecycle example
│   ├── example2.md       # Escalation workflow example
├── README.md             # Project documentation (this file)
