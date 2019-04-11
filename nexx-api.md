## Init session

```
curl "https://api.nexx.cloud/v3/741/session/init" --data "nxp_devh=4"%"3A1500496747"%"3A178989"
```

```
{
  "metadata": {
    "status": 201,
    "apiversion": "3.0.11",
    "processingtime": 0.3162519931793213,
    "calledwith": "/session/init",
    "forclient": 741
  },
  "result": {
    "general": {
      "cid": "3154455148505954051",
      "isNewSession": 1,
      "isUnique": 0,
      "clid": 741,
      "uid": 0,
      "campaign": 0,
      "affiliatePartner": 0,
      "playlicenseAdref": "",
      "webViewOrigin": "",
      "geocode": "DE",
      "latitude": "50.096",
      "longitude": "8.7111",
      "gateway": "html",
      "language": "de",
      "referrer": "",
      "portal": ""
    },
    "device": {
      "id": "4:1500496747:178989",
      "ip": "87.123.240.54",
      "type": "pc",
      "manufacturer": "",
      "model": "",
      "sessionIndex": 13,
      "allowTrack": 1,
      "browser": "curl",
      "browser_version": "7.44",
      "os": "",
      "os_version": "",
      "supportsWebP": 0,
      "needsUpdate": 0
    },
    "system": {
      "clientstatus": "online",
      "sdkstatus": 1,
      "reporttoken": "%2B7aLq9ixziaqg7h%2BpiWvfBafA4VLcIiUr3eBOVOyq0c%3D&se=1544925363",
      "reportregion": "we",
      "samaritanToken": "9oI%2BlL%2Fgzz1PX7yZaPcxRv3gwlguQivU8l04Es1WLXA%3D&se=1544925363"
    }
  }
}
```

## Get Video metadata
```
curl "https://api.nexx.cloud/v3/741/videos/byid/1369342" -H "x-request-cid: 3154455148505954051" -H "x-request-token: f058a27469d8b709c3b9db648cae47c2" --data "addStatusDetails=1&addStreamDetails=1&addFeatures=1&addCaptions=1&addBumpers=1&captionFormat=data"
```

- number after **byid**: entityId of the video by funk api
- number after **x-request-cid**: result.general.cid of nexx session init call (above)


```
{
   "metadata":{
      "status":200,
      "apiversion":"3.0.11",
      "processingtime":0.1634969711303711,
      "calledwith":"\/videos\/byid\/1369342",
      "forclient":741
   },
   "result":{
      "general":{
         "ID":1369342,
         "hash":"NEZEWG1369342AV",
         "title":"Liebe ist alles - DRUCK - Folge 1",
         "subtitle":"Liebe ist alles - DRUCK - Folge 1",
         "orderhint":"",
         "uploaded":1521886128,
         "created":1521879752,
         "videotype":"episode",
         "runtime":"00:18:19",
         "isPay":0,
         "payrefnr":"",
         "isUGC":0,
         "isPicked":0,
         "isRacy":0,
         "episode":1,
         "season":1
      },
      "imagedata":{
         "thumb":"https:\/\/thumbs.nexx.cloud\/201803\/LAX13693425Z8PCxL.jpg",
         "thumb_hasX2":0,
         "thumb_hasX3":0,
         "thumb_action":"https:\/\/thumbs.nexx.cloud\/global\/nodata\/nodata_v2xL.jpg",
         "thumb_quad":"https:\/\/thumbs.nexx.cloud\/global\/nodata\/nodata_v2.jpg",
         "thumb_alt":"https:\/\/thumbs.nexx.cloud\/global\/nodata\/nodata_v2xL.jpg",
         "animation":"https:\/\/thumbs.nexx.cloud\/global\/nodata\/nodata_v2.jpg",
         "preview":"https:\/\/thumbs.nexx.cloud\/previews\/11790\/1369342\/NEZEWG1369342AV.mp4?fv=1"
      },
      "interactiondata":{
         "rating":3,
         "ratingcount":0,
         "likecount":0,
         "commentcount":0,
         "favouritecount":0
      },
      "captiondata":[

      ],
      "streamdata":{
         "originalDomain":11790,
         "adMode":0,
         "originalAdChannel":"",
         "showWarningBeforePlay":0,
         "payPreviewSeconds":-1,
         "bumperMode":0,
         "watermarkMode":1,
         "encodedTHUMBS":1,
         "encodedWEBM":1,
         "encodedVP9":0,
         "encodedFBA":0,
         "encodedChunkedHEVC":0,
         "encodedChunkedVP9":0,
         "cdnType":"azure",
         "applyAzureStructure":1,
         "azureFileDistribution":"0400:320x180,0700:640x360,0900:720x404,1500:1024x576,2500:1280x720,4000:1920x1080,6000:1920x1080",
         "applyFolderHierarchy":0,
         "customWatermark":"",
         "thumbInterval":10,
         "isPreChunked":0,
         "isOnColdStorage":0,
         "cdnShieldHTTP":"funk-01.akamaized.net\/",
         "cdnShieldHTTPS":"funk-01.akamaized.net\/",
         "cdnShieldProgHTTP":"funk-01dd.akamaized.net\/",
         "cdnShieldProgHTTPS":"funk-01dd.akamaized.net\/",
         "azureLocator":"a7f51520-c20f-4d3a-960a-0aca422b81aa",
         "azureStaticLocator":"06e2895e-c33d-48a5-8a36-77f93bcf6828",
         "azureAccount":"nexxplayplus6"
      },
      "protectiondata":{
         "method":"",
         "token":"",
         "provider":"",
         "server":"",
         "key":""
      },
      "features":{
         "width":1920,
         "height":1080,
         "aspectRatio":"16:9",
         "orientation":"landscape",
         "fps":25,
         "isHD":0,
         "isFullHD":1,
         "is2K":0,
         "is4K":0,
         "isPanorama":0,
         "hasHDR":0,
         "hasAudio":1,
         "hasStereo":1,
         "hasSurroundSound":0,
         "hasMultiAudio":0
      },
      "statusdata":{
         "ageok":1,
         "timeok":1,
         "commok":1,
         "embedok":1,
         "devok":1,
         "geook":1,
         "canBeDownloaded":0,
         "shouldBeCached":0,
         "shouldAllowEmbed":1
      }
   }
}
```

## Get URL from video metadata

### Streams

```
https://funk-01.akamaized.net/a7f51520-c20f-4d3a-960a-0aca422b81aa/1369342_src.ism/Manifest

=> https://[result.streamdata.cdnShieldHTTPS]/[result.streamdata.azureLocator]/[videoEntityId]_src.ism/Manifest
```

### Static files

```
http://funk-01dd.akamaized.net/a7f51520-c20f-4d3a-960a-0aca422b81aa/1369342_src_320x180_400.mp4
http://funk-01dd.akamaized.net/a7f51520-c20f-4d3a-960a-0aca422b81aa/1369342_src_1920x1080_6000.mp4

=> https://[result.streamdata.cdnShieldProgHTTP]/[result.streamdata.azureLocator]/[videoEntityId]_src_[result.streamdata.azureFileDistribution].mp4
```
