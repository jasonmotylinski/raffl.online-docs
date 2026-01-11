---
title: Managing Entries & Payments
---

# Managing Entries & Payments

After your sponsor event is live, you can manage sponsor entries and view payment information.

## Editing Sponsor Entries

Use the **Edit Entries** tab to manually override or add sponsor names. This is useful for offline payments (checks, cash, etc.).

### To Edit a Sponsor Entry:

1. Navigate to your sponsor event
2. Click the **Edit Entries** tab
3. Enter or modify the sponsor name in the input field for the desired sponsorship space
4. Click **Save All Entries**

### Entry Status Indicators

Each sponsorship space shows:

- **Filled** (green checkmark) – Sponsor name has been entered
- **Price** – Shows the price if not yet purchased
- **Free** – Shows "Free" if the space has no cost

### Example

```
                Friday AM    Friday PM    Saturday AM    Saturday PM
Puppy Classes
  Best Puppy      Acme Corp    [empty]    Doggy Treats   Paws & Co
  Reserve Puppy   [empty]      Bark Inc    [empty]        PetLand
```

## Offline Payment Workflow

For sponsors paying by check, cash, or other offline methods:

1. Receive payment from sponsor
2. Go to **Edit Entries** tab
3. Enter the sponsor's name in the appropriate sponsorship space
4. Click **Save All Entries**
5. The sponsor's name will appear on the public sponsor page

---

## Viewing PayPal Payment Details

View all PayPal transactions for your sponsor event.

### To View Payment Details:

1. Navigate to your sponsor event
2. Click the **PayPal Details** tab

The table displays:

| Column | Description |
|--------|-------------|
| **Item Number** | PayPal transaction item number |
| **Payment Status** | Status badge (Completed, Pending, etc.) |
| **Payment Date** | Date the payment was received |
| **Last Name** | Buyer's last name |
| **First Name** | Buyer's first name |
| **Amount** | Total amount paid |

!!! note
    Only transactions processed through PayPal appear in this table. Offline payments won't appear here (but will show up in Edit Entries once you add them manually).

## Metrics & Analytics

View sponsorship statistics and activity:

### To View Metrics:

1. Navigate to your sponsor event
2. Click the **Metrics** tab

The dashboard displays:

- **Unique Visitors** – Total number of people who viewed your sponsor page
- **Last 7 Days Activity** – Graph showing daily visitor counts
- **Total Sponsor Spaces** – Total number of sponsorship spaces available
- **Spaces Sold** – Number of sponsored spaces (both online and manually added)

!!! tip
    Use these metrics to track interest in your sponsor event and optimize pricing if needed.

---

## Common Tasks

### Add an Offline Sponsor

1. Receive payment (check/cash)
2. Go to **Edit Entries** tab
3. Find the sponsorship space
4. Enter sponsor name
5. Click **Save All Entries**

### Correct a Sponsor Name

1. Go to **Edit Entries** tab
2. Find the sponsorship space with the incorrect name
3. Edit the name
4. Click **Save All Entries**

### Remove a Sponsor (Refund)

1. Go to **Edit Entries** tab
2. Clear the sponsor name field (leave empty)
3. Click **Save All Entries**
4. Process refund through PayPal or bank (manually)

### View a Specific Payment

1. Go to **PayPal Details** tab
2. Locate the payment by buyer name or date
3. Note the Item Number for your records

---

## Integration with Public Page

Changes you make in the admin panel immediately appear on the public sponsor page:

- New offline payments show up within seconds
- Corrected sponsor names update instantly
- Removed entries are hidden from public view

There's no need to publish or deploy—everything is live in real-time.

---

## Need Help?

- **Sponsorship spaces won't populate?** Make sure you've added both days and groups/classes in the setup steps
- **Can't find the Edit Entries tab?** You need to complete Steps 1-3 (Event Details, Days, Groups & Classes) first
- **PayPal details missing?** PayPal payments sync automatically via webhook; offline payments must be added manually in Edit Entries
