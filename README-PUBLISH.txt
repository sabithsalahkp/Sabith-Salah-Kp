SABITH SALAH K P — GITHUB PAGES SITEMAP CONFIGURATION

Production home page:
https://sabithsalahkp.github.io/Sabith-Salah-Kp/

Primary sitemap (submit ONLY this in Google Search Console):
https://sabithsalahkp.github.io/Sabith-Salah-Kp/sitemap.xml

INSTALLATION
1. Extract this ZIP locally.
2. Open the Sabith-Salah-Kp-main folder and upload all files AND folders inside
   to the ROOT of your existing GitHub repository (not under a nested folder).
3. Include the empty .nojekyll file. It tells GitHub Pages to serve files as-is.
4. Commit to the branch that GitHub Pages publishes from. Wait for Pages to deploy.
5. Open the sitemap URL above in your browser: it must load XML and not HTML/404.
6. In Google Search Console > Sitemaps, submit: sitemap.xml
7. Optionally remove the older sitemap-main.xml submission to avoid duplicate
   submissions. The old file is retained so existing URLs do not break.
8. Use URL Inspection for the home page, then request indexing if needed.

CHANGES IN THIS BUILD
- Added .nojekyll for predictable static file serving.
- robots.txt now advertises only the primary sitemap.xml.
- Kept sitemap-main.xml and image-sitemap.xml as backward-compatible aliases.
- No changes to the website layout, scripts, styles or imagery.

NOTES
- "Couldn't fetch" is a Google Search Console fetch state; XML validity alone
  does not guarantee immediate successful retrieval. Recheck after deployment.
- GitHub Pages project sites live in a subpath; the project-level robots.txt is
  not the host-root robots.txt used for crawler policies. Submit sitemap.xml
  directly in Search Console instead of relying on robots.txt discovery.
- Google indexing is not guaranteed immediately after sitemap submission.
