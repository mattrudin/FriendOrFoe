# FriendOrFoe
Codewars 7kyu Kata

Tags: *Fundamental*

## Index

[1. Instructions](https://github.com/mattrudin/FriendOrFoe/blob/master/README.md#1-instructions/) 

[2. Lessons learned](https://github.com/mattrudin/FriendOrFoe/blob/master/README.md#2-lessons-learned)


## 1. Instructions
```
Make a program that filters a list of strings and returns a list with only your friends name in it.
If a name has exactly 4 letters in it, you can be sure that it has to be a friend of yours! 
Otherwise, you can be sure he's not...

Ex: Input = ["Ryan", "Kieran", "Jason", "Yous"], Output = ["Ryan", "Yous"]

Note: keep the original order of the names in the output.
```
## 2. Lessons learned
### Arrow Functions
The whole function should be an arrow function. Eg:
```javascript
const friend = friends => friends.filter(friend => friend.length === 4);
```