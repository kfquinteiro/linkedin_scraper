# LinkedIn Competitor Post Scraper

This simple Python script allows you to gather data from any company's public LinkedIn posts. As a marketing data analyst, I faced a challenge when our third-party service for competitor analysis was discontinued. To overcome this, I developed a solution to fetch and process competitor data, which I then use to feed our marketing dashboard with actionable insights.

With this script, you can retrieve the URL of each post, as well as all publicly available engagement data (likes, comments, shares) and the post description. While it’s a straightforward tool, it’s highly useful when building marketing strategies based on competitor benchmarking.

## Technologies

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)

## Features

- Fetches public posts from a specified LinkedIn company profile.
- Retrieves post engagement data, including:
  - Number of likes, comments, and shares.
  - Post description (text content).
  - Post URL.
- Outputs data in a format suitable for feeding into dashboards or further analysis.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/linkedin-competitor-scraper.git

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the script and provide the LinkedIn company profile URL
   ```bash
   python linkedin_scraper.py

## Improvements and Known Issues

LinkedIn frequently updates its HTML structure, which may cause this script to break. If you encounter any errors or optimization suggestions, please feel free to report them or contribute fixes.
Contributions are always welcome!

## Missing Post Publish Date

One known issue is the occasional lack of post publish date in the data, since LinkedIn currently relies on relative time (e.g., "2 months ago"). 
A more accurate solution is needed to convert this into a specific publish date.

## Last but not least...

Since it's a scraper, use carefully.
