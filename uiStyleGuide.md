# UI Dev Style Guide in Markdown
See: [Markdown Guide](https://guides.github.com/features/mastering-markdown/)

This style guide template was created to be a versatile way for designers to communicate to front-end developers. Examples are given and comments for clarification are included in the md file. Make additions and changes as needed.

[comment]: <> (Describe project here)

** Description of project: **

** Platform: **

** Main users: **

** Additional comments: **
***
## COLORS
Colors and corresponding numbers come from [Material Design](https://material.io/guidelines/style/color.html#color-color-palette)

[comment]: <> (Depending on background, toggle between background-color or color)
[comment]: <> (Create new tables as needed, such as grouping vectors together)

### Interface Pallette
#COLOR       | $VARIABLE    | DESCRIPTION
------------ | -------------|-------------
<span style="background-color: #0E12BB", "color: ">#0E12BB</span> | $blue | primary-activated
<span style="color: #00D3A4", "color: ">#00D3A4</span> | $green | secondary-activated


### Greyscale Pallette
#COLOR       | $VARIABLE    | DESCRIPTION
------------ | -------------|-------------
<span style="color: #FFFFFF ", "color: ">#FFFFFF </span>      | $white       | default background
<span style="color: #F5F5F5  ", "color: ">#F5F5F5 </span>       | $grey-100      | vector outlines
<span style="color: #E0E0E0", "color: ">#E0E0E0</span>      | $grey-300      | unuseable icon
<span style="color: #95989A", "color: ">#95989A</span>      | $grey-ui        | default ui grey
<span style="background-color: #212121", "color: ">#212121</span>      | $grey-900      | better alternative to pure black
<span style="background-color: #000000", "color: ">#000000</span>      | $black       |

### Gradient Pallette
[comment]: <> (if applicable)

#COLOR1 | #COLOR2 | ANGLE | DESCRIPTION
------- | ------- | ----- | ---------- | -----
$blue | $black | 90deg | main background
***
## TYPOGRAPHY

TAG          |FONT           | $SIZE         | REM           | $COLOR        | BOLD          | ITALIC        | UPPERCASE     | DESCRIPTION   
------------ | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | -------------
H1         |Source Sans Pro  | $size-1       | 3em            |  $white        | x     |      |  x     | Main headings
H2         | Source Sans Pro  | $size-2        |  2.5rem      | $green            |        |x   |  | Sub-heading   


***

## ICONS
ICON | COLOR | FILE_NAME | DESCRIPTION | DEV_COMMENTS
----- | ----- | ----- | ----- | -----
<img src="icons/magnifier.svg" alt="Drawing" style="width: 20px;"/> | $grey-ui | magnifier.svg | in searchbar |
<img src="icons/shopping-cart.svg" alt="Drawing" style="width: 20px;"/> | $green | shopping-cart.svg | view items in shopping cart | needs a number to increment

***



## UI SCREENSHOTS
[comment]: <> (Add screenshots to this section. References should be made to styles that are already defined)

<img src="interface/assembleScreenshot.png" alt="Drawing" style="width: 300px;"/>  screenshot of assemble.io
* upper background: $white
* lower background: $black
