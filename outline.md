# HTML/CSS I

## HTML Framework

- `<!DOCTYPE html>` is how the web browser knows how to interpret the page. We are using the html 5 standard here. this won't be shown on the web page and 'meta data'

- `<html></html>` is used to wrap the content of our web page. everything we want to be on the site needs to be between these tags.

- `<head></head>` is going to be full of more 'meta data' and is the information about the page. useful to google and the browser to know what the page is about and how to display it.

- `<meta>` a weird tag because it doesn't need a closing tag or a self closing tag. its how we tell the internet about our web page.

  - `<meta charset="UTF-8">` this tells the browser to use the newest version of text encoding that the world uses. This gets very computer sciencey, but basically, you need this.

  - `<meta name="description" content="yup">` this gives search engines a basic intro to what the site is about

  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">` this makes sure your web site is appropriately scaled to the device you are viewing it on, whether it be on desktop or mobile.

  - `<title>🐶 Hot Dog 🐶</title>` this sets the text on the tab in the browser

  - `<link rel="stylesheet" href="./main.css">` this brings in the styles from other css files or fonts

- `<body></body>` this is for the content of your webpage and typically what goes in here will be displayed on the web page.

## Body

- make a div/section that fills in the whole page using vw and vh, but without a reset.

- show the students the weird that happens and the padding that comes with it. Then fix it by showing them what a reset.css file is and what it fixes do. also show the importance of order when we bring in css files.

- show them the image from the lecture folder and that is what we will be building. talk about the structure of HTML and the idea of nesting things.

- build header, make height 100px and show inspect tool to show height. add padding then show how it changes the size of the box. use padding to center nav items. talk about how padding is a short hand property. Talk about box model here.

- when we add the second item it stacks underneath it but we want it to go on either side. use floats on both left and right.

- fill in the body with a main and give it a bg tag. show them how there is no content in the lower section so lets make main take up the available space using calc.

- make the center box and use margin auto to center it. use padding on the main to center it with calc. calc((100vh - 100) / 4)

- make the 3 rows and give them different widths. use margin to move each guy around.

- use classes to specify each one but also use nested selector to select the divs in general. in the bottom one make two divs that float to each side of the container;

## Mini Project

- working with background images, set the background image to the desk image. set the background posistion to center; its not 'centered' or is it? give the body a height of 100vh and width 100%;

- this should look super weird if you have not used a reset.css file. include one now and give it box-sizing: border-box; then give bg image no-repeat and cover;

- make the header and add the dm image. its huge and needs to be resized. wrap it in a figure and style the figure. set the image style to width 100% height auto;

- make the nav for the right and style it to float right, and figure to float left. inside the nav make an `<ul>` full of '<li>` to show them about lists. give them a bit of margin to spread them out.

- the default font is ugly, so lets go to google fonts and import a new one. show them how to do this and then set the font-family in the body tag so all things have that tne font.

- make the main body section, and use the padding calc trick to center the content. make a div inside that to hold the 3 items. center them and style appropriatly

- make a button and style that. show them psudo selectors like active or hover to give the button a bit more life.