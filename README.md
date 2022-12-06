# Ingot
A bookmarklet to disable extensions based on LTBEEF with an interface based on the chrome extension page

### Installation
For easy setup go the the website at [https://upland-mutton-903.github.io/Beans/](https://upland-mutton-903.github.io/Beans/)

1. Show your bookmarks bar with `ctrl + shift + b`

2. Right click on the bar and choose `Add Page`

3. Set the name to `Ingot` and the URL to the code below or [here](https://raw.githubusercontent.com/Upland-Mutton-903/Beans/main/bookmarklet.js)

```js
javascript:(function () {var a = document.createElement('script');a.src = 'https://raw.githubusercontent.com/Upland-Mutton-903/Beans/main/ingot.min.js';document.body.appendChild(a);}())
```
