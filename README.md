# Portfolio

Simple personal portfolio site for Vamsi Valluri.

## Deploy to Vercel

This is a static site; you can deploy it to Vercel in two ways:

- Import the repo on the Vercel dashboard: https://vercel.com/new and pick this GitHub repository.
- Or use the Vercel CLI:

```bash
npm i -g vercel
cd path/to/project
vercel --prod
```

I included a `vercel.json` so Vercel will serve this as a static site and route all paths to `index.html`.

After deployment, add a Vercel badge here by replacing the example below with your project URL.

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new)

## Notes

- The site entry is `index.html`.
- Styles are in `style/style.css` and scripts in `js/script.js`.
