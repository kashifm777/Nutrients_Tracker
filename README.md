# Nutrients Tracker with Google Gemini Pro Vision

This repository offers a Streamlit application called "Nutrients Tracker" that leverages Google's Gemini Pro Vision API to estimate the total calories in an uploaded food image.  


![Pakistani Tikka Platter](food_images/food_6.jpg)

### Run on Streamlit  
You can try this app on Streamlit:  
[Nutrients Tracker](https://nutrients-tracker.streamlit.app)

## 1. Key Features:

- **Image Upload:** Upload a picture of your food for analysis.
- **Text Prompt:** Optionally, provide a descriptive text prompt to assist the model's understanding.
- **Calorie Estimation:** The application utilizes the model's capabilities to estimate the total number of calories in the food image.
- **Food Item Breakdown (Optional):** When using the provided prompt, the model may attempt to identify individual food items in the image and provide a breakdown of their estimated calorie content.

## 2. How it Works:

- **Upload an Image:** Select a clear image of the food you want to analyze.
- **Enter Text Prompt (Optional):** Provide a brief description of the food in the image. This can enhance the model's accuracy for complex dishes.
- **Click "Tell me the total calories":** Initiate the analysis process.
- **View Results:** The application will display the estimated total calorie count based on the processed image and text prompt (if provided).

## 4. Requirements:

- Python 3.x
- Streamlit (`pip install streamlit`)
- Pillow (`pip install Pillow`)
- A Google Cloud Project with a Generative AI Vision API enabled (and a valid API Key)

## 5. Getting Started:

- Clone or download this repository.
- Install the required libraries (`pip install -r requirements.txt`).
- Create a file named `.env` in the project's root directory and add the line `GOOGLE_API_KEY=<YOUR_API_KEY>` (replace `<YOUR_API_KEY>` with your actual Google Cloud Generative AI Vision API Key).
- Run the application using `streamlit run main.py`.

## 6. Note:

- A valid Google Cloud Project with a Generative AI Vision API enabled and a corresponding API Key are necessary for the application to function.
- The accuracy of calorie estimation may vary depending on the complexity of the image and the food items within it.
- The food item breakdown feature is optional and may not always be available in the response.

## 7. Further Enhancements:

- Implement error handling for invalid inputs or API errors.
- Integrate a dietary tracker where users can log their meals and track calorie intake.
- Explore advanced visualization techniques to highlight potential food items in the uploaded image.

## 8. Disclaimer:

This application is designed for informational purposes only and should not be used as a substitute for professional dietary advice. Always consult with a registered dietitian or healthcare professional for personalized guidance on your nutritional needs.
