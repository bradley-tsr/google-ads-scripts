# Google Ads Scripts — Take Some Risk

A collection of Google Ads Scripts built and maintained by [Take Some Risk](https://takesomerisk.com), a digital marketing agency specializing in paid search and shopping.

These scripts are production-tested across real client accounts. Each one is designed to solve a specific, practical problem — automating the kind of ongoing maintenance work that's easy to forget and expensive when you do.

---

## Scripts

### [`brand-shopping-negative-keywords.js`](./brand-shopping-negative-keywords.js)

Automatically excludes non-brand search terms from a brand Shopping campaign to keep it clean and properly segmented.

Pulls search terms from the last 30 days, checks each one against your defined brand keywords, and adds any non-brand terms as exact match negatives to a shared negative keyword list. Handles Google's 5,000-term list cap by automatically creating overflow lists and sending email alerts when limits are approached.

**Schedule:** Weekly

---

## Usage

Each script has a configuration block at the top with variables you need to set before running. Instructions are included in the file header.

To add a script to Google Ads:
1. Go to **Tools > Bulk Actions > Scripts**
2. Click the **+** button to create a new script
3. Paste the script contents
4. Update the configuration variables
5. Click **Preview** to test, then **Save** and schedule

---

## About Take Some Risk

Take Some Risk is a Toronto-based digital marketing agency focused on paid search, shopping, and marketing measurement. We work with e-commerce and lead gen clients across Google Ads, Microsoft Ads, and Performance Max.

[takesomerisk.com](https://takesomerisk.com)
