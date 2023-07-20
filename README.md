# Restuarant Landing Page <br>
this project illustrated implementation of image as a background and blackish shade as a linear gradient.<br>
 ## How to set image as background in html

1. Save the image file in the same directory as your HTML file.
2. In your HTML file, add the following code inside the `<body>` tag:

```html
<div style="background-image: url('image_name.jpg');"></div>
```

Replace `image_name.jpg` with the name of your image file.

3. Save your HTML file and open it in a web browser. You should see the image displayed as the background of the `<div>` element.

Here is an example of an HTML file that sets an image as a background:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Image Background Demo</title>
</head>
<body>
  <div style="background-image: url('background.jpg');">
    This is a text paragraph.
  </div>
</body>
</html>
```

This HTML file sets the image `background.jpg` as the background of the `<div>` element. The text paragraph inside the `<div>` element will be displayed on top of the background image.

You can try this example yourself by opening it in a web browser. You should see the background image displayed behind the text paragraph.

Here are some additional CSS properties that you can use to control the appearance of the background image:

* `background-repeat` : This property controls how the image is repeated. The possible values are `repeat`, `repeat-x`, `repeat-y`, and `no-repeat`.
* `background-position` : This property controls the position of the image. The possible values are `top left`, `top center`, `top right`, `center left`, `center`, `center right`, `bottom left`, `bottom center`, and `bottom right`.
* `background-size` : This property controls the size of the image. The possible values are `cover`, `contain`, `auto`, and a value in pixels or percentage.


