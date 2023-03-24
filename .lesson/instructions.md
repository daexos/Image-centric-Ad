# Image-Based Ad
Build an "ad" or a "menu item" around a single image. Include a comment in your code citing the source of your image.

First, find an image you find visually appealing (I recommend a food or item of clothing).

Second, put some text with the image: some simple ad copy, a price, and an item description/title, such as you would see on a menu or in a catalogue.

Finally, choose colors, a layout, and fonts that work well to form a coherent, professional looking advertisement.

Example here: [https://replit.com/@ThomasHinkle/BrownieDemo#style.css](https://replit.com/@ThomasHinkle/BrownieDemo#style.css)

## How-To Videos

Here are some helpful how to's for this project:

- [Putting an Image in a repl.it](https://youtu.be/rnsf-TNecR8)
- [Making an image into the background of a div](https://youtu.be/8Xljn20vGdQ)
- [Using a Color Picker to build a color scheme from an image](https://youtu.be/DbEYZPOBwX0)
- [Making text readable over an image](https://youtu.be/nvsOGRNERkc)

## Quick Code-Snippets

### To size and position a background
[https://codepen.io/thinkle-iacs/pen/WNgZrmP?editors=1000](https://codepen.io/thinkle-iacs/pen/WNgZrmP?editors=1000)

### To make an image cover an HTML element...

```css
    div {
      background: url('url-of-my-image.png');
      background-size: cover; /* Cover the whole div */
      width: 200px; /* Specify width */
      height: 300px; /* Specify height */
    }
```

### To make a See through div over a div

#### All in HTML

#### With separate HTML and CSS
In your HTML...
```html
    <div id="pic">
      <div class="text">
        Here is some text I need to be readable
      </div>
    </div>
```

In your CSS
```css
    #pic {
      background: url('url-of-my-image.png');
      background-size: cover; /* Cover the whole div */
    }

    .text {
      /* Make it 45% opaque -- i.e. 55% see-through */
      background: hsl(45deg 50% 50% / 45%);
    }
```

### Making Text Readable

To make text readable, you can put an overlay behind it, or you can put an outline on the text itself. 

[Here is a code-pen showing multiple techniques for making outlined text](https://codepen.io/thinkle-iacs/pen/qBMPdvK?editors=1000)

Here's a [lengthy discussion of options for outlining text on the web](https://css-tricks.com/adding-stroke-to-web-text/).

