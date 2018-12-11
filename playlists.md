## All Playlists
```
curl "https://www.funk.net/api/v4.0/playlists/?size=10" -H "authorization: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJjbGllbnROYW1lIjoid2ViYXBwLXYzMSIsInNjb3BlIjoic3RhdGljLWNvbnRlbnQtYXBpLGN1cmF0aW9uLWFwaSxuZXh4LWNvbnRlbnQtYXBpLXYzMSx3ZWJhcHAtYXBpIn0.mbuG9wS9Yf5q6PqgR4fiaRFIagiHk9JhwoKES7ksVX4"
```

## One Playlist via entityId
```
curl "https://www.funk.net/api/v4.0/playlists/3537" -H "authorization: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJjbGllbnROYW1lIjoid2ViYXBwLXYzMSIsInNjb3BlIjoic3RhdGljLWNvbnRlbnQtYXBpLGN1cmF0aW9uLWFwaSxuZXh4LWNvbnRlbnQtYXBpLXYzMSx3ZWJhcHAtYXBpIn0.mbuG9wS9Yf5q6PqgR4fiaRFIagiHk9JhwoKES7ksVX4"
```

## All Playlists of one Channels (by alias)
```
curl "https://www.funk.net/api/v4.0/playlists/byChannelAlias/doctor-who-1164" -H "authorization: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJjbGllbnROYW1lIjoid2ViYXBwLXYzMSIsInNjb3BlIjoic3RhdGljLWNvbnRlbnQtYXBpLGN1cmF0aW9uLWFwaSxuZXh4LWNvbnRlbnQtYXBpLXYzMSx3ZWJhcHAtYXBpIn0.mbuG9wS9Yf5q6PqgR4fiaRFIagiHk9JhwoKES7ksVX4"
```

