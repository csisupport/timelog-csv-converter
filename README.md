# ⏱ Time Log to CSV Converter

A simple web app that converts raw biometric time log data (from `.txt` files) from Sentry Local into a clean `.csv` file with formatted **12-hour time (AM/PM)** — no seconds included.

## 📋 Features

- 📤 Upload plain `.txt` time log files from Sentry Local
- 🕒 Converts time to **12-hour format** (e.g., `07:05 AM`)
- 🧹 Removes seconds from timestamps
- 📄 Outputs a clean CSV file with columns:
  - **Biometric ID**
  - **Date**
  - **Time In**
  - **Time Out**

## 🚀 How to Use

1. Open the app in your browser:
   👉 [Live App](https://csisupport.github.io/timelog-csv-converter/)  

2. Click **“Choose File”** and select your `.txt` time log.

3. Click **“Convert and Download CSV”**.

4. Done! 🎉 Open the CSV in Excel, Google Sheets, etc.

## 🧪 Input Format (Sample)
001 2024-05-01 07:05:09
001 2024-05-01 17:01:52
002 2024-05-01 08:02:21
002 2024-05-01 16:56:10

## 📦 Output Format

| Biometric ID | Date       | Time In | Time Out |
|--------------|------------|---------|----------|
| 001          | 2024-05-01 | 07:05 AM| 05:01 PM |
| 002          | 2024-05-01 | 08:02 AM| 04:56 PM |

## 🛠️ Tech Stack

- HTML5
- JavaScript
- Bootstrap 5
- GitHub Pages

## 📡 Hosting

This app is hosted for free using **GitHub Pages**.  
To deploy your own version:
1. Fork or clone this repo
2. Upload your files
3. Enable GitHub Pages under the **Settings > Pages** tab

## 🙌 Acknowledgments

Built with simplicity in mind to assist HR/Admin teams with quick time log processing.

