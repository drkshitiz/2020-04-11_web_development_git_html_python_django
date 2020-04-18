# Web Development using Python and Javascript
## git commands

```git clone url```

```git add fileName```

```git commit -m "message"```

```git status```

```git push```

Command to save git credentials in the ubuntu terminal ```git config --global credential.helper cache``` source: <https://help.github.com/en/github/using-git/caching-your-github-password-in-git>

```git pull```

* To merge conflicts after a pull request, open the file in text editor and keep what you need and remove everything else.

```git log```


Get references to git changes by ```git reflog``` 

```git reset --hard <commitID>```

```git reset --hard origin/master```

### How to amend a commit message
```git commit --amend -m "new commit message"```

### command for adding and commiting a new message at the same time
git commit -am "message"

### Git command to list branches in the current repository
```git branch```

### Git to branch current branch
```git branch name-of-new-branch```

### list branches in current repository and identify the  current working branch
```git branch```
Note - '*' indicates the branch on which we are currently working.

### How to switch for working in another branch?
```git checkout name-of-the-another-branch```

### Concept of git remotes
### How to merge my local master branch with the remote origin/master branches
```git pull```

### Forks
fork is completely separate different version of a repository.



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
### New tags in HTML5
```<header>, <nav>, <section>, <footer>, <audio>, <video>, <datalist>```

### Datalist is  nice, new feature in HTML5

### Different input types in HTML
```<input name="name" type="text" placeholder="First Name">```
- Other input types are -- text, number, password, radio

### How to style html elements by using types
```
<style>
  input[type=text] {
    background-color: red;
  }
  input[type=number] {
    background-color: yellow;
  }
</style>
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

### formatting immediate children by CSS using > sign
```
<style>
  ol > li {
    color: red;
  }
  </style>
  ```

### formatting all descendants by CSS using 'space' operator
  ```
  <style>
    ol li {
      color: red;
    }
    </style>
  ```

### how to use pseudoclasses in css to make html elements change state, such as changing colour by hover
```
button:hover {
  background-color: orange;
}
```
### How to use psedoelements to add content before certain html tags
```
<style>
  a::before{
    content: "\21d2 Click here: ";
    font-weight: bolder
  }
</style>
```
## how to install Sass in ubuntu terminal 
```
sudo apt-get install ruby-full build-essential rubygems
sudo gem install sass
```
## github-pages for deploying html pages
- Go to github repository.
- create new repository your-username.github.io, which will serve as your url.

## Sources:
* Bootstrap <https://getbootstrap.com/docs/4.3/getting-started/introduction/>
* HTML5 tables https://htmlreference.io/tables/
* sass installation https://sass-lang.com/install
