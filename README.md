# Resume Generator

This project is a resume generator that creates a formatted resume document based on JSON data. It allows you to programmatically generate and update resumes using a JSON file as input.

## Purpose

The purpose of this project is to automate the process of creating and updating resumes. By providing the resume data in a structured JSON format, the script generates a well-formatted resume document in DOCX format.

## Installation

To use this resume generator, follow these steps:

1. Clone the repository to your local machine using the following command:

```shell
git clone https://github.com/your-username/resume-generator.git
```
2. Navigate to the project directory:
```shell
cd resume-generator
```
3. Install the required libraries by running the following command:
```shell
pip install -r requirements.txt
```
This will install the necessary libraries specified in the requirements.txt file, including docx.

## Usage
1. Prepare your resume data in a JSON file. The structure and fields required can be found in the provided example JSON file (resume.json). Replace this file with your own resume data.

2. Open the generate_resume.py script and update the filename in the line:
```python
with open('resume.json', 'r', encoding='utf-8-sig') as f:
```
Replace 'resume.json' with the path to your actual JSON file.

3. Run the script using the following command:
```shell
python generate_resume.py
```
This will generate a resume document in DOCX format based on the JSON data.

4. Find the generated resume document named resume.docx in the project directory.

## Customization
You can customize the resume format and structure by modifying the generate_resume.py script. The script uses the python-docx library to generate the DOCX document. Refer to the library's documentation for more details on how to modify the document structure, styles, and content.

## Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

Feel free to customize the README file according to your specific requirements and additional information you would like to provide to the users of your resume generator project.

