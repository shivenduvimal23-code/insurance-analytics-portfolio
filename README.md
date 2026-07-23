# Shivendu Vimal — Fintech Data & Business Intelligence Portfolio

A recruiter-focused portfolio for data analyst, business analyst, BI analyst, risk analyst and product analytics opportunities.

## Positioning

This version presents Shivendu as a **fintech data and business intelligence professional**, rather than limiting the profile to insurance reporting. It connects real insurance analytics experience with the independent CardPulse payments-risk project.

## What the site highlights

- Complex SQL and business-rule implementation
- Python/Pandas data preparation and automation
- Large-scale IRDAI regulatory data pipelines
- Revenue, premium and commission analytics
- Data quality, reconciliation and root-cause analysis
- Executive dashboards and stakeholder communication
- Payments risk, merchant intelligence and fraud metrics
- Cloud/data-warehouse exposure through Trino, Hive, Snowflake and S3

## Deployment on GitHub Pages

1. Open the repository: `insurance-analytics-portfolio`.
2. Replace the existing `index.html` with the new `index.html` from this folder.
3. Replace the existing `README.md` with this file.
4. Commit the changes to the `main` branch.
5. Open **Settings → Pages** and confirm the source is **Deploy from a branch**, branch `main`, folder `/root`.
6. Wait for the GitHub Pages deployment check to finish, then hard refresh the live site.

## Optional improvements

### Add a professional photo

Use a square or portrait headshot with a clean background. Save it as `profile.jpg`, upload it to the repository, then replace the `.avatar` initials element in `index.html` with:

```html
<img class="avatar-photo" src="profile.jpg" alt="Shivendu Vimal" />
```

Add this CSS:

```css
.avatar-photo {
  width: 82px;
  height: 82px;
  object-fit: cover;
  border-radius: 24px;
  border: 2px solid rgba(85, 214, 190, 0.35);
}
```

### Add a resume button

Upload the latest one-page resume as `Shivendu_Vimal_Resume.pdf`, then add this button in the hero action area:

```html
<a class="btn btn-secondary" href="Shivendu_Vimal_Resume.pdf" target="_blank">View resume ↗</a>
```

### Add a social preview image

A placeholder Open Graph path is already included as `portfolio-preview.png`. Upload a 1200 × 630 image with that filename for a stronger LinkedIn/WhatsApp preview.

## Important accuracy note

All company work should remain sanitised. Do not upload confidential SQL, customer data, internal dashboard links, credentials, S3 paths or proprietary rate grids.
