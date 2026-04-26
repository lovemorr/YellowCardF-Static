# YellowCardF - Static Verification Site

Static HTML/CSS/JS site for COMESA Yellow Card verification.

## Structure
- `index.html` - Landing page
- `form.html` - Policy form
- `generator.html` - Policy generator  
- `YellowCard-policy-verify.html` - Verification page
- `master_policy_list.html` - Policy list
- `css/` - Stylesheets
- `js/` - Client-side JavaScript

## Deploy to Vercel

1. **Create new Vercel project**:
   - Go to https://vercel.com/new
   - Import this repository
   - Framework: **Other**
   - Deploy

2. **Update API URL**:
   - After deploying the admin repo, update `js/config.js`
   - Replace `YOUR-ADMIN-APP` with actual admin app URL
   - Redeploy

## URLs
- Main site: `https://your-static-app.vercel.app/`
- Verification: `https://your-static-app.vercel.app/YellowCard-policy-verify.html`
