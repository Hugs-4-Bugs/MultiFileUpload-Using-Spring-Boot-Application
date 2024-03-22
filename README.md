# MultiFileUpload-Using-Spring-Boot-Application

This Spring Boot project provides an API for testing the upload of multiple files into a database. It demonstrates how to handle multipart file uploads and store the files in a database using Spring Data JPA.



## Setup

```bash


#### 1. Clone the Repository:
git clone https://github.com/Hugs-4-Bugs/MultiFileUpload-Using-Spring-Boot-Application.git

#### 2. Navigate to the Project Directory:
cd MultiFileUpload-Using-Spring-Boot-Application

#### 3. Build the Project:
mvn clean install

#### 4. Run the Application:
mvn spring-boot:run



## Usage

### Uploading Files

Send a POST request to /api/upload endpoint with the files to be uploaded as form-data. Multiple files can be uploaded simultaneously.

Example using Postman:

>  Open Postman and create a new request.
>  Set the request type to POST.
>  Set the request URL to http://localhost:8080/api/upload.
>  Select the form-data option.
>  Add one or more file fields with the key file and select the files to upload.
>  Click on "Send" to execute the request.



### Response
Upon successful upload, the API returns a JSON response with details of the uploaded files, including file name and size.


## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.




