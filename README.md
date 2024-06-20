# Skin_Cancer_Detection_Keras

This project implements a deep learning pipeline to classify skin lesions as cancerous or benign. The pipeline follows these steps:

1. **Data Acquisition:**
    * The project utilizes the HAM10000 dataset, a collection of dermoscopic images of skin lesions.

2. **Data Preprocessing:**
    * Classifies images into seven categories (0-6) based on the provided metadata.
    * Transforms the data into a tabular format.
    * Resamples the dataframes to address class imbalance.
    * Uses a Lambda function to resize images and convert them into NumPy arrays with 8-bit pixel values.

3. **Model Training:**
    * Employs AutoKeras to automatically select and build a convolutional neural network (CNN) model suitable for image classification.

4. **Model Evaluation:**
    * Trains the chosen CNN model on the preprocessed data.
    * Calculates the loss and accuracy of the trained model.

**Getting Started**

1. Clone this repository:
   ```bash
   git clone https://<your_username>@github.com/<your_username>/skin-cancer-detection.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the HAM10000 dataset (not included in this repository due to size constraints).
4. Preprocess the data according to the provided instructions.
5. Train the model.
6. Evaluate the model's performance.

**Further Developments**

* Explore different deep learning architectures for potentially improved performance.
* Integrate the solution into a web application for ease of use.
* Deploy the model as an API for wider accessibility.

**Disclaimers**

* This is a  research project, and the model should not be used for real-world medical diagnosis. 
* Always consult a qualified dermatologist for any skin concerns.


**Note:**

* Replace `<your_username>` with your actual GitHub username in step 1.
