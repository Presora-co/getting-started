# Presora tips and gotchas

Short, practical lessons for getting the most out of [Presora](https://presora.co), grouped by area. Each one links to the guide or [official doc](https://presora.co/docs) with the details.

## Setup

- **Business info is the source of truth.** Fix details there, not on the page, and the site, chatbot and emails all follow. → [Business info](https://presora.co/docs/business-info)
- **Run *Build into my website* after every Business info change** to sections like hours, pricing, team or FAQs. It's free, safe to repeat, and never touches sections you added by hand. → [Guide](../guides/01-first-hour.md#2-build-it-into-your-website)
- **Opening hours and booking hours are separate.** Change one, check the other. → [Opening hours and booking hours](https://presora.co/docs/booking-hours)

## Website

- **Use *Select* for precise AI edits.** Drag a box over the part you mean, so the AI changes exactly that and not the whole page. → [Guide](../guides/02-website.md#ask-the-ai)
- **Asking questions in the editor chat is free.** Only changes cost a credit.
- **Out of AI credits? You're not stuck.** Editing by hand and restoring from History cost nothing.
- **Save publishes immediately.** Check the **Mobile** preview before you press *Save to live site*.
- **Undo is one click.** History keeps your last 25 versions. → [Website history](https://presora.co/docs/website-history)
- **Describe photos instead of searching for them.** *"A photo with only pizza in it"* picks from your uploads and stock photos for your trade.

## Domain and DNS

- **Copy DNS values from the *Your domain* page.** Never guess them or reuse old ones.
- **Cloudflare: grey cloud, not orange.** The proxy must be off (*DNS only*).
- **Already have an A record? Change it.** Don't add a second one.
- **Leave MX records alone** until you're ready to move your email. Adding Presora's MX replaces Gmail or Outlook for that domain.
- **Turn off registrar forwarding.** Web forwarding or redirects at the registrar stop the domain from reaching your site.
- **Give DNS up to an hour.** It's usually minutes. Use **Check now** rather than re-adding records.
- **Stuck?** Use the *Setup guide* on the domain page, or ask the team to manage the domain for you. → [Domain troubleshooting](https://presora.co/docs/domain-troubleshooting)

## Chatbot

- **Brief it like a new receptionist.** Prices, areas, policies, what you *don't* do. → [Guide](../guides/04-chatbot-and-leads.md)
- **Spend ten minutes a week on *What it couldn't answer*.** It's the fastest way to make the chatbot better.
- **Use *Most-asked questions* as content ideas** for FAQs, service pages and blog posts.
- **Promotions teach it automatically.** When a promotion is live, the chatbot knows about it.

## Customers and pipeline

- **Move cards.** Several automations run on stage changes, so a board that never moves means automations that never fire.
- **Replace AI estimates with real numbers.** Values marked ✦ ~ are guesses, and your own figure makes *Open value* meaningful.
- **Automatic follow-ups need a Presora email address**, because they track emails sent from inside Presora. → [Follow-ups](https://presora.co/docs/follow-ups)

## Automations

- **Start with drafts, then let it send.** When you trust an email workflow, add a *Send draft* block.
- **Test before you switch on.** Test runs change nothing, but AI blocks write real text, so you can read it first.
- **Duplicate to experiment.** *More → Duplicate* keeps the original safe.
- **Check *Failed this week*.** A failed run usually means a missing detail, like a contact with no email. The *Runs* tab shows which step failed.
- **Only one review request.** If you run a shop, use one of the two review workflows, not both. → [Shop automations](../automations/online-shop.md#tips)

## Shop

- **No card payments.** The shop takes cash on delivery, bank transfer or payment in the shop. Say so clearly on your site.
- **Mark orders completed on time.** Surveys and review requests count their days from that moment.
- **Moving from WordPress?** Import your WooCommerce shop instead of retyping it. → [WooCommerce import](https://presora.co/docs/shop-import-woocommerce)

## AI employee

- **Ask it to set things up.** *"Let's set up my business"* gives you a plan card, and nothing changes until you press **Apply**. Every applied plan has **Undo**. → [Guide](../guides/10-ai-employee.md)
- **It can't change billing, connect domains or invite teammates.** It points you to the right page instead.

## Getting found

- **Run the [free website checker](https://presora.co/tools/website-checker)** on your site, and on a competitor's.
- **Add a page per town you cover.** → [Website pages](https://presora.co/docs/website-pages)
- **Read the [small business website checklist](https://presora.co/blog/small-business-website-checklist)** once a year.

---

Back to [README](../README.md) · Have a tip? [Contribute it](../README.md#contributing).