## Example Response
```
{
  "_embedded": {
    "playlistDTOList": [
      {
        "channelId": 11881,
        "channelAlias": "penpaper-11881",
        "videoCount": 2,
        "language": "german",
        "shortTitle": "Wo ist Waldemar?",
        "publicationDate": "2018-12-06T16:04:51.763+0000",
        "updateDate": "2018-12-06T16:01:06.000+0000",
        "importDate": "2018-12-11T12:15:05.753+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0948a342a6060001c0e1d9",
        "genre": [
          "Entertainment Show"
        ],
        "secondGenre": [
          "Religion u. Spirtitualität"
        ],
        "description": "Das nächste Pen&Paper Abenteuer. Mitten im 1. Weltkrieg machen sich vier Kinder auf die Suche nach einem vermissten Schwein - und retten so vielleicht nebenher ihr Dorf.",
        "title": "Wo ist Waldemar? Der Krieg und ein Schwein",
        "alias": "wo-ist-waldemar-der-krieg-und-ein-schwein-4819",
        "type": "default",
        "entityId": 4819
      },
      {
        "fsk": 12,
        "channelId": 1164,
        "channelAlias": "doctor-who-1164",
        "videoCount": 8,
        "language": "german",
        "shortTitle": "Doctor Who - Staffel 5",
        "publicationDate": "2018-10-23T20:00:00.000+0000",
        "expirationDate": "2019-01-04T22:59:00.000+0000",
        "updateDate": "2018-12-04T21:36:28.000+0000",
        "importDate": "2018-12-11T12:15:05.753+0000",
        "imageUrlOrigin": "https://www.funk.net/api/v4.0/images/5c06f36042a6060001c0d9be",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c06f35f42a6060001c0d9bb",
        "imageUrlSquare": "https://www.funk.net/api/v4.0/images/5c06f36042a6060001c0d9c8",
        "imageUrlPortrait": "https://www.funk.net/api/v4.0/images/5c06f36042a6060001c0d9c5",
        "genre": [
          "TV Drama"
        ],
        "shortDescription": "Eine englische Telefonzelle als Eingang zu einer fremden Welt: Wer jetzt an Harry Potter und das Zaubereiministerium denkt, liegt falsch, denn: Besagte \"Telefonzelle\" hat noch einiges mehr drauf und ist streng genommen gar keine. Nicht typisch rot, sondern blau, ist \"TARDIS\" eigentlich eine \"Police Box\" und gleichzeitig Tor durch Zeit und Raum für \"den Doktor\". Doktor wer? Genau der!",
        "description": "Eine englische Telefonzelle als Eingang zu einer fremden Welt: Wer jetzt an Harry Potter und das Zaubereiministerium denkt, liegt falsch, denn: Besagte \"Telefonzelle\" hat noch einiges mehr drauf und ist streng genommen gar keine. Nicht typisch rot, sondern blau, ist \"TARDIS\" eigentlich eine \"Police Box\" und gleichzeitig Tor durch Zeit und Raum für \"den Doktor\". Doktor wer? Genau der!",
        "title": "Doctor Who - Staffel 5",
        "alias": "doctor-who-staffel-5-2830",
        "type": "default",
        "entityId": 2830
      },
      {
        "fsk": 12,
        "channelId": 1164,
        "channelAlias": "doctor-who-1164",
        "videoCount": 8,
        "language": "german",
        "shortTitle": "Doctor Who - Staffel 5 (OV)",
        "publicationDate": "2018-10-23T20:00:00.000+0000",
        "expirationDate": "2019-01-04T22:59:00.000+0000",
        "updateDate": "2018-12-04T21:36:16.000+0000",
        "importDate": "2018-12-11T12:15:05.753+0000",
        "imageUrlOrigin": "https://www.funk.net/api/v4.0/images/5c06f35242a6060001c0d9ae",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c06f35242a6060001c0d9ab",
        "imageUrlSquare": "https://www.funk.net/api/v4.0/images/5c06f35342a6060001c0d9b8",
        "imageUrlPortrait": "https://www.funk.net/api/v4.0/images/5c06f35242a6060001c0d9b5",
        "genre": [
          "TV Drama"
        ],
        "shortDescription": "Amy and the Doctor explore time and space, visiting 16th century Venice, France during the 1890s and the United Kingdom in the far future, now an entire nation floating in space. As always, wherever the Doctor goes, his oldest enemies are never far behind – the Daleks are hatching a new master plan from the heart of war-torn London in the 1940s. But they are not the only strange creatures the Doctor and Amy must face – there are also alien vampires, humanoid reptiles, old enemies such as the Weeping Angels, and a silent menace that follows Amy and the Doctor around wherever they go.",
        "description": "Amy and the Doctor explore time and space, visiting 16th century Venice, France during the 1890s and the United Kingdom in the far future, now an entire nation floating in space. As always, wherever the Doctor goes, his oldest enemies are never far behind – the Daleks are hatching a new master plan from the heart of war-torn London in the 1940s. But they are not the only strange creatures the Doctor and Amy must face – there are also alien vampires, humanoid reptiles, old enemies such as the Weeping Angels, and a silent menace that follows Amy and the Doctor around wherever they go.",
        "title": "Doctor Who - Staffel 5 (OV)",
        "alias": "doctor-who-staffel-5-ov-2837",
        "type": "default",
        "entityId": 2837
      },
      {
        "channelId": 898,
        "channelAlias": "iamserafina-898",
        "videoCount": 11,
        "language": "german",
        "shortTitle": "iam.serafina - Staffel 11",
        "publicationDate": "2018-12-11T08:41:24.520+0000",
        "updateDate": "2018-11-28T15:12:53.000+0000",
        "importDate": "2018-12-11T12:15:05.753+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0f783454cd0c000170effc",
        "genre": [
          "Web Drama"
        ],
        "secondGenre": [
          "Freundschaft",
          "Sex u. Liebe"
        ],
        "shortDescription": "Staffel 11",
        "description": "Staffel 11",
        "title": "iam.serafina - Staffel 11",
        "alias": "iamserafina-staffel-11-4814",
        "type": "default",
        "entityId": 4814
      },
      {
        "channelId": 11955,
        "channelAlias": "fashion-future-berlin-11955",
        "videoCount": 8,
        "language": "german",
        "shortTitle": "Fashion Future Berlin I Staffel 1",
        "publicationDate": "2018-12-11T11:45:10.101+0000",
        "updateDate": "2018-11-28T06:47:39.000+0000",
        "importDate": "2018-12-11T12:15:05.753+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0fa34654cd0c000170f1f1",
        "shortDescription": "Alle Folgen der ersten Staffel Fashion Future Berlin.",
        "title": "Fashion Future Berlin I Staffel 1",
        "alias": "fashion-future-berlin-i-staffel-1-4677",
        "type": "default",
        "entityId": 4677
      },
      {
        "channelId": 11945,
        "channelAlias": "projekthorizont-11945",
        "videoCount": 12,
        "language": "deutsch",
        "shortTitle": "Projekt:Horizont - Staffel 1",
        "publicationDate": "2018-12-07T14:53:19.011+0000",
        "updateDate": "2018-11-23T15:37:49.000+0000",
        "importDate": "2018-12-11T12:15:05.753+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0a895e42a6060001c0e67a",
        "shortDescription": "Hier findest du alle Folgen der ersten Staffel von Projekt:Horizont",
        "title": "Projekt:Horizont - Staffel 1",
        "alias": "projekthorizont-staffel-1-4663",
        "type": "default",
        "entityId": 4663
      },
      {
        "fsk": 16,
        "channelId": 1248,
        "channelAlias": "orange-is-the-new-black-1248",
        "videoCount": 4,
        "language": "deutsch",
        "shortTitle": "Orange is the new Black - Staffel 4",
        "publicationDate": "2018-10-11T23:00:00.000+0000",
        "expirationDate": "2018-12-22T22:55:00.000+0000",
        "updateDate": "2018-11-22T13:02:03.000+0000",
        "importDate": "2018-12-11T12:15:05.753+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5bf6a8cdbd38d100015bac96",
        "imageUrlPortrait": "https://www.funk.net/api/v4.0/images/5bf6a8cdbd38d100015bac98",
        "genre": [
          "TV Drama",
          "TV Comedy"
        ],
        "shortDescription": "In der Emmy-prämierten Dramedy-Serie wird die gut situierte New Yorkerin Piper Chapman von einem vergangenen Verbrechen eingeholt und landet im Frauenknast. Die Staffel ist FSK 16 und auf funk.net ab 22 Uhr zu sehen.",
        "description": "In der Emmy-prämierten Dramedy-Serie wird die gut situierte New Yorkerin Piper Chapman von einem vergangenen Verbrechen eingeholt und landet im Frauenknast. Die Staffel ist FSK 16 und auf funk.net ab 22 Uhr zu sehen. Check doch mal die funk App, da kannst du nach Alterscheck Orange is the new Black jederzeit anschauen. Jeden Freitag zwei neue Folgen!",
        "title": "Orange is the new Black - Staffel 4",
        "alias": "orange-is-the-new-black-staffel-4-2858",
        "type": "default",
        "entityId": 2858
      },
      {
        "channelId": 11867,
        "channelAlias": "klicknapped-11867",
        "videoCount": 7,
        "language": "german",
        "shortTitle": "KLICKNAPPED - Staffel 1",
        "publicationDate": "2018-11-27T12:58:27.168+0000",
        "updateDate": "2018-11-22T08:09:54.000+0000",
        "importDate": "2018-12-11T12:15:05.753+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5bfd3f734ccd54000152840a",
        "imageUrlPortrait": "https://www.funk.net/api/v4.0/images/5bfd3f734ccd54000152840f",
        "genre": [
          "Web Drama",
          "Web Comedy"
        ],
        "secondGenre": [
          "Freundschaft",
          "Sex u. Liebe"
        ],
        "shortDescription": "In der fiktionalen Webserie versucht ein verrückter Fan ein getrenntes YouTube-Paar vor laufenden Kameras wieder zusammenzubringen, indem er sie entführt und in einen Keller sperrt.",
        "description": "In der fiktionalen Webserie versucht ein verrückter Fan ein getrenntes YouTube-Paar vor laufenden Kameras wieder zusammenzubringen, indem er sie entführt und in einen Keller sperrt.",
        "title": "KLICKNAPPED - Staffel 1",
        "alias": "klicknapped-staffel-1-4675",
        "type": "default",
        "entityId": 4675
      },
      {
        "channelId": 11097,
        "channelAlias": "boah-bergmann-11097",
        "videoCount": 11,
        "language": "englisch",
        "publicationDate": "2018-11-12T09:26:36.024+0000",
        "updateDate": "2018-11-12T09:26:34.000+0000",
        "importDate": "2018-12-11T12:15:05.753+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5be9474bfdb03c0001f9b3f4",
        "title": "Antarktika - Staffel 1",
        "alias": "antarktika-staffel-1-3530",
        "type": "default",
        "entityId": 3530
      },
      {
        "channelId": 11097,
        "channelAlias": "boah-bergmann-11097",
        "videoCount": 2,
        "language": "englisch",
        "publicationDate": "2018-11-12T09:26:12.829+0000",
        "updateDate": "2018-11-12T09:26:11.000+0000",
        "importDate": "2018-12-11T12:15:05.754+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5be94734fdb03c0001f9b3f2",
        "title": "Antarktika - Extras",
        "alias": "antarktika-extras-3537",
        "type": "default",
        "entityId": 3537
      }
    ]
  },
  "_links": {
    "next": {
      "href": "https://www.funk.net/api/v4.0/playlists/?size=10&sort=updateDate,desc&page=1"
    },
    "self": {
      "href": "https://www.funk.net/api/v4.0/playlists/?size=10&sort=updateDate,desc&page=0"
    }
  },
  "page": {
    "size": 10,
    "totalElements": 127,
    "totalPages": 11,
    "number": 0
  }
}
```
