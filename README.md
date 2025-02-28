# Flask Autocorrect Suggestion App

This is a simple Flask web application that provides spelling suggestions for input words based on text similarity and word frequency.

## Features
- Reads words from a text file (`autocorrect book.txt`).
- Computes word probabilities based on frequency.
- Uses Jaccard similarity for suggesting similar words.
- Displays ranked suggestions based on similarity and probability.

## Requirements
Ensure you have Python installed and install the required dependencies using:
```sh
pip install flask pandas textdistance
```

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/SahilM1508/flask-autocorrect.git
   cd flask-autocorrect
   ```
2. Place your word corpus in `autocorrect book.txt`.
3. Run the Flask application:
   ```sh
   python app.py
   ```

## Usage
- Open `http://127.0.0.1:5000/` in your browser.
- Enter a word and receive spelling suggestions.

## File Structure
```
flask-autocorrect/
│-- .venv/                 # Virtual environment (optional)
│-- templates/
│   ├── index.html         # Frontend template
│-- app.py                 # Main Flask application
│-- autocorrect book.txt   # Text file containing words
│-- keyword.ipynb          # Jupyter Notebook for analysis
│-- README.md              # Project documentation
```

## Contributing
Feel free to fork this repository, make improvements, and submit a pull request!

## License
This project is licensed under the MIT License.

## Author
Your Name - [Your GitHub Profile](https://github.com/yourusername)

