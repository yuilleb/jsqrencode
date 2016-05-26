# jsqrencode
Updated version of jsqrencode (https://code.google.com/archive/p/jsqrencode/)

>Fast QR encoding entirely in javascript as a HTML5 canvas webapp
>
>There are lots of web pages, but I couldn't find a webapp. And I wrote a very compact implementation for the Arduino, so I'm trying a port. It takes 5 seconds on a 2G iPod touch to do the maximum size.

This version enhances the original code by turning it into an object oriented class called QR. Slight improvements in the drawing code have been made as well.

## Example
```
<canvas id="qrcanv"></canvas>
<script type="text/javascript">
var qr = new QR(document.getElementById('qrcanv'), "Hello World!", 400, 400);
</script>
```
