# Lead_generation
Lead_gen using web and python flask backend
# Simple Lead Generation Web App

This is a basic web application for lead generation using Flask, HTML, CSS, and JavaScript. It allows users to submit lead information through a web form, which is then saved to a CSV file.

## Prerequisites

- Python 3.7+
- Flask

## Installation

1. Clone this repository or download the source code.
2. Navigate to the project directory: `cd path/to/project`
3. Install the required dependencies: `pip install flask`

## Project Structure
lead_generation_app/
│
├── app.py
├── templates/
│   └── index.html
└── leads.csv (will be created when leads are submitted)


## Running the Application

1. Ensure you're in the project directory.
2. Run the Flask application: `python app.py`
3. Open a web browser and navigate to `http://127.0.0.1:5000/`

## Usage

1. Fill out the lead information form on the web page.
2. Click the "Submit" button.
3. The lead information will be saved to `leads.csv` in the project directory.

## Customization

- To modify the form fields, edit the HTML in `templates/index.html`.
- To change the CSV structure or add additional processing, modify the `/submit` route in `app.py`.

## Notes

- This is a basic demo application and is not suitable for production use without further development and security measures.
- Ensure you have the necessary permissions to write to the project directory for CSV file creation.

## Troubleshooting

If you encounter a `TemplateNotFound` error:
1. Ensure the `templates` folder exists in the same directory as `app.py`.
2. Check that `index.html` is correctly placed inside the `templates` folder.
3. Verify there are no typos in file names or paths.

For any other issues, please check the Flask documentation or create an issue in this project's repository.

## Contributing

Contributions to improve the application are welcome. Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.
