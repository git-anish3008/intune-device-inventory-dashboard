# Intune Device Inventory Dashboard

This project is a web-based dashboard that visualizes device inventory data exported from Microsoft Intune. It takes a CSV export from Intune and converts it into a clean, easy-to-understand dashboard showing OS versions and overall device distribution.

I built this to get better visibility into device inventory and to create a lightweight reporting tool that works without requiring direct Graph API access.

When working with Intune, inventory data is often exported as CSV files. While useful, the raw data isn’t easy to quickly analyze or present.

This dashboard helps by:
- Making OS version distribution easy to understand
- Providing a visual overview of the environment
- Allowing quick analysis without manually filtering CSV files

The dashboard runs entirely in the browser.

You export the device inventory from Intune as a CSV file, load it into the dashboard, and the JavaScript processes the data and renders the results. No backend or server is required.

## Features

- Upload and process Intune inventory CSV files
- Visualize OS version distribution
- Lightweight and fast
- No backend required
- Runs locally in the browser

## Technologies Used

- HTML
- CSS
- JavaScript

Future plan: Microsoft Graph API integration

## How to Use

1. Export device inventory from Microsoft Intune (Include all inventory data in the exported file)
2. Download the CSV file
3. Open the dashboard (index.html)
4. Load the CSV file when prompted
5. View the dashboard results

This project helped me better understand Intune inventory structure and how to build practical tools around real-world endpoint management workflows.
It also serves as a foundation for future integration with Microsoft Graph API and Azure-hosted dashboards.
