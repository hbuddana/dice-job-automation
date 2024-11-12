
# Dice Job Application Automation 🚀

![Dice Logo](./src/img/dice_logo.png)

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Selenium](https://img.shields.io/badge/Selenium-Automation-green.svg?logo=selenium&logoColor=white)](https://www.selenium.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An automated script that helps streamline the job application process on Dice.com using Selenium WebDriver. The script handles login, job searching, filtering, and automated application submission.

## ✨ Features

- ✅ Automated login to Dice.com
- 🔍 Custom keyword job search
- 🎯 Automatic filtering for:
  - 📅 Today's job postings
  - ⚙️ Third-party listings
- ⚡ Automated "Easy Apply" process
- 🔄 Smart handling of already applied jobs
- 💡 Shadow DOM interaction for modern web elements
- 📊 Detailed logging of the application process

## 📂 Project Structure

```
dice-job-automation/
├── README.md
├── requirements.txt
├── config.py
├── main.py
└── src/
    ├── __init__.py
    ├── automation.py
    ├── handlers/
    │   ├── __init__.py
    │   ├── job_handler.py
    │   ├── shadow_dom_handler.py
    │   └── search_filter_handler.py
    └── utils/
        ├── __init__.py
        └── webdriver_setup.py
```

## 📋 Requirements

- Python 3.x
- Chrome Browser
- ChromeDriver matching your Chrome version
- Required Python packages (see requirements.txt)

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hbuddana/dice-job-automation.git
   cd dice-job-automation
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a config.py file with your credentials:
   ```python
   CREDENTIALS = {
       "username": "your_email@example.com",
       "password": "your_password"
   }

   SEARCH_SETTINGS = {
       "keyword": "your search keyword",  # e.g., "Data Engineer"
       "max_applications": 10
   }
   ```

## 🚀 Usage

1. Update `config.py` with your Dice.com credentials and search preferences.
2. Run the script:
   ```bash
   python main.py
   ```

## 🔧 Configuration Options

In `config.py`, you can customize:
- Login credentials
- Search keywords
- Maximum number of applications
- Other search parameters

## ⚠️ Important Notes

- Keep your `config.py` file private and never commit it to Git
- Review Dice.com's terms of service regarding automation
- The script includes delays to mimic human behavior
- Verify all applications manually in your Dice account

## 🤝 Contributing

1. Fork the repository
2. Create a new branch for your feature
3. Commit your changes
4. Push to your branch
5. Create a Pull Request

## Special Thanks 

[![Contributors](https://img.shields.io/github/contributors/hbuddana/dice-job-automation)](https://github.com/hbuddana/dice-job-automation/graphs/contributors)

<a href="https://github.com/hbuddana">
  <img src="https://avatars.githubusercontent.com/hbuddana?s=50" width="50" height="50" style="border-radius: 50%;" alt="hbuddana"/>
</a>
<a href="https://github.com/Deeraj7">
  <img src="https://avatars.githubusercontent.com/Deeraj7?s=50" width="50" height="50" style="border-radius: 50%;" alt="Deeraj7"/>
</a>





## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This tool is for educational purposes only. Use responsibly and in accordance with Dice.com's terms of service.
