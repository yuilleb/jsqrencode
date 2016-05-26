# jsqrencode
Updated version of jsqrencode (https://code.google.com/archive/p/jsqrencode/)

I've turned the original code into an object oriented class called QR.

## Example
```
<canvas id="qrcanv"></canvas>
<script type="text/javascript">
var qr = new QR(document.getElementById('qrcanv'), "Hello World!", 400, 400);
</script>
```
