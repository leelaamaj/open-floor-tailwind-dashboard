# OPEN FLOOR // Backstage

A static, responsive creator dashboard for fictional house DJ Rafi Solis. Built for the 4Geeks **A simple Dashboard with Tailwind CSS** project using semantic HTML and Tailwind CSS v4. The page contains fictional sample data for September 1–28, 2026.

## Preview

Open `index.html` in a browser, or serve this folder with a simple static server. The page loads Tailwind v4 from `https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4`, so the browser needs an internet connection for its styles.

## What the dashboard answers

- How much commission did Rafi earn? **€3,232.50** from **280** tracked sales.
- Which product earns the most? **Creator Kit**, with **€1,440** commission.
- Which platform has the highest commission ROI? **Twitch**, at **215.00%**.
- Which platform brings the most sales? **TikTok**, with **90**.

Commission is 15% of each product's sales value. Sales per platform reach is sales divided by that platform's reach. Engagement rate is engagements divided by reach. Commission ROI is `(commission - promotion cost) / promotion cost`. The combined reach of 134,000 is a sum across platforms and is **not** a unique audience count.

## Assignment structure

1. **The Pulse:** three headline KPIs.
2. **What Moved the Room:** platform performance, product performance, and a directional content funnel.
3. **The Crate:** operational platform and product details plus a recommendation.

The layout is mobile first and adapts through Tailwind's responsive breakpoints. It uses no React, Vue, external chart package, custom stylesheet, or interactive controls.

[4Geeks project page](https://learn.4geeks.com/main-cohort/miami-ft-ai-engineering-4/syllabus/web-ui-fundamentals-with-tailwind-miami-self-paced/project/simple-dashboard-tailwind-css?moduleId=2)
