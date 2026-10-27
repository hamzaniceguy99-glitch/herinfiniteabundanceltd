# Her Infinite Abundance — her infinite abundance ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `herinfiniteabundanceltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/herinfiniteabundanceltd.mjs`).
> To change the content, edit that file and run `node build.mjs herinfiniteabundanceltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@herinfiniteabundanceltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Never) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Her Infinite Abundance Ltd provides business consultancy and training from Devon, trading since 2017 and formerly named Momentum South West and Momentum Business Academy. We work with owner-managed businesses on strategy and planning, operations and process, training and workshops, and ongoing advisory support. What we do not do defines us more usefully. There are no income screenshots on this site and no promises of revenue, because an earnings claim has to be capable of substantiation under the advertising code and almost none in this industry are. We also say plainly that business coaching is unregulated: no licence, no protected title, nobody vetting anyone. And we refer out what is reserved, including investment advice, which needs FCA authorisation, and reserved legal activities. Site: herinfiniteabundanceltd.shop
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
