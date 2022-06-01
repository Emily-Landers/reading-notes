# Django CRUD and Forms

- Django provides generic form editing views that can do almost all the work to define pages that can create, edit, and delete records associated with a single model instance.
- An HTML Form is a group of one or more fields/widgets on a web page, which can be used to collect information from users for submission to a server. 
- Forms are a flexible mechanism for collecting user input because there are suitable widgets for entering many different types of data
- hey allow us to send data in POST requests with cross-site request forgery protection.
- Django Forms provides a framework that lets you define forms and their fields programmatically, and then use these objects to both generate the form HTML code and handle much of the validation and user interaction.
- The main things that Django's form handling does are:
    - Display the default form the first time it is requested by the user.
    - Receive data from a submit request and bind it to the form.
    - Clean and validate the data.
    - If any data is invalid, re-display the form, this time with any user populated values and error messages for the problem fields.
    - If all data is valid, perform required actions
    - Once all actions are complete, redirect the user to another page.
- The Form class specifies the fields in the form, their layout, display widgets, labels, initial values, valid values, and (once validated) the error messages associated with invalid fields.

## Resources

- https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Forms#summary 