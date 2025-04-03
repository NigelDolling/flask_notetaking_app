
# Note Taking App
=====================

A simple note taking app built with HTML, CSS, JavaScript, and Flask.

## Features

* Create new notes
* Delete existing notes
* Display all notes

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6+)
* Flask (Python web framework)
* Fetch API

## Project Structure

* `app.py`: The Flask application file
* `templates/`: Directory containing HTML templates
	+ `index.html`: The main entry point of the app
	+ `base.html`: The base template for the app
* `static/`: Directory containing static files
	+ `styles.css`: The stylesheet for the app
	+ `script.js`: The JavaScript file containing the app's logic
* `delete-note.js`: The server-side script for deleting notes (not included in this repository)

## How to Use

1. Install Flask by running `pip install flask` in your terminal.
2. Run the Flask application by executing `python app.py` in your terminal.
3. Open `http://localhost:5000` in a web browser to access the app.
4. Click the "Create Note" button to create a new note.
5. Type in the note text and click the "Create Note" button again to save the note.
6. Click the "X" button next to a note to delete it.

## Flask Routes

* `/`: The main route for the app, rendering the `index.html` template.
* `/delete-note`: The route for deleting notes, handled by the `delete-note` function in `app.py`.

## Notes

* This app uses Flask to handle requests and render templates.
* The app uses the Fetch API to send requests to the server.
* The app uses JavaScript ES6+ features, such as arrow functions and template literals.

## Contributing

Pull requests and issues are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.