# jQuery Simple SkillBar

![jQuery](https://img.shields.io/badge/jQuery-Plugin-blue?logo=jquery)
![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)

A lightweight and easy-to-use **jQuery plugin** for displaying animated skill bars with minimal setup.

Designed for:
- 📊 Showcasing skill levels in a sleek animated bar.
- 🎨 Customizable styling options with JavaScript or HTML attributes.
- ⚡ Quick integration with just a single line of code.

## 🚀 Features

- Simple and lightweight.
- Easy customization using JavaScript or `data` attributes.
- Supports percentage and pixel-based widths.
- Smooth animation effects.

## 🔧 Installation

Include jQuery and the SimpleSkillbar script in your HTML:

```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="path/to/jquery.simpleskillbar.js"></script>
<link rel="stylesheet" href="path/to/simpleskillbar.css">
```

## 📋 Options

You can configure the skill bars using **JavaScript** or **HTML `data` attributes**.

### Using JavaScript:

| Option       | Type   | Description                                      | Default       |
|-------------|--------|--------------------------------------------------|---------------|
| `width`     | String | Set bar width (px or %).                         | `80px`        |
| `height`    | String | Set bar height (px).                             | `30px`        |
| `textColor` | String | Set the text color inside the bar.               | `#ffffff`     |
| `background`| String | Set the background color of the bar.             | `#337ab7`     |

#### Example:

```javascript
$('#skill1').simpleSkillbar({ width: '95%', background: '#ff3333' });
```

### Using HTML `data` Attributes:

| Attribute         | Description                          | Default       |
|------------------|----------------------------------|---------------|
| `data-width`    | Set bar width (px or %).          | `80px`        |
| `data-height`   | Set bar height (px).              | `30px`        |
| `data-text-color` | Set text color inside the bar. | `#ffffff`     |
| `data-background` | Set background color of the bar. | `#337ab7`     |

#### Example:

```html
<div id="skill1" data-width="95%" data-background="#ff3333">PHP</div>
```

## 🎯 How to Use

### 1. Basic Usage

Create a simple HTML structure:

```html
<div id="skill1">PHP</div>
<div id="skill2">HTML</div>
```

Then initialize the plugin:

```javascript
$('#skill1').simpleSkillbar();
```

### 2. Multiple Skill Bars

```javascript
$('#skill1, #skill2').simpleSkillbar();
```

### 3. Customizing with Options

Using JavaScript:

```javascript
$('#skill1').simpleSkillbar({ width: '95%', background: '#ff3333' });
```

Using HTML attributes:

```html
<div id="skill1" data-width="95%" data-background="#ff3333">PHP</div>
```

## 💡 Notes
- Ensure that jQuery is loaded before initializing the plugin.
- Supports pixel (`px`) and percentage (`%`) widths for flexible design.
- Animations work smoothly with modern browsers.

## 📜 License

This project is licensed under the **MIT License**.

---

Happy Coding! 🎨💻
