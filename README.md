# Cotton Disease Prediction

This project is a Flask web application that uses a trained deep learning model to predict the condition of cotton leaves. The model can classify images into four categories: diseased cotton leaf, diseased cotton plant, fresh cotton leaf, and fresh cotton plant.

## Features

- Upload an image of a cotton leaf.
- Get predictions about the health of the cotton leaf.

## Requirements

- Python 3.6 or higher
- TensorFlow
- Flask
- NumPy
- Werkzeug

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Hassa678/cotton-desise_prediction.git
    cd cotton-desise_prediction
    ```

2. **Create a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate    # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Place the trained model file (`model_inception.h5`) in the project root directory:**

    Ensure the model file is named `model_inception.h5` and is located in the same directory as `application.py`.

## Usage

1. **Run the application:**

    ```bash
    python application.py
    ```

2. **Access the application:**

    Open your web browser and go to `http://127.0.0.1:5001`.

3. **Upload an image:**

    - Click on the "Choose File" button to upload an image of a cotton leaf.
    - Click on the "Predict" button to get the prediction result.

## File Structure

- `application.py`: The main application file.
- `requirements.txt`: List of required Python packages.
- `notebook/`: Directory containing Jupyter notebooks used for training and experimentation.
- `static/`: Directory for static files like CSS and JavaScript.
- `templates/`: Directory for HTML templates.
- `uploads/`: Directory where uploaded images are stored.

## Model

The application uses a pre-trained Inception model fine-tuned on a custom dataset of cotton leaf images. The model file should be named `model_inception.h5` and placed in the project root directory.

## Example

Here is an example of how to use the application:

1. **Navigate to the home page:**

    ![Home Page](uploads/homepage_screenshot.png)

2. **Upload an image and get a prediction:**

    ![Prediction Result](uploads/prediction_result_screenshot.png)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the TensorFlow and Keras teams for their amazing deep learning libraries.
- Thanks to the Flask team for providing a simple and powerful web framework.

---

You can create this file in your project root directory by saving the content above into a file named `README.md`. Make sure to adjust any file paths or project-specific details as needed.

To create the `README.md` file, you can use the following command:

```bash
echo "# Cotton Disease Prediction
This project is a Flask web application that uses a trained deep learning model to predict the condition of cotton leaves. The model can classify images into four categories: diseased cotton leaf, diseased cotton plant, fresh cotton leaf, and fresh cotton plant.

## Features

- Upload an image of a cotton leaf.
- Get predictions about the health of the cotton leaf.

## Requirements

- Python 3.6 or higher
- TensorFlow
- Flask
- NumPy
- Werkzeug

## Installation

1. **Clone the repository:**

    \`\`\`bash
    git clone https://github.com/Hassa678/cotton-desise_prediction.git
    cd cotton-desise_prediction
    \`\`\`

2. **Create a virtual environment:**

    \`\`\`bash
    python -m venv venv
    source venv/bin/activate    # On Windows use \`venv\Scripts\activate\`
    \`\`\`

3. **Install the dependencies:**

    \`\`\`bash
    pip install -r requirements.txt
    \`\`\`

4. **Place the trained model file (\`model_inception.h5\`) in the project root directory:**

    Ensure the model file is named \`model_inception.h5\` and is located in the same directory as \`application.py\`.

## Usage

1. **Run the application:**

    \`\`\`bash
    python application.py
    \`\`\`

2. **Access the application:**

    Open your web browser and go to \`http://127.0.0.1:5001\`.

3. **Upload an image:**

    - Click on the \"Choose File\" button to upload an image of a cotton leaf.
    - Click on the \"Predict\" button to get the prediction result.

## File Structure

- \`application.py\`: The main application file.
- \`requirements.txt\`: List of required Python packages.
- \`notebook/\`: Directory containing Jupyter notebooks used for training and experimentation.
- \`static/\`: Directory for static files like CSS and JavaScript.
- \`templates/\`: Directory for HTML templates.
- \`uploads/\`: Directory where uploaded images are stored.

## Model

The application uses a pre-trained Inception model fine-tuned on a custom dataset of cotton leaf images. The model file should be named \`model_inception.h5\` and placed in the project root directory.

## Example

Here is an example of how to use the application:

1. **Navigate to the home page:**

    ![Home Page](uploads/homepage_screenshot.png)

2. **Upload an image and get a prediction:**

    ![Prediction Result](uploads/prediction_result_screenshot.png)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the TensorFlow and Keras teams for their amazing deep learning libraries.
- Thanks to the Flask team for providing a simple and powerful web framework." > README.md
```

This command will create a `README.md` file with the content provided above. Make sure to adjust any file paths or project-specific details as needed.
