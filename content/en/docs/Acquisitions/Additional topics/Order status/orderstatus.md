---
title: "Order status"
linkTitle: "Order status"
weight: 10
tags: ["subtopic"]
---

The status of an order record impacts downstream workflows related to Receiving, Invoices, and aspects of Metadata Management.

## What is workflow status and why is it significant?
## Which fields are editable when an order is open?
## How does FOLIO know when to close an order as 'Complete'?
An order will automatically close with a ‘Reason for closure’ of Complete if all POL associated with the order achieve one of the following:
| Receiving status   | Payment status |
| -------- | ------- |
| Fully Received  | Fully Paid    |
| Fully Received | Payment Not Required     |
| Receipt Not Required   | Fully Paid    |
| Receipt Not Required   | Payment Not Required    |
| Cancelled  | Cancelled    |
