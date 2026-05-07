# HTML Tables:
-> HTML tables represent data in the form of tables.  
-> Table is the combination of rows and columns.  
-> The table consists of rows and columns.  
-> To provide a table in a webpage we have to use a <table> tag. 
-> Each row of the table is represented by using <tr> tag.  
-> Each column is represented by using the <td> tag. 
-> Table contains a heading which can be represented by using <th> tag. 
-> Table title can be provided by using <caption> tag.

# Structure of Table - rows , columns: 
-> The smallest unit of a table is called as “cell".
-> OR The intersection of row and column is called a Cell.

# Table Contents ⇒ thead, tbody, tfoot, caption, tr, td, th:
-> <thead> ⇒  It is used to provide table heading. 
-> <tbody> ⇒  It is used to define blocks for table body. 
-> <tfoot> ⇒  It is used to define the block for the footer for the table. 
-> <caption> ⇒ It is used to provide the caption or title or description for the table. 
-> <tr> ⇒  With the help <tr> we can provide the row to the table. 
-> <td> ⇒  It is used to provide the column or cell to the table. 
-> <th> ⇒  With the help of <th>, we can provide heading for the table data and by default heading will be in bold and align as center to cell.

#Example:
<table border="1"> 
      <caption> 
        Student Data 
      </caption> 
      <thead> 
        <tr> 
          <th>Sr.No.</th> 
          <th>Name</th> 
          <th>Age</th> 
        </tr> 
      </thead> 
      <tbody> 
        <tr> 
          <td>1</td> 
          <td>Ramesh</td> 
          <td>24</td> 
        </tr> 
        <tr> 
          <td>2</td> 
          <td>Suresh</td> 
          <td>26</td> 
        </tr> 
      </tbody> 
      <tfoot> 
        <tr> 
          <th>Total Students = 3</th> 
        </tr> 
      </tfoot> 
</table> 

# Styling of Table  Border, bgcolor, etc: 
-> border ⇒ It is used to provide the border to the table. 
-> bgcolor ⇒ This attribute is used to provide the background color to the table, row, or each cell. 
-> But the above two attributes are depreciated now. That means they are no longer in use. Instead of this we prefer CSS styling to the table.

# Cellspacing, Cellpadding:
-> With the help of cellpadding and cellspacing we can provide padding inside the cells and also space between the cells. 

1. cellpadding: This attribute is used to increase the surrounding area of a content which is present inside the cell.

2. cellspacing: This attribute which is used to increase the space between two cells.

# In Short:
-> Space between the cell wall and content is cell padding.  
-> Space between two cells is cell space.

#  colspan, rowspan:
1. colspan ⇒ This is an attribute which is used to merge two or more than two columns is called as colspan. 

2. rowspan ⇒  This is an attribute which is used to merge two or more than two rows (cells) is called as rowspan. 

# Example:
<table border="1"> 
        <thead> 
           <tr> 
             <th>Sr.No.</th> 
             <th>Name</th> 
             <th>Age</th> 
           </tr> 
        </thead> 
        <tbody> 
           <tr> 
             <td>1</td> 
             <td>Ramesh</td>
             <td>24</td> 
          </tr> 
          <tr> 
            <td>2</td> 
            <td>Suresh</td> 
            <td>26</td> 
          </tr> 
          <tr> 
            <td>3</td> 
            <td>Ganesh</td> 
            <td>25</td> 
          </tr> 
       </tbody> 
       <tfoot> 
          <tr> 
            <th colspan="3">Total Students = 3</th> 
          </tr> 
       </tfoot> 
</table> 
