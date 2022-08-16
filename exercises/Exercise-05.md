# Exercise 05

Before continuing, make sure that all steps so far are completed by checking your site as it stands against the image below:



## Basic Styles

Now we will do some basic styles.

### Create fonts folder

In the `assets` folder, create a new folder/directory called `fonts`.

Put a `.keep` file into this folder.

### Updating the index header

Open the `index.html` file and modify the `head` section by adding in the following links to the Cairo and InknutAntiqua fonts:

```html
<!-- Local fonts -->

<!-- Google fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;700&display=swap"
      rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Inknut+Antiqua:wght@300;400;500;700;900&display=swap" 
      rel="stylesheet">
```


## Whole of Page defaults
Open the `site.css` file from the `assets\css\` folder/directory.

Move to the top of the CSS file and add:

```css
html {
    font-family:  
}
```

## Creating site classes


Add the class names from the index page.

Remember that classes start with full stops (`.`).  For example:
```css
.demo-class {
    /* css definitions */
}
```
Make sure that the classes with `site-` are listed first.

