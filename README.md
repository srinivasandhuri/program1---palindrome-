# program1---palindrome-
writing code for the given string is palindrome or not???



var str="level";
var text="";
var next="";

for(var i=0;i<str.length;i++) {
text = str[i];
}
for(var j=str.length;j>=0;j--) {
next = str[j];
}
if(text==next) {
console.log("it is a palindrome");
}else {
console.log("it is not a palindrome");
}

output: it is a palindrome.........
