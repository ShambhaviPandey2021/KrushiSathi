# Krushi Saathi

**Krushi Saathi** is an agricultural assistance platform designed to provide farmers with essential services such as crop disease prediction, soil quality analysis, fertility recommendations, and fertilizer suggestions. This repository contains the complete codebase for the Krushi Saathi platform, covering frontend development, Flask integration, model deployment, and instructions for local deployment.

## Frontend Development

The frontend of the Krushi Saathi platform was developed using the following technologies:

- **HTML**: Used for structuring the web pages.
- **CSS**: Styled the visual elements and provided layout design.
- **JavaScript**: Added dynamic functionality for interactive features.

The user interface (UI) is designed to be seamless and intuitive, catering to the needs of farmers and agricultural stakeholders.

## Flask Integration

Flask, a lightweight Python web framework, serves as the backend for the Krushi Saathi platform. It enables the integration of machine learning models for various functionalities. Key components of Flask integration include:

- **Model Deployment**: Trained models are serialized and deployed within the Flask application.
- **API Endpoints**: Flask routes handle incoming requests, make predictions using models, and return results.
- **Data Preprocessing**: Ensures accurate predictions by processing data within Flask.
- **Frontend Communication**: AJAX requests facilitate communication between the frontend and Flask backend.
- **Result Rendering**: Predicted results are dynamically rendered on the frontend.

## Local Deployment

You can deploy the Krushi Saathi project locally on your machine for testing and development purposes. Follow these steps to deploy and access the project locally:

1. **Run the Flask Development Server**: Use the provided `app.py` file to run the Flask application locally.
2. **Access the Local Host**: Visit `http://localhost:5000` in your web browser to access the Krushi Saathi website.
3. **Frontend Access**: HTML, CSS, and JavaScript files are served by Flask from specific directories (`templates` and `static`).
4. **Model Integration**: Machine learning models are loaded into memory when running the Flask application locally.

## Folder Structure

The repository follows a specific folder structure for better organization:

- `app.py`: Main Flask application file.
- `disease.py`, `fertility.py`, `soil.py`, `price.py`, `fertilizer.py`: Flask blueprints for various services.
- `models/`: Contains trained machine learning models, transformers, and scalers.
- `static/`: Directory for static files (CSS, JavaScript, images).
- `templates/`: Directory for HTML templates.
- `training/`: Contains Jupyter Notebooks used for model training and visualization.
- `requirements.txt`: List of Python packages required for the project.

## Usage

To get started with Krushi Saathi, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the project directory**:
   ```bash
   cd KRUSHI-SAATHI
   ```

3. **Install the required Python packages**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask application**:
   ```bash
   python app.py
   ```

5. **Access the Krushi Saathi website** in your web browser at `http://localhost:5000`.

---

This README file should give users a comprehensive understanding of the Krushi Saathi project and guide them through the setup and usage process.
