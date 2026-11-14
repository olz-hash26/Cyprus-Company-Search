# CompanyData Cyprus SEO referral page

A small, static information page designed to attract relevant Cyprus company-search queries and send visitors to the main website: [https://companydata.com.cy/](https://companydata.com.cy/).

## Files
- `index.html` — SEO-focused copy, page metadata, FAQ content, structured data and links to the main CompanyData website
- `styles.css` — responsive styles
- `robots.txt` and `sitemap.xml` — crawler discovery files (review the sitemap URL to match the final hosting domain)

## Important
This is **not** a separate company-search product. It has no search form, database or search results. All primary calls to action direct visitors to https://companydata.com.cy/.

## Deploy
Publish the repository root using your chosen static host. Configure the host's actual domain and HTTPS, then update `sitemap.xml` and the Sitemap line in `robots.txt` to use that deployed domain. Do not set the referral page's canonical URL to companydata.com.cy unless this page is actually hosted at that URL.

## SEO launch checks
- Confirm the final hosting URL and add a self-referencing canonical URL only when appropriate.
- Submit the deployed sitemap in Google Search Console and Bing Webmaster Tools.
- Keep the text accurate and useful; avoid adding unsupported claims about company records, data coverage or update frequency.
- Make sure the host allows indexing and that the page returns HTTP 200.
