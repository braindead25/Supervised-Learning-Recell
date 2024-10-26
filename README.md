# Supervised-Learning-Recell
ML based solution to develop a dynamic pricing strategy for used and refurbished devices. 
*ReCell* is a startup aiming to establish a dynamic pricing strategy for used and refurbished phones and tablets through machine learning. They have hired a data scientist to analyze device data and build a linear regression model that predicts the price of used devices and identifies key influencing factors.

### Project Overview:
- **Objective**: To develop a predictive pricing model using linear regression for used/refurbished devices, helping ReCell optimize pricing strategies in a growing market.
- **Target Variable**: `normalized_used_price` (the normalized price of the used/refurbished device in euros).
- **Data Collection Year**: 2021.

### Data Details:
- **Device Attributes**:
  - **brand_name**: Manufacturing brand.
  - **os**: Operating system.
  - **screen_size**: Screen size in centimeters.
  - **4g** / **5g**: Availability of 4G and 5G.
  - **main_camera_mp** / **selfie_camera_mp**: Rear and front camera resolutions (in megapixels).
  - **int_memory** / **ram**: Internal memory (ROM) and RAM in GB.
  - **battery**: Battery capacity in mAh.
  - **weight**: Device weight in grams.
  - **release_year**: Year of the device's release.
  - **days_used**: Number of days the device has been in use.
  - **normalized_new_price**: Normalized price of a new device of the same model.

The linear regression model will analyze these features to predict the used price of devices, identifying factors (e.g., brand, screen size, memory, battery, and usage duration) that most significantly impact pricing. This insight will guide ReCell’s pricing strategies to remain competitive in the refurbished device market.
