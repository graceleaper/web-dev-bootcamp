#  HTML Image Elements
- Image element to add images to our websites

```
<img src="grace-lee.png">
```
- `img` is the HTML element, and `src` is an attribute. Its value can be a URL of an image, or an image from your computer (but we can only use images from our computers if we're coding with an editor or app that we installed in our computers. Wouldn't work when we're coding on a coding editor on a browser, like BSD)
- Right click on an image you find online and select "Copy Image Address"
    - If you paste this address in the search bar, you can see the full URL of the image
    - Usually, image files end in .jpg, .png, and .gif
- Use this image address, or image source and paste it as a value of the `src` atrribute in `img` tag

```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Grace's Personal Site</title>
</head>
<body>
    <img src="...jpg" alt="grace lee">

    <h1>All About Grace</h1>

    <p>I'm a <em>computer science teacher</em> at <strong>The Buckley School in NYC</strong>.</p>

    <p>I was born and raised in New York. And I love coffee.</p>
    <hr>

    <h3>Education</h3>

    <ul>
        <li>Fullstack Academy of Code: Software Engineerig Program<li>
        <li>Teachers College, Columbia Univesity: Master of Education</li>
    </ul>

    <h3>Hobbies</h3>

    <ol>
        <li>Digital drawing</li>
        <li>Watching Netflix</li>
        <li>HIIT at home</li>
    </ol>
</body>
</html>
```
- Notice above, the image tag has an `alt` attribute. If the browser can't render the image, the browser will display the text in the alt tag (alternative text)
- Google will use image alt tags to display our webpage if users use similar keywords when searching on Google
- We have our first image!
- Create an Photobucket account (photobucket.com) to upload images you can't get online but still want to put on your website
    - After uploading on Photobucket, right click on image. And select "Copy Image Address"
- If you don't see an image, the server that delivered the image may be down
- Can use crop-cicle tool to crop images in a circle, with transparent edges
    - Image with circular border common among social media sites (YouTube, Instagram)
- *** Can use repl.it to create websites on the browser, AND save images from your device