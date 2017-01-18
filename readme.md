# jQuery Simple SkillBar

SimpleSkillbar is a jQuery plugin for displaying animated skill bar set.

This plugin can be run only from the html tag or by using a simple one line js code.


## Options

Using Javascript:

* **width**: set width or percentage value of the bar (in pixel). *Default: 80px*.
* **height**: set height value of the bar (in pixel). *Default: 30px*.
* **textColor**: set label color of the bar. *Default: "#ffffff"*.
* **background**: set background color of the bar. *Default: "#337ab7"*.

Using HTML 'data' Attributes:

* **data-width**: set width or percentage value of the bar (in pixel). *Default 80px*.
* **data-height**: set height value of the bar (in pixel). *Default: 30px*.
* **data-text-color**: set label color of the bar. *Default: "#ffffff"*.
* **data-background**: set background color of the bar. *Default: "#337ab7"*.


## How To Use

First, create the simple HTML:

```html
<div id="skill1">PHP</div>
<div id="skill2">HTML</div>
```
Then call the function:

```javascript
$('#skill1').simpleSkillbar();
```

You can also use multiple ids for the function:

```javascript
$('#skill1, #skill2').simpleSkillbar();
```

And you're done.

## Using The Options

To use the options, there are 2 ways.

Either by adding options to the function:

```javascript
$('#skill1').simpleSkillbar({ width: 95 });
```

Or to the HTML itself with 'data' atributes:

```html
<div id="skill1" data-width="95">PHP</div>
```

Now, let's use more options in there:

```javascript
$('#skill1').simpleSkillbar({ width: 95, background: "#ff3333" });
```

or with the 'data' attibutes:

```html
<div id="skill1" data-width="95" data-background="#ff3333">PHP</div>
```