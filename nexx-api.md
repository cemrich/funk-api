## Init session

```
curl "https://api.nexx.cloud/v3/741/session/init" --data "nxp_devh=1647698623"%"3A45213"
```

- value of **nxp_devh** is a url encoded device id (`<unix_timestamp>:<random_number>`, random number has to be in [10000:99999])

```
{
   "metadata":{
      "status":201,
      "apiversion":"3.1.30",
      "verb":"POST",
      "processingtime":0.3488759994506836,
      "calledwith":"\/session\/init",
      "forclient":741
   },
   "result":{
      "general":{
         "cid":"4164769873184175132",
         "isNewSession":1,
         "isUnique":1,
         "clid":741,
         "uid":0,
         "affiliatePartner":0,
         "deliverPartnerAdref":"",
         "webViewOrigin":"",
         "geocode":"DE",
         "georegion":0,
         "gdprApplies":1,
         "latitude": "50.096",
         "longitude": "8.7111",
         "gateway":"html",
         "language":"de",
         "referrer":"",
         "portal":""
      },
      "device":{
         "id":"1647698623:45213",
         "ip":"198.51.100.47",
         "type":"pc",
         "manufacturer":"",
         "model":"",
         "sessionIndex":1,
         "browser":"curl",
         "browser_version":"7.79",
         "os":"",
         "os_version":"",
         "supportsWebP":0,
         "supportsAVIF":0,
         "needsUpdate":0
      },
      "system":{
         "clientstatus":"online",
         "domainstatus":"online",
         "sdkstatus":1,
         "samaritanToken":"Gh5WB6%2FMoCIaS6X6nJt0oqKSx5DfZEqcgc4F7cZqrDU%3D&se=1648086942"
      }
   }
}
```

## Get Video metadata

```
curl "https://api.nexx.cloud/v3/741/videos/byid/1369342" -H "x-request-cid: 4164769873184175132" -H "x-request-token: 137782e774d7cadc93dcbffbbde0ce9c" --data "addStatusDetails=1&addStreamDetails=1&addFeatures=1&addCaptions=1&addBumpers=1&captionFormat=data"
```

- number after **byid**: entityId of the video by funk api
- number after **x-request-cid**: result.general.cid of nexx session init call (above)
- hash after **x-request-toke**: md5(byid741CA4SDGOBTRM421IRNO0)

