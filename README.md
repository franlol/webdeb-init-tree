# WiT - Web-development Initial Tree
Script to create a simple initial tree folders for the web development

Get your project folder structure with a single command

![alt text](https://raw.githubusercontent.com/franlol/webdeb-init-tree/master/demo.gif)

## Installation
```
git clone https://github.com/franlol/webdeb-init-tree
sudo cp ./webdeb-init-tree/wit /bin/wit
```

## Features
 Create index.html with the following flags
- --css: Custom folder for css with 'style.css' linked
- --js: Custom folder for JS with 'script.js' linked
- --bootstrap: Bootstrap cdn link (css + js)
- --bulma: Bulma cdn link
- --fontawesome: Font Awesome cdn link
- --jquery: jQuery cdn link

## Usage / example
```
wit folder-name --flags

wit my-project --css --bulma --jquery
```