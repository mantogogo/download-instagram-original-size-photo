# Download Instagram Original Size Photo
A JavaScript code to download original size photo on Instagram web version.


## How to
Just add this code to your bookmark, that's it.

```javascript
javascript: var s = document.createElement("a");
s.innerHTML = "Click to download";
s.href = document.getElementById("pImage_0").src;
s.id = "theLink";
s.download = true;
document.body.appendChild(s);
document.getElementById("theLink").click();
```
