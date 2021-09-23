# Toggler

![Toggler](https://github.com/Chandra-sekhar-pilla/Toggler/blob/main/resouces/toggler%20(small).png "Toggler")

A package(atleast the code) to toggle properties of tags.

> I mostly use toggle classes while making a switch theme method, button interaction etc.

# New feature:

**Toggle images too:**

- Now toggle images with an ease.
- No more InteractionCount().

**Syntax:**

```js 
const toggler = new Toggler;
toggler.toggleImage('elementID', 'fromImage', 'toImage');
```

- Create a new object using `const toggler = new Toggler`.


**Toggle slides:**
- You can now toggle slides(an element).

**Syntax:**

```js 
const toggler = new Toggler;
toggler.toggleSlide('elementID', 'direction', speed);
```

**Direction**:

- Direction says about in what direction the slide to start either horizontal slide or vertical slide.
(visit docs for more info link is below.)

**Speed:**

- Speed defines the speed of the toggling that mean how fast it to slide.

**Example:**

```js
const toggler = new Toggler;
toggler.toggleSlide('testElement', 'horizontal', 60);//toggles the slide horizontally i.e from left to right ot right to left
```

- vertical slide is still in dev.

# Optimizations:
- Now Toggler is a class.
- Removed `InteractionCount()` which sometimes doesn't work properly.

# How to download:

**Downloading:**

- Click on the code dropdown and click 'Download zip' to download.

**Cloning using cmd(only for contribution purpose)**

- To clone the repo click on the code dropdown and there you can copy the link.
- Then open cmd in your pc and type

```
$ git clone url
```
- Replace 'url' with the copied link and click enter.
- Repository will be cloned and you can use Toggler.js in your code.
- If you want to contribute changes can be pushed(check the code before pushing to origin or push to 'other' branch).

**Or else:**
- Just copy paste the code.

**Note: While using Toggler.js please make sure you have a backup because if something goes wrong and you pushed the changes then things will become tedious to handle.**

# How to use:

- You can clone the project or just download the ToggleClass.js. (Will release a npm package later)
- include this script before including your main script.

for example:
```html
<script src = "Toggler.js"></script>
<script src = "myscript.js"></script>
```
- After this you can use `toggler.toggleClass(elementId, fromClass, toClass)` method to toggle between classes `toggler.toggleImage(elementID, fromImage, toImage)` to toggle between images in your main script. 

# Syntax:
**In HTML file**:
```html
<head>
    <script src = "Toggler.js"></script>
    <script src = "myscript.js"></script>
</head>
```
- You can use these in `<body></body>` too.

**Your main JavaScript file**:
```js
 const toggler = new Toggler;
 toggler.toggleClass('elementID', 'fromClass', 'toClass');
```

**For example:**

```js
 const toggler = new Toggler;
 toggler.toggleClass('elementID', 'fromClass', 'toClass');
 toggler.toggleImage('elementID', 'fromImage', 'toImage');
 toggler.toggleSlide('elementID', 'direction', speed)
```

**elementID:**

ID of the element to which you want to change the class.

**fromClass:**

element's current class name.

**toClass:**

New class name to the given element.

**Direction**:

- Direction says about in what direction the slide to start either horizontal slide or vertical slide.
(visit docs for more info link is below.)

**Speed:**

- Speed defines the speed of the toggling that mean how fast it to slide.

- Note that speed is int literal.

**Note: Remember all the arguments are strings except speed.**

Remember to use this syntax in your main script not in ToggleClass.js

**Note: Don't try to manipulate the ToggleClass.js unless you know javascript.**

**For more info about the 'Toggler' visit [Toggler Docs.](https://the-atelier.ml/Pages/Toggler/toggler.html)
# Contribution:
- You can contribute to this repo by creating a pull request for features and issue for bug reports

# license:
- This repository is licensed under MIT.

# Contact us:
- You can join our official discord server [The Atelier](https://discord.gg/6Mcy5NpSpH)
- You can support us on [The Atelier team patreon](https://www.patreon.com/the_Atelier)