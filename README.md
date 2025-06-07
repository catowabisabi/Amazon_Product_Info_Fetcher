# Amazon Canada Web Scraper
# Amazon 加拿大網站爬蟲工具

A Python web scraper to extract product information from Amazon Canada search results, including product names, ratings, prices, and URLs.

一個用於從 Amazon 加拿大搜索結果中提取產品信息的 Python 網路爬蟲工具，包括產品名稱、評分、價格和網址。

## Overview
## 概述

This script scrapes Amazon Canada search results for a specified product query and extracts key product information across multiple pages. The data is then saved to a CSV file for further analysis.

此腳本會爬取 Amazon 加拿大指定產品查詢的搜索結果，並從多個頁面中提取關鍵產品信息。數據隨後會保存到 CSV 文件中以便進一步分析。

## Features
## 功能特點

- Multi-page scraping (configurable page range)
- Product information extraction (name, rating, price, URL)
- CSV export functionality
- Request throttling to avoid being blocked
- Error handling for missing data fields

- 多頁面爬取（可配置頁面範圍）
- 產品信息提取（名稱、評分、價格、網址）
- CSV 導出功能
- 請求節流以避免被封鎖
- 缺失數據字段的錯誤處理

## Dependencies
## 依賴項

```python
import requests
from bs4 import BeautifulSoup as bs
import pandas as pd
from time import sleep
```

## Installation
## 安裝

```bash
pip install requests beautifulsoup4 pandas
```

