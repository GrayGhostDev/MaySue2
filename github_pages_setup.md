# GitHub Pages Setup for May Sue Case Management

## Steps to Complete GitHub Pages Setup

1. Go to your GitHub repository in a web browser
2. Click on the **Settings** tab
3. In the left sidebar, click on **Pages** under "Code and automation" section
4. Under "Build and deployment", set the following:
   - Source: Deploy from a branch
   - Branch: Select "gh-pages" from the dropdown menu
   - Folder: / (root)
5. Click **Save**

Your site will be published at: `https://[username].github.io/may-sue-case-management/`

## Important Notes

- It may take up to 10 minutes for changes to publish after you've pushed to GitHub
- Make sure all assets (images, CSS, JS) use relative paths to work correctly on GitHub Pages
- If you need a custom domain, you can configure it in the GitHub Pages settings

## Troubleshooting

If your site doesn't appear or has styling issues:
- Check that all file paths are relative, not absolute
- Verify that the gh-pages branch contains all necessary files
- Look at the GitHub Pages section in Settings for any error messages 