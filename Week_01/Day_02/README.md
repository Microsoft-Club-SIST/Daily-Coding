# Day 2 - Detect Capital Usage

### Problem Statement

We define the usage of capitals in a word to be right when one of the
following cases holds:

- All letters in this word are capitals, like "USA".
- All letters in this word are not capitals, like "leetcode".
- Only the first letter in this word is capital, like "Google".

Given a string `word`, return `true` if the usage of capitals in it is right.

### Input Format

A single line input that has a multi-character string.

### Constraints

1 <= `word.length` <= 100,

`word` consists of lowercase and uppercase English letters.

### Output Format

Return `true` or `false` based on the usage of the capitals.

### Sample Input 0

```
USA
```

### Sample Output 0

```
true
```

### Sample Input 1

```
FlaG
```

### Sample Output 1

```
false
```

### Sample Input 2

```
Kamal Sharma
```

### Sample Output 2

```
true
```
