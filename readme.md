# copy2clipboard.js
___   
Copy value in html elements to the clipboard by Javascript and jQuery.  
___
##### How it works:
copy2clipboard.js will listen for click event on elements with class "C2cb". It then create a temporary div off screen with the target value. Using Javascript's document.execCommand() API, the value will be copied to the clipboard and the temporary div will be removed.
___
##### Usage:
1. Add script tag for jQuery in the html head.
2. Add script tag for copy2clipboard.js in html head. (after jQuery)
3. Create an element with class "C2cb".
4. Within this element, add the desired value in "data-copy2clipboard".

Example:
```<div class="C2cb" data-copy2clipboard="Some data in div">Click this div to copy</div>```
___
##### Demo:
Visit https://jsfiddle.net/hszeto/yhngez3n/