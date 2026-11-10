# Automations for an online shop

A [Presora](https://presora.co) online shop comes with its own set of automations. They appear in **Automations** once your shop is open. Customer emails here **send on their own**, with product pictures and buttons straight back to your shop. Set the shop up first: [Online shop guide](../guides/09-online-shop.md).

Discount codes created by these workflows are personal to each shopper and expire, so they can't be shared around.

## On by default

| Automation | When | What happens |
|---|---|---|
| **Remind shoppers about their cart** | 4 hours after a cart is left without an order | Emails them what's in it, with a button back to the cart. *Recovers orders that were one click away.* |
| **Wishlisted product back in stock** | A product someone saved can be bought again | Emails them a picture of it and a button straight to it. *Sales from shoppers who were already waiting.* |
| **Wishlisted product on sale** | A product someone saved gets cheaper | Emails them the new price next to the old one. *Turns "maybe later" into an order.* |
| **Ask how their order went** | 3 days after you mark an order completed | Emails a short survey with stars for the order, the delivery and the packaging. *You hear about a problem before it becomes a bad review.* |
| **Remind about unpaid bank transfers** | 3 days after a bank-transfer order, if it's still not marked paid | Emails the buyer the bank details again and tells the team. *Fewer orders stuck waiting for money.* |
| **Alert on a bad review** | A product gets 3 stars or fewer | Everyone on the team hears about it by phone and email. *An unhappy customer gets an answer, not silence.* |
| **Alert when stock runs low** | A product (or one of its sizes) is down to 2 or fewer | A note on the team's phones. *Best sellers don't quietly go out of stock.* |
| <a id="monday-sales-summary"></a>**Monday sales summary** | Every Monday at 8:00 | Last week's orders, takings, average order, new customers, best sellers and what's running low. *Know how the shop did without opening it.* |

## Optional (switch on if you want them)

| Automation | When | What happens |
|---|---|---|
| **Second cart reminder with a code** | The cart is still there a day later | Emails again with a personal **10% code**, valid 3 days. Works alongside the first reminder. |
| **Alert on a big cart left behind** | A cart worth 100 or more (10.000 in dinars) sits for 2 hours | A note on the team's phones with who it is and what's in it, so you can get in touch. |
| **Turn happy survey answers into reviews** | A buyer gives their order 4–5 stars in the survey | Thanks them and asks for a review, with a review link for each product. |
| **Ask for a review after delivery** | 5 days after you mark an order completed | Emails the products they bought with a button to review them. |
| **Welcome code for new accounts** | A shopper creates an account | Emails a **10% code** for their first order (valid 14 days) with your best sellers. |
| **Thank first-time buyers with a code** | 3 days after someone's first order | Thanks them and gives **10% off** their next order (valid 30 days). |
| **Win back customers who stopped ordering** | A past customer hasn't ordered for 90 days | Emails a **10% code** (valid 14 days) with what's new. |
| **Show new arrivals to shoppers who haven't visited** | A shopper with an account hasn't visited for 60 days | Emails them the newest products. No discount needed. |
| **Spot your VIP customers** | An order takes a customer past a total spent (500 in euros, 50.000 in dinars) | Tags them `vip` and tells the team. |

## Tips

- **Pick one review route.** *Turn happy survey answers into reviews* and *Ask for a review after delivery* both ask for reviews. Use one, or space them out, so buyers aren't asked twice.
- **Mark orders completed on time.** Surveys and review requests count their days from that moment.
- **Change any number.** Discount percentage, wait time and thresholds can all be changed in the editor, or ask the [AI employee](../guides/10-ai-employee.md): *"make the cart reminder 6 hours"*.

---

Official doc: [The shop's ready-made automations](https://presora.co/docs/shop-automations) · [All automations](README.md)
