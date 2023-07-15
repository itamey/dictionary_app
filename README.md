# Dictionary App README

## Description

The Dictionary App is a web application that allows users to search for word definitions, synonyms, and antonyms. It's built using HTML, CSS, JavaScript, Bootstrap, AJAX with jQuery, and Python Flask. This app utilizes the Merriam-Webster API to fetch word data and provide users with accurate and up-to-date information.

## Features

- Word Definitions: Users can enter a word in the search bar and get its definition instantly.
- Synonyms and Antonyms: Along with the definition, the app provides synonyms and antonyms for the searched word.
- Autocomplete: The app offers suggestions as users type in the search bar to improve the search experience.
- Pronunciation: The app includes audio pronunciation for the searched word.
- Responsive Design: The app is designed to work seamlessly on various devices, including desktops, tablets, and mobile phones.

## Technologies Used

- HTML: For creating the structure and content of the web pages.
- CSS: For styling the user interface and improving the visual appeal.
- JavaScript: For implementing the client-side functionalities, such as autocomplete and API calls.
- Bootstrap: For responsive design and layout components.
- AJAX with jQuery: To make asynchronous API calls without refreshing the entire page.
- Python Flask: To handle backend logic and serve the web application.
- Merriam-Webster API: For fetching word data, definitions, synonyms, and antonyms.

## Setup Instructions

Follow these steps to set up the Dictionary App locally:

1. Clone the repository:

```bash
git clone https://github.com/your-username/dictionary-app.git
cd dictionary-app
```

2. Set up the Python environment and install dependencies:

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
```

3. Obtain an API key:

Visit the [Merriam-Webster API website](https://dictionaryapi.com/register/index) and sign up to get an API key. You may need to choose a plan based on your usage requirements.

4. Configure the API key:

Copy the API key you obtained in the previous step and paste it in the `config.py` file:

```python
# config.py
API_KEY = 'YOUR_API_KEY_HERE'
```

5. Run the Flask application:

```bash
python app.py
```

6. Open your web browser and visit `http://localhost:5000` to access the Dictionary App.

## Contributing

Contributions to the Dictionary App are welcome! If you find any bugs or have suggestions for improvements, please create an issue or submit a pull request.

## License

The Dictionary App is open-source software licensed under the [MIT License](LICENSE).

---

Happy searching and learning with the Dictionary App! If you have any questions or need further assistance, please don't hesitate to contact us.
