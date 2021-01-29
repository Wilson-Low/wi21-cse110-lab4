# Intro to JavaScript
<ol>
  <li>The line prints the value of i after the for loop ends (prices.length) because it is a function-level variable that is visible through code blocks</li>
  <li>The line prints the value of discountedPrice after the for loop ends (the raw discounted price of the last price) because it is a function-level variable that is visible through code blocks</li>
  <li>The line prints the value of finalPrice after the for loop ends (the discounted price of the last price rounded to the nearest cent) because it is a function-level variable and the modifications in the for loop stay after the for loop</li>
  <li>The function returns [50, 100, 150] because it iterates through the prices, calculates their price after the 0.5 discount, and then stores and returns the discounted price in a function-level vaiable</li>
  <li>There is an error because i is only visible inside the for loop</li>
  <li>There is an error because discountedPrice is only visible inside the for loop</li>
  <li>The line prints the value of finalPrice after the for loop ends (the discounted price of the last price rounded to the nearest cent) because it is a function-level variable and the modifications in the for loop stay after the for loop</li>
  <li>The function returns [50, 100, 150] because it iterates through the prices, calculates their price after the 0.5 discount, and then stores and returns the discounted price in a function-level vaiable</li>
  <li>There is an error because i is only visible inside the for loop</li>
  <li>There is an error because discountedPrice is only visible inside the for loop</li>
  <li>The line prints the value of finalPrice, which is 0 because its value cannot be changed from 0</li>
  <li>The function returns [] because the return variable discounted is a const empty list</li>
  <li>
    <ol>
      <li>student.name</li>
      <li>student['Grad year']</li>
      <li>student.greeting()</li>
      <li>student['Favorite Teacher']['name']</li>
      <li>student['courseLoad'][0]</li>
    </ol>
  </li>
  <li>
    <ol>
      <li>Output is '32' because it concatenates the string with the number type converted to a string</li>
      <li>Output is 1 because it type converts the string to a number in order to do the subtraction operation</li>
      <li>Output is 3 because it type converts null to 0 in order to do the addition operation</li>
      <li>Output is '3null' because it type converts null to 'null' in order to do the string concatenation operation</li>
      <li>Output is 4 because it type converts true to 1 in order to do the addition operation</li>
      <li>Output is 0 because it type converts false to 0 and null to 0 in order to do the addition operation</li>
      <li>Output is '3undefined' because it type converts undefined to 'undefined' in order to do the string concatenation operation</li>
      <li>Ouput is NaN because it type converts "3" to 3 and undefined to NaN in order to do the subtraction </li>
    </ol>
  </li>
  <li>
    <ol>
      <li>Output is true because it type converts '2' to 2 and 2 is greater than 1</li>
      <li>Output is false because '2' is lexicographically greater than '12'</li>
      <li>Output is true because '2' is type converted to 2 and 2 equals 2</li>
      <li>Output is false because '2' is not strictly equal to 2</li>
      <li>Output is false because true is type converted to 1 and 1 is not equal to 2</li>
      <li>Output is true because Boolean(2) is true and true strictly equals true</li>
    </ol>
  </li>
  <li>The '==' operator checks for equality using type conversion if it is comparing different types. The '===' operator checks for strict equality without type conversion even if it is comparing different types. </li>
  <li>The code snippet prints "How are you?" because in the if conditional, 2 does not equal true (see #15). In the following else conditional, 2 gets type converted to true and so the conditional is true. The following else conditional then does not matter.</li>
  <li>Separate file</li>
  <li>The result is [6,8,10] because for each integer in [1,2,3], it stores the return value of doSomething(), which takes in the integer and a function that multiplies its parameter by 2, into a return array. doSomething() then adds 2 to the integer and calls the function which multiplies it by 2. So for example, the first element 1 would result in (1+2) * 2 = 6 </li>
  <li>Separate file</li>
  <li>The code outputs in the console 1, then 4, then 3, then 2.</li>
</ol>
