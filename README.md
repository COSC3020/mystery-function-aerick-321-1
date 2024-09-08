# Mystery Function

What does the `mystery()` function in the following piece of code do? Add your
answer to this markdown file.

```javascript
function mystery(a) {
    if(a.length == 1) return a[0];
    var foo = mystery(a.slice(1, a.length))
    if(foo > a[0]) return foo;
    else return a[0];
}
```
The function uses an array. If the array only has 1 item then it returns it. The is recursively calls itself the slice the array at the second item. If foo is larger that the first item in the array then it returns it, returns the larget item. The whole function is recursive and finds tha largest number in the array by comparing them.


“I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.”
I worked through the function and then used ChatGPT to double check if I was right.
