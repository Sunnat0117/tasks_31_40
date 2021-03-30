**31. Use Bracket Notation to Find the Nth Character in a StringPassed**

You can also use bracket notation to get the character at other positions within a string.

Remember that computers start counting at `0`, so the first character is actually the zeroth character.

**Example:**

```jsvar firstName = "Ada";
var secondLetterOfFirstName = firstName[1];

```
`secondLetterOfFirstName` would have a value of the string `d`.
**********************************************
- [x] **Task_31** Let's try to set `thirdLetterOfLastName` to equal the third letter of the `lastName` variable using bracket notation.


**Hint:** Try looking at the example above if you get stuck.

**32. Use Bracket Notation to Find the Last Character in a StringPassed**

In order to get the last letter of a string, you can subtract one from the string's length.

For example, if `var firstName = "Charles"`, you can get the value of the last letter of the string by using `firstName[firstName.length - 1]`.

**Example:**

```js
var firstName = "Charles";
var lastLetter = firstName[firstName.length - 1];

```

`lastLetter` would have a value of the string `s`.

*******************************************

- [x] **Tasks_32** Use _bracket notation_ to find the last character in the lastName variable.

**Hint:** Try looking at the example above if you get stuck.

**33. Use Bracket Notation to Find the Nth-to-Last Character in a StringPassed**

You can use the same principle we just used to retrieve the last character in a string to retrieve the Nth-to-last character.

For example, you can get the value of the third-to-last letter of the `var firstName = "Charles"` string by using `firstName[firstName.length - 3]`

**Example:**
```js
var firstName = "Charles";
var thirdToLastLetter = firstName[firstName.length - 3];
```

`thirdToLastLetter` would have a value of the string `l`.
**************************************
- [x] **Task_33** Use bracket notation to find the second-to-last character in the `lastName` string.
**Hint:** Try looking at the example above if you get stuck.

**34.  Word BlanksPassed**

We will now use our knowledge of strings to build a "Mad Libs" style word game we're calling "Word Blanks". You will create an (optionally humorous) "Fill in the Blanks" style sentence.

In a "Mad Libs" game, you are provided sentences with some missing words, like nouns, verbs, adjectives and adverbs. You then fill in the missing pieces with words of your choice in a way that the completed sentence makes sense.

Consider this sentence - It was really ____, and we ____ ourselves ____. This sentence has three missing pieces- an adjective, a verb and an adverb, and we can add words of our choice to complete it. We can then assign the completed sentence to a variable as follows:

```js
var sentence = "It was really " + "hot" + ", and we " + "laughed" + " ourselves " + "silly" + ".";
```

******************************************

 In this challenge, we provide you with a noun, a verb, an adjective and an adverb. You need to form a complete sentence using words of your choice, along with the words we provide.


You will need to use the string concatenation operator + to build a new string, using the provided variables: `myNoun`, `myAdjective`, `myVerb`, and `myAdverb`. You will then assign the formed string to the wordBlanks variable. You should not change the words assigned to the variables.


- [x] **Task_34** You will also need to account for spaces in your string, so that the final sentence has spaces between all the words. The result should be a complete sentence


**35. Store Multiple Values in one Variable using JavaScript ArraysPassed**

With JavaScript `array` variables, we can store several pieces of data in one place.

You start an array declaration with an opening square bracket, end it with a closing square bracket, and put a comma between each entry, like this:

```js
var sandwich = ["peanut butter", "jelly", "bread"]
```
********************************
- [x] **Task_35** Modify the new array `myArray` so that it contains both a `string` and a `number` (in that order).

**36 Nest one Array within Another ArrayPassed**

You can also nest arrays within other arrays, like below:
```js
[["Bulls", 23], ["White Sox", 45]]
```
This is also called a _multi-dimensional array._

- [x] **Task_36** Create a nested array called myArray.

**37. Access Array Data with IndexesPassed**

We can access the data inside arrays using indexes.

Array indexes are written in the same bracket notation that strings use, except that instead of specifying a character, they are specifying an entry in the array. Like strings, arrays use zero-based indexing, so the first element in an array has an index of `0`.


**Example**
```js
var array = [50,60,70];
array[0];
var data = array[1];
```
`array[0]` is now `50`, and `data` has the value `60`.


**Note:** There shouldn't be any spaces between the array name and the square brackets, like `array [0]`. Although JavaScript is able to process this correctly, this may confuse other programmers reading your code.
*******************************
- [x] **Task_37** Create a variable called myData and set it to equal the first value of myArray using bracket notation.


**38. Modify Array Data With IndexesPassed**

Unlike strings, the entries of arrays are mutable and can be changed freely.

**Example**
```js
var ourArray = [50,40,30];
ourArray[0] = 15;
```
`ourArray` now has the value `[15, 40, 30]`.

**Note:** There shouldn't be any spaces between the array name and the square brackets, like `array [0]`. Although JavaScript is able to process this correctly, this may confuse other programmers reading your code.
***************************************
- [x] **Task_38** Modify the data stored at index 0 of myArray to a value of 45.


**39. Access Multi-Dimensional Arrays With IndexesPassed**

One way to think of a *multi-dimensional array*, is as an *array of arrays*. When you use brackets to access your array, the first set of brackets refers to the entries in the outer-most (the first level) array, and each additional pair of brackets refers to the next level of entries inside.

**Example**
```js
var arr = [
  [1,2,3],
  [4,5,6],
  [7,8,9],
  [[10,11,12], 13, 14]
];
arr[3];
arr[3][0];
arr[3][0][1];
```

`arr[3]` is `[[10, 11, 12]`, `[13, 14]`, `arr[3][0]` is `[10, 11, 12]`, and `arr[3][0][1]` is `11`.


**Note:** There shouldn't be any spaces between the array name and the square brackets, like `array [0][0] `and even this `array [0] [0]` is not allowed. Although JavaScript is able to process this correctly, this may confuse other programmers reading your code.
*****************************************

- [x] **Task_39** Using bracket notation select an element from myArray such that myData is equal to 8.


**40. Manipulate Arrays With push()Passed**

An easy way to append data to the end of an array is via the `push()` function.

`.push()` takes one or more parameters and "pushes" them onto the end of the array.

**Examples:**
```js
var arr1 = [1,2,3];
arr1.push(4);

var arr2 = ["Stimpson", "J", "cat"];
arr2.push(["happy", "joy"]);
```
`arr1` now has the value `[1, 2, 3, 4]` and `arr2` has the value `["Stimpson", "J", "cat", ["happy", "joy"]]`.
***********************************


- [x] **Task_40** Push ["dog", 3] onto the end of the myArray variable.