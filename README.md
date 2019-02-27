# Arithmetic Lab

## Assignment
It's time for your first solo assignment since joining the Flatbook team!

Here at Flatbook HQ, we're a bit overwhelmed by all of the user data we've been
collecting, and we need some help crunching the numbers.

There are three challenges we need you to solve. Code your solution in
`index.js`. We'll provide some brief instructions here, but you should really
rely on the test failure messages to guide your code.

## Instructions
1. When we started out, we assigned ID numbers sequentially to new users, so our first user ID is `1`, second is `2`, third is `3`, and so on. That was fine when we were a fledgling company, but, now that we have millions of active users, it would be easier if all of our user IDs were the same length. We'd like the IDs to start from `1000000001` (one billion and one) instead of `1`. Create a variable named `newID` that adds `1000000000` to the value in `oldID`. Don't define `oldID` — assume the system already knows what it is just by using that variable name.

2. During the sign-up process, we require new users to provide their age. However,the junior developer tasked with creating the sign-up form forgot to validate that the user had entered an integer, so we have a lot of accounts floating around with weird ages like `21.7` or `9.5`. We'd like you to help us identify which users need to be prompted to reenter their age. Create a variable named `ageIsValid` that checks whether the value in `currentAge` is a valid integer. You don't have to define `currentAge` — the system will take care of that part.

3. Finally, we need a way to randomly select a user by their ID number. As you know, we have millions of active users, but since this is your first assignment we'll limit the testing pool to twenty users with IDs between `1000000001` and `1000000020`. You're tasked with creating three variables:
- `randomNumber`, which should contain a randomly-generated number between `0` (inclusive) and `20` (exclusive).
- `randomInteger`, which should take the value in `randomNumber` and round it down to the nearest integer.
- `randomUserID`, which should convert `randomInteger` into a valid ID number — an integer between `1000000001` and `1000000020`.

![Good luck](https://user-images.githubusercontent.com/17556281/28846833-e671480c-76da-11e7-9285-17b5c592e065.gif)

## Resources
- MDN
  + [Basic math in JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Math)
  + [Arithmetic operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators)
  + [Operator precedence](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence)
  + [Assignment operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Assignment_Operators)
  + [`NaN`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/NaN)
  + [`Number`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)
  + [`Math`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math)
- [2ality — How numbers are encoded in JavaScript](http://2ality.com/2012/04/number-encoding.html)
