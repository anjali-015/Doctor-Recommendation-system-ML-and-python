<h1 align="center">Doctor Recommendation System</h1>

<p align="center">
  <strong>A web application to recommend doctors based on symptoms</strong>
</p>

## Table of Contents

- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Features](#features)
- [Limitations](#limitations)
- [Conclusion](#conclusion)

## Prerequisites

Before running the Doctor Recommendation System, ensure that you have the following installed:

- Python 3.x
- Pandas
- Streamlit
- scikit-learn
- Streamlit Components

## Project Structure

The project consists of the following files:

- `doctors.csv`: A CSV file containing the doctor dataset. It includes information such as the doctor's name, specialty, location, experience, and other relevant details.
- `symptoms_specialist.csv`: A CSV file mapping symptoms to specialist doctors. It contains two columns: `symptoms` and `specialist`.

## Usage

1. Install the necessary dependencies using `pip install pandas streamlit scikit-learn streamlit_components`.

2. Place the `doctors.csv` and `symptoms_specialist.csv` files in the same directory as the Python script.

3. Run the Python script using the command `streamlit run doctor_recommendation_system.py`.

4. Access the Doctor Recommendation System in your web browser at the provided URL (typically `localhost:8501`).

5. On the web application, select the relevant symptoms from the dropdown list.

6. The system will recommend doctors based on the selected symptoms and display their profiles.

## Features

- Interactive User Interface: The application provides a user-friendly interface where users can select their symptoms.

- Dynamic Recommendations: The system filters doctors based on the selected symptoms and recommends doctors with matching specialties.

- Doctor Profiles: The recommended doctors are displayed with their profiles, including their name, specialty, location, and experience.

- CSS Styling: The application is styled using CSS to enhance the user interface and improve the overall design.

## Limitations

- Insufficient Data: If there are not enough specialist doctors available for the selected symptoms, the system displays a message indicating insufficient data for making a recommendation.

- Data Accuracy: The accuracy of recommendations relies on the correctness and completeness of the doctor and symptoms-specialist datasets.

## Conclusion

The Doctor Recommendation System simplifies the process of finding suitable doctors based on selected symptoms. By leveraging the provided datasets and utilizing an interactive web interface, users can easily identify doctors specializing in treating their specific symptoms.

Please note that this documentation provides a general overview of the Doctor Recommendation System. Additional improvements and enhancements can be made based on specific requirements and further customization.
