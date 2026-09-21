# Invoice a finished job

**Screen: Invoicing, the table under Ready to invoice**

## Read the row

| Column | Meaning |
|---|---|
| When | The date of the visit |
| Customer | Who the invoice is for |
| Job | The job type |
| Time | Chargeable time, in 30-minute blocks |
| Labour | Time at the hourly rate agreed at booking |
| Travel | The flat travel charge for the customer's postcode band |
| Materials | Parts the service supplied, at cost |
| VAT | Worked out for this job and household. Some jobs are zero-rated, so it will often be less than 20% of the net |
| Total | What the customer pays |

## Check it against the tracker

Each row is compared with the service's payment tracker, and shows the result:

| Shown as | Meaning | What to do |
|---|---|---|
| Agrees with the tracker | Both records show the same amount | Carry on |
| Tracker says (an amount) | The two records disagree | Find out which is right before you issue |
| Not in the tracker | The tracker has no entry for this visit | Check whether it was missed |
| In the tracker, no amount recorded | There is an entry, but no figure | Carry on, and fill in the tracker |
| Already paid | The tracker shows this was settled | Do not invoice again. Record the payment |
| Not a chargeable visit | For example a quoting visit | Nothing to invoice |
| Tracker check unavailable | The comparison could not be run | Check by hand |

## Preview, then issue

1. Select **Preview** to open the invoice as a PDF. Nothing is recorded, and no invoice number is used.
2. If it is right, select **Issue invoice**.
3. Your browser asks you to confirm. Issuing takes the next invoice number and **fixes the figures**. Select OK.
4. Send the PDF to the customer by your usual route.

!!! warning "Preview first, every time"
    Once issued, an invoice cannot be edited. The only way to change it is to [cancel it with a credit note](credit-notes.md) and issue a new one.

## Mark invoiced

If the invoice was raised outside Handy Andy, select **Mark invoiced** so the job leaves the list.

## Record payment

Use **Take card payment** for a card, or send a [payment link](payment-links.md). A row that shows **already paid** has nothing left to do.

## Jobs funded by an energy award

Jobs marked as paid by an energy redress award are not invoiced to the household. They are still costed in full so that the award can be reported against.
