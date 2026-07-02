# hmongservicecenter.org

Static landing page for **Hmong Service Center, Inc.** (Oshkosh, WI · EIN 39-1484528 · 501(c)(3)).
Single self-contained `index.html` (inline CSS, no build step). Style: warm editorial, Hmong *paj ntaub* textile motif, indigo/crimson/gold, serif.

## Deploy (GitHub Pages)
1. `git init && git add -A && git commit -m "feat: initial Hmong Service Center landing page"`
2. Create repo, push.
3. Repo Settings → Pages → deploy from `main` / root.
4. DNS (registrar Spaceship): apex A records → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`; `www` CNAME → `<user>.github.io`. `CNAME` file already set to `hmongservicecenter.org`.
5. Enable HTTPS in Pages.

## Before applying to Claude for Nonprofits (build-guards)
- [ ] **Set MX** + create `info@hmongservicecenter.org` (needed for org email + Goodstack).
- [ ] **Age domain 60 days** from registration before applying (playbook rule).
- [ ] Confirm real contact **phone** + add it (not yet on file).
- [ ] Replace avatar initials with **real leader photos/bios** when available (Mee Yang, Nalee Yang, Yeng Lor) → strengthens identity-verification.
- [ ] Wire the **Support Our Work / donate** button to a real donation link.
- [ ] Apply as a **named officer** (Mee Yang, President) from an `@hmongservicecenter.org` email.

## Guard note
Services are foregrounded (economic/education/language/resource-navigation); festival/cultural framing intentionally minimized to protect the Goodstack beneficiary (G5) test. Keep it that way.
