# Creative Tech Portfolio

Public, recruiter-facing portfolio for Abraham Haddioui Lastras.

Live site: <https://creative-tech-portfolio.vercel.app/>

Preserved Hacker Lab: <https://v0-flipper-zero-cv-page.vercel.app/>

## Positioning

**Creative Technologist & Hybrid Maker**

Audience: English-speaking creative agencies, event studios, product teams and marketing teams in the Netherlands, with Arnhem and Gelderland as the geographic focus.

Primary goal: employment with an English-speaking creative, event or product team. Secondary goal: selected freelance collaborations. Payments and marketplace features are intentionally outside the first release.

## Public/private boundary

- This repository is the public source of truth for the portfolio and printable CV.
- `NEXUS Visual Engine` is linked as a live public project.
- `Career OS` is described only as an anonymised case study. Its working application and personal data stay private.
- `Job Alerts NL` is described as a local automation case study until its sources and public configuration are hardened.

## Files

- `index.html` - public portfolio landing page.
- `cv/index.html` - ATS-readable, print-ready one-page CV.
- `cv/Abraham-Haddioui-Creative-Technologist.pdf` - generated delivery PDF.
- `vercel.json` - static routing and security headers.

## Local preview

```powershell
python -m http.server 4173
```

Open `http://127.0.0.1:4173/` and `http://127.0.0.1:4173/cv/`.

## Deployment workflow

1. Work locally.
2. Deploy a Vercel Preview without `--prod`.
3. Check desktop, mobile, CV download and print output.
4. Promote the verified Preview to Production.
5. Connect the final professional domain to the Production deployment.

Do not copy the `.vercel` directory or secrets into Git.
