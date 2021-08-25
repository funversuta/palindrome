# palindrome
UniverProject
palindrome ('racecar');
//palindrome ('123321');
palindrome ('QQeeQQ');
//palindrome ('321321');
 function palindrome (str) {
   str = str.toLowerCase();
   return str === str.split('').reverse().join('');
 }
console.log(palindrome ('racecar'));
console.log(palindrome ('QQeeQQ'));
console.log(palindrome ('321321'));
console.log(palindrome ('321123'));
console.log();
