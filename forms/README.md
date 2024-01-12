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
It is the URL where the form is submitted. The data is sent to this URL.

2. What is the purpose of the _method_ attribute in the _form_ tag?
It determines the HTTP method used in the form.

3. What is the purpose of the _name_ attribute in the _input_ tag?
It assigns a name to this input element as a identifier so that it could be found in the submitted form data.

4. What is the purpose of the _type_ attrbute in the _input_ tag?
It spefcifies the type of input field to display. For example, if type is password, the input value is hidden to protect privacy.

5. What is the purpose of the _label_ tag?
It is a label for form control. It improves accessbility for users. For example, if user clicks on label, it activates associated control, in this case is the corresponding input field.

6. What is the purpose of the _required_ attribute?
It indicates form field must be filled with value before submit the form. Otherwise, the form could not be submitted.
