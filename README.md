# Guides by Locals — Social Media Pipeline Dashboard

An interactive, responsive social media workflow dashboard designed for GitHub Pages or static web hosting, powered by Google Sheets backend data via Google Apps Script.

## Features
- **Pipeline Kanban Board**: Track content across Visual & Drafting, Video Production, QA Verification, and Approved/Scheduled gates.
- **Search & Multi-Filters**: Filter instantly by social platform (Instagram, TikTok, Threads), content pillar, and QA status.
- **Deep-Dive Drawer Modal**: 1-click caption copy, format specs, location verifications, audit notes, and Drive asset links.
- **Live Google Apps Script Sync**: Connect your Google Sheets Web App URL in settings to pull real-time editorial updates, with automatic offline fallback to embedded sample data.
- **Analytics & Insights**: Platform share, pillar breakdown, and funnel conversion powered by Chart.js.

## GitHub Deployment
1. Push `index.html` to the root of your GitHub repository.
2. In your repository on GitHub, go to **Settings** > **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**, choose `main` branch and `/ (root)`, then click **Save**.
4. Open the deployed GitHub Pages URL, click **Connect Sheets API**, and paste your Apps Script Web App URL.
