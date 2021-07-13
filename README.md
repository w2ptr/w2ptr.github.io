# w2ptr.github.io

Head over to [w2ptr.github.io](https://w2ptr.github.io) to view the website.

## Website Generation

The HTML files are generated from a base file `github-page.html` which has several placeholders denoted with a `$`
sign. For each actual page there is a separate file which fills in the placeholders, as denoted by a `#` sign.

For instance, the base file `github-page.html` might look like this:

```html
<!DOCTYPE html>

<html>
<head>
    <title>$TITLE</title>
</head>
<body>
    $CONTENT
</body>
</html>
```

And the file `index.html` might look something like this:

```html
#TITLE
Home Page

#CONTENT
<p>Content</p>
```

The files used to generate this page are not currently on github, but they might be added later. To generate the files,
there is a simple script written in `D` (also not on github right now).
