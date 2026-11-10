# Automations for leads and enquiries

Workflows that make sure every enquiry from your [Presora](https://presora.co) website gets a fast, sensible response. Most of them use the [CRM](https://presora.co/features/crm). See [Customers and follow-ups](../guides/05-customers-and-follow-ups.md).

---

## Follow up when a lead goes quiet

**Status:** On by default · **Sends:** leaves a draft, plus a task for you

> No lead slips through the cracks.

**When:** someone fills in a form on your website.

**What happens:**

1. Waits **3 days**.
2. Checks whether you've moved them past **New** in your pipeline.
3. If you haven't, it drafts a friendly follow-up email to them and creates a task for you: *"Call [name] — no reply yet"*, due today.

**Adjust it:**

- Change the wait to 1 or 2 days if your customers decide fast (emergency trades, restaurants).
- Add a **Send draft** block after the email if you're happy for it to go without checking.

**Tip:** It only fires if the customer is still in **New**, so moving cards along your pipeline is what stops it.

---

## AI drafts a reply to every enquiry

**Status:** Optional · **Sends:** leaves a draft

> Answer enquiries in minutes, not days.

**When:** someone fills in any form on your website.

**What happens:**

1. AI writes a warm, helpful reply that answers what it can from what it knows about your business. If it doesn't know something, like an exact price, it says you'll confirm it. It ends by suggesting a next step.
2. The reply is saved as a draft addressed to the customer.
3. A note is added to their timeline in Customers saying a draft is waiting.

**Adjust it:**

- Open the **AI write** block and add your own instructions, for example *"Always mention we offer free quotes within 10 miles."*
- The better your Business info and chatbot knowledge, the better the drafts.

---

## Sort enquiries with AI

**Status:** Optional · **Sends:** an email to you for sales enquiries

> Spend your time on the enquiries that pay.

**When:** someone fills in any form on your website.

**What happens:** AI reads the message and decides whether it's **sales**, **support** or **spam**.

- **Spam** → the contact is marked **Lost** and tagged `spam`.
- **Sales** → tagged `sales-lead`, and you're emailed straight away.
- **Support** → tagged `support`.

**Adjust it:** add a fourth category (say, *job application*) to the **AI sort** block and give it its own branch.

---

## Monday pipeline check-in

**Status:** Optional · **Sends:** nothing to customers, tasks for you

> Deals keep moving.

**When:** every Monday at 9:00.

**What happens:** finds **Qualified** customers with no activity for **7 days** (up to 25 at a time) and creates a task for each: *"Check in with [name]"*.

**Adjust it:** change the day, the stage it looks at, or the number of quiet days.

---

## Ask happy customers for a review

**Status:** Optional · **Sends:** leaves a draft

> More reviews, from the customers most likely to leave a good one.

**When:** you move a customer to **Won**.

**What happens:**

1. Waits **2 days**.
2. Drafts a short thank-you that asks for a review.
3. Adds a note to their timeline saying the request is waiting.

**Before you switch it on:** open the **Draft email** block and add your review link, such as your Google review link. Once you trust it, add a **Send draft** block so it goes out on its own.

---

## Email the landing page leads who qualify

**Status:** Recipe · **Sends:** on its own

> Your reply goes to the leads worth replying to.

**When:** someone sends the form on one of your [ad landing pages](https://presora.co/features/ad-landing-pages).

**What happens:** checks one of their answers, for example *"Do you have a budget of $50 or more?" = Yes*, and emails only the people who pass. Nobody else is emailed or removed.

**Adjust it:** choose the landing page, the question and the answer that counts as a pass, and write the email.

---

Related: [Chatbot automations](chatbot.md) · [All automations](README.md) · [Leads guide](../guides/04-chatbot-and-leads.md) · Read: [How to stop missing customer enquiries](https://presora.co/blog/missed-customer-enquiries)
