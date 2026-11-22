# Steady

Steady is a private, phone-friendly monthly spending tracker. Set a limit for each category, log purchases, and compare what you planned with what actually happened. It is designed to help people notice patterns without shaming them.

## Use it

Open `index.html` in a current browser. Add or edit category limits, use **Log a purchase** when you spend, and mark whether the purchase was planned. Choose a month to look back; each month's category limits are stored separately. **Export data** downloads a CSV of purchase entries. The currency picker supports USD, KES, EUR, GBP, INR, NGN, ZAR, GHS, UGX, and TZS.

No sign-up, bank connection, server, or build step is needed. Data is saved in local storage in the browser on that device. It does not sync to other devices. Export a copy if you want a backup or want to move your data. The default currency is USD and can be changed in the app. The tracker is for personal awareness, not financial or tax advice.

## Publish on GitHub Pages

Create a GitHub repository, add the files in this folder to the repository root, then enable Pages in **Settings → Pages**. Select deployment from the main branch and root folder. Once published, share the site with people who might use it and gather feedback before adding paid features.

## A realistic earning plan

The free tracker is a way to test whether this problem is real for the people you know. It does not yet have user accounts, cloud sync, payments, or paying customers, so there is no basis to promise revenue. Start by asking 5–10 people who say budgeting is hard to use it for a couple of weeks. Ask what they logged, what they stopped using, and what would save them enough time or stress to pay for. Look for actual willingness to pay before building a paid tier.

Possible paid additions, only if users ask for them: secure account sync and backup, shared household budgets, recurring bills, or multiple budgets. A hosted paid version would need a backend, authentication, privacy and security work, and a payment provider. Keep the open-source core useful on its own.

## License

MIT. See [LICENSE](LICENSE).
