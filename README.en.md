# ytb_cmt_spider

> 🔥 YouTube comment collection tool / YouTube comment crawler GUI, supporting batch video comment collection, language detection, paginated comment collection, CSV/JSON export, and runtime logging.
>
> 💡 Supports Windows/macOS with no Python environment required. This repository is used for software introduction, release distribution, usage documentation, and issue feedback. The complete source code is not publicly available.
>
> [⬇️Download Latest Release](https://github.com/mashukui/ytb_cmt_spider/releases/) | [🎬Video Demo](https://www.bilibili.com/video/BV1qWUwBsEo9/) | [🏠Homepage](https://mashukui.github.io/ytb_cmt_spider/) | [💳Purchase Access](https://mgnb.pro/product/youtube_cmt)

<p align="center">
  <a href="README.md">简体中文 README</a> | <a href="README.en.md">English README</a>
</p>

## 👋 Overview

`ytb_cmt_spider` is a desktop GUI tool designed for YouTube comment data collection scenarios. It supports batch input of video links, automatically collects video comments, comment authors, comment time, likes, language detection results, and related data, then exports the results as CSV/JSON files. Users do not need to install or configure a Python environment. Download the client, log in, and start using it.

It is suitable for the following scenarios:

| Scenario | Description |
| --- | --- |
| ✅ Cross-border operations | Collect YouTube video comments to understand overseas user feedback, content preferences, and product reviews |
| ✅ Public opinion analysis | Track comments under brand, event, or topic-related videos to observe discussion trends and user attitudes |
| ✅ Content research | Analyze frequent questions, audience interests, and interaction feedback in popular video comment sections |
| ✅ Data research | Export comment text, author information, and language information for further data cleaning and analysis |

## ⚙️ Features

| Feature | Description | Output |
| --- | --- | --- |
| ✅ Batch video comment collection | Enter multiple YouTube video links and collect comments in batches | CSV, JSON |
| ✅ Paginated comment collection | Automatically collect paginated comment lists and reduce manual copying or repeated operations | CSV, JSON |
| ✅ Comment language detection | Automatically detect comment languages for filtering comments in different languages | CSV, JSON |
| ✅ Comment interaction data | Collect comment time, likes, and related interaction fields | CSV, JSON |
| ✅ Incremental saving | Continuously save results during collection to reduce data loss caused by interruptions | CSV, JSON |
| ✅ Runtime logs | Record runtime logs for troubleshooting | logs files |

## 🚀 Quick Start

1. Open [Releases](https://github.com/mashukui/ytb_cmt_spider/releases/) and download the latest version.
2. Extract the package and run the client for your operating system.
3. Log in to the software account.
4. Batch-fill YouTube video links in `目标视频.xlsx`.
5. Click "Start" and wait for the collection task to finish.
6. Check the CSV/JSON result files and log files in the software directory.

## 💻 Supported Platforms

| Platform | Support |
| --- | --- |
| Windows | Supported. Download and run the Windows client |
| macOS | Supported. Download and run the macOS client |

## 🖼️ Screenshots

### Comment Collection

The software provides a GUI interface for entering YouTube video links and starting comment collection tasks.

<img alt="YouTube comment crawler v3.3" src="https://github.com/user-attachments/assets/af3caca6-f071-4377-871e-77e3d45a63bb" />

### Data Export

After collection is complete, the software generates structured result files for further processing with Excel, Python, databases, or BI tools.

<img alt="YouTube comment collection result" src="https://github.com/user-attachments/assets/928dc2e4-da41-49b0-b205-be4f1e9e5b47" />

## 📊 Output Fields

The software generates CSV/JSON files based on the collection task. Since there are many fields, the main field groups are shown first. You can expand the section below to view the full field list.

### Comment Data

- Collection info: video link, video id, page or index
- Comment info: comment id, comment content, comment time, comment likes, comment level
- Author info: author nickname, author channel id, author channel link
- Language info: comment language, language detection result

<details>
<summary>View full comment fields</summary>

Video link, video id, comment id, comment index, author nickname, author channel id, author channel link, comment time, comment likes, comment level, comment language, comment content

</details>

### Export Files

- CSV: suitable for Excel, WPS, Numbers, Python pandas, and similar tools
- JSON: suitable for programmatic processing, database import, API integration, and retaining structured data
- Log files: record collection progress, exception information, and save paths for troubleshooting

## 🛠️ Technical Notes

The software is developed in Python. Core modules include:

| Module | Purpose |
| --- | --- |
| tkinter | GUI interface |
| requests | API requests |
| json | Response parsing |
| pandas | CSV export |
| logging | Runtime logging |

The software collects data through web interfaces and does not require manually copying comments. During collection, results are incrementally saved to reduce data loss caused by network issues, account state changes, or task interruptions.

## 💰 Pricing

| Plan | Duration | Price | Recommended Usage |
| --- | --- | --- | --- |
| Day pass | 1 day | 39 CNY | Trial use or small one-time tasks |
| Monthly pass | 1 month | 149 CNY | Short-term collection needs |
| Quarterly pass | 3 months | 399 CNY | Medium-term collection needs |
| Yearly pass | 1 year | 799 CNY | Long-term stable use |

Purchase page: [https://mgnb.pro/product/youtube_cmt](https://mgnb.pro/product/youtube_cmt)

## 🔐 License and Activation Rules

- The software uses a one-device-one-license mechanism. One license key can only be used on one computer.
- Only one software instance is allowed on a single computer. Multiple concurrent instances are not supported.
- The software is maintained by the author, and future versions will be published through [GitHub Releases](https://github.com/mashukui/ytb_cmt_spider/releases/).

## ❓ FAQ

### Do I need to install Python?

No. The software is packaged as a desktop client. Download the version for your operating system and run it directly.

### Do I need to log in to YouTube?

No. The software collects comments through web interfaces and does not require logging in to a YouTube account.

### Will collected data be lost if the task is interrupted?

The software incrementally saves results during collection. If the task is interrupted, completed data is usually still preserved in the result files.

### Where are result files saved?

By default, result files are saved in the software directory. `CSV/JSON` files and log files are generated by task.

### How many comments can it collect?

The software has handled anti-crawling issues and can continuously collect comments. The actual number of comments collected is usually consistent with the number of comments visible in the comment section.

### What should I do if an error occurs?

Check the log files under the `logs` directory first. When reporting an issue, please provide:

- Software version
- Operating system
- Video link used
- Collection parameters
- Error screenshot
- Log content around the time when the error occurred

## ⚠️ Compliance Statement

This software is intended only for lawful data analysis, learning, research, and authorized business scenarios. Users are responsible for complying with YouTube's terms of service, privacy policy, and applicable laws and regulations.

Do not use this software for:

- High-frequency, malicious, or destructive requests
- Unauthorized collection, distribution, or sale of sensitive personal information
- Activities that infringe the lawful rights of platforms, channel owners, or users
- Any other behavior that violates laws, regulations, or platform rules

Users are solely responsible for risks and liabilities caused by improper use.

## 📦 Get the Software

- GitHub Releases: [https://github.com/mashukui/ytb_cmt_spider/releases/](https://github.com/mashukui/ytb_cmt_spider/releases/)
- Reply `爬油管评论` in the WeChat official account `老男孩的平凡之路`

<img width="573" height="196" alt="二维码-公众号放底部v4" src="https://github.com/user-attachments/assets/6113cb90-3f25-4e31-831d-52d4d7516596" />
