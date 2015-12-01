# Kitty Replace
_A Google Chrome Extension that replaces animated GIFs with Kittens._

### About
Animated GIFs are great. On most pages on the internet, animated gifs are the perfect supplement to the material they are paired with. Writers will add these moving pictures to illustrate emotion, showcase a product feature, or add comic relief. And they are everywhere. But most of the time, I hate them.

When you are busy concentrating on the material at hand, moving pictures, especially ones not in your direct focus, are super distracting.

Kitty Replace sets to suppress these unwanted peripheral vision hi-jackers. Simply hit the icon and all animated GIFs will be replaced with adorable kittens.

![Kitty Replace](resources/icon_64.png)

### Technical Details

There's not much going on here. The extension makes use of Mark James' [PlaceKitten](https://placekitten.com/). It uses a quick javascript inspection of the DOM for any files with the .gif extension. It then asks what the height and width of are of that image. Lastly it uses this metadata to make a request for the perfectly sized kitten image. Viola.

### FAQs

*I changed my mind. How do I see the animated gifs again?*

Toggling doesn't currently work right now (maybe later). For now, just refresh your page!

*Does this help with load times? Those gifs are so dang slow.*

Not at all. This extension only works after all resources have been loaded onto a page.

##### Thanks for sharing!
