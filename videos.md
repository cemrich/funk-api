## All Videos
```
curl "https://www.funk.net/api/v4.0/videos/?size=10" -H "authorization: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJjbGllbnROYW1lIjoid2ViYXBwLXYzMSIsInNjb3BlIjoic3RhdGljLWNvbnRlbnQtYXBpLGN1cmF0aW9uLWFwaSxuZXh4LWNvbnRlbnQtYXBpLXYzMSx3ZWJhcHAtYXBpIn0.mbuG9wS9Yf5q6PqgR4fiaRFIagiHk9JhwoKES7ksVX4"
```

## Alle Videos of one Channel (by id)
```
curl "https://www.funk.net/api/v4.0/videos/byChannelId/1164?size=10" -H "authorization: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJjbGllbnROYW1lIjoid2ViYXBwLXYzMSIsInNjb3BlIjoic3RhdGljLWNvbnRlbnQtYXBpLGN1cmF0aW9uLWFwaSxuZXh4LWNvbnRlbnQtYXBpLXYzMSx3ZWJhcHAtYXBpIn0.mbuG9wS9Yf5q6PqgR4fiaRFIagiHk9JhwoKES7ksVX4"
```

## All Videos of one Channel (by alias)
```
curl "https://www.funk.net/api/v4.0/videos/byChannelAlias/doctor-who-1164?size=10" -H "authorization: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJjbGllbnROYW1lIjoid2ViYXBwLXYzMSIsInNjb3BlIjoic3RhdGljLWNvbnRlbnQtYXBpLGN1cmF0aW9uLWFwaSxuZXh4LWNvbnRlbnQtYXBpLXYzMSx3ZWJhcHAtYXBpIn0.mbuG9wS9Yf5q6PqgR4fiaRFIagiHk9JhwoKES7ksVX4"
```

## One Video via entityId
```
curl "https://www.funk.net/api/v4.0/videos/1580678" -H "authorization: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJjbGllbnROYW1lIjoid2ViYXBwLXYzMSIsInNjb3BlIjoic3RhdGljLWNvbnRlbnQtYXBpLGN1cmF0aW9uLWFwaSxuZXh4LWNvbnRlbnQtYXBpLXYzMSx3ZWJhcHAtYXBpIn0.mbuG9wS9Yf5q6PqgR4fiaRFIagiHk9JhwoKES7ksVX4"
```

