# Specification
In the scope of this task you'll have to implement a web application accordingly to the specification below:
The app should have only 1 page, which should contain a form with 3 inputs and a submit button. Inputs:
1) Name;
2) Phone;
3) Message.

Phone input should be masked to allow type only phone-related characters and represent a phone in human-readable form
2 other inputs should contain a non-empty value (HTML-5 validation is ok)
After clicking a submit button ajax request with requested data should be sent to the server.

The server has to validate phone number using 3rd party API, e.g https://numvalidate.com/, or any other free alternative (you can see alternatives here https://github.com/toddmotto/public-apis/#data-validation).
In case the phone is invalid client-side should display validation error and highlight phone field.
In case validation passes obtained data should be saved in the DB and client-side should display the following message:
>"Thank you, username, we will process your request soon".

Notes:
- Please use either Laravel(preferable) or Symfony for the implementation
- Pay attention to possible vulnerabilities
- Implementation should be stored on GitHub/BitBucket/GitLab
- You can use any SQL(preferable)/NoSQL DB
