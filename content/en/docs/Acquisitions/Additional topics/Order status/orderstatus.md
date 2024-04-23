---
title: "Order status"
linkTitle: "Order status"
weight: 10
tags: ["subtopic"]
---

The status of an order record impacts downstream workflows related to Receiving, Invoices, and aspects of Metadata Management.

## What is workflow status and why is it significant?
Workflow status is the overall status of the order record: Pending, Open, or Closed. When an order record is created, it is saved in a 'Pending' status and cannot be opened until at least one purchase order line (POL) is associated with the order.

When an order is opened, several different events occur. See [Opening an Order] (../acquisitions/orders/#opening-an-order) for more information. The act of opening an order also impacts editability of select fields on the order and POL (see below).

An order can be closed automatically by the system (see below) or can be manually closed by a staff user in FOLIO. See [Closing an Order] (../acquisitions/orders/#closing-an-order) for more information.

## Which fields are editable when an order is open?
A library may need to edit fields on an order record with an 'Open' status. This is especially common on Ongoing and Ongoing subscription orders. Use the table below to determine if a field is editable. If the field is not listed in the table below, and order must be unopened to edit the field. See [Unopening an Order] (../acquisitions/orders/#unopening-an-order) for more information.

### Order fields
| One-Time   | Ongoing | Ongoing Subscription |
| -------- | ------- | ------- |
| Vendor |     |     |
| Acquisition unit |      |     |
| Bill to   |     |     |
| Ship to  |     |     |
| Tags  |    |    |
| Note  |    |    |
| Custom fields  |    |    |

### Order line fields
| One-Time   | Ongoing | Ongoing Subscription |
| -------- | ------- | ------- |
| Receiving note |     |     |
| Subsciption from |      |     |
| Subscription to   |     |     |
| Linked package  |     |     |
| Internal note  |    |    |
| Receipt date  |    |    |
| Receipt status  |    |    |
| Payment status  |    |    |
| Claiming active  |    |    |
| Claiming interval  |    |    |
| Cancellation restriction  |    |    |
| Cancellation description  |    |    |
| Line description  |    |    |
| Tags  |    |    |
| Donor information  |    |    |
| Vendor reference number and type  |    |    |
| Unit price (physical and electronic)  |    |    |
| Additional cost  |    |    |
| Currency  |    |    |
| Set exchange rate  |    |    |
| Discount  |    |    |
| Fund distribution |    |    |
| Receipt/Activation due  |    |    |
| Expected activation/receipt date  |    |    |
| URL  |    |    |

## How does FOLIO know when to close an order as 'Complete'?
An order will automatically close with a ‘Reason for closure’ of Complete if all POL associated with the order achieve one of the following:
| Receiving status   | Payment status |
| -------- | ------- |
| Fully Received  | Fully Paid    |
| Fully Received | Payment Not Required     |
| Receipt Not Required   | Fully Paid    |
| Receipt Not Required   | Payment Not Required    |
| Cancelled  | Cancelled    |
