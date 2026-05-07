# What is List in HTML?
-> A list is a collection of items / data / elements.
-> There are 3 ways to create List in HTML:

# Types of List:
    1. Ordered List
    2. Unordered List
    3. Descriptive List

# 1. Ordered List:
-> A list which can follow the order is called as ordered list.
-> We can create ordered list by using <ol> tag.
-> We can create a list of items by using <li> tag.
-> By default ordered list has a type = 1 (default).
-> It is also called as Numbered List.
-> Syntax: 
            <ol>
                <li>HTML</li>
                <li>CSS</li>
                <li>JS</li>
            </ol>

-> type attribute values = 1 (default), A, a, I, i
            <ol type="1">
                <li>HTML</li>
                <li>CSS</li>
                <li>JS</li>
            </ol>
-> start => start attribute is used to start a list from any random number. It will always accept as a number.
-> reversed => reversed attribute is used to reverse a list order, but the content will remains unchange.


# 2. Unordered List:
-> A list which doesn't follow any order is called as unordered list.
-> We can create unordered list by using <ul> tag.
-> We can create a list of items by using <li> tag.
-> By default unordered list has a type = disc (default).
-> It is also called as Bulleted List.
-> Syntax: 
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JS</li>
            </ul>

-> type attribute values = disc (default), circle, sqaure, none
            <ul type="disc">
                <li>HTML</li>
                <li>CSS</li>
                <li>JS</li>
            </ul>


# 3. Descriptive List:
-> This list is rarely type used list in HTML.
-> Syntax:
            <dl>
                <dt> Description Title or Term </dt>
                <dd> Description Data or Defination </dd>
            </dl>

# 4. Nested List:
-> A list which is present inside another list is called Nested List.
-> In HTML, a nested list must be inside a list item (<li>).
-> For Example:
            <ol>
                <li>
                Frontend
                <ul>
                    <li>HTML</li>
                    <li>CSS</li>
                    <li>JS</li>
                </ul>
                </li>
            </ol>
