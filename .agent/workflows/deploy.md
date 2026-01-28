---
description: how to deploy the application to Vercel
---

Since you have already pushed your code to GitHub, deploying to Vercel is straightforward:

1. **Sign Up/Log In**: Go to [vercel.com](https://vercel.com) and sign up or log in using your GitHub account.
2. **New Project**:
   - Click the **"Add New..."** button.
   - Select **"Project"** from the dropdown.
3. **Import Repository**:
   - Find your repository `Clean` (from `DevHubFusionX/Clean`) in the list.
   - Click the **"Import"** button next to it.
4. **Configure Project**:
   - **Framework Preset**: Vercel usually detects "Other" or "Plain HTML" for static sites.
   - **Build and Output Settings**: Since this is a static project, you can leave these as default (Empty).
   - **Root Directory**: Ensure it points to the root of your project `./`.
5. **Deploy**:
   - Click the **"Deploy"** button.
6. **Assign Domain** (Optional):
   - Once deployed, Vercel will provide a `.vercel.app` URL.
   - You can add a custom domain in the **Settings > Domains** section of your project dashboard.

// turbo
7. **Automatic Deployments**: Every time you `git push` to your `main` branch, Vercel will automatically trigger a new deployment to update your site.
