# Build your own automation

In [Presora](https://presora.co), you don't need to drag blocks around to make a workflow. Open **Automations → Describe an automation**, write what you want in plain English, and the AI builds it. You see the result on the canvas before anything is saved. Each AI build or change costs 1 AI credit (or nothing on plans with unlimited credits).

You can also ask the [AI employee](../guides/10-ai-employee.md) in its chat: *"make an automation that…"*.

## How to write a good prompt

Say four things:

1. **When:** the trigger. *"When someone fills in the quote form…"*
2. **Check (optional):** a condition. *"…if they're in Leeds…"*
3. **Do:** the actions. *"…email them a thank-you and add a call task for tomorrow."*
4. **Send or draft:** whether email goes out on its own or waits for you. *"Leave the email as a draft."*

## Prompts to copy

### Leads

- *"When someone fills in the quote form, send them a thank-you email saying we'll reply within one working day, and create a task for me due today."*
- *"When a new customer is added from the chatbot, tag them 'chatbot' and email me their conversation."*
- *"When I move a customer to Lost, wait 60 days, then draft a friendly check-in email."*
- *"Every Friday at 16:00, give me a task for each customer still in Contacted with no activity for 5 days."*

### Bookings

- *"When someone books, add a note to their customer page with the service and time."*
- *"Three days after an appointment, email the client a link to book again."*

### Email

- *"When an email arrives that mentions 'invoice', notify me on my phone."*
- *"When an email arrives from someone already in my customers, use AI to sort it as praise, question or complaint, and notify the team about complaints."*

### Team

- *"When a job application form is submitted, notify the whole team with all the answers."*
- *"Every weekday at 17:30, send me a summary of today's enquiries and bookings."*

## After it's built

1. **Read the canvas.** Check that each block does what you meant.
2. **Test.** Nothing is sent or changed, though AI blocks write real text so you can read it.
3. **Switch on** when you're happy with it.
4. Watch the **Runs** tab for the first few days.

To tweak it later, use **Change with AI** (*"wait 2 days instead of 1"*) or edit blocks by hand. See [Build, test and switch on a workflow](https://presora.co/docs/automation-editor).

## Limits worth knowing

- Workflows work with what's inside Presora: forms, bookings, the chatbot, customers, email, the shop, promotions and the blog. They don't connect to outside apps.
- Customer blocks need a plan with the CRM ([compare plans](https://presora.co/plans)).

Have a workflow that works well for your business? [Open a pull request](../README.md#contributing) to add it here.

---

[All automations](README.md) · [Automations guide](../guides/07-automations.md)
