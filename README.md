# Sitecore-Headless-JSS

| Author      | Email                | GitHub                |
|-------------|----------------------|-----------------------|
| Priyanshu Kuldeep    |  itzchaturvedi@gmail.com   | [github.com/itzchaturvedi](https://github.com/itzchaturvedi) |


# Sitecore 10.2 Headless Development

## Installation

To begin developing with Sitecore 10.2 Headless Development, follow these steps:

1. **Download Headless Services Package**: First, download the Sitecore Headless Services zip package from the [Sitecore Downloads](https://dev.sitecore.net/Downloads/Sitecore_Headless_Rendering.aspx) page. Check the [compatibility table](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1000576) to ensure compatibility with Sitecore XP 10.0 and later versions.

2. **Install Package**: Log in to your Sitecore instance, then open the Desktop. Navigate to Development Tools, then click on Installation Wizard. Follow the instructions to install the downloaded package.

3. **Verify Installation**: After installation, verify by accessing the following URL in your browser:

http://your-sitecore-instance/sitecore/api/layout/render/jss?item=/&sc_apikey=TEST

Replace `your-sitecore-instance` with your Sitecore instance URL.

4. **API Key Configuration**: Go to `/sitecore/templates/System/Services/API Key` and insert your Sitecore instance's API key. For example, if your instance is named `sc102`, use that as the API key. Set CORS Origins and Allowed Controllers as needed. Publish the changes.

5. **Test Configuration**: Run the following URL:

http://xp102sc.dev.local/sitecore/api/layout/render/jss?item=/&sc_apikey=TEST

Replace `xp102sc.dev.local` with your Sitecore instance URL. Use the ItemID provided by your Sitecore instance at the place of TEST

6. **Download JSON Formatter**: Download the JSON formatter as required for your project.

Congratulations! You've completed the setup for Sitecore 10.2 Headless Development.

