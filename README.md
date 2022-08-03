# Problem Statement

A palindrome is a word, phrase, number, or other sequence of characters which reads the same backwards and forwards. Can you determine if a given string,  *text*, is a palindrome?
To solve this challenge, we must first take each character in *text*, enqueue it in a queue, and also push that same character onto a stack. Once that is done, we must dequeue the first character from the queue and pop the top character off the stack, then compare the two characters to see if they are the same; as long as the characters match, we continue dequeueing, popping, and comparing each character until our containers are empty (a non-match means *text* is not a palindrome).</br></br>
**Write the following declarations and implementations:**</br>
1. Two instance variables: one for your stack, and one for your queue.
2. push_character(character) method that pushes a character onto a stack.
3. enqueue_character(character) method that enqueues a character in the queue instance variable.
4. pop_character() method that pops and returns the character at the top of the stack instance variable.
5. dequeue_character() method that dequeues and returns the first character in the queue instance variable.
# Input Format
`You do not need to read anything from stdin. The stub code in your editor reads a single line containing string,` **`text`**.`It then calls the methods specified above to pass each character to your instance variables.`

# Constraints
`The`**`text`**`is composed of lowercase English letters.`
# Output Format
`You are not responsible for printing any output to stdout. 
If your code is correctly written and text is a palindrome, the stub code will print` **`The word, text, is a palindrome.`**`;otherwise, it will print` **`The word, text, is not a palindrome.`**

# Sample Input
```
rotator
```
# Sample Output
```
The word, rotator, is a palindrome.
```
