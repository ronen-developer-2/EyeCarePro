# Privacy Policy for EyeCare Pro

**Effective Date:** March 7, 2026

Your privacy is important to us. This Privacy Policy explains how **EyeCare Pro** ("we", "us", or "the extension") handles your data when you install and use the extension.

## 1. Information We Collect
**We do not collect, store, or transmit any of your personal data to our servers.**

All extension settings, preferences (such as your reminder intervals, sound preferences, and smart pausing blacklists), and usage data (such as how many breaks you've taken today) are saved locally on your device or synced via your standard Google Chrome account using the `chrome.storage.sync` API. We do not have access to this data.

## 2. Permissions We Use and Why
EyeCare Pro requires specific browser permissions to function as intended:
- **Alarms (`alarms`)**: Used to perfectly time your eye rest reminders in the background without slowing down your browser.
- **Storage (`storage`)**: Used to save your customized preferences and break history locally.
- **Windows / Notifications (`windows`, `notifications`)**: Used to spawn the visual reminder popup on your screen when it is time to take a break.
- **Active Tab (`activeTab` / `tabs`)**: Used exclusively for the Premium "Smart Pausing" feature to check if your current URL matches your custom blacklist (e.g., netflix.com) so the extension knows to delay the alarm. We do not monitor, log, or transmit your browsing history.

## 3. Third-Party Services (Premium Users Only)
If you choose to upgrade to **EyeCare Premium**, you will be asked to enter a Gumroad License Key.
When you click "Verify," the extension makes a secure, direct request to the official **Gumroad API** (`api.gumroad.com`) to validate your purchase. We do not store your payment information, email address, or any other personal details related to the transaction. The license verification is handled entirely between your browser and Gumroad.

## 4. Analytics and Tracking
EyeCare Pro contains **no tracking scripts, no analytics, and no advertising**. We do not track your clicks, your browsing habits, or how you interact with the extension. 

## 5. Changes to This Policy
We may update this Privacy Policy from time to time if new features require different permissions. Any changes will be reflected on this page, and the "Effective Date" will be updated.

## 6. Contact Us
If you have any questions or concerns about this Privacy Policy or how your data is handled, please reach out to us via the support contact provided on our Chrome Web Store page.
