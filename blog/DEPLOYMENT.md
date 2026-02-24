# Deployment Guide

## Option 1: GitHub Pages

1. Create a new GitHub repository
2. Upload all files from this directory
3. Go to Settings > Pages
4. Select "main" branch as source
5. Your site will be live at `https://yourusername.github.io/repo-name`

## Option 2: Netlify

1. Sign up at netlify.com
2. Drag and drop this entire folder
3. Your site will be live instantly with a random URL
4. Optional: Configure custom domain

## Option 3: Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in this directory
3. Follow the prompts
4. Site will be deployed

## Option 4: Traditional Web Host

1. Use FTP/SFTP client (FileZilla, Cyberduck, etc.)
2. Upload all files to `public_html` or `www` directory
3. Site will be accessible at your domain

## Testing Locally

### Simple Python Server
```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

### Simple PHP Server
```bash
php -S localhost:8000
# Visit http://localhost:8000
```

### Node.js http-server
```bash
npx http-server
# Visit http://localhost:8080
```
