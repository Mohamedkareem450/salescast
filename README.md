# SalesCast

Static website (no build step). Everything is in `index.html`.

## Deploy to Vercel

Option A, command line:
    npm i -g vercel
    cd salescast-site
    vercel --prod

Option B, GitHub:
    1. Create a GitHub repo and upload these files.
    2. On vercel.com choose Add New > Project, import the repo.
    3. Framework preset: Other. Leave build command empty. Deploy.
