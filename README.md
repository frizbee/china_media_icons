# Chinese Media Icons

![Alt text](https://s3-ap-southeast-1.amazonaws.com/viimgs/china-media-fonts.png)

## Icon Font Cloud

<link href="https://file.myfontastic.com/iLoXdJm75bmJM4orFL4oMA/icons.css" rel="stylesheet">

### HOW TO INSERT ICONS INTO YOUR WEBSITE?

First, link your HTML page to the icon fonts and CSS files.

Insert the icon class name into any HTML tag to add the icon. The default CSS class prefix is 'icon-' ~> class="icon-baidu":

![Alt text](http://app.fontastic.me/static/images/download/5.png)

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

### Brand colors
```
TaoBao HEX:#ff4400 RGB(255, 68, 0)
Weibo HEX:#E51C34 RGB(229, 28, 52)
Tencent Weibo HEX:#3FA1D8 RGB(63, 161, 216)
QQ HEX:#60A5E4 RGB(96, 165, 228)
WeChat HEX:#7CB139 RGB(124, 177, 57)
Baidu HEX:#2319dc RGB(35, 25, 220)
(Tencent) Friend Circle? ???
Dou Ban HEX:#007722 RGB(0,119,34)
Ren Ren HEX:#227DC5 RGB(34,125,197)
Qzone HEX:#FFD302 RGB(255,211,2)
Kaixin HEX:#EE4C56 RGB(238,76,86)
(Xiaomi) Miliao HEX:#3DCE56 RGB(61,206,86)
```

## Credits
This set was made by me, using ready made icon set of *`zcool.com.cn`* and genereted using *`fontastic.me`* for the needs of the company. The company adapts to the tourism market and at this moment the largest number of tour flow comes from China.

*Adobe Illustrator icon set Author `zcool.com.cn`*
*Icons generated using `fontastic.me`*
