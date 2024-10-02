# Mini Project 

## Project Overview

This project focuses on analyzing human images to generate personalized fashion, makeup, and hairstyle suggestions. The system processes input data, including body and face features, and outputs the most suitable outfit, makeup, and hairstyle recommendations.

## Project Aim

The system has two primary objectives:

1. **Outfit & Makeup Suggestions:**
   - Analyze the provided image and user inputs (body type, skin type) to suggest:
     - Best-suited outfit types
     - Recommended color schemes for outfits
     - Makeup item suggestions

2. **Hairstyle Suggestions:**
   - Detect face shape from the image and analyze additional inputs (eye color, face color, and lip color) to suggest:
     - Best-suited hair colors
     - Suitable hairstyles
     - Ideal hair lengths

## Inputs

### For Outfit & Makeup Suggestions:
- A picture of a human subject
- Body type (provided by the user)
- Skin type (provided by the user)

### For Hair & Face Suggestions:
- A face image
- Eye color
- Face color
- Lip color

## Outputs

### For Outfit & Makeup Suggestions:
- Recommend outfit type
- Suggest suitable outfit colors
- Suggest makeup items based on skin tone and facial features

### For Hair & Face Suggestions:
- Suggest  hair color
- Suitable hairstyle
- Suggest hair length

## How It Works

1. **Image Input:** The user uploads an image of themselves.
2. **Feature Extraction:** The system processes the image to analyze body and face attributes.
3. **User Input:** The user provides additional information like body type, skin type, eye color, face color, and lip color.
4. **Recommendation Generation:** Based on the image analysis and input features, the system generates personalized suggestions for outfits, makeup, and hairstyles.

## Technology Stack

- **Programming Language:** Python
- **Image Processing Libraries:** OpenCV, Pillow, dlib
- **Machine Learning Frameworks:** TensorFlow, scikit-learn (for face and feature recognition)
- **Data Handling:** Pandas, NumPy

## Future Scope

- Integration with e-commerce platforms for real-time outfit and makeup purchases.
- Advanced face recognition algorithms for better accuracy.
- Augmented reality (AR) feature to visualize makeup and hairstyle changes in real time.


