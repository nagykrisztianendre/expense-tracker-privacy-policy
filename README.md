# Household Expense Tracker Public Compliance Pages

This repository hosts the public compliance pages for **Household Expense Tracker** by **Nagy Tech Studio**. These static pages are intended for Google Play Console and user transparency:

- Privacy Policy
- Terms of Use
- Account Deletion

The public pages clarify that deleting an app account does not automatically cancel
subscriptions purchased through Google Play or the Apple App Store. Subscription
cancellation remains platform-managed and must be handled through the store where
the subscription was purchased.

The site is intentionally lightweight and uses plain HTML and CSS only. No backend is required.

## File Structure

```text
.
|-- index.html
|-- privacy-policy.html
|-- terms-of-use.html
|-- delete-account.html
|-- styles.css
`-- README.md
```

## Customize Before Publishing

Replace these values in all files before publishing:

- `GITHUB_PAGES_BASE_URL`: only needed when documenting or sharing final hosted URLs

The app name is already set to **Household Expense Tracker**, the developer name is already set to **Nagy Tech Studio**, and the contact email is already set to **nagykrisztian.endre@gmail.com**.

## Enable GitHub Pages

1. Create a new GitHub repository for these public pages.
2. Commit and push these files to the repository.
3. In GitHub, open the repository settings.
4. Go to **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the `/root` folder.
7. Save the settings.
8. Wait for GitHub Pages to publish the site.

## Google Play Console URLs

After GitHub Pages is enabled, use the final published URLs in Google Play Console.

Example URLs:

```text
https://<username>.github.io/<repo-name>/privacy-policy.html
https://<username>.github.io/<repo-name>/terms-of-use.html
https://<username>.github.io/<repo-name>/delete-account.html
```

Use the privacy policy URL for the app's Privacy Policy field:

```text
https://<username>.github.io/<repo-name>/privacy-policy.html
```

Use the account deletion URL for the app's account deletion URL field:

```text
https://<username>.github.io/<repo-name>/delete-account.html
```

Use `delete-account.html` as the account deletion page in Google Play Console. It
explains what account data is deleted or retained and states that deleting the app
account does not automatically cancel store-managed subscriptions.

Use the Terms of Use URL anywhere the app, store listing, support flow, or other public materials need a terms link:

```text
https://<username>.github.io/<repo-name>/terms-of-use.html
```

## Updating the Text Later

Edit the relevant HTML file, commit the change, and push it to the GitHub Pages branch. GitHub Pages will automatically republish the updated version.

When policy details change, update `privacy-policy.html`, `terms-of-use.html`, and `delete-account.html` if the change affects account deletion, retained data, anonymization, contact information, shared household data handling, or Firebase data handling.

Also update the subscription wording across the public pages if subscription
handling changes. Do not state that account deletion cancels subscriptions unless
that behavior is implemented and verified through the relevant app store platform.
