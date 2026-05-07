# Role of forms in webpages:
-> HTML forms are used to take user inputs.
-> With the help of forms we can collect the data from all the users at once.


# HTML Forms:
-> To provide forms in webpage we have to use <form> tag. 
-> action ⇒ It is used to provide server reference to which data has to be sent.


# Form Elements:
-> To take different inputs, form provides different elements.
-> To take inputs from the user we have to use <input>.
-> <input> tag has attributes type, name and id.
-> type attribute decides which different elements to take different inputs. 
-> name is used to provide name and id is used to provide unique name.
-> Form elements consist of:

1. <input> => Used to create various types of user input fields (text, email, password, etc.)
2. <label> => Defines a label for an input element to improve accessibility
3. <button> => Creates a clickable button for actions like submit or reset
4. <textarea> => Used to take multi-line text input from the user (address, feedback, etc)
5. <fieldset> => Groups related form elements together inside a box (border)
6. <legend> => Provides a caption/title for a <fieldset>
7. <select> => Creates a dropdown list for selecting options
8. <option> => Defines individual items inside a dropdown (<select>)
9. <optgroup> => Groups related options inside a dropdown
10. <datalist> => Provides predefined suggestions for an <input> field


# What is <select>?
-> A <select> tag is used to create a dropdown list where the user can only choose from predefined options.
-> Only select from list ❌ typing not allowed.
-> For Example:
        <label>Select your country:</label>
        <select>
          <option>India</option>
          <option>USA</option>
          <option>UK</option>
        </select>


# What is <datalist>?
-> A <datalist> tag is used to show suggestions in an input field while still allowing the user to type their own value.
-> Suggestions + typing allowed ✅
-> For Example: 
        <label>Choose your browser:</label>
        <input list="browsers">
        <datalist id="browsers">
          <option value="Chrome">Chrome</option>
          <option value="Firefox">Firefox</option>
          <option value="Edge">Edge</option>
        </datalist>


# Input Types:
1. <input type=”button”> 
2. <input type=”checkbox”> 
3. <input type=”color”> 
4. <input type=”date”> 
5. <input type=”date-time local”> 
6. <input type=”email”> 
7. <input type=”file”> 
8. <input type=”hidden”> 
9. <input type=”image”> 
10. <input type=”month”> 
11. <input type=”number”> 
12. <input type=”password”> 
13. <input type=”radio”> 
14. <input type=”range”> 
15. <input type=”reset”> 
16. <input type=”search”> 
17. <input type=”submit”> 
18. <input type=”tel”> 
19. <input type=”text”> 
20. <input type=”time”> 
21. <input type=”url”> 
22. <input type=”week”> 


# Input Attributes:
1. type => Defines the type of input (text, email, password, number, etc.)
2. id => Unique identifier for an element (used for CSS/JS and linking with label)
3. name => Name used to identify form data when submitting
4. placeholder => Shows hint text inside input before user types
5. required => Makes the field mandatory to fill before submitting
6. value => Sets the default value of an input field
7. readonly => Makes input non-editable but still submits value
8. disabled => Disables the input (cannot edit or submit value)
9. size => Sets the visible width of input (in characters)
10. autofocus => Automatically focuses the input when page loads
11. min & max => Sets minimum and maximum values for input (mainly numbers/dates)
12. minlength & maxlength => Sets minimum and maximum number of characters allowed
13. multiple => Allows selecting multiple values (for file or select inputs)
14. list => Connects input with <datalist> for suggestions
15. step => Defines interval between allowed values (e.g., 1, 2, 0.5 etc.)