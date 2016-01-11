Outstanding AR
===============

A. Overdue Accounts
===================

1. Statements and Overdue Notices
------------------------------

Statements for overdue accounts should be sent out by email on or around the beginning of each month. Ideally, these emails should be generated and sent from within Quickbooks -- QuickBooks maintains a log of all emails (dates and subject lines) sent to a given account, which will be a useful record if the overdue account becomes actionable. Different email templates can be used, depending upon how old an account is. For instance, an account which is only a week overdue may get a note reminding the member that their dues for the current month are still owing, and asking them if a payment has been missed. An account which over 30 days overdue may get a note reminding the member that the board may suspend accounts which reach 60 days.

To filter the customer list for overdue accounts, select the drop-down menu on the left-hand side of the "Customers & Jobs" screen, and select "Customers with Overdue Invoices". Note that this filter will also capture any customers who have money on account. When scanning the list, ignore any names which have a negative balance. 

In order to send a statement, select "Create Statements" from the Customer menu. Set the statement date to today (unless you are generating a historical statement), and make sure that "One Customer" is selected, with the correct customer's name. Preview the statement before sending, to make sure it looks correct.

Selecting the "Email" button will either open Quickbook's own email client, or your native one, depending upon how you have Quickbooks configured. If you are using QuickBook's internal email client, select the message body template you want to use (or write your own message). CC treasurer@kwartzlab.ca on all emails sent from Quickbooks. While Quickbooks keeps a log of all messages, it doesn't keep a copy of the message bodies. If you are sending notice of a board meeting to review the account, CC bod@kwartzlab.ca.

In addition to monthly email notices, a copy of the statement should also be sent by post once an account reaches 30 days overdue. This letter should remind members that their account may be suspended if it reaches 60 days overdue. 

2. Account Suspension & Termination
--------------------------------

When a member's account becomes 60 days overdue, the board will review it for suspension or termination. It is the Treasurer's responsibility to notify both the board and the member of this occurance. 

Our bylaws require that a member be given at least 10 days notice of this review. Ensuring these notices are sent out in a timely fashion requires some careful attention. At least 10 days before each board meeting, review the AR list for any accounts which will reach 60 days by the meeting's date. For each of these accounts:

    * send an email (CC'ing bod@kwartzlab.ca) to the member notifying them that if they are not able to bring their account up to date, it will be considered for suspension at the meeting. Invite the member to attend the meeting, or contact the board before the meeting, if they have any comments to make
    * send a copy of the email by postal mail
    * send an email to bod@kwartzlab.ca summarizing the (in camera) account actions to be added to the meeting agenda
    
If you miss the 10 day window, notify the board of the overdue accounts. The board may decide to schedule a special meeting to handle the accounts, or wait until the next regularly scheduled meeting. Once you know when the meeting will take place, advice the member. 

B. Resolving Uncollectable AR in QuickBooks
===========================================

1. Credit Memos
------------

Invoices may be cancelled if they were created in error or if the service is cancelled before its been used. For instance: if a member is invoiced for January dues, but then terminates their membership *before* January begins, the invoice should be cancelled. If the member waits until February to terminate their membership, without paying January dues, January's invoice should not be cancelled*. See instead, "Writing off Bad Debt".

To cancel an invoice, open it up in QuickBooks, and then select the "Refund/Credit" button from the menu bar. This will automatically create a credit memo in the amount of the outstanding balance of the invoice, with all of the invoice's details filled in. Make sure the date on the credit memo is set for today's date, and save. QuickBooks will ask if you want to apply the credit to an outstanding invoice. Select yes, and select the invoice which is being cancelled (it should select the correct invoice by default, but if the customer has multiple outstanding invoices, the wrong one may be selected).

2. Deleting Invoices
-----------------

Technically, QuickBooks will allow you to delete an invoice. This is not recommended, as it can create irregularities which may prolong the financial review process. These irregularities include:

    * Jumping invoice numbers. When an invoice is deleted, its invoice number will disappear from the invoice list. This gap in invoice numbers will raise questions. There is no simple way to record an explanation for this in Quickbooks, so anybody auditing the books will have to ask the Treasurer for details. Resolving the question and locating supporting documentation will invariably take longer than keeping the original invoice and issuing a credit memo would have.
    
    * Adjusting the Income/Expense totals for the period. Deleting an invoice will reduce the month's recorded Income. If that income has already been reported to the board, then those reports will no longer be valid, and will need to be resubmitted. Nobody wants to have to review multiple versions of the same report. 
    
Deleting an invoice immediately after creating it (on the same day, before any other invoice are created) won't cause any issues, however its better to develop the habit of always using credit memos. Note that deletions are still recorded in QuickBook's audit log, so if something is deleted, you can review its details. 

If you do delete an invoice, for any reason, put a note somewhere in the invoice (e.g., add a zero value line item) indicating why the invoice is being deleted. Save (to save the note) before deleting. This will help anybody reviewing the deleted invoices or audit log.

3. Writing off Bad Debt
-------------------

Bad debt is any outstanding AR which we no longer expect to recive. Most frequently, this will be outstanding membership dues from members who have since left.

Any bad debt from the previous year should be written off before corporate tax filings are calculated. Writing them off will reduce our income for the year, as well as our HST obligations. 

In Quickbooks, go to the customer who has debt to be written off, and record a new payment. The payment window should list all of the outstanding invoices for the customer. Click on the invoice number for the first invoice you want to write off -- this will select the row, without actually marking the invoice for payment (the total value of the payment should remain zero).

Click the "Discounts and Credits" button from the manu bar. Discount the full amount of the invoice. Select the "Bad Debt" account as the Discount Account. 

Repeat for all of the invoice being written off. 

In the Payment Window, select something inocuous like "Other" for the "PMT Method" (it doesn't really matter what method you select). Put "BAD DEBT" in the Reference field (so that you can easily identify the write-off, in a list-view of transactions).

Save & close.

If the debt being written off is membership dues, make sure there is also a note indicating this amount in the (confidential) Archived Membership Register. If the former member re-applies for membership, advice the board of this outstanding amount before the vote. Per current board procedures, the returning member will be responsible for this outstanding amount, before they may be readmitted. Note that the board may, at their discretion, opt to 