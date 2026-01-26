# LinkedIn Content Tracker

A simple tool to capture LinkedIn post ideas, organize them, and track what you've posted.

## Features

- **Ideas Bank** - Capture and organize post ideas with categories
- **Generate Post** - Create post drafts from starred ideas
- **Scheduled** - Track posts you plan to publish
- **Posted Ideas** - Archive of everything you've published

## Data Storage

- Data is saved automatically in your browser's localStorage
- **Export Backup** - Download your data as JSON (recommended regularly)
- **Import Backup** - Restore data from a backup file

## Deployment to GitHub Pages

1. Create a new GitHub repository (e.g., `linkedin-content-tracker`)

2. Push this code:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/linkedin-content-tracker.git
   git branch -M main
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to repo Settings → Pages
   - Source: Deploy from branch
   - Branch: main, folder: / (root)
   - Save

4. Your app will be live at: `https://YOUR_USERNAME.github.io/linkedin-content-tracker`

## Local Usage

Just open `index.html` in your browser. No server needed.
