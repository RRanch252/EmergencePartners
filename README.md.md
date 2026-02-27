# Emergence Partners — Website

**Live URL:** [www.emergence.partners](https://www.emergence.partners)  
**Hosting:** GitHub Pages  
**Domain:** Custom domain via CNAME  

---

## File Inventory

| File | Purpose |
|------|---------|
| `index_v2.html` | Main site — investment philosophy, strategy, risk management, team, insights, ESG |
| `search.html` | Search page — knowledge base with quick actions |
| `privacy.html` | Privacy Policy (GDPR Article 13/14) — **requires Lewis sign-off before publish** |
| `cookies.html` | Cookie Policy — **requires Paul to confirm analytics setup** |
| `CNAME` | Custom domain configuration (`www.emergence.partners`) |
| `README.md` | This file |

---

## Regulatory Controls

- **Jurisdiction gate** on all pages — visitors must confirm investor status and location before accessing content
- **US 506(b) notice** displayed when US jurisdiction is selected
- **Cookie consent banner** appears after gate acceptance (Accept All / Essential Only)
- **GDPR consent checkbox** on newsletter subscription form
- **No commercial terms** on public site (fees, minimums, lock-up, returns removed)
- **No track record or case studies** on public site
- **Reverse solicitation posture** — site is informational, not promotional

---

## Pending Items (Do Not Publish Until Resolved)

- [ ] Entity identification in footer — Lewis to confirm EP Services FZco details (name, address, registration number)
- [ ] Privacy Policy — Lewis to review and approve content, confirm data controller
- [ ] Cookie Policy — Paul to confirm whether Google Analytics or other tracking is installed
- [ ] CIMA disclaimer — Lewis + Cayman counsel to confirm whether needed given EP's advisory relationship
- [ ] Board sign-off — Lewis requires EP management committee approval before go-live

---

## Deployment

Site is deployed automatically via GitHub Pages when changes are pushed to the `main` branch. See step-by-step guide below.

### To update the site:

```bash
git clone https://github.com/[USERNAME]/[REPO].git
cd [REPO]
# Replace files, then:
git add .
git commit -m "description of changes"
git push origin main
```

Changes go live within 1–2 minutes of pushing.

---

## Change Log

| Date | Change | Approved By |
|------|--------|-------------|
| 27 Feb 2026 | Regulatory cleanup: removed Track Record, Fund Terms, Service Providers sections. Stripped commercial terms. Added jurisdiction gate, cookie consent, privacy/cookie policy pages. | Pending board sign-off |

---

## Governance

- **Regulatory text changes** require Lewis's written approval
- **Content changes** require Paul's approval
- **Material changes** (new disclaimers, structural changes) require EP management committee sign-off
- **Quarterly review** against regulatory changes in BVI, Cayman, UK, UAE, US, Ireland
- All versions archived via Git commit history
