# TutorialsNinja Automation Project

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/artyomchernenko/TutorialsNinjaAutomation/ci.yml?branch=main)
![GitHub last commit](https://img.shields.io/github/last-commit/artyomchernenko/TutorialsNinjaAutomation)
![GitHub repo size](https://img.shields.io/github/repo-size/artyomchernenko/TutorialsNinjaAutomation)

## 📌 Project Description
This project automates the testing of the TutorialsNinja website using Selenium and Python. It covers various test scenarios, including user interactions, form submissions, and UI element validations.

## 🚀 Technologies Used
- **Python 3.11**
- **Selenium WebDriver**
- **PyTest**
- **Allure Reports**
- **GitHub Actions (CI/CD)**

## 🛠 Features & Implementations
- **Element interactions** (clicks, form inputs, and assertions)
- **List handling** (verifying product lists, dropdowns, etc.)
- **Mouse actions** (hovering, dragging, and right-clicks)
- **Page Object Model (POM)** for test organization
- **Parameterized testing** using `pytest.mark.parametrize`
- **Test reports with Allure**
- **CI/CD integration with GitHub Actions**

## 📥 Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/artyomchernenko/TutorialsNinjaAutomation.git
   ```
2. Navigate to the project directory:
   ```sh
   cd TutorialsNinjaAutomation
   ```
3. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
4. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## ▶️ Running Tests
To execute tests, run:
```sh
pytest --alluredir=allure-results
```
To generate an Allure report:
```sh
allure serve allure-results
```

## 📸 Screenshots
Here are some preview images from the automation execution:
![Test Execution](https://via.placeholder.com/800x400?text=Test+Execution+Screenshot)
![Allure Report](https://via.placeholder.com/800x400?text=Allure+Report+Screenshot)

## 🤝 Contributing
Contributions are welcome! If you'd like to improve this project, follow these steps:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Added new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Submit a pull request

## 📜 License
This project is licensed under the MIT License.

## 🎓 Credits & Acknowledgements
This project was developed as part of the training at **Automation College - Gal Matalon**.

---
🔗 **GitHub Repository:** [TutorialsNinjaAutomation](https://github.com/artyomchernenko/TutorialsNinjaAutomation)
