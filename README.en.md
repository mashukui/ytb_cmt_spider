# ytb_cmt_spider

> **Original by 马哥:** I independently developed a crawler software using Python: YouTube Comment Spider. Purpose: Crawl comment data from specified YouTube videos.

> **Already wrapped as GUI software, designed for non-programmers!**

---

## Table of Contents

- [Introduction](#introduction)
  - [Target](#target)
  - [Demo Video](#demo-video)
  - [Software Description](#software-description)
- [Features](#features)
- [How to Use](#how-to-use)
- [Requirements](#requirements)
- [Pricing](#pricing)
- [Purchase Methods](#purchase-methods)
- [License Agreement](#license-agreement)
- [Software Distribution](#software-distribution)

---

## Introduction

### Target

Hello! I am [@马哥python说](https://github.com/mashukui), a 10-year software developer.

I independently developed a crawler software using Python that crawls comment data from specified YouTube videos, supporting batch video collection.

**Contains 10 key fields:**

```
1. cid (Comment ID)
2. text (Comment Content)
3. time (Comment Time - Relative)
4. author (Commenter Nickname)
5. channel (Commenter Channel)
6. votes (Comment Likes)
7. replies (Comment Replies)
8. time_parsed (Comment Time Converted)
9. time2 (Comment Time - Absolute)
10. video_id (Video ID)
```

The software calls YouTube's web API interface, not simulating browser operations, so it has high stability!

**Development purpose:** To facilitate use by non-programmers, no need to install Python, no need to modify code, just double-click to use!

**Software Interface:**

![Software Screenshot](https://files.mdnice.com/user/32110/621e7907-cca6-4399-bdad-8c8dfbfa3a5d.png)

**Target Video Template:**

![Target Video](https://files.mdnice.com/user/32110/3c662da2-bbd4-4f0e-a34b-4aba1580dbf5.png)

**Example:**
- In the target video file, you fill in 5 videos to crawl
- On the software interface, select the top 30 popular comments for each video
- The CSV result file will automatically export 150 popular comments

**Crawling Result Screenshot:**

![Crawling Result](https://files.mdnice.com/user/32110/96f28217-2a65-415e-a7ab-117d9a99609f.png)

---

### Demo Video

Complete demonstration video of software usage: [【爬虫演示】爬油管评论软件v3.0版](https://mp.weixin.qq.com/s/6tvQyS4QxohuELKUZJnbIA)

---

### Software Description

**Key Points:**

1. Designed for non-programmers, works on both Windows and Mac systems directly, no Python environment configuration needed
2. Software crawls via API, not via browser simulation or RPA tools, high stability!
3. After software completes, a CSV result file is generated in the current folder (where the software is located)
4. During crawling, results are saved after each page is crawled, not all at once after completion, to prevent data loss from unexpected interruptions (1-2s interval between page requests)
5. During crawling, a log file records the running process in detail for easy troubleshooting
6. Crawling results contain 10 fields: cid, text, time, author, channel, votes, replies, time_parsed, time2, video_id

---

## Features

✅ **GUI Interface** - No programming required, double-click to use
✅ **Batch Processing** - Crawl multiple videos at once
✅ **High Stability** - Uses API instead of browser simulation
✅ **Real-time Saving** - Data saved after each page to prevent loss
✅ **Detailed Logging** - Complete log file for troubleshooting
✅ **10 Key Fields** - Comprehensive comment data extraction

---

## How to Use

### Step 1: Prepare Target Video File

Create an Excel file (named `目标视频.xlsx`) and fill in YouTube video URLs in the first column.

**Example:**

| Video URL |
|-----------|
| https://www.youtube.com/watch?v=abc123 |
| https://www.youtube.com/watch?v=def456 |
| https://www.youtube.com/watch?v=ghi789 |

### Step 2: Open Software

Double-click the software executable to launch it.

### Step 3: Configure Settings

- **Video Source:** Select or import the target video file
- **Comment Count:** Enter the number of comments to crawl per video (e.g., 30)
  - Use `-1` to crawl all comments
- **Output Format:** CSV file

### Step 4: Start Crawling

Click the **"Start"** button to begin crawling.

### Step 5: View Results

After completion, a CSV file with the same name as the video ID will be generated in the software's folder.

**Result Example:**

| cid | text | time | author | channel | votes | replies | time_parsed | time2 | video_id |
|-----|------|------|--------|---------|-------|---------|-------------|-------|----------|
| 123456 | Great video! | 2 hours ago | John Doe | Tech Channel | 150 | 20 | 2026-03-19 09:00:00 | 2026-03-19 11:00:00 | abc123 |

---

## Requirements

- **Operating System:** Windows 7/10/11 or macOS 10.14+
- **Python:** Not required (software is standalone)
- **Memory:** 512MB+
- **Storage:** 100MB+ free space

---

## Pricing

### License Types

| Type | Duration | Price | Notes |
|------|----------|-------|-------|
| **Daily Pass** | 1 day | ¥39 | One-time purchase, for trial use |
| **Monthly Pass** | 1 month | ¥149 | Multiple purchases allowed, for short-term needs |
| **Quarterly Pass** | 3 months | ¥399 | Multiple purchases allowed, for medium-term needs |
| **Yearly Pass** | 1 year | ¥799 | Multiple purchases allowed, for long-term needs |

---

## Purchase Methods

### Method 1: Self-Service Activation (Recommended)

Activation Portal: https://mgnb.pro/product/youtube_cmt

### Method 2: Self-Service Activation

Activation Portal: https://kjyjf.xetlk.com/s/2Qne5a

### Method 3: Manual Activation

After payment, add WeChat (493882434) to connect:

![Payment QR Code](https://github.com/user-attachments/assets/0f3c32ad-099a-416b-8677-103fe230a5a9)

---

## License Agreement

### One Device One Code

The software uses a **one-device-one-code** mechanism. A license key can only run on one computer and cannot be used on multiple computers.

### Software Multi-Instance

Only one instance of the software is allowed to run on a single computer. Multi-instance is not supported.

### Software Maintenance

The software is independently and originally developed by the author, with long-term maintenance and updates provided for stable operation.

---

## Software Distribution

**Get the latest version from:**

WeChat Official Account: **老男孩的平凡之路**

Reply to: **"爬油管评论"** (Crawl YouTube Comments)

![WeChat QR Code](https://github.com/user-attachments/assets/bf8a3a19-eb1f-49a0-b919-d0d5d67fe20d)

---

## Support

If you encounter any issues:

1. Check the log file in the `logs/` folder for detailed error messages
2. Ensure your internet connection is stable
3. Verify YouTube video URLs are correct
4. Contact support via WeChat (493882434) for further assistance

---

## Credits

**Developer:** [@马哥python说](https://github.com/mashukui)

**Original Work:** YouTube Comment Spider v3.0

---

**© 2026 马哥python说. All Rights Reserved.**
