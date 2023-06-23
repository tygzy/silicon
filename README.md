# Silicon

Silicon is a stylesheet with no requirement for classes, a **light** and **dark** mode, 
responsive, but also has classes to allow for some minor customization.
This allows anyone to have a website with a modern design that works on desktop, 
tablet or mobile device without having to worry about design decisions, 
but if you do want to be able to, you could.

Visit https://silicon-css.com for a live preview of Silicon on a web page.

## Speed 

There are two versions of Silicon, a normal version and a basic version, 
the basic version uses system fonts instead of a custom font, 
this allows faster loading times for developers which desire faster loading times.

Standard version: `silicon.min.css`

Basic version: `silicon_basic.min.css`

## Usage

After downloading silicon, use this code snippet to use it:

```html
<!DOCTYPE html>
<html>
    <head>
        <link rel='stylesheet' href='silicon.min.css'/>
        <!--    allows responsive design    -->
        <meta name='viewport' content='width=device-width, initial-scale=1.0'/>
    </head>
</html>
```

or for the basic version to only use system fonts for faster loading times

```html
<link rel='stylesheet' href='silicon_basic.min.css'/>
```

The standard (non-minified) version is also included with css variables at the top of the file 
to allow some core level customization to colours, border width and other things.

![dark theme example](https://i.imgur.com/rG6AFQX.png)

![light theme example](https://i.imgur.com/mNSiIbx.png)

