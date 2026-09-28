# Annapurna Mandal — Portfolio (Netlify-ready static site)

## Before deploying
1. Put your resume at `resume/Annapurna_Mandal_Resume.pdf`
2. Put screenshots at `assets/healthsentinel.png` and `assets/swiggy-dashboard.png`
3. Set your real LinkedIn URL in `index.html` (search `linkedin.com`)

## Deploy (easiest: drag & drop)
1. Go to https://app.netlify.com/drop  (sign up free)
2. Drag this whole folder onto the page.
3. You get a link like https://random-name.netlify.app
4. Site settings -> Change site name -> e.g. `annapurna-mandal` => https://annapurna-mandal.netlify.app

## After you have your final link (important for Google)
Replace `https://YOUR-SITE.netlify.app` with your real link in:
`index.html` (canonical, og:url, JSON-LD), `robots.txt`, `sitemap.xml`
Then re-deploy (drag the folder again).

## Show up in Google
1. Open https://search.google.com/search-console -> Add property -> URL prefix -> your link
2. Verify (Netlify: HTML tag method — paste the meta tag in <head> of index.html and redeploy)
3. Submit `sitemap.xml`, then "URL Inspection" -> Request indexing
Indexing takes a few days to a few weeks.


## Project screenshots
The `assets/` folder contains HealthSentinel and Swiggy Sales Analysis dashboard screenshots used in the project showcase.
