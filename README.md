# web

## GitHub Copilot — "Reached the Limit" Error in VS Code

If VS Code still shows a **"You've reached the limit"** message for GitHub Copilot after upgrading your subscription, the extension is likely using a cached version of your account status. Follow the steps below to force VS Code to pick up your updated plan.

### Steps to resolve

1. **Sign out of GitHub in VS Code**
   - Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
   - Run **"GitHub Copilot: Sign Out"**

2. **Sign back in**
   - Open the Command Palette and run **"GitHub Copilot: Sign In"**
   - Complete the browser authentication flow for the account that has the updated subscription

3. **Reload the VS Code window**
   - Open the Command Palette and run **"Developer: Reload Window"**

4. **Verify your subscription**
   - Confirm your Copilot subscription is active at <https://github.com/settings/copilot>

If the issue persists after these steps, uninstall and reinstall the **GitHub Copilot** extension, then repeat the sign-in step.