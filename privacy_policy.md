# Privacy Policy for EyeCare Pro

**Last Updated:** May 19, 2026

Your privacy is our highest priority. **EyeCare Pro** is designed with a "Local-First" architecture, meaning we have built the extension to function without harvesting, storing, or transmitting your personal data. This policy explains exactly how we handle the minimal data points required for the extension to work.

## 1. Zero Data Collection & Transmission
**We do not collect, store, or transmit any of your personal data to our servers.**

All settings, preferences (such as your reminder intervals, sound preferences, and smart pausing blacklists), and productivity metrics (the count of breaks you've taken today) are stored exclusively on your device. We use the standard `chrome.storage` API, which ensures your data remains within your browser environment.

## 2. Permissions & Data Usage
EyeCare Pro requires specific browser permissions to provide its vision-health features. We follow the principle of **Least Privilege**:

- **Alarms (`alarms`)**: Used to schedule break intervals. Timing data is processed locally to trigger reminders.
- **Storage (`storage`)**: Used to save your customized preferences locally. If you are signed into Chrome, this data may sync across your own devices via Google's secure sync service; we never have access to this sync stream.
- **Tabs (`tabs`)**: Used exclusively for the **"Smart Pausing"** feature. The extension checks the hostname of the currently active tab against your local blacklist (e.g., streaming or meeting sites) to intelligently delay reminders. **We do not monitor, log, or transmit your browsing history.** The check happens in real-time and no record of the sites you visit is ever kept.
- **Notifications (`notifications`)**: Used to send system-level alerts when a break is due.
- **System Display (`system.display`)**: Used to ensure the break popup is perfectly centered on your screen, regardless of your monitor setup or resolution.
- **Windows (`windows`)**: Used to create, display, and manage the focus of the break reminder popup window, ensuring you receive your scheduled reminders effectively.

## 3. No Third-Party Tracking & Fully Free
- **Completely Free**: EyeCare Pro is 100% free with all features (custom intervals, strict mode, smart pausing, and all alert sounds) unlocked for everyone. There are no paid upgrades or commercial licenses.
- **No Analytics or Network Requests**: The extension makes **zero external network requests**. We do not use Google Analytics, cookies, tracking pixels, or third-party servers.
- **No Advertising**: We do not serve ads or sell data to third parties. Our extension is built solely to support vision health.

## 4. Compliance
EyeCare Pro is fully compliant with the **Chrome Web Store User Data Policy**, including the "Limited Use" requirements. We ensure that the data accessed is only what is necessary to provide and improve the user-facing features of the extension.

## 5. Contact
If you have questions about this policy or our privacy practices, please contact us at **ronen.developer.2@gmail.com** or through the developer support link on the Chrome Web Store.
