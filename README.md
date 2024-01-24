# Email/SMS Spam Classifier

This project is a simple spam classifier for emails or SMS messages. It uses a Naive Bayes classifier trained on a dataset of labeled messages.

## Requirements

Make sure you have the required libraries installed. You can install them using:

pip install -r requirements.txt

## Usage

1. Clone the repository:

git clone https://github.com/your_username/your_project.git
cd your_project

2. Install the dependencies:

pip install -r requirements.txt

3. Run the Flask app:

python app.py

4. Open your browser and go to http://localhost:5000/ to access the application.

## Project Structure

- app.py: The main Flask application file.
- templates/: Contains HTML templates for the web interface.
- static/: Static files such as CSS stylesheets or images.

## Model Files

- vectorizer.pkl: Pickle file containing the TF-IDF vectorizer.
- model.pkl: Pickle file containing the trained Naive Bayes classifier.

## License

This project is licensed under the MIT License - see the LICENSE.txt file for details.
