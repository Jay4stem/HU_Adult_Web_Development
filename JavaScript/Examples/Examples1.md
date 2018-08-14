# HU_Adult-JavaScript-Examples1

### Working with Variables

      1. let hello = 'Hello world!';
      2. let message;
      3. message = hello; // copy 'Hello world' from hello into message
      4. // now two variables hold the same data
      5. alert(hello); // Hello world!
      6. alert(message); // Hello world!

### Show the Sign/Check the Login

*The if statement may contain an optional “else” block. It executes when the condition is wrong.*

      1. let year = prompt('What Year is it?', '');
      2. if (year === 2018) {
      3.    alert( 'You guessed it right!' );
      4. } 
      5. else {
      6.    alert( 'How can you be so wrong?' ); // any value except 2018
      7. }

### Nesting For Loops
      
      1. for (let i = 0; i < 10; i++) {
      2.  if (i % 2) {
      3.    alert( i );
      4.  }
      5. }

### Array Operations
      1. let fruits = ["Apple", "Orange", "Pear"];
      2. alert( fruits.pop() ); // remove "Pear" and alert it
      3. alert( fruits ); // Apple, Orange
      4. fruits.push("Pear");
      5. alert( fruits ); // Apple, Orange, Pear
      6. alert( fruits.shift() ); // remove Apple and alert it
      7. alert( fruits ); // Orange, Pear
      8. fruits.push("Orange", "Peach");
      9. fruits.unshift("Pineapple", "Lemon");
      10. alert( fruits ); // ["Pineapple", "Lemon", "Orange", "Peach"]
