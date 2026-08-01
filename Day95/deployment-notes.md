# Deployment Notes - Day 95

## Vercel
- Best for frontend / Next.js apps
- Auto-deploys from GitHub on every push
- Free tier available
- Zero config for most frameworks

## Render
- Good for Node.js / Express backends
- Supports web services, databases, cron jobs
- Free tier with spin-down on inactivity

## Environment Variables
- Never commit .env files to GitHub
- Add variables in the platform dashboard
- Use process.env.VARIABLE_NAME in Node.js

## CI/CD
- Continuous Integration: auto-test on push
- Continuous Deployment: auto-deploy on merge
- GitHub Actions can handle both
