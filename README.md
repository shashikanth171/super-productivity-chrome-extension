# Super Productivity Browser Extension
Allows communication with Jira and idle time tracking for Super Productivity inside the browser.

Compatible with Chrome and Firefox.

Link to Chrome Web Store: https://chrome.google.com/webstore/detail/super-productivity/ljkbjodfmekklcoibdnhahlaalhihmlb

## Building

1. Install dependencies:
   ```bash
   npm install --legacy-peer-deps
   ```

2. Build for production:
   ```bash
   npm run build
   ```
   This creates `sp-ext.zip` for Chrome.

3. Build for Firefox:
   ```bash
   npm run build-firefox
   ```
   This creates `dist/super_productivity-0.5.4.zip` for Firefox submission.

4. For development:
   - Start dev server: `npm start`
   - Build dev version: `npm run build-dev`
   - Test in Firefox: `npm run run-firefox` (requires Firefox installed)


