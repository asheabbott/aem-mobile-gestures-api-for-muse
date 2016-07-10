# AEM Mobile Gestures API for Muse

This Muse Configurable Options Widget (mucow) is a simple way to add the Adobe AEM Mobile Gestures API to Adobe Muse projects, so that tapping the AEMM article will toggle the navigation.

## How To Use

Download the .mucow file, open your Muse project and navigate to the Master page.

`File > Place` the .mucow file into your Master page.

When you export your Muse project to HTML, the JS code for the Gestures API will be added to the end of your index.html file, and tapping the AEMM article should toggle the navigation.

## Considerations

* The JS in the .mucow file targets iOS devices, as tapping on Android devices toggle the navigation without the Gestures API.
* The .mucow file is best placed on the canvas, as placing it off the canvas can result in unexpected dimensions of the HTML article.
* The .mucow file needn't be hidden or otherwise obscured; though a <> icon does appear where the .mucow file is placed in Muse, it will not be visible in the exported HTML.
* The .mucow file has no options.

## About

I developed this widget at [Bates Creative](http://batescreative.com). We are currently using it within our process for creating Adobe AEM Mobile articles in Adobe Muse. We are really happy to be able to share it with the community, as we know there's substantial need to bridge the gap between designer-friendly Adobe Muse and developer-friendly AEM Mobile.
