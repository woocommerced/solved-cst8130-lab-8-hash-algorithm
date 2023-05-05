Download Link: https://assignmentchef.com/product/solved-cst8130-lab-8-hash-algorithm
<br>
In this lab, we will write a program to handle inserts to a dynamically allocated array or ArrayList using a hash algorithm and a collision resolution algorithm.   You can just write the code inside a method main to do the following;

<ol>

 <li>Declare a dynamically allocated array or <strong>ArrayList </strong>object called <strong>dataItems</strong> of 100 <strong>String</strong></li>

</ol>

Think about both of these options – what code needs to be in the constructor???




<ol>

 <li>Write a menu loop which allows these options

  <ul>

   <li>Add a String to the array dataItems –

    <ul>

     <li>Prompt user to enter a String</li>

     <li>use a hash algorithm to calculate the index of where to store the string in the dataItems array</li>

     <li>the algorithm should be the first letter of the string to be added (converted to an int) added to the second letter of the input string if there is one (converted to an int) – modulus 100 (so that you make sure the result is a number between 0 and 99.</li>

     <li>if there is already a String in this index position – move to the next sequential element position in the array until you find an empty location (but not past 99! – in this case display error message – String cannot be added)</li>

    </ul></li>

   <li>search for a String in the array <strong>dataItems </strong>as efficiently as possible– and display the index of where it is found or a message if it is not found</li>

   <li>quit</li>

  </ul></li>

</ol>











