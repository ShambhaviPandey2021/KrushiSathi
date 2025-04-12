# Krushi Saathi

Krushi Saathi is an agricultural assistance platform designed to provide farmers with valuable services such as crop disease prediction, soil quality analysis, fertility recommendation, and fertilizer suggestion. This repository contains the codebase for the Krushi Saathi platform, including frontend development, Flask integration, model deployment, and local deployment instructions.

## Frontend Development

The frontend of the Krushi Saathi platform was developed using HTML, CSS, and JavaScript, along with the Flask web framework for Python. The user interface (UI) was designed to offer a seamless and intuitive experience for farmers and agricultural stakeholders. Here's an overview of the frontend development:

- **HTML**: Used for structuring the web pages.
- **CSS**: Styled the visual elements and provided layout design.
- **JavaScript**: Added dynamic functionality for interactive features.

## Flask Integration

Flask, a lightweight Python web framework, serves as the backend for the Krushi Saathi platform. It enables seamless integration of machine learning models for various functionalities. Here's how Flask is integrated into the project:

- **Model Deployment**: Trained models are serialized and deployed within the Flask application.
- **API Endpoints**: Flask routes handle incoming requests, make predictions using models, and return results.
- **Data Preprocessing**: Implemented within Flask to ensure accurate predictions.
- **Frontend Communication**: AJAX requests facilitate communication between frontend and Flask backend.
- **Result Rendering**: Predicted results are dynamically rendered on the frontend.

## Local Deployment

The Krushi Saathi project can be deployed locally on your machine for testing and development purposes. Here's how you can deploy and access the project locally:

1. **Flask Development Server**: Run the Flask application locally using the provided `app.py` file.
2. **Local Host Access**: Access the Krushi Saathi website by visiting http://localhost:5000 in your web browser.
3. **Frontend Access**: HTML, CSS, and JavaScript files are served by Flask from specific directories (templates and static).
4. **Model Integration**: Machine learning models are loaded into memory when running the Flask application locally.

## Folder Structure

The repository follows a specific folder structure:

- `app.py`: Main Flask application file.
- `disease.py`, `fertility.py`, `soil.py`, `price.py`, `fertilizer.py`,: Flask blueprints for various services.
- `models/`: Contains trained machine learning models, transformers, and scalers.
- `static/`: Directory for static files (CSS, JavaScript, images).
- `templates/`: Directory for HTML templates.
- `training/`: Contains Jupyter Notebooks used for model training and visualization.
- `requirements.txt`: List of Python packages required for the project.


![Screenshot description](https://github.com/ShambhaviPandey2021/KrushiSathi/blob/main/static/images/Screenshot%202025-04-12%20114856.png)

![Screenshot description](https://github.com/ShambhaviPandey2021/KrushiSathi/blob/main/static/images/Screenshot%202025-04-12%20114939.png)

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
