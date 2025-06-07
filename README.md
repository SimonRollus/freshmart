# Freshmart

This repository contains the initial setup for the **Freshmart** e-commerce application built with [Next.js](https://nextjs.org/).

## Development

1. **Install dependencies** (requires Node.js 18):

   ```bash
   npm install
   ```

2. **Run the development server**:

   ```bash
   npm run dev
   ```

   Open `http://localhost:3000` in your browser to see the app.

## Project Structure

- `pages/` – Next.js pages and API routes
- `public/` – static assets
- `styles/` – global styles
- `next.config.js` – Next.js configuration

## Deployment to Azure

This project can be deployed to **Azure App Service**. A simple deployment workflow using GitHub Actions is provided in `.github/workflows/azure.yml`.

1. Create an App Service instance and configure a publishing profile.
2. Add the publishing profile as a secret named `AZURE_WEBAPP_PUBLISH_PROFILE` in your repository.
3. Push to `main` to trigger the workflow and deploy.

## Useful Commands

- `npm run build` – build the production version
- `npm start` – start the production server
- `npm run lint` – run ESLint

