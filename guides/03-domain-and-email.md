# Domain and email

Every [Presora](https://presora.co) website gets a free `yourname.presora.co` address with HTTPS. You can also connect a domain you own and get email addresses on it. See [managed website hosting](https://presora.co/features/website-hosting) and [business email](https://presora.co/features/business-email).

## Your free presora.co address

**My website → Domain → Free Presora address**: claim one, or press **Change subdomain**. It can be 3–40 letters, numbers or hyphens, and some names are reserved.

- Changing it means the old address stops reaching your site.
- HTTPS for a new address takes about a minute.

Official doc: [Your website's address](https://presora.co/docs/website-address)

## Connect your own domain

1. On your website's page, in the **Domain** panel under **Your own domain**, type the domain without `https://` (for example `yourshop.com`).
2. Keep **Also serve the www version** ticked if you want `www.yourshop.com` to work too.
3. Press **Connect domain**. The **Your domain** page opens.
4. At your domain registrar (GoDaddy, Namecheap, Cloudflare and so on), add the records listed under **Add these at your domain registrar**:
   - an **A record** on the domain (`@`) pointing at Presora
   - a **TXT record** at `_presora-verify` that proves you own the domain
   - a **CNAME** for `www`, if you ticked it
5. Wait. Presora re-checks DNS by itself (or press **Check now**), then issues the HTTPS certificate automatically, usually within minutes of DNS being right.

> **Always copy the record values from the Your domain page.** Don't guess them or copy them from an old guide.

**Not sure where to click at your registrar?** Use the **Setup guide** on the same page. Say which registrar your domain is with and it shows you where to go. For a plain-English explanation of A, CNAME, TXT and MX records, read [Connect your domain to your website: DNS records explained](https://presora.co/blog/connect-domain-dns-records-explained).

**Don't want to touch DNS at all?** Presora can manage the domain for you. Ask the team in **Messages**.

Official doc: [Connect your own domain](https://presora.co/docs/connect-domain)

## If your domain isn't working yet

Statuses on **Your domain**:

**Waiting for DNS** → **Verified — issuing certificate** → **Live**

**Needs attention** shows the problem it hit. The checklist on that page shows which part is missing: *Domain points here*, *Ownership verified*, *www works*, *Secure (HTTPS)*.

The usual fixes:

- **Give it time.** DNS changes usually show within minutes and can take up to an hour. Leave TTL alone.
- **One A record only.** If the domain already has an A record, change it instead of adding a second one.
- **Cloudflare users:** turn the proxy off. The orange cloud must be grey (*DNS only*).
- **Turn off web forwarding** or redirects at your registrar.
- **Leave MX records alone** unless you're moving your email to Presora.

Official doc: [My domain isn't working yet](https://presora.co/docs/domain-troubleshooting)

## Email on your own domain

Once your domain is live, **Set up email** under it on **Your domain** shows the email records to add: **MX**, three **DKIM** CNAMEs, **SPF** and **DMARC**.

> ⚠️ **Adding the MX record moves the domain's email to Presora.** It replaces Gmail, Outlook or whatever handled that email before. Plan the switch first so you don't miss any mail.

- DKIM can take up to an hour to verify.
- The status goes from **Email — waiting for DNS** to **Email live**. Then **Create inboxes →** takes you to **Email**.
- **Turn off email on this domain** undoes it.

Email on your own domain and custom addresses are on the Growth and Enterprise plans ([compare plans](https://presora.co/plans)).

Official docs: [Email addresses on your own domain](https://presora.co/docs/domain-email) · [Your email inbox](https://presora.co/docs/inbox) · [Add an email address](https://presora.co/docs/email-addresses) · [Forward mail to another inbox](https://presora.co/docs/email-forwarding) · [Email style and signature](https://presora.co/docs/email-style)

---

← [Edit your website](02-website.md) · Next: [Chatbot and leads →](04-chatbot-and-leads.md)
