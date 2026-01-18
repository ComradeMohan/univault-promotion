# 🔐 UniVault Promotion Website

Showcasing the features and benefits of UniVault through a dedicated promotional web presence.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-licensed)
![Stars](https://img.shields.io/github/stars/ComradeMohan/univault-promotion?style=social)
![Forks](https://img.shields.io/github/forks/ComradeMohan/univault-promotion?style=social)


## ✨ Features

*   🌍 **Custom Domain Support:** Easily host the promotional site on your preferred custom domain using `CNAME` records.
*   📄 **Comprehensive Privacy Policy:** Provides a dedicated `privacypolicy.html` to ensure transparency and user trust.
*   🗑️ **Account Deletion Page:** Includes a `deleteaccount.html` for users to understand the process of managing their UniVault account data.
*   ⚙️ **Configurable Application Settings:** Utilizes `app_config.json` for managing application-wide settings and dynamic content.
*   🖼️ **Rich Media Assets:** Organized `assets` folder for images, stylesheets, and other media to enhance the user experience, including a custom logo.

## 🚀 Installation Guide

This project is a static HTML website. You can run it locally by cloning the repository and opening the `index.html` file in your browser, or by serving it with a simple local web server.

### 📥 Cloning the Repository

First, clone the `univault-promotion` repository to your local machine:

```bash
git clone https://github.com/ComradeMohan/univault-promotion.git
cd univault-promotion
```

### 🖥️ Manual Setup (Opening in Browser)

The simplest way to view the site is to open the main HTML file directly:

1.  Navigate to the cloned directory:
    ```bash
    cd univault-promotion
    ```
2.  Open `index.html` in your preferred web browser.
    *   On most systems, you can simply double-click `index.html`.
    *   Alternatively, use your browser's "File > Open File..." option.

### 🌐 Serving with a Local Web Server (Recommended)

For a more robust local development experience, especially for testing paths and configurations, it's recommended to use a simple HTTP server. If you have Node.js installed, `http-server` is a great option.

1.  **Install `http-server` (if you don't have it):**
    ```bash
    npm install -g http-server
    ```
2.  **Start the server from the project root:**
    ```bash
    cd univault-promotion
    http-server
    ```
3.  Open your browser and navigate to `http://localhost:8080` (or the address shown in your terminal).

## 💡 Usage Examples

Once installed, the `univault-promotion` website serves as a static information hub for UniVault.

### Viewing the Main Page

To access the primary promotional content, simply open `index.html` in your browser or navigate to the root of your local server:

```
http://localhost:8080/index.html
```
or
```
http://localhost:8080/
```

### Accessing Specific Pages

You can directly navigate to other pages like the privacy policy or account deletion information:

*   **Privacy Policy:**
    ```
    http://localhost:8080/privacypolicy.html
    ```
*   **Delete Account Information:**
    ```
    http://localhost:8080/deleteaccount.html
    ```

### Configuration Options

The `app_config.json` file can be used to store global configuration settings for your website. While this is a static site, `app_config.json` can be consumed by JavaScript for dynamic content rendering or feature toggles.

| Key          | Type    | Description                                       | Example Value |
| :----------- | :------ | :------------------------------------------------ | :------------ |
| `appName`    | `string`| The name of the application being promoted.       | `"UniVault"`  |
| `version`    | `string`| Current version of the UniVault service.          | `"2.0.0"`     |
| `contactEmail`| `string`| Email address for support or inquiries.           | `"support@univault.com"` |
| `featureFlags`| `object`| Object containing boolean flags for features.     | `{ "darkMode": true }` |

```json
{
  "appName": "UniVault",
  "version": "2.0.0",
  "contactEmail": "support@univault.com",
  "featureFlags": {
    "darkMode": true,
    "newFeaturePromo": false
  }
}
```

## 🗺️ Project Roadmap

The `univault-promotion` website is continuously evolving. Here are some planned enhancements and future goals:

*   **Version 1.1.0:**
    *   Integrate a contact form for user inquiries.
    *   Add a dedicated "About Us" section for the UniVault team.
    *   Implement basic SEO optimizations for better discoverability.
*   **Future Enhancements:**
    *   Develop a dynamic content loading system using JavaScript and `app_config.json`.
    *   Introduce a blog or news section for updates.
    *   Enhance accessibility (A11y) across all pages.
    *   Expand language support for global reach.

## 🤝 Contribution Guidelines

We welcome contributions to the `univault-promotion` project! To ensure a smooth collaboration, please follow these guidelines:

### 📝 Code Style

*   **HTML:** Use semantic HTML5 elements. Ensure proper indentation (2 spaces) and well-formed tags.
*   **CSS:** Keep CSS organized and maintainable. Use descriptive class names.
*   **JavaScript:** (If applicable in future updates) Follow modern JavaScript best practices, including JSDoc for functions.

### 🌿 Branch Naming Conventions

Please use the following conventions for your branch names:

*   `feature/your-feature-name`: For new features or significant additions.
*   `bugfix/issue-description`: For bug fixes.
*   `docs/update-description`: For documentation improvements.
*   `chore/task-description`: For routine maintenance or build process changes.

### 📤 Pull Request Process

1.  **Fork** the repository and clone your fork.
2.  **Create a new branch** from `main` with an appropriate name.
3.  **Make your changes** and commit them with clear, concise commit messages.
4.  **Push your branch** to your fork.
5.  **Open a Pull Request** against the `main` branch of the original repository.
6.  Ensure your PR description clearly explains the changes, their purpose, and any related issues.
7.  Be responsive to feedback during the review process.

### ✅ Testing Requirements

Before submitting a pull request, please ensure:

*   **Browser Compatibility:** Test your changes across major web browsers (Chrome, Firefox, Edge, Safari).
*   **Responsiveness:** Verify that your changes display correctly on various screen sizes (desktop, tablet, mobile).
*   **Functionality:** If adding new interactive elements, ensure they work as expected.

## 📜 License Information

This project is currently **unlicensed**. This means that by default, all rights are reserved by the copyright holder (ComradeMohan), and you may not reproduce, distribute, or create derivative works from this project without explicit permission.

For inquiries regarding licensing or usage, please contact the main contributor.

---
© 2026 ComradeMohan
