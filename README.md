[![npm version](https://badge.fury.io/js/cordova-plugin-watermark-video.svg)](https://badge.fury.io/js/cordova-plugin-watermark-video)

# PhoneGap/Cordova add watermark to video

## Installation

    cordova plugin add ccordova-plugin-watermark-video

## Supported Platforms

- Android [Soon]
- iOS

## Usage

### Typescript

```
import WatermarkVideo from "cordova-plugin-watermark-video";

WatermarkVideo.addWatermarkToVideo(
	videoSrc,
	videoDest,
	waterMarkImageSrc,
	top,
	left,
	progress
);
```

### Javascript

```
window.Watermark.addWatermarkToVideo(
	videoSrc,
	videoDest,
	waterMarkImageSrc,
	top,
	left,
	progress
);
```
Example:

```
waterMark(mediaFile.fullPath, "video.mp4", "path_to_image", 0, 0, checkProg);

function checkProg(progressval) {
  console.log("Progress %: " + progressval);
}
```

## Response Promise<{videoDest: 'URI'}>

done: string - videoDest URI
