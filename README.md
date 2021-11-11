# [File Metadata Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/file-metadata-microservice)


## User stories:
- You can submit a form that includes a file upload.
- The form file input field has the name attribute set to upfile.
- When you submit a file, you receive the file name, type, and size in bytes within the JSON response.

## Usage:
Go to the main page, and upload a file using the provided form.

## Hint:
To handle the file uploading you should use the <code>multer</code> npm package.

## Output:
The analysis itself consists of a JSON object, returned in the 'api/fileanalyse' path and detailing the:
- file's name;
- file's type;
- file's weight. In bytes.