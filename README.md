# IERONIMVS POVELLVS - A Monument to the Chairman

A tribute website to Jerome Powell, Chairman of the Federal Reserve.

## Local Development

1. Install dependencies:
```bash
npm install
```

2. Start the server:
```bash
npm start
```

3. Visit http://localhost:3000

## Deployment to Railway

### Option 1: Using Railway CLI

1. Install Railway CLI:
```bash
npm i -g @railway/cli
```

2. Login to Railway:
```bash
railway login
```

3. Initialize and deploy:
```bash
railway init
railway up
```

### Option 2: Using GitHub Integration

1. Push your code to GitHub
2. Go to [Railway](https://railway.app)
3. Click "New Project"
4. Select "Deploy from GitHub repo"
5. Choose your repository
6. Railway will automatically detect the Node.js project and deploy

### Option 3: Using Railway Dashboard

1. Go to [Railway](https://railway.app)
2. Click "New Project"
3. Select "Empty Project"
4. Connect your GitHub repository or upload files
5. Railway will automatically build and deploy

## Environment Variables

No environment variables are required for this project.

## Notes

- The site uses external image sources with fallbacks
- All styling and functionality is contained in a single HTML file
- The server serves the static HTML file on all routes
