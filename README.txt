STINK PYRENEES — COMING SOON SITE

FILES TO UPLOAD TO GITHUB (upload the files, not the zip):
- index.html
- great-pyrenees.jpg

1. Create a free account at https://github.com if you do not have one.
2. Create a NEW PUBLIC repository named stink-pyrenees-coming-soon.
3. Open the repository, click Add file > Upload files, upload index.html and great-pyrenees.jpg, then Commit changes.
4. Go to Settings > Pages > Build and deployment. Set Source to Deploy from a branch, Branch to main, folder /(root), then Save.
5. Wait for the temporary URL, typically https://YOURUSERNAME.github.io/stink-pyrenees-coming-soon/.
6. Under Settings > Pages > Custom domain, enter YOUR ACTUAL DOMAIN WITHOUT www, and Save. GitHub may create a CNAME file automatically.
7. In Namecheap, go to Domain List > Manage > Advanced DNS. Make sure your nameservers are Namecheap BasicDNS, PremiumDNS or FreeDNS; otherwise edit records wherever DNS is managed.
8. Add four A records with Host @ pointing to:
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
9. Add a CNAME record with Host www pointing to YOURUSERNAME.github.io (replace YOURUSERNAME with your real GitHub username).
10. Remove only conflicting parking, redirect, or website A/CNAME records for @ and www. Do not delete MX, TXT or other email records.
11. Wait for DNS to propagate (up to 24 hours). In Settings > Pages, enable Enforce HTTPS when available.
12. Visit both https://YOURDOMAIN and https://www.YOURDOMAIN and verify the image and text.

Notes: GitHub Pages repositories are public on the free tier. Do not upload secrets or private files. This static page has no email form and does not collect customer information. GitHub Pages is suitable for a coming-soon page, not a full ecommerce checkout.

Official docs:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
https://www.namecheap.com/support/knowledgebase/article.aspx/9645/2208/how-do-i-link-my-domain-to-github-pages/
