# Privacy Policy — Page to Markdown for AI

Last updated: 2026-08-18

Page to Markdown for AI does not collect, store, transmit, sell, or share any user data, browsing history, or
personal information. There are no external servers involved in the extension's operation — all processing
happens locally inside your browser.

## What the extension does

- When you click "Export This Page", the extension reads the content of the page currently open in your active
  tab and converts it to Markdown, entirely within your browser.
- When you click "Export Selected as Markdown" in the linked-pages feature, the extension fetches only the
  specific linked pages you have checked in the popup, directly from your browser to the linked page's own
  server (the same as if you had opened that link yourself), and converts the result to Markdown.
- The generated Markdown file is saved to your computer using Chrome's built-in downloads feature.

## What the extension does not do

- It does not send any data to the developer or any third party.
- It does not use analytics, tracking, or telemetry of any kind.
- It does not read or store your browsing history beyond the single tab/pages you explicitly export.
- It does not require an account, login, or payment.

## Permissions

- `activeTab` / `scripting`: to read and convert the content of the page you choose to export.
- `downloads`: to save the generated Markdown file to your computer.
- `offscreen`: to safely parse the HTML of linked pages you select, before converting to Markdown.
- `host_permissions` (`<all_urls>`): to allow the extension to operate on any site you choose to export from, and
  to fetch the specific linked pages you select in the "linked pages" feature.

## Contact

Questions about this policy can be sent to: bgcena@gmail.com