```
{
   "metadata":{
      "status":200,
      "apiversion":"3.1.30",
      "verb":"POST",
      "processingtime":0.049755096435546875,
      "calledwith":"\/videos\/byid\/1369342",
      "forclient":741,
      "notice":"'captionFormat' is deprecated. please specify the Caption Format in 'addCaptions'."
   },
   "result":{
      "general":{
         "ID":1369342,
         "GID":594604,
         "hash":"NEZEWG1369342AV",
         "title":"Liebe ist alles",
         "subtitle":"Liebe ist alles",
         "orderhint":"",
         "uploaded":1521886128,
         "created":1521886128,
         "videotype":"episode",
         "runtime":"00:18:19",
         "isPay":0,
         "contentModerationAspects":"",
         "isUGC":0,
         "forKids":0,
         "isPicked":0
      },
      "imagedata":{
         "thumb":"https:\/\/assets.nexx.cloud\/media\/69\/44\/15\/QPP09PHI6WJOR5NxL.jpg",
         "thumb_hasXS":1,
         "thumb_hasXL":1,
         "thumb_hasX2":1,
         "thumb_hasX3":1,
         "coversShowTitle":0,
         "thumb_alt":"https:\/\/assets.nexx.cloud\/defaults\/nodataxL.jpg",
         "thumb_action":"https:\/\/assets.nexx.cloud\/defaults\/nodataxL.jpg",
         "thumb_banner":"https:\/\/assets.nexx.cloud\/defaults\/nodataxL.jpg",
         "thumb_quad":"https:\/\/assets.nexx.cloud\/defaults\/nodataxL.jpg",
         "thumb_abt":"https:\/\/assets.nexx.cloud\/defaults\/nodataxL.jpg",
         "thumb_animation":"https:\/\/assets.nexx.cloud\/defaults\/nodataxL.jpg",
         "preview":"https:\/\/assets.nexx.cloud\/media\/50\/28\/52\/KH3CVC0CK5UMWD.mp4"
      },
      "interactiondata":{
         "rating":3,
         "ratingavg":0,
         "ratingbayes":0,
         "ratingcount":0,
         "likecount":0,
         "commentcount":0,
         "favouritecount":0,
         "reactioncount":0,
         "topitemposition":0,
         "topitemexternalposition":0
      },
      "captiondata":[
         {
            "ID":83997,
            "title":"deutsch",
            "type":"subtitles",
            "language":"de",
            "origin":"http",
            "isAudioDescription":0,
            "data":[
            ],
            "format":"data",
            "assetRoot":"media\/80\/86\/57\/092V4LWSXL4DB02"
         }
      ],
      "streamdata":{
         "originalDomain":11790,
         "originalDomainAdReference":"",
         "adMode":0,
         "showWarningBeforePlay":0,
         "payPreviewSeconds":-1,
         "isPartOfStory":0,
         "bumperMode":0,
         "watermarkMode":1,
         "encodedTHUMBS":1,
         "encodedTHUMBSAVIF":0,
         "encodedWEBM":1,
         "encodedVP9":0,
         "encodedAV1":0,
         "encodedFBA":0,
         "encodedHYVE":0,
         "encodedChunkedHEVC":0,
         "encodedChunkedVP9":0,
         "encodedChunkedTS":0,
         "cdnType":"3q",
         "applyAzureStructure":0,
         "azureFileDistribution":"0455:426x240:5-m92Nf8wb7zDqjpHtZJLG,0898:640x360:4-YdRGxwHp8MbgkycLTz4D,1615:1024x576:32-ZYg4D32NqKxXWJvf9dCk,2968:1280x720:2-frjhwDkmxZt2PRbNQ8F6,4106:1920x1080:1-t6ChXKWQMqP43YcT8Vdb",
         "applyFolderHierarchy":0,
         "customWatermark":"",
         "thumbRoot":"media\/76\/61\/14\/YX7G10JTF3YYKF",
         "thumbInterval":10,
         "isRemote":0,
         "isPreChunked":0,
         "useRealtime":0,
         "isOnColdStorage":0,
         "cdnShieldHTTP":"funk-02.akamaized.net\/",
         "cdnShieldHTTPS":"funk-02.akamaized.net\/",
         "cdnShieldProgHTTP":"funk-02dd.akamaized.net\/",
         "cdnShieldProgHTTPS":"funk-02dd.akamaized.net\/",
         "qLocator":"2884266",
         "qHash":"tGJbDmXYVwz6qCp",
         "qPrefix":"21\/02\/27",
         "qAccount":"22679",
         "qStatic":"06e2895e-c33d-48a5-8a36-77f93bcf6828",
         "qReferences":",html5:2881250:jRry4JB9xYGVHkLXqcfb"
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
         "filesize":1574610179,
         "orientation":"landscape",
         "fps":25,
         "isHD":0,
         "isFullHD":1,
         "is2K":0,
         "is4K":0,
         "isPanorama":0,
         "isHDR":0,
         "hasAudio":1,
         "hasStereo":1,
         "hasSurroundSound":0,
         "hasMultiAudio":0,
         "readingTime":2.40223,
         "volume_avg":0,
         "volume_max":0
      },
      "statusdata":{
         "ageok":1,
         "timeok":1,
         "commok":1,
         "embedok":1,
         "devok":1,
         "geook":1,
         "concurrentok":1,
         "shouldBeCached":0,
         "shouldAllowEmbed":1
      }
   }
}
```

## Get URL from video metadata

### Streams

```
https://funk-02.akamaized.net/22679/files/21/02/27/2884266/22679-tGJbDmXYVwz6qCp.ism/Manifest

=> https://[cdnShieldHTTPS][qAccount]/files/[qPrefix]/[qLocator]/[qAccount]-[qHash].ism/Manifest
```

### Static files

```
https://funk-02.akamaized.net/22679/files/21/02/27/2884266/2-frjhwDkmxZt2PRbNQ8F6.mp4 (1280x720)
https://funk-02.akamaized.net/22679/files/21/02/27/2884266/1-t6ChXKWQMqP43YcT8Vdb.mp4 (1920x1080)

=> https://[cdnShieldHTTPS][qAccount]/files/[qPrefix]/[qLocator]/[azureFileDistribution].mp4
```
