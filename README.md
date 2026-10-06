# ZB Beneficiaries — zb beneficiaries ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `zbbeneficiariesltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/zbbeneficiariesltd.mjs`).
> To change the content, edit that file and run `node build.mjs zbbeneficiariesltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@zbbeneficiariesltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Quote) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
ZB Beneficiaries Ltd, a private limited company registered in England and Wales (company number 15376500), provides management consultancy services other than financial management to small and mid-sized organisations: reviewing operations and identifying where time and cost are lost, improving and documenting processes, supporting organisational structure and team planning, and setting up performance reporting that managers use. Engagements are scoped and quoted in writing after a free first meeting and billed per project or per day. The company is not a financial adviser, accountancy practice or law firm and gives no financial, investment, tax or legal advice. Site: zbbeneficiariesltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
