# Chinese Media Icons

![Alt text](https://s3-ap-southeast-1.amazonaws.com/viimgs/china-media-fonts.png)

## Icon Font Cloud

<link href="https://file.myfontastic.com/iLoXdJm75bmJM4orFL4oMA/icons.css" rel="stylesheet">

### HOW TO INSERT ICONS INTO YOUR WEBSITE?

First, link your HTML page to the icon fonts and CSS files.

Then, add the CSS class, from the Icons Reference above, to any HTML tag.

## SVG Sprite Icon Cloud

### HOW TO INSERT ICONS INTO YOUR WEBSITE?

Let's assume that you already clicked the "Publish" button and copied the script tag into your HTML page header. There are two more steps left to see your icons on it.

1 - Go to "Icons Reference" and choose an icon that you want to have on your HTML page. Then click and copy its markup to your HTML page. For instance, the markup for a twitter icon could look like this:

```
<svg class="icon-twitter"><use xlink:href="#icon-twitter"></use></svg>
```

2 - Add the code below to the CSS file that you use for your html page:

```
[class^="icon-"], [class*=" icon-"] {
    height: 32px;
    width: 32px;
    display: inline-block; 
    fill: currentColor; 
}
```

You can use `height` and `width` properties to control icon size. To define icon color use `fill` property. Note: `currentColor` keyword inherits the color value of a parent element.

* Adobe Illustrator icon set Author `zcool.com.cn` *
