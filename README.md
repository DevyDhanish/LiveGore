# LiveGore Video Downloader

A simple Python script to download videos from LiveGore by parsing the video page and fetching the direct video URL. Supports single and batch downloads with progress bars.

---

## Features

- Download single LiveGore video by URL  
- Download multiple videos from a list file  
- Shows download progress with file size  
- Automatically creates output folder if missing  
- Easy command-line usage  

---

## Requirements

- Python 3.x  
- `requests`  
- `tqdm`  
- `HtmlParser` (custom parser to extract video element)

Install dependencies:

```bash
pip install requests tqdm bs4
