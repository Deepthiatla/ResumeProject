# ResumeProject

## Deployment

### Deploy to Vercel

This project is configured for easy deployment to Vercel. Follow these steps:

#### Prerequisites
- A [Vercel account](https://vercel.com)
- Git repository pushed to GitHub

#### Deployment Steps

1. **Connect your repository to Vercel:**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Select your GitHub repository (Deepthiatla/ResumeProject)
   - Vercel will auto-detect your project settings

2. **Configure build settings (if needed):**
   - Build command: (auto-detected based on your project)
   - Output directory: (auto-detected based on your project)
   - Environment variables: Add any required environment variables

3. **Deploy:**
   - Click "Deploy"
   - Vercel will build and deploy your project automatically

4. **Access your live project:**
   - Your resume will be live at a URL like: `https://resume-project-{username}.vercel.app`

#### Continuous Deployment

- Every push to the `main` branch will automatically trigger a new deployment
- Preview deployments are created for pull requests

#### Custom Domain (Optional)
- In Vercel dashboard → Settings → Domains
- Add your custom domain and follow the DNS configuration steps

