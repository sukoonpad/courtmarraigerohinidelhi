# Court Marriage Delhi — Website

**Live Website:** https://courtmarriagedelhi.in  
**Contact:** 9891343962

---

## Website Structure

```
courtmarriage-website/
│
├── index.html          ← Homepage (main landing page)
├── court-marriage.html ← Court Marriage service page
├── arya-samaj.html     ← Arya Samaj Marriage page
├── muslim-nikah.html   ← Muslim Nikah page
├── pricing.html        ← Pricing / Fees page
├── about.html          ← About Us page
├── contact.html        ← Contact / Location page
└── style.css           ← Global stylesheet (shared by all pages)
```

---

## GitHub Pages pe Deploy Karne ke Steps

1. GitHub pe naya repository banao (e.g. `courtmarriagedelhi`)
2. Saari files upload karo (ya `git push` karo)
3. Repository Settings → Pages → Source: `main` branch, `/ (root)` select karo
4. Save karo — website live ho jayegi at `https://yourusername.github.io/courtmarriagedelhi/`

---

## Custom Domain (courtmarriagedelhi.in) Lagane ke Steps

1. Repository mein ek file banao: `CNAME`
2. Usme sirf likho: `courtmarriagedelhi.in`
3. Domain provider (GoDaddy/Namecheap) mein DNS settings mein jaao:
   - `A` record → `185.199.108.153`
   - `A` record → `185.199.109.153`
   - `A` record → `185.199.110.153`
   - `A` record → `185.199.111.153`
   - `CNAME` → `www` → `yourusername.github.io`
4. GitHub Pages settings mein custom domain add karo
5. "Enforce HTTPS" checkbox on karo

---

## Services & Pricing

| Service | Price | Time |
|---------|-------|------|
| Arya Samaj Marriage | ₹3,100 | Same Day |
| Court Marriage | ₹6,100 | 1–2 Hours |
| Muslim Nikah | ₹7,000 | Same Day |
| Tatkal / Urgent | ₹12,000 | Priority Same Day |

---

*© 2026 Court Marriage Consultants Delhi. All Rights Reserved.*
