# Smooth Tooltip

 Smooth Tooltip is a css file for style and customize tooltip attribute.
 - Link to the [DEMO](https://netha.github.io/Smooth-tooltip/)

### Contents

- Download/Install
- Features
- How To Use

### Download/Installation

```sh
$ git clone https://github.com/Netha/Smooth-tooltip.git
```
if you want to update or change it. simply update the SCSS file and compile it with npm command.

### Features

- choose the position of the Tooltip.
- choose with or without smooth animation.

### How to use
Fisrt copy the "smooth-tooltip.css" to your dir, and import it to your html file.
```
<link rel="stylesheet" type="text/css" media="screen" href="css/smooth-tooltip.min.css" />
```

You can simply add the 'tooltip' attribute to any element you would like(div, span, p, h1, button, etc...).
Example element after applying smooth-tooltip.css effect:

```sh
<span tooltip='Hey from tooltip'>Hello, world!</span>
```

You can choose **Driction**  of the tooltip by add "flow" attribute:
example:
```
<span tooltip='text in down tooltip' flow='down'>Hello, world!</span>
```
```
flow='down'
flow='up'
flow='left'
flow='right'
```

### No animation mode:
Simply add the this attribute


```
tooltip-an^="none"
```



License
----

MIT


**Free Software, Hell Yeah!**
 