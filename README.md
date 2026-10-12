# Gospel Journey

**[Start the journey →](https://systemslibrarian.github.io/gospel-journey/)**

An interactive path through Scripture to understand the good news of Jesus Christ.

> *"If you declare with your mouth, 'Jesus is Lord,' and believe in your heart that God raised him from the dead, you will be saved."*  
> — Romans 10:9 (NIV)

## Part of a larger path

Gospel Journey is **Step 1 — Believe** in the Scripture & ministry path of [Prayer Sealed Ministries, Inc.](https://prayersealed.org), built by [Paul Clark](https://github.com/systemslibrarian). It is where the path begins: coming to know Jesus Christ as Lord and Savior.

| # | Stage | Project |
|---|---|---|
| **1** | **Believe** | **Gospel Journey** ← you are here |
| 2 | Understand | [Scripture Journey](https://scripturejourney.com) · [repo](https://github.com/systemslibrarian/scripture-journey) |
| 3 | Remember | [Hide in Heart](https://hideinheart.com) · [repo](https://github.com/systemslibrarian/HideInHeart) |
| 4 | Discern | [His Will Guide](https://hiswillguide.com) · [repo](https://github.com/systemslibrarian/hiswillguide) |
| 5 | Intercede | [Prayer Sealed](https://prayersealed.org) |
| 6 | Pass It On | My Life With Christ *(in development)* |

## Mission

Gospel Journey is designed to help visitors understand the Gospel clearly, personally, and biblically - from creation and sin to the cross, resurrection, and the invitation to receive salvation by grace through faith.

## Stack

- Vite
- TypeScript
- HTML/CSS
- Vanilla TypeScript

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Multi-page Routes

- Home: `index.html`
- Journey: `journey.html`
- Who Is Jesus?: `who-is-jesus.html`
- Why Do I Need Saving?: `why-saving.html`
- The Scarlet Thread: `scarlet-thread.html`
- Ready to Respond?: `respond.html`
- New Believer Next Steps: `next-steps.html`
- Scripture Library: `scripture-library.html`
- Prayer Response: `prayer-response.html`
- About: `about.html`

## GitHub Pages

- Live site: https://systemslibrarian.github.io/gospel-journey/
- Vite is configured with `base: './'` in `vite.config.ts` for project-page compatibility.
- Automated deploy workflow is included at `.github/workflows/deploy-pages.yml`.
- In GitHub repository settings, set **Pages** source to **GitHub Actions**.

## Privacy

- No tracking or analytics by default
- No accounts
- No backend
- Optional reflection/progress data uses localStorage only
