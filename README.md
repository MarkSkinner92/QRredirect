## Example
This link will take you to amazon.ca: [https://markskinner92.github.io/QRredirect/?id=1](https://markskinner92.github.io/QRredirect/?id=1)

This link will take you to ebay.com: [https://markskinner92.github.io/QRredirect/?id=2](https://markskinner92.github.io/QRredirect/?id=2)

## Instructions
1. Clone this project to your own Github account
2. Host it on Github Pages

## How to add your own URLs
Edit your index.html like this:
```
{
  0: "default/fallback URL", <- if there is no ID, the ID is 0, or the ID isn't listed below
  
  ID : "URL",
  ID : "URL",
  ID : "URL",
  ...
}
```
Commit your changes, give it a few minutes, and go to this URL (after replacing yourusername and yourid):
yourusername.github.io/QRredirect/?id=yourid

This will instantly take you to the corresponding URL

## Make that URL into a QR code
I reccomend using this site:
https://www.the-qrcode-generator.com/
paste in the link you made and there you go!
