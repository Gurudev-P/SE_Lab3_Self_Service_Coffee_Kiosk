# Software Engineering Lab 3 — Self-Service Coffee Kiosk

This repository contains the Lab 3 architecture submission for the **Self-Service Coffee Kiosk System**.

## Selected Architecture

**Layered Architecture** was selected. The design is divided into three layers:

1. **Presentation Layer** — handles customer interaction through the touch-screen user interface.
2. **Business Layer** — contains the order-management and payment-processing responsibilities.
3. **Data / Hardware Layer** — contains database access and receipt-printer integration.

## Main Components

The component diagram identifies five main components:

- User Interface Component
- Order Manager Component
- Payment Service Component
- Receipt Printer Component
- Database Component

## Deliverables

| File | Description |
|---|---|
| `deliverables/Lab3_PES2UG24AM125_Component_Diagram.pdf` | UML component diagram showing the layered architecture, components, and interfaces. |
| `deliverables/Lab3_PES2UG24AM125_Justification.pdf` | Written justification for selecting Layered Architecture, including separation of concerns, component interaction, payment isolation, and performance considerations. |

## Interfaces Shown

The diagram uses provided/required interface notation for the Order API, Payment API, Menu/Price API, Receipt API, and USB/Printer interface.

## Submission Note

The PDFs in `deliverables/` are the submitted files supplied for this Lab 3 repository. No implementation code is included in this submission package.
