# Freelance invoice checklist

A field-by-field checklist for invoices sent by freelancers and small trades in the US: what each field is for, what to write in it, and the mistakes that get an invoice sent back by a client's accounts payable team.

Copy it, fork it, print it. Pull requests with corrections are welcome.

## Header

- [ ] The word **Invoice** at the top. A document titled "Bill" or "Statement" may be filed differently by the client.
- [ ] **Invoice number**, unique and increasing. Common formats:

  | Format | Example | Good for |
  |---|---|---|
  | Plain sequence | `1001`, `1002` | a few invoices a month |
  | Year + sequence | `2026-001` | most freelancers; files by year |
  | Client code + sequence | `ACME-014` | repeat clients; keep one master log |
  | Date + sequence | `20260314-01` | several invoices a day |

  Never reuse a number, even for a cancelled invoice: void it and issue the next one. More on formats and voids: [invoice number guide](https://avoinvoice.com/guides/invoice-number/?utm_source=github&utm_medium=referral&utm_campaign=links-2026-10).
- [ ] **Invoice date**: the day you issue it.
- [ ] **Due date**: a calendar date. If your terms are "Net 15", print the date as well.

## You

- [ ] Your legal name or business name, as it appears on your bank account.
- [ ] Email, phone, mailing address.
- [ ] Website or portfolio link.
- [ ] Tax ID or license number only if your trade or your client requires it. Most clients ask for a W-9 separately instead.

## The client

- [ ] The client's **legal business name**, not your contact's name.
- [ ] Billing address and the email of whoever pays invoices.
- [ ] **PO number**, if the client issued one. Companies with an AP department often reject invoices without it.
- [ ] Project or job name, so the invoice can be matched to the work.

## Line items

- [ ] One line per deliverable or per block of work.
- [ ] Each line: description, quantity, rate, amount.
- [ ] Hourly work shows hours and rate: `Design, 12 h × $85`.
- [ ] Extra revision rounds, rush fees and add-ons on their own named lines.
- [ ] Expenses you pass through (stock licenses, travel) as separate lines.
- [ ] Deposit received shown as a **negative line**, with the number of the invoice it was paid against.

## Totals

- [ ] Subtotal.
- [ ] Sales tax only on taxable lines, with the rate shown. Many freelance services are not taxable; check your state.
- [ ] Discounts or credits as negative lines.
- [ ] **Total due**, the largest number on the page.

## Payment terms

- [ ] Due date or term (Due on receipt, Net 15, Net 30).
- [ ] Accepted payment methods, with the details needed to pay (bank transfer details, PayPal email, a card payment link).
- [ ] Late fee, if you charge one, stated as a rate and when it starts.

## Before you send

- [ ] Saved as **PDF**, not as an editable file.
- [ ] File named by number and client: `2026-007-acme.pdf`.
- [ ] Email subject has the invoice number, amount and due date.
- [ ] Sent the day the work was delivered.
- [ ] Logged somewhere you will check weekly (spreadsheet, app, notebook).

## Common reasons an invoice comes back

| Problem | Fix |
|---|---|
| No PO number | Ask for it before you start the job |
| Wrong legal name of the client | Copy it from the contract or W-9 request |
| "Due on receipt" with no date | Print a calendar date |
| One lump-sum line | Split it so the client can approve each part |
| No way to pay listed | Add at least one method with full details |

---

This checklist is maintained by the makers of [Avo](https://avoinvoice.com/?utm_source=github&utm_medium=referral&utm_campaign=links-2026-10), an invoice app for iPhone. The checklist itself is tool-independent and works with any template, spreadsheet or app.

Practical guidance, not tax or legal advice.
