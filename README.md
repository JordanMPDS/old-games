# Website Downloader

This script automates the process of downloading files from a specific website using Selenium and stores them locally. It also maintains a record of downloaded files to avoid re-downloading.

## Features

- **Automated Downloads**: Uses Selenium to automate browser interaction for downloading files.
- **Progress Tracking**: Utilizes a SQLite database to track which files have already been downloaded.
- **Efficiency**: Downloads are performed with a progress bar showing the download status.

## Prerequisites

Before running this script, ensure you have the following installed:
- Python 3.6 or higher
- `selenium` package
- `requests` package
- `tqdm` package
- Edge WebDriver installed on your system

## Setup

1. **Clone this repository:**
   ```bash
   git clone https://github.com/yourusername/old-games-downloader.git
   cd old-games-downloader
   ```
   
2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Paths:**
   * Update the documents variable in the script to the path where you want to save downloaded files.
   * Update the database connection string in the con variable to point to your SQLite database file.

# Usage
Run the script using:
```bash
python old-games.py
```
The script will start downloading files, skipping any that have already been downloaded as recorded in the database.

