# Polar Polycule Network Graph

Interactive visualization of historical relationships using vis.js Network.

## GitHub Pages Deployment

This project is set up for automatic deployment via GitHub Pages. Any changes pushed to the `main` branch will automatically update the live site.

**Live URL:** https://stopitsgingertime.github.io/graph2/

### To Enable GitHub Pages (if not already enabled):

1. Go to your GitHub repository: https://github.com/stopitsgingertime/graph2
2. Click on **Settings**
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Click **Save**
6. Your site will be available at: `https://stopitsgingertime.github.io/graph2/`

### To Update the Live Site:

1. Make changes to `index.html` in Cursor
2. Commit and push:
   ```bash
   git add index.html
   git commit -m "Update graph"
   git push
   ```
3. GitHub Pages will automatically rebuild and deploy (usually takes 1-2 minutes)

You can monitor the deployment status in the **Actions** tab of your GitHub repository.