## Example Response
```
{
  "_embedded": {
    "videoDTOList": [
      {
        "channelId": 828,
        "channelAlias": "die-frage-828",
        "duration": 665,
        "creationDate": "2018-12-06T08:49:44.000+0000",
        "hash": "ZW91585268SSYO",
        "shortTitle": "Kann ich günstig nachhaltige Mode shoppen?",
        "publicationDate": "2018-12-11T12:00:00.000+0000",
        "updateDate": "2018-12-11T10:41:44.000+0000",
        "importDate": "2018-12-11T12:13:43.136+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0fa2f954cd0c000170f1e9",
        "genre": [
          "Reportage"
        ],
        "shortDescription": "Fast Fashion vs. nachhaltige Mode – genau darum geht es in meiner Spezial-Folge „Schluss mit Fast Fashion: Kann ich günstig nachhaltige Mode shoppen?“. Denn ich frage mich: Kann man auch günstig nachhaltige Mode shoppen und damit endlich weg von Fast Fashion kommen?",
        "description": "Fast Fashion vs. nachhaltige Mode – genau darum geht es in meiner Spezial-Folge „Schluss mit Fast Fashion: Kann ich günstig nachhaltige Mode shoppen?“. Denn ich frage mich: Kann man auch günstig nachhaltige Mode shoppen und damit endlich weg von Fast Fashion kommen? \r\n\r\nJedes Jahr kaufen wir tonnenweise Fast Fashion, also Wegwerf-Mode, die billig und unter schlechten Bedingungen für Mensch und Umwelt produziert wird, um dann für wenig Geld verkauft zu werden. Wegwerf-Mode deshalb, weil sie nur den aktuellen Fashion Trend bedient und damit nach kurzer Zeit wieder aus der Mode ist – oder weil die Kleidung auf Grund der Qualität super schnell kaputtgeht. Und dann fliegend die Klamotten auch mal schnell direkt in die Mülltonne, wenn sie ausgeblichen oder verwaschen sind.\r\n\r\nDie nachhaltige Kleidung Challenge: \r\nDeshalb gibt es heute eine ganz spezielle Challenge. Ich versuche innerhalb von zwei Wochen prallgefüllte Einkaufstüten mit Fast Fashion nachzukaufen – und zwar zum kleinen Preis und natürlich nachhaltig!\r\n\r\nAber wie kommt man überhaupt an nachhaltige Mode? Ich besuche einen Fair Fashion-Laden in München und hole mir Unterstützung von Angela (https://www.instagram.com/angeladoe), die sich seit Jahren mit den Themen Nachhaltigkeit und nachhaltige Kleidung beschäftigt.\r\n\r\nIhr wollt wissen, ob man wirklich günstig nachhaltige oder faire Kleidung kaufen kann und ob meine Shoppingtour erfolgreich war? In meinem neuen Video „Schluss mit Fast Fashion: Kann ich günstig nachhaltige Mode shoppen?“ erfahrt ihr es. \r\n\r\nNormalerweise gehe ich in mehreren Folgen einer Frage nach - um unterschiedliche Facetten eines Themas zu zeigen. \r\nMit dieser Folge ist das ein bisschen anders: Ich habe mich nämlich mit verschiedenen Channels aus dem funk-Netzwerk zusammengetan, um uns gemeinsam die Kehrseiten unseres Klamottenkonsums anzuschauen.\r\n\r\nUnd hier findet ihr faire Online-Shops und nützliche Tipps rund um nachhaltiges und faires Shoppen: \r\nhttps://www.br.de/puls/themen/leben/fair-shoppen-tipps-100.html\r\n\r\n\r\nDas ist Die Frage: \r\n\r\nEs gibt diese großen, kniffligen Fragen, auf die es keine einfachen Antworten gibt. Wie komme ich mit dem Tod klar? Was ist so geil an einem Fetisch? Muss ich Angst vor der Psychiatrie haben? Ich suche Antworten auf diese Fragen, Woche für Woche, für euch. Ich gebe mich nicht mit einfachen Antworten zufrieden - ich probiere lieber aus, bohre nach und gehe dahin, wo&#39;s auch mal unangenehm wird. Ich frage keine Experten, ich bin vor allem dabei: in der Psychiatrie, auf der Fetisch-Party, im Rettungshubschrauber. Jeden Dienstag, 13:00 Uhr gibt&#39;s eine neue Folge. \r\n\r\n► Folgt mir auch auf Facebook: https://www.facebook.com/DieFrage/\r\n\r\n────────────────────────\r\nDie Frage ist ein Programm von #funk. Schaut mal rein:\r\nYouTube: https://youtube.com/funkofficialfunk \r\nWeb-App: https://go.funk.netFacebook: https://facebook.com/funk \r\n\r\nImpressum: http://go.funk.net/impressumfunk ist ein Gemeinschaftsangebot der Arbeitsgemeinschaft der Rundfunkanstalten der Bundesrepublik Deutschland (ARD) und des Zweiten Deutschen Fernsehens (ZDF).",
        "title": "Schluss mit Fast Fashion: Kann ich günstig nachhaltige Mode shoppen?",
        "alias": "schluss-mit-fast-fashion-kann-ich-guenstig-nachhaltige-mode-shoppen-1585268",
        "entityId": 1585268
      },
      {
        "channelId": 11991,
        "channelAlias": "doppelpunkt-11991",
        "duration": 481,
        "creationDate": "2018-12-10T13:27:13.000+0000",
        "hash": "1FTM921585128J9",
        "publicationDate": "2018-12-10T14:42:52.000+0000",
        "updateDate": "2018-12-11T09:36:00.000+0000",
        "importDate": "2018-12-11T12:13:43.136+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0f89ac54cd0c000170f06b",
        "title": "Neid & Eifersucht",
        "alias": "neid-eifersucht-1585128",
        "entityId": 1585128
      },
      {
        "copyright": "This music requires a license for use. Please contact your local office for assistance.",
        "channelId": 856,
        "channelAlias": "game-two-856",
        "duration": 1562,
        "creationDate": "2018-12-10T16:33:26.000+0000",
        "hash": "9U0Y8W1585191CG",
        "shortTitle": "Montalk #15",
        "publicationDate": "2018-12-10T19:00:00.000+0000",
        "updateDate": "2018-12-10T18:59:17.000+0000",
        "importDate": "2018-12-11T12:13:43.136+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0eceb054cd0c000170efcb",
        "genre": [
          "Web Comedy",
          "Reportage",
          "Factual Entertainment"
        ],
        "shortDescription": "Alle Jahre wieder lädt Mastermind Geoff Keighley zur wohl wichtigsten Preisverleihung der internationalen Spielwelt. Doch bei den Game Awards werden traditionell nicht nur die besten Titel des Jahres in den unterschiedlichsten Kategorien ausgezeichnet. Der gestreamte Show wird traditionell auch für die Neuankündigung kommender Highlights oder spektakuläre Trailer-Updates genutzt. Auch 2018 waren mit großen Namen wie DRAGON AGE 4, MORTAL KOMBAT 11, THE OUTER WORLDS (dem neuesten Werk der FALLOUT-Erfinder), FAR CRY: NEW DAWN oder dem Remake von CRASH TEAM RACING wieder einige Überraschungen dabei. Trant, Micha und Markus analysieren die Highlights und Enttäuschen der zweistündigen Gala. Also, schnappt euch ne Apfelschorle oder nen Kaffen und dann viel Spaß mit MONTALK Nr. 15!",
        "description": "Alle Jahre wieder lädt Mastermind Geoff Keighley zur wohl wichtigsten Preisverleihung der internationalen Spielwelt. Doch bei den Game Awards werden traditionell nicht nur die besten Titel des Jahres in den unterschiedlichsten Kategorien ausgezeichnet. Der gestreamte Show wird traditionell auch für die Neuankündigung kommender Highlights oder spektakuläre Trailer-Updates genutzt. Auch 2018 waren mit großen Namen wie DRAGON AGE 4, MORTAL KOMBAT 11, THE OUTER WORLDS (dem neuesten Werk der FALLOUT-Erfinder), FAR CRY: NEW DAWN oder dem Remake von CRASH TEAM RACING wieder einige Überraschungen dabei. Trant, Micha und Markus analysieren die Highlights und Enttäuschen der zweistündigen Gala. Also, schnappt euch ne Apfelschorle oder nen Kaffen und dann viel Spaß mit MONTALK Nr. 15!",
        "title": "Preiswürdig oder platt? Die Game Awards 2018 | Montalk #15",
        "alias": "preiswuerdig-oder-platt-die-game-awards-2018-montalk-15-1585191",
        "entityId": 1585191
      },
      {
        "facebookId": "128747098018504",
        "channelId": 11977,
        "channelAlias": "funk-politik-11977",
        "duration": 35,
        "creationDate": "2018-12-10T16:02:13.000+0000",
        "hash": "L9Z158516075843",
        "publicationDate": "2018-12-10T17:29:48.000+0000",
        "updateDate": "2018-12-10T17:33:58.000+0000",
        "importDate": "2018-12-11T12:13:43.136+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0ea40c54cd0c000170ef85",
        "genre": [
          "News"
        ],
        "secondGenre": [
          "Zeitgeschehen"
        ],
        "shortDescription": "Die Bahngewerkschaft streikt, viele Bahnfahrer sind genervt.",
        "description": "Streiken ist ein Grundrecht im Arbeitskampf. Trotzdem sind viele Bahnfahrer von den Warnstreiks der Bahngewerkschaft genervt. Sollten wir uns solidarisch zeigen?",
        "title": "Sollten wir uns bei Bahnstreiks solidarisch zeigen?",
        "alias": "sollten-wir-uns-bei-bahnstreiks-solidarisch-zeigen-1585160",
        "entityId": 1585160
      },
      {
        "channelId": 856,
        "channelAlias": "game-two-856",
        "duration": 346,
        "creationDate": "2018-12-10T13:50:27.000+0000",
        "hash": "F1585132Y6E23A",
        "shortTitle": "Game Two Adventskalender #10",
        "publicationDate": "2018-12-10T15:05:02.000+0000",
        "updateDate": "2018-12-10T15:08:28.000+0000",
        "importDate": "2018-12-11T12:13:43.136+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0e85a154cd0c000170ef18",
        "shortDescription": "Kein Bock auf Schokolade oder Spielzeugtant? Dann haben wir den passenden Adventskalender für euch. Jeden Tag erwartet euch hinter dem Türchen jemand von uns, der oder die sein oder ihr absolutes Lieblingsspiel vorstellt. Und weil&#39;s bis Weihnachten mehr Tage hat als unser Team Mitglieder, haben wir auch Freunde und YouTube-Kollegen gebeten, uns ein wenig über ihre persönliche Spieleperle für die einsame Insel zu erzählen. Lasst euch überraschen!",
        "description": "Kein Bock auf Schokolade oder Spielzeugtant? Dann haben wir den passenden Adventskalender für euch. Jeden Tag erwartet euch hinter dem Türchen jemand von uns, der oder die sein oder ihr absolutes Lieblingsspiel vorstellt. Und weil&#39;s bis Weihnachten mehr Tage hat als unser Team Mitglieder, haben wir auch Freunde und YouTube-Kollegen gebeten, uns ein wenig über ihre persönliche Spieleperle für die einsame Insel zu erzählen. Lasst euch überraschen!",
        "title": "Mein Lieblingsspiel: Trant | Game Two Adventskalender #10",
        "alias": "mein-lieblingsspiel-trant-game-two-adventskalender-10-1585132",
        "entityId": 1585132
      },
      {
        "channelId": 11664,
        "channelAlias": "cinema-strikes-back-11664",
        "duration": 611,
        "creationDate": "2018-12-10T13:19:04.000+0000",
        "hash": "G3D21585124J1Q5",
        "shortTitle": "CINEMA NEWS #44",
        "publicationDate": "2018-12-10T14:29:03.000+0000",
        "updateDate": "2018-12-10T15:03:00.000+0000",
        "importDate": "2018-12-11T12:13:43.136+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0fa02854cd0c000170f1b3",
        "shortDescription": "In unseren heutigen News gibt es unter anderem den Rekord des Trailers zu AVENGERS: ENDGAME, wir zeigen euch die meistdiskutierten Filme 2018 und ein ganz besonderer Darsteller wird den Antagonisten in SPIDER-MAN: FAR FROM HOME spielen.",
        "description": "In unseren heutigen News gibt es unter anderem den Rekord des Trailers zu AVENGERS: ENDGAME, wir zeigen euch die meistdiskutierten Filme 2018 und ein ganz besonderer Darsteller wird den Antagonisten in SPIDER-MAN: FAR FROM HOME spielen.\r\n\r\nGolden Globes 2019:\r\nhttps://de.wikipedia.org/wiki/Golden_Globe_Awards_2019\r\n\r\nInstagram: https://www.instagram.com/cinemastrikesback/\r\nFacebook: https://www.facebook.com/CinemaStrikesBackDE/\r\nTwitter: https://twitter.com/csb_de\r\nLetterboxd: https://letterboxd.com/CSB_DE/\r\n\r\nCinema Strikes Back gehört zu #funk.\r\nHier gibt es mehr von funk:\r\nYouTube: https://www.youtube.com/funkofficial\r\nfunk Web-App: https://go.funk.net\r\nFacebook: https://facebook.com/funk\r\n\r\n#avengers4 #avengersendgame",
        "title": "AVENGERS 4 Trailer bricht Rekorde / SPIDER-MAN 2: Bösewicht gecastet / Meistdiskutierter Film 2018",
        "alias": "avengers-4-trailer-bricht-rekorde-spiderman-2-boesewicht-gecastet-meistdiskutierter-film-2018-1585124",
        "entityId": 1585124
      },
      {
        "channelId": 11999,
        "channelAlias": "nisi156-11999",
        "duration": 123,
        "creationDate": "2018-12-10T12:14:47.000+0000",
        "hash": "0I2JTS15851274V",
        "shortTitle": "Nisi ist krank",
        "publicationDate": "2018-12-10T14:39:05.000+0000",
        "updateDate": "2018-12-10T14:46:56.000+0000",
        "importDate": "2018-12-11T12:13:43.136+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0e7f8154cd0c000170eed8",
        "shortDescription": "In der heutigen Story ist Nisi krank und probiert ein neues Rezept aus, was ihr bei der Genesung helfen soll.",
        "title": "Nisi ist krank",
        "alias": "nisi-ist-krank-1585127",
        "entityId": 1585127
      },
      {
        "copyright": "℗ 2017 Animal 63",
        "facebookId": "335189643730481",
        "channelId": 912,
        "channelAlias": "jaeger-sammler-912",
        "duration": 134,
        "creationDate": "2018-12-07T12:09:24.000+0000",
        "hash": "3K4W32P41585059",
        "shortTitle": "Im Schlaglicht",
        "publicationDate": "2018-12-10T14:00:00.000+0000",
        "updateDate": "2018-12-10T14:07:50.000+0000",
        "importDate": "2018-12-11T12:13:43.136+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0e735c54cd0c000170eea8",
        "genre": [
          "Reportage",
          "Meinung/Kommentar"
        ],
        "secondGenre": [
          "Aktuelle Information",
          "Zeitgeschehen"
        ],
        "shortDescription": "Häusliche Gewalt ist Alltag in Deutschland – Jeden zweiten Tag stirbt eine Frau, jeden 11. Tag ein Mann.",
        "description": "Häusliche Gewalt ist Alltag in Deutschland – Jeden zweiten Tag stirbt eine Frau, jeden 11. Tag ein Mann.",
        "title": "Im Schlaglicht",
        "alias": "im-schlaglicht-1585059",
        "entityId": 1585059
      },
      {
        "copyright": "imago/PA Images",
        "channelId": 11940,
        "channelAlias": "manu-thiele-11940",
        "duration": 470,
        "creationDate": "2018-12-10T12:21:32.000+0000",
        "hash": "CSRO41585114DZ0",
        "shortTitle": "Der Absturz von Mesut Özil!",
        "publicationDate": "2018-12-10T14:00:00.000+0000",
        "updateDate": "2018-12-10T14:06:13.000+0000",
        "importDate": "2018-12-11T12:13:43.136+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0e78ed54cd0c000170eead",
        "genre": [
          "Meinung/Kommentar"
        ],
        "secondGenre": [
          "Sport"
        ],
        "shortDescription": "Für Mesut Özil lief das Jahr 2018 katastrophal. Wir blicken auf die Gründe, wieso er seiner Form hinterherläuft.",
        "description": "Für Mesut Özil lief das Jahr 2018 katastrophal. Nach der WM 2018 wollte sich Özil auf den FC Arsenal konzentrieren, jedoch steht er auch dort vor dem Aus. Heute blicke ich auf sein zweites Halbjahr inkl. einiger Probleme: Stress mit Trainer Unai Emery, eine Privatparty mit Spielern inkl. Drogenkonsum und dem wohl bitteren Abgang im Winter zu Inter Mailand. Hat Mesut Özil seine Liebe zum Fußball verloren? Oder wird er wieder zu alter Stärke zurückfinden? Außerdem blicken wir auch noch auf den Spielstil von Özil, was seine Stärken sind und soviel sei verraten: In einer Kategorie ist er besser als Lionel Messi und Cristiano Ronaldo. \r\n-----\r\nWICHTIG: Die Trikots, die in den Videos getragen werden, spiegeln nicht meine Sympathien wider. Es dient lediglich dazu, das aktuelle Thema zu untermalen.\r\n-----\r\nDu willst ein Autogramm? Dann schicke mir einen Brief inkl. vorfrankierten Rückumschlag an folgende Adresse:Manu Thiele Postfach 66 21 41 81218 München\r\n----\r\nMein Kanal gehört zu #funk.\r\n\r\nSchaut rein:\r\n► YouTube - https://www.youtube.com/funkofficial\r\n► funk Web-App - https://go.funk.net\r\n► Facebook - https://facebook.com/funk",
        "title": "Der Absturz von Mesut Özil! | Analyse",
        "alias": "der-absturz-von-mesut-oezil-analyse-1585114",
        "entityId": 1585114
      },
      {
        "channelId": 933,
        "channelAlias": "kickbox-933",
        "youtubeId": "Vq_LK0llL14",
        "duration": 477,
        "creationDate": "2018-12-10T10:09:47.000+0000",
        "hash": "6X8AYNT1585086F",
        "shortTitle": "Dribbel-Challenge vs. Nicole Rolser",
        "publicationDate": "2018-12-10T11:30:21.000+0000",
        "updateDate": "2018-12-10T13:44:32.000+0000",
        "importDate": "2018-12-11T12:13:43.136+0000",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0e6e7754cd0c000170ee95",
        "secondGenre": [
          "Sport"
        ],
        "shortDescription": "Heute ist die Kickbox mit Lena und Lynn wieder zu Gast bei der Frauennationalmannschaft des DFB. Hier wartet schon die ehemalige Spielering vom FC Liverpool und englische Meisterin Nicole Rolser, welche mittlerweile für den FC Bayern München spielt. Lena und Nicole duellieren sich in der Dribbel-Challenge. Kann sich Lena gegen die quirlige Fußballerin durchsetzen, oder wird es ein klarer Sieg für die Nationalspielerin?\r\nIm Anschluss der Challenge erfahrt ihr außerdem noch im exklusiven Fragen-Geballer einige interessante Details über Nicole. Das dürft ihr nicht verpassen.",
        "description": "Heute ist die Kickbox mit Lena und Lynn wieder zu Gast bei der Frauennationalmannschaft des DFB. Hier wartet schon die ehemalige Spielering vom FC Liverpool und englische Meisterin Nicole Rolser, welche mittlerweile für den FC Bayern München spielt. Lena und Nicole duellieren sich in der Dribbel-Challenge. Kann sich Lena gegen die quirlige Fußballerin durchsetzen, oder wird es ein klarer Sieg für die Nationalspielerin?\r\nIm Anschluss der Challenge erfahrt ihr außerdem noch im exklusiven Fragen-Geballer einige interessante Details über Nicole. Das dürft ihr nicht verpassen.\r\n\r\nAbonniert uns für weitere Videos: https://goo.gl/leBPPu\r\nBeobachtet uns auf Instagram: http://instagram.com/diekickbox\r\n\r\nBei KICKBOX erwartet Euch Fußball, Fußball, Fußball - und das mit Euren Stars aus der Bundesliga! \r\n\r\nJede Woche besuchen Fabi, Max, Lena oder Till einen neuen Fußballprofi & fordern ihn auf oder neben dem Fußballplatz in Challenges heraus. Die neuen Videos gehen montags & donnerstags online!\r\n\r\nSo habt ihr die Fußballer noch nie gesehen - abonniert uns, um Eure Lieblingsspieler nicht zu verpassen! KICKBOX gehört zu #funk.\r\n\r\nSchaut rein:\r\n► YouTube - https://www.youtube.com/funkofficial\r\n► funk Web-App - https://go.funk.net\r\n► Facebook - https://facebook.com/funk",
        "title": "Meister mit Liverpool! | Dribbel-Challenge vs. Nicole Rolser | Frauen-Nationalmannschaft | Kickbox",
        "alias": "meister-mit-liverpool-dribbelchallenge-vs-nicole-rolser-frauennationalmannschaft-kickbox-1585086",
        "entityId": 1585086
      }
    ]
  },
  "_links": {
    "next": {
      "href": "https://www.funk.net/api/v4.0/videos/?size=10&sort=updateDate,desc&page=1"
    },
    "self": {
      "href": "https://www.funk.net/api/v4.0/videos/?size=10&sort=updateDate,desc&page=0"
    }
  },
  "page": {
    "size": 10,
    "totalElements": 8550,
    "totalPages": 854,
    "number": 0
  }
}
```
