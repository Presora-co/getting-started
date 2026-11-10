# Automations

[Presora automations](https://presora.co/features/automations) are workflows that run on their own: confirm bookings, follow up quiet leads, tell your team about new forms, send weekly summaries. Automations are on the Growth and Enterprise plans ([compare plans](https://presora.co/plans)).

Looking for something to switch on? Go to the **[pre-built automations](../automations/README.md)**.

## Three ways to get a workflow

1. **Presora defaults.** Workflows Presora sets up for you, in two groups:
   - **On for everyone**: already running. Switch any off, or open one to change it.
   - **Switch on if you want them**: ready to go, off until you turn them on.
2. **Start from a recipe.** Ready-made workflows open in the editor **switched off**, so you can check them before they run.
3. **Describe an automation.** Write what you want in your own words and the AI builds it. This costs 1 AI credit, or nothing on plans with unlimited credits. See [Build your own](../automations/build-your-own.md) for prompts.

Official doc: [Automations: workflows that run on their own](https://presora.co/docs/automations-overview)

## How a workflow is built

Every workflow starts from a **trigger**:

- a website form is filled in
- a call, appointment or table is booked
- the chatbot gets a question, or captures a lead
- a new customer is added, or a customer changes stage
- an email is received
- a shop event happens (order, cart, review, stock and so on)
- a promotion ends, or someone signs up through a pop-up
- a schedule fires (for example every Monday at 9:00)
- or only when you press run

Blocks then run **left to right** along the connections:

| Group | Blocks |
|---|---|
| Email | Draft email, Send draft |
| Notifications | Notify me, Notify team (phone and/or email) |
| Customers | Find or add customer, Edit customer, Add timeline note, Create task |
| AI | AI write, AI sort |
| Logic | If, Filter answers, Schedule, Loop, Fork, Stop |
| Also | Website settings and promotions, shop blocks |

Customer blocks need a plan with the CRM. Locked blocks show *Not on your plan*.

## Test, then switch on

1. **Test** runs the workflow with sample details. Nothing is sent or changed, though AI blocks do write real text so you can read it.
2. **Switch on**, and it runs by itself from then on.
3. **Run now** runs it once for real, after it's on.

**Change with AI:** say what to change (*"wait 2 days instead of 1"*). You see the result on the canvas before saving.

**Undo / Redo:** ⌘Z / ⇧⌘Z (Ctrl+Z / Ctrl+Y on Windows). The **Runs** tab shows each run step by step, and why a step failed. **More → Duplicate** is the safe way to try a variation.

Official doc: [Build, test and switch on a workflow](https://presora.co/docs/automation-editor)

## Drafts waiting for you

Emails a workflow writes **wait as drafts** unless the workflow has a **Send draft** block. That's deliberate: AI-written replies get a human check first. Find them in **Automations → Waiting for you**, and the bell also tells you when some are waiting. Open a draft to edit it, then **Send**, **Save changes** or **Discard**.

Official doc: [Emails your automations wrote](https://presora.co/docs/automation-drafts)

## Keep an eye on them

The tiles on **Automations** show *Switched on*, *Runs this week*, *Drafts to review* and *Failed this week*. A failed run is usually a missing detail, like a contact with no email. Open **Runs** to see which step failed.

> **Tip:** Turn workflows on one or two at a time and check the first few runs. It's easier to see what each one does before the next is switched on.

---

← [Online booking](06-booking.md) · Next: [Marketing and blog →](08-marketing-and-blog.md)
