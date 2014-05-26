Mobi
====
> Framework for mobile platform.

## Features
* Mobile Only
* High performance
* Accessibility Support
* Custom build support

## Screenshot

![screenshot1](https://f.cloud.github.com/assets/677114/2280325/a3db2e1e-9f87-11e3-85bd-6ca4e58a433e.png)

![screenshot2](https://f.cloud.github.com/assets/677114/2280329/a796fb1e-9f87-11e3-86fe-9f88657827c1.png)

## Demo

Scan below QR code or visit [https://rawgit.com/mobijs/mobi/master/demo/index.html](https://rawgit.com/mobijs/mobi/master/demo/index.html) on your handset.

![qrcode](https://cloud.githubusercontent.com/assets/677114/3079397/ec17757e-e498-11e3-819e-f19e3e82f192.png)

## Basic template

Copy the HTML below to begin working with a minimal MOBI document.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <title>MOBI</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">

    <!-- MOBI CSS -->
    <link rel="stylesheet" type="text/css" href="css/mobi.css">
</head>
<body class="ui-app">

    <div class="ui-top-bar js-no-bounce">
        MOBI
    </div>

    <div class="ui-bottom-bar js-no-bounce" role="toolbar" tabindex="0">
        <button class="ui-bottom-bar-button js-active" data-toggle="tab" data-target="#page1">
            <span class="ui-icon"></span>
            <span class="ui-label">CSS</span>
        </button>
        </div>
    </div>

    <div id="page1" class="ui-page js-active">
        <div class="ui-page-content">
             <h1>Hello, world!</h1>
        </div>
    </div>

    <!-- MOBI JS -->
    <script src="js/mobi.js"></script>
  </body>
</html>
```
## Platform support

Current version have been tested on the below platforms:

 * iOS 4.0-7.0
    * iOS 4.3 (iPad 1)
    * iOS 5.1 (iPhone 4)
    * iOS 6.1 (iPhone 4S)
    * iOS 7.0 (iPhone 5)
 * Android 2.3-4.4
    * Android 2.3 (ZTE)
    * Android 4.0 (HTC Rhyme S510B)
    * Android 4.1 (LG Optimus G)
    * Android 4.2 (Sony Xperia Z)
    * Android 4.3 (Nexus 4)
    * Android 4.4 (Nexus 4)
