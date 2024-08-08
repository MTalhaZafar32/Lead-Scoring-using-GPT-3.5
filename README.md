# Lead Scoring using GPT-3.5

Welcome to the "Lead Scoring using GPT-3.5" project! This README provides an overview of the project and guides you through its components and usage.

## Introduction

This repository showcases a project developed during my internship at AI Data House (SMC-PVT) LTD. The project focuses on automating lead scoring by integrating Google Apps Script with the OpenAI API (GPT-3.5). It aims to enhance the efficiency of scoring leads based on various customer data inputs.

## Technologies Used

- **Google Apps Script**: Used for automating the lead scoring process and interacting with Google Sheets.
- **OpenAI GPT-3.5**: Utilized to generate performance scores based on customer data.
- **Google Sheets**: Used for data storage and displaying lead scores.

## Project Overview

The project involves:
- **Custom Menu**: Adding a custom menu in Google Sheets to trigger the lead scoring function.
- **Data Integration**: Fetching customer data from Google Sheets and sending it to the OpenAI API.
- **Score Calculation**: Receiving the performance score from GPT-3.5 and updating the Google Sheet with the results.

## Repository Structure

The repository includes the following files:
1. **leads.csv**: Contains the customer data used for lead scoring.
2. **Lead Scoring using GPT 3.5.xlsx**: The Excel workbook that integrates with Google Apps Script to manage and calculate lead scores.

## Getting Started

To get started with this project, follow these steps:
1. **Clone the repository**: git clone 
   ```bash
   https://github.com/MTalhaZafar32/Lead-Scoring-using-GPT-3.5.git
   ```
2. **Open the Excel workbook**:
   - Open `Lead Scoring using GPT 3.5.xlsx` in Excel.
   - Follow the instructions within the workbook to integrate with Google Apps Script.
3. **Set up Google Apps Script**:
   - Open the Google Sheet linked to this project.
   - Go to **Extensions > Apps Script**.
   - Copy and paste the relevant Google Apps Script code from this repository into the Apps Script editor.
   - Save and authorize the necessary permissions for Google Apps Script to access your Google Sheets and the OpenAI API.

## Usage

- **Load Data**: Import `leads.csv` into your Google Sheet.
- **Run the Script**: Use the custom menu in the Google Sheet to trigger the lead scoring process.
- **View Results**: The script will calculate scores using GPT-3.5 and update the Google Sheet with the results.

## Contributions

Contributions to improve the project are welcome! If you have suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the `MIT License` See the LICENSE file for details.
