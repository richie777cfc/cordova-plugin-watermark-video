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

## Response Promise<{videoDest: 'URI'}>

done: string - videoDest URI
