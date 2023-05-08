# Class-03 HTML Lists, Control Flow with JS, and CSS Box Model

## HTML

+ When should you use an unordered list in your HTML document?

An unordered list is useful for lists in which the order does not matter. For example when listing types of a material used for growing plants indoors.

+ How do you change the bullet style of unordered list items?
The list-style-type will allow you to change the style of the bullets in an unordered list.

+ When should you use an ordered list vs an unorder list in your HTML document?
 When working with something like a set of instructions and order matters then an ordered list is best.

+ Describe two ways you can change the numbers on list items provided by an ordered list?

You can use CSS or the list-style-type to change the numbers.

## CSS

+ Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
Margin and padding are the protectors of the content and will put space between other elements and the elements within the box. 

+ List and describe the four parts of an HTML elements box as referred to by the box model.

+ Margin - space between the boarder and the remaining window space
+ Border - Creates the visual box
+ Padding - space between the content and the margin
+ Content - could be h1 p or images this is the content you want displayed

## Javascript

+ What data types can you store inside of an Array?

+ Similar to a variable arrays can store booleans, strings, numbers, or be empty, or not yet defined

+ Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
 Yes, it is an array of arrays. You could use something like console log(people[0][1]); And I think it would return 32.

+ List five shorthand operators for assignment in javascript and describe what they do.

+ += Addition assignment will add the value to the old value and assign the new sum to the variable
+ *= Multiplication assignment will assign the product of the two values and assign it to the variable
+ /= Division assignment will assign the quotient of the two values to the variable
+ -= Subtraction will assign the difference between the two values to the variable
+ %= Remainder assignment will assign the remainder of the quotient of the two values to the variable.

+ Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

 If we let d = (a + c) + b; and we return d we would get 10dog

+ Describe a real world example of when a conditional statement should be used in a JavaScript program.

If the user clicks a button then we need the appropriate page to load.

+ Give an example of when a Loop is useful in JavaScript.

We can use loops for validating data like passwords.

## Things I want to know more about

I am still curious about APIS and other things this was a good refresher on Arrays and I am still not sure if I got it right.
