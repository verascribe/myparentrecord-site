---
layout: post
title: "How to Upgrade Your Data"
date: 2026-01-12
category: Guide
permalink: /upgrade-guide/
description: "A step-by-step guide to exporting and importing your workbook data."
---

## Upgrading In 3 Easy Steps

### Step 1: Export your data.

<img src="{{ '/assets/images/guides/upgrade-guide/export-data.png' | relative_url }}" alt="Export Data" class="w-full rounded-lg border border-white/10 shadow-lg">

1. Open your existing workbook.
2. In the My Parent Record sidebar menu, select "Export Data".
3. Click the "Export Now" button.
4. Choose a location to save your workbook data to your computer.
5. Click "Save".

### Step 2: Make a copy of the new workbook.

<img src="{{ '/assets/images/guides/upgrade-guide/make-a-copy.png' | relative_url }}" alt="Make a Copy" class="w-full rounded-lg border border-white/10 shadow-lg">

1. Open the link to the new workbook.
2. In the Google Sheets menu, select "File" > "Make a Copy".
3. Choose a location to save your workbook to your Google Drive.
4. Click "Save".

### Step 3: Import your data.

<img src="{{ '/assets/images/guides/upgrade-guide/import-data.png' | relative_url }}" alt="Import Data" class="w-full rounded-lg border border-white/10 shadow-lg">

1. Go to your copy of the new workbook.
2. In the My Parent Record sidebar menu, select "Import Data".
3. Click the "Validate Import" button and select the file you exported in Step 1.
4. If the import is valid, click "Import File".
5. The import will begin. This may take a few minutes.

### Note: Pre-v2.1.0 Data

<img src="{{ '/assets/images/guides/upgrade-guide/import-warning-pre-210-data.png' | relative_url }}" alt="Import Data" class="w-full rounded-lg border border-white/10 shadow-lg">

If you are migrating from a version prior to v2.1.0, you will see a warning message indicating that some data columns are missing. **This is to be expected** and does not indicate an error.

1. **Payment_Method** column was added in 2.1.0 to support the addition of Personal Expenses tracking.
2. **Schedule_End_Date** column was added in 2.1.0 to support the addition of flexible scheduling.
