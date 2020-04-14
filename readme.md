# Web Development using Python and Javascript
## git commands

git clone url

git add fileName

git commit -m "message"

git status

git push

git pull

* To merge conflicts after a pull request, open the file in text editor and keep what you need and remove everything else.

git log

git reset --hard <commitID>

git reset --hard origin/master

git commit --amend -m "new commit message"

## HTML

```html
<!DOCTYPE html>
<html>
<head>
  <title>My Web Page!</title>
</head>
<body>
Hello, world!
<h1>Heading-1</h1>
<h2>Heading-2</h2>
<h3>Heading-3</h3>
<h4>Heading-4</h4>
<h5>Heading-5</h5>
<h6>Heading-6</h6>
An ordered list:
<ol>
  <li>item-1</li>
  <li>item-2</li>
  <li>item-3</li>
</ol>
An unordered list:
<ul>
  <li>item-1</li>
  <li>item-2</li>
  <li>item-3</li>
</ul>
Add image:
<img src = "dog.jpg" height = "200" width = "300">
[If we want to maintain the aspect ratio of the image, add only one attribute, either height or width.]
<img src="dog.jpg" width="50%"">
<form>
<input type="text" placeholder="Full Name" name="name">
<button>Submit!</button>
</form>
</body>
</html>
```

## CSS (Make  webpages look nicer)
```CSS
<!DOCTYPE html>
<html>
<head>
  <title>My Web Page!</title>
</head>
<body>
<h1 style = "color:#0c8e05;text-align:center;">Welcome to my webpage</h1>
<p>Hello,world!</p>
<p>This is my webpage</p>
</body>

</html>
```
* To find hexvalue of the color we need, just google "html color picker", the google search results will show a slider for finding the hexvalue or rgb value of any color.
### Properties which can be added in div tags to position different elements in a webpage
Margin:30px; padding:20px; font-size:28px; font-weight: bold;font-family:Arial, sans-serif; border: 3px solid blue;

## github-pages for deploying html pages
- Go to github repository.
- create new repository your-username.github.io, which will serve as your url.
