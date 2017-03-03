# Test embedding two Sozi presentations in the same page.

# SVG format

## Object

<object data="sozi-tutorial-full.svg" type="image/svg+xml"></object>

## Embed

<embed src="sozi-tutorial-full.svg"></embed>

## Iframe

<iframe src="sozi-tutorial-full.svg"></iframe>

# HTML format

## Object

<object data="first-presentation.sozi.html" type="text/html"></object>

## Embed

<embed src="first-presentation.sozi.html"></embed>

## Iframe

<iframe src="first-presentation.sozi.html"></iframe>

<!-- pandoc --standalone -t slidy Sozi-embed.md -o Sozi-embed.html-->
