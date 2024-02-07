<div align="center">
  <img src="logo.png" width="64px">
  <h1>chipinCSS</h1>
</div>

ChipinCSS is a powerful and customization capable CSS library, with everything you wanted outside of it! It comes with many styles, color modes, styling elements, and many more. The library is all open-source, so you can modify it yourself!

## Installing

Installing the framework is very simple and very straightforward. You can install it with our CDN network, using NodeJS, or downloading it using our precompiled version. There are some requirements you should have first:

* JQuary
* PopperJS

To start off, download the precompiled files, and store them in a folder or your own CDN network, if you have one hosted. For example, a layout for a HTML page would look like this:


```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>My website</title>
</head>
<body>
<h1>Hello world!</h1>
</body>
</html>
```

When you have the files unpacked, add these lines to your HTML file.

```html
<link href="/path/to/your/files/chipinCSS/main.css" rel="stylesheet">
<!-- Replace the path where the CSS files are located! -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
```

> NOTE: Remember to add these lines to your `<head>` tag so that they appear correctly. If JQuary does not work, you can put it to the `<body>` tag.

Save the file, and reload the page. Now you have ChipinCSS installed on your website! Lets get to customizing it!

## Settings

We have a bunch of settings for you to choose from. Some of them include:

* Dark mode
* Color schemes
* Alerts
* Popups
* Hints (requires popperJS)
* Containers
* Navbars
* Flexing
* Buttons
* Tables
* Headers
* Models
* Cards

To see more of these settings, please see our documentation. Keep in mind that some of them require Javascript, so be sure to have JQuary installed!

## Contributing
We always like when people help us out on projects like this. In fact, anyone is free to edit and customize this framework however they like. Just fork this repo and you can modify it anyway you like!

## Notes
Keep in mind that this framework may not have features that a person would expect from other CSS framworks. This can include:

- Javascript librarys
- Scaling the screen with the elements
- Grid boxes
- Color modes
- Form layouts

This framework is expected to simple and small for starters. You may see problems with the listed things above, but you should wait for a release on some of them.

## Licence
This project is under the Apache License 2.0. See more on our license file.
