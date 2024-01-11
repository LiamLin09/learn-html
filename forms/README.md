## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
answer: it specifies the URL to which the form's data is sent when the form is submitted.

2. What is the purpose of the _method_ attribute in the _form_ tag?
answer: it determines how the browser sends the form data to the server. "GET" appends the form data to the URL in pairs.

3. What is the purpose of the _name_ attribute in the _input_ tag?
answer: it identifies the form element when sending the data upon form submission.

4. What is the purpose of the _type_ attrbute in the _input_ tag?
answer: it specifies the type of input element to display.

5. What is the purpose of the _label_ tag?
answer: it is used to define a label for an 'input' element.
Labels are important for accessibility as they provide a description of the input field, which screen readers can use to aid users with visual impairments.

6. What is the purpose of the _required_ attribute?
answer: it specifies that an input field must be filled out before submitting the form.
it is used for form validation, ensuring that essential fields are not left empty by the user. 
When a form is submitted with a blank required field, the browser displays an error message and prevents the form from being submitted until the field is completed.
