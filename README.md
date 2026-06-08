
# ip-extractor
Extract, clean, filter, and export IP addresses from scanner outputs, logs, and CSV files directly in your browser.
=======
# IP Extractor
[🇮🇷 فارسی (Persian)](README_FA.md)
A lightweight and fully client-side IP extraction tool built with pure HTML, CSS, and JavaScript.

This tool helps you extract IP addresses from scanner outputs, logs, and text files without uploading anything to a server.

## Features

- Extract IPv4 addresses from TXT, LOG, and CSV files
- Remove ports from IPs
- Remove duplicate IPs
- Filter only healthy entries
- Limit output size (10, 20, 50, 100, or all)
- Copy results to clipboard
- Download extracted IPs as a TXT file
- Fully client-side (no backend required)
- Drag & Drop support
- Modern terminal-inspired UI

## Supported File Types

- .txt
- .log
- .csv

## How It Works

1. Upload or drag your scanner output file.
2. Select the desired filtering options.
3. Click Extract IPs.
4. Copy or download the results.

## Available Filters

| Option | Description |
|----------|-------------|
| Remove Port | Removes port numbers from extracted IPs |
| Remove Duplicates | Removes duplicate IP addresses |
| Healthy Only | Keeps only entries containing healthy |
| Output Limit | Limits the number of returned IPs |

## Author

Created by ErPyCode

GitHub:
https://github.com/erpycode

