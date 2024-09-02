# Vision Language Model for Dietary Analysis

## Overview

**Vision Language Model for Dietary Analysis** is an advanced application that utilizes Google's Gemini Pro Vision API to analyze images of food and provide detailed dietary information. The app integrates a Vision Language Model (VLM) to identify food items in an image, compute their calorie content, and present a thorough nutritional breakdown.

## Features

- **Image-Based Food Analysis**: Upload a meal image, and the app will identify each food item.
- **Calorie Calculation**: Calculate total calorie intake based on identified food items.
- **Detailed Nutritional Information**: Receive a detailed breakdown of calories per food item.
- **Streamlit Interface**: Easy-to-use web interface built with Streamlit.

## Technology Stack

- **Google Gemini Pro Vision API**: For food recognition and analysis.
- **Streamlit**: Framework for building the web interface.
- **Python**: Core programming language.
- **Pillow (PIL)**: For image handling.
- **dotenv**: For managing environment variables.

## Installation

### Prerequisites

- Python 3.7+
- Google Cloud API Key with access to Gemini Pro Vision API

### Setup

1. **Clone this repository:**
   ```bash
   git clone https://github.com/yourusername/vision-language-model-dietary-analysis.git
   cd vision-language-model-dietary-analysis

2. **Create and activate a virtual environment:**
  ```bash
  Copy code
  python3 -m venv venv
  source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. **Install the required packages:**
  ```bash
  pip install -r requirements.txt

4. **Set up your environment variables:**

  Create a .env file in the root directory.
  Add your Google API key:
  env
  Copy code
  GOOGLE_API_KEY=your_google_api_key_here

## Usage
Run the Streamlit app:

bash
Copy code
streamlit run app.py
Upload an image of a meal.

Enter any specific input prompt if needed.

Click "Tell me the total calories" to get a detailed analysis of the food items and their calorie content.

Example Output
When you upload an image and submit it, the app will return:

markdown
Copy code
1. Apple - 95 calories
2. Sandwich - 250 calories
3. Salad - 150 calories
----
Total: 495 calories
Contributing
Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments
Thanks to Google Cloud for providing the Gemini Pro Vision API.
Special thanks to the developers of Streamlit for their easy-to-use framework.
Contact
For any inquiries or issues, please contact yourname.

css
Copy code

This version is formatted to ensure clarity and completeness, suitable for inclusion in a GitHub repository. Adjust any placeholders or specifics to fit your project.
