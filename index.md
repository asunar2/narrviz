## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/asunar2/soccerviz/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

<!DOCTYPE html>
<html>
<head>
<script type="text/javascript" src="d3.min.js"></script>
<style>
body{ font: Arial 12px; text-align: center;}
.link {
  stroke: #ccc;
}
.node text {
  pointer-events: none;
  font: sans-serif;
}
</style>
<link rel="stylesheet" type="text/css" href="main.css">
</head>
<body>
<h3>Game of Thrones-Social Network Analysis</h3>
<script type="text/javascript">
  
  //Set margins and sizes
var margin = {
top: 20,
bottom: 50,
right: 30,
left: 50
};

var width = 960 - margin.left - margin.right;
var height = 700 - margin.top - margin.bottom;

//Load Color Scale
var c10 = d3.scale.category10();

//Create an SVG element and append it to the DOM
var svgElement = d3.select("body")
.append("svg").attr({"width": width+margin.left+margin.right, "height": height+margin.top+margin.bottom})
.append("g")
.attr("transform","translate("+margin.left+","+margin.top+")");


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/asunar2/soccerviz/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
