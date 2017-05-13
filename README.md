[v0.0.2](https://github.com/littleflute/b44/edit/master/README.md)


<br> 
<div id="divCurPic"></div> 
<br> 
<button onclick="show(1)">+1</button> 
<img id="myImg" width="320" height="200" src="044/DSC_4726.JPG" > 
</img>  
<br>

<script>  
var vid = document.getElementById("myImg"); 
var n = 4726;
function show(i) {
    n += i;
    var s = "https://littleflute.github.io/b44/";
    s += "044/DSC_";
    s += n;
    s += ".JPG";
	  document.getElementById("divCurPic").innerHTML = s;  
    vid.src = s;
} 
</script> 








## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/littleflute/b44/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/littleflute/b44/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
