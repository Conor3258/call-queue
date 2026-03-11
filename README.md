# Call Queue GitHub Pages Wrapper

This repository is intended to be published with GitHub Pages.

## Expected live URL
https://conor3258.github.io/call-queue/

## Files
- index.html

## How to publish
1. Create a public GitHub repository named `call-queue` under the account `conor3258`.
2. Upload `index.html` to the root of the repository.
3. In GitHub: Settings -> Pages.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**.
6. Save.
7. Wait for Pages to publish. The site should become available at:
   https://conor3258.github.io/call-queue/

## Teams app notes
- The Teams manifest in the ZIP package points contentUrl to https://conor3258.github.io/call-queue/
- validDomains includes conor3258.github.io and portal.hostedpbx.ie
- websiteUrl points to https://portal.hostedpbx.ie/#/apps/callcenter/callcenter/queues?view=table

## Important
If HostedPBX blocks iframe embedding or login inside Teams desktop, the fallback link in the page opens the queue in the browser.
