# Privacy Policy for Grocery Ledger

**Last updated:** June 22, 2026

Grocery Ledger ("the extension") is a browser extension that builds a personal record of your grocery spending across supported delivery websites (Blinkit, Zepto, and Swiggy Instamart). This policy explains exactly what data the extension handles, how it is used, and where it is kept.

The short version: everything the extension reads stays on your own device. The extension has no server, sends nothing to the developer, and shares nothing with any third party.

## Who this policy is for

Anyone who installs and uses Grocery Ledger.

## What data the extension handles

The extension only reads data on grocery websites that you explicitly enable, and only after you are already logged in to those sites. It reads this data directly from each store's own pages and order API, on the same site, using your existing browser session.

The extension handles the following categories of data:

1. **Financial and payment information.** This is the core purpose of the extension. It reads your order history from the enabled stores: order dates, item names, quantities, prices, discounts, delivery and platform fees, and order totals. It uses this to show you what you spent. It does NOT read or store credit or debit card numbers, bank details, or credit ratings.

2. **Website content.** To extract your orders, the extension reads the text content of your order history and order detail pages on the enabled stores. It only reads order related content. It does not read unrelated pages.

3. **Authentication information.** To request your own order data from a store's order API, the extension reuses the authentication headers that your browser already sends to that same store while you are logged in. These headers are held only in Chrome's in-memory session storage, are never written to permanent storage, are never included in logs, diagnostics, or exports, and are never transmitted to the developer or any third party. They are automatically cleared when the browser session ends or when you clear the extension's data.

## What the extension does NOT collect

The extension does not collect, store, or transmit:

- Names, postal addresses, email addresses, phone numbers, age, or government identifiers
- Health information
- Personal communications such as emails, texts, or chat messages
- Location data, including precise location or GPS coordinates
- A list of the web pages you browse (web history)
- Clicks, mouse movement, scrolling, or keystrokes
- Cookies, passwords, or saved payment methods

These items are excluded from all captures, logs, diagnostics, and exports.

## How your data is used

Captured order data is used for one purpose only: to display your purchase ledger and spending summaries inside the extension. Data is processed and stored locally in your browser profile using Chrome's storage. There is no developer account, no backend service, no analytics, no advertising, and no telemetry. No remote code is executed; all logic ships inside the installed package.

## When data leaves your browser

Your data leaves your browser only when you choose to make it leave:

- When you explicitly export a file from the extension
- When you open a "Request Feature" email draft, which is composed in your own email client under your control

The extension itself makes no third party network calls and sends no data to the developer.

## Data retention and deletion

Your ledger data stays in your browser profile until you delete it. You can remove all extension data at any time from the extension's Settings. Uninstalling the extension also removes its stored data. In-memory authentication headers are cleared automatically when the browser session ends.

## "Ask AI" preview

The dashboard shows an "Ask AI" preview screen. In this version it is a non-functional, coming-soon teaser for a future release. It sends no data, makes no network calls, and runs no model. No question, order data, or API key is collected or transmitted by this build.

## Data sharing and sale

The extension does not sell or transfer your data to third parties. It does not use or transfer your data for any purpose unrelated to showing your purchase ledger. It does not use or transfer your data to determine creditworthiness or for lending purposes. The extension follows the Chrome Web Store User Data Policy, including the Limited Use requirements.

## Changes to this policy

If this policy changes, the updated version will be posted at this same URL with a new "Last updated" date.

## Contact

Questions about this policy can be sent to: mehul355180@gmail.com
