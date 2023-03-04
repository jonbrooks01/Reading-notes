# Class 09 Reading Notes

## HTML Forms

1) Forms are important in web development because they allow the user to enter data for processing and storage. Without the ability to enter data the website would not be interactive to the user and would not capture the correct audience to be successful.

2) When designing the form you have to think about the users that are going to interact with it on a daily basis. By making sure that it is a simple form not to big or to long will keep users engaged and the website wont lose any vistors.  

3) The five tag for creating a form will be: form, label, input, textarea and button.

- form: is the start of creating a form, it defines what a form will be.
- label: is used when the user is expected to input only a single line.
- input: is a tag that will only accept email addresses in the field.
- text-area: will accept any lines of text.
- button: allows the data to be submitted after entry

## Learn JS

1) Events are something that occurs when a user interacts with a page. even loading a webpage is called an event. When an event is triggered it will automatically run some type of code. For example when you signup on a webpage and enter in your information to create and account, after you hit submit an event is created to store your information and render an account on that webpage with all your information you just entered.

2) Two arguments that you will need when using the 'addEventListener()' will be a string so the code will be able to react when the button is being used, and you will need a function to run when that button is pressed.

3) The event object is a way to pass information to event handlers to provide additional features/information. The target withing the event object is the object that will have the event not an external item like the background of a webpage. For example when using the event object, instead of having a function change the font on a text tag the event will occur on the handler a button perhaps.

4) Event Bubbling describes what the action that is occurring and how that interaction is affecting the HTML. For example when writing a button tag inside a section or inside a dic tag, using the event bubbling method it will show the parent tag for the button. However you can write specific code to see a tree even to see what happens when there are several parent tags for the button tag. using event capture displays the opposite of event bubbling, it will show what is happening from to parent tag to the button element inside.