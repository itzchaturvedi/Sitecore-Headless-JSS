# Sitecore-Headless-JSS

| Author      | Email                | GitHub                |
|-------------|----------------------|-----------------------|
| Priyanshu Kuldeep    |  itzchaturvedi@gmail.com   | [github.com/itzchaturvedi](https://github.com/itzchaturvedi) |

# Sitecore 10.2 Headless Development

## Introduction

This repository provides guidance and resources for setting up a headless Sitecore development environment using Sitecore JavaScript Services (JSS). Follow the steps below to install Sitecore Headless Services and configure your instance.

## Installation

1. **Download Headless Services Package**: Download the Sitecore Headless Services zip package from the [Sitecore Downloads]([https://sitecore.com/downloads](https://dev.sitecore.net/Downloads/Sitecore_Headless_Rendering.aspx)) page. Refer to the [compatibility table](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1000576) for compatibility information with Sitecore XP 10.0 and later versions.

2. **Install Package**: Log in to your Sitecore instance, open the Desktop, navigate to Development Tools, and then click on Installation Wizard. Follow the wizard to install the downloaded package.

3. **Verify Installation**: Once the package is installed, verify the installation by accessing the following URL in your browser:

4. Replace `your-sitecore-instance` with your Sitecore instance URL. 

4. **API Key Configuration**: Navigate to `/sitecore/templates/System/Services/API Key` and insert the API key corresponding to your Sitecore instance. Set the CORS Origins and Allowed Controllers as required. Publish the changes.

5. **Test Configuration**: Run the following URL to ensure the setup is complete:
Replace `your-sitecore-instance` with your Sitecore instance URL.

6. **JSON Formatter**: Download and integrate the JSON formatter as required for your project.

## Setup

Follow the installation steps above to set up the headless development environment for Sitecore 10.2 using JavaScript Services (JSS).

