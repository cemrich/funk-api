## All Channels
```
curl "https://www.funk.net/api/v4.0/channels/?size=10" -H "authorization: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJjbGllbnROYW1lIjoid2ViYXBwLXYzMSIsInNjb3BlIjoic3RhdGljLWNvbnRlbnQtYXBpLGN1cmF0aW9uLWFwaSxuZXh4LWNvbnRlbnQtYXBpLXYzMSx3ZWJhcHAtYXBpIn0.mbuG9wS9Yf5q6PqgR4fiaRFIagiHk9JhwoKES7ksVX4"
```

## One Channel via entityId
```
curl "https://www.funk.net/api/v4.0/channels/1164" -H "authorization: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJjbGllbnROYW1lIjoid2ViYXBwLXYzMSIsInNjb3BlIjoic3RhdGljLWNvbnRlbnQtYXBpLGN1cmF0aW9uLWFwaSxuZXh4LWNvbnRlbnQtYXBpLXYzMSx3ZWJhcHAtYXBpIn0.mbuG9wS9Yf5q6PqgR4fiaRFIagiHk9JhwoKES7ksVX4"
```

## Example Response
```
{
  "_embedded": {
    "channelDTOList": [
      {
        "creationDate": "2018-11-12T09:22:39.000+0000",
        "publicationDate": "2018-11-26T11:00:00.000+0000",
        "updateDate": "2018-12-05T15:46:10.000+0000",
        "importDate": "2018-12-11T12:01:43.365+0000",
        "imageUrlOrigin": "https://www.funk.net/api/v4.0/images/5c07f2c542a6060001c0de41",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c07f2c442a6060001c0de3d",
        "imageUrlSquare": "https://www.funk.net/api/v4.0/images/5c07f2c542a6060001c0de4f",
        "imageUrlPortrait": "https://www.funk.net/api/v4.0/images/5c07f2c542a6060001c0de4a",
        "shortDescription": "Wer will ich sein? Was ist ein Freund? Wieso fühlt man Neid? Mit vielen Büchern und\r\nCharme suchen Jana und Sophia Antworten auf ihre vielseitigen Fragen.",
        "description": "Wie können Bücher und ihre Geschichten uns in besonderen Lebenslagen ein Ratgeber\r\nsein?\r\n\r\nDoppelpunkt ist ein Instagram-Format von funk, dem jungen Angebot von ARD und\r\nZDF und startet Ende November 2018. Die Zwillinge Jana und Sophia Münster sind immer\r\nganz nah an Büchern und ihren Geschichten. In wechselnden Themenwochen zeigen sie: Es\r\nmacht nicht nur Spaß zu lesen, sondern auch über das Lesen zu reden! Außerdem kennen\r\nsie die Sorgen, Probleme und Ängste, die das Erwachsenwerden mit sich bringt.",
        "title": "Doppelpunkt",
        "alias": "doppelpunkt-11991",
        "type": "format",
        "entityId": 11991
      },
      {
        "creationDate": "2018-11-26T09:31:31.000+0000",
        "linkModels": [
          {
            "link": "https://www.youtube.com/user/Nisi156",
            "linkType": "youtubeLink",
            "entityId": 60166
          },
          {
            "link": "https://www.instagram.com/nisi156/?hl=de",
            "linkType": "instagramLink",
            "entityId": 60165
          }
        ],
        "publicationDate": "2018-11-30T23:00:00.000+0000",
        "updateDate": "2018-12-05T12:25:46.000+0000",
        "importDate": "2018-12-11T12:01:43.365+0000",
        "imageUrlOrigin": "https://www.funk.net/api/v4.0/images/5c0a384b42a6060001c0e35a",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0a384b42a6060001c0e357",
        "imageUrlSquare": "https://www.funk.net/api/v4.0/images/5c0a384c42a6060001c0e361",
        "imageUrlPortrait": "https://www.funk.net/api/v4.0/images/5c0a384b42a6060001c0e35e",
        "shortDescription": "Einige sagen, Nisi sei verrückt. Sie hingegen findet die Welt verrückt: Alle wollen perfekt sein, alle wollen reich sein, alle hassen sich. Nisi will nicht wie die anderen sein, sie ist einfach sie selbst, unperfekt und ehrlich.",
        "title": "nisi156",
        "alias": "nisi156-11999",
        "type": "format",
        "entityId": 11999
      },
      {
        "creationDate": "2018-11-19T13:35:23.000+0000",
        "publicationDate": "2018-11-30T23:00:00.000+0000",
        "updateDate": "2018-12-04T13:39:00.000+0000",
        "importDate": "2018-12-11T12:01:43.365+0000",
        "imageUrlOrigin": "https://www.funk.net/api/v4.0/images/5c06837742a6060001c0d706",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c06837642a6060001c0d701",
        "imageUrlSquare": "https://www.funk.net/api/v4.0/images/5c06837742a6060001c0d70d",
        "imageUrlPortrait": "https://www.funk.net/api/v4.0/images/5c06837742a6060001c0d709",
        "entityGroup": 1,
        "shortDescription": "„Iss bunter“ - Hier gibt Vielfalt auf dem Teller. Denn das Leben ist zu kurz für langweiliges Essen.",
        "description": "„Iss bunter“ - . Ohne erhobenen Zeigefinger geht es in diesem Instagram-Format um Vielfalt auf dem Teller.\r\n\r\nRezepte, Kochanleitungen und viele Informationen rund um gutes Essen – es wird nie langweilig! Mit Lebensfreude und bunt gemischten, unverbissenen vegetarischen Rezepten, die schnell und einfach zuzubereiten sind, wird von Bloggerin und Fotografin Mirja Glatz Spaß an gutem Essen vermittelt und ungezwungen kulinarisch gebildet.\r\nNeben appetitlichen Bildern, Vergleichen und Zitaten rund um die Welt der Kulinarik und verschiedenen Kochformaten in den Stories bietet „Iss bunter“ außerdem unterschiedliche Aktionen zum Mitmachen und selbst aktiv werden.\r\nWas kann ich kochen, wenn es niemand anderes für mich tut? Und wie bringe ich einfach und kostengünstig Vielfalt auf den Teller? Diesen Fragen geht Mirja immer wieder aufs Neue nach.\r\nVor erhöhtem Speichelfluss und der Gefahr, versehentlich auf das Handydisplay zu sabbern, wird ausdrücklich gewarnt.",
        "title": "iss bunter",
        "alias": "iss-bunter-11996",
        "type": "format",
        "entityId": 11996
      },
      {
        "creationDate": "2018-11-22T15:47:23.000+0000",
        "publicationDate": "2018-11-30T23:00:00.000+0000",
        "updateDate": "2018-12-04T13:38:03.000+0000",
        "importDate": "2018-12-11T12:01:43.365+0000",
        "imageUrlOrigin": "https://www.funk.net/api/v4.0/images/5c06833d42a6060001c0d6f7",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c06833d42a6060001c0d6f4",
        "imageUrlSquare": "https://www.funk.net/api/v4.0/images/5c06833e42a6060001c0d6ff",
        "imageUrlPortrait": "https://www.funk.net/api/v4.0/images/5c06833e42a6060001c0d6fa",
        "shortDescription": "Land und Leute durch die Augen eines Fotografen sehen – das ist die Mission von Felix Goergens. Er ist aber kein Profi, sondern zeigt auf dem Kanal @goergy Momente aus dem Alltag und der Arbeit als Hobbyfotograf.",
        "description": "Land und Leute durch die Augen eines Fotografen sehen – das ist die Mission von Felix Goergens. Er ist aber kein Profi, sondern zeigt auf dem Kanal @goergy Momente aus dem Alltag und der Arbeit als Hobbyfotograf. Egal ob vor der eigenen Haustür in Hamburg oder auf Reisen in der ganzen Welt – tolle Fotomotive findet man überall. @goergy wirft auch einen Blick hinter die Motive. So zeigt der Hobbyfotograf, worauf man bei der „perfekten“ Komposition achten muss und welche Apps sowie Programme bei der Bearbeitung der Bilder helfen. Die Motive der Fotos reicht dabei von Portraits über Landschafts- bis hin zu Nachtszenen. Challenges mit anderen Fotografen sind ebenso Teil des Kanals wie Location Scouting und Tipps zu Fotoreisen .",
        "title": "Goergy",
        "alias": "goergy-11997",
        "type": "format",
        "entityId": 11997
      },
      {
        "creationDate": "2016-09-24T10:45:36.000+0000",
        "linkModels": [
          {
            "link": "https://www.instagram.com/bongoboulevard",
            "linkType": "instagramLink",
            "entityId": 59711
          },
          {
            "link": "https://www.facebook.com/BongoBoulevard",
            "linkType": "facebookLink",
            "entityId": 12196
          },
          {
            "link": "https://www.youtube.com/c/bongoboulevard",
            "linkType": "youtubeLink",
            "entityId": 12189
          }
        ],
        "publicationDate": "2016-09-30T22:00:00.000+0000",
        "updateDate": "2018-12-03T18:05:32.000+0000",
        "importDate": "2018-12-11T12:01:43.365+0000",
        "imageUrlOrigin": "https://www.funk.net/api/v4.0/images/5c05706f42a6060001c0d569",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c05706f42a6060001c0d564",
        "imageUrlSquare": "https://www.funk.net/api/v4.0/images/5c05707042a6060001c0d574",
        "imageUrlPortrait": "https://www.funk.net/api/v4.0/images/5c05707042a6060001c0d56f",
        "shortDescription": "Bongo Boulevard baut einmalige Bühnen und zeigt Musiker*innen so echt, persönlich und emotional wie nie zuvor.",
        "description": "Viele Musiker müssen erleben, wie ihre Leidenschaft im Alltag zum immer gleichen Frage-Antwort-Spiel im Promo-Tour-Spektakel wird. Gossip dominiert die Schlagzeilen. Ein Werbetermin jagt den nächsten. »BONGO BOULEVARD« ist eine Promo-Pause. Ein Ort voller Instrumente – an dem die Werbung draußen bleiben muss. Und es wieder um das geht, um was es bei Musikern gehen sollte: Musik. Und echte Momente zwischen Menschen. Alle zwei Wochen jammen die Gastgeber Marti Fischer und Marie Meimberg mit Stars von großen Bühnen und spannenden Hinterhof-Tonstudios und gewährt in den Wochen dazwischen Einblicke hinter die Kulissen von »BONGO BOULEVARD«. Über die Macher Wenn Marti Fischer mit seiner Loopmaschine bekannte Hits in völlig eigene Gewänder steckt oder seine Version von »Chabos wissen, wer der Babo ist« im Max Raabe-Stil über 4,5 Millionen Aufrufe erzielt, wird klar: Marti Fischer liebt Musik. Und geht damit viral. Oft dann, wenn er gemeinsam mit der Sängerin und Produzentin Marie Meimberg Dinge rockt. Für »BONGO BOULEVARD« vereinen sich zwei Musiker und ein Team kreativer Köpfe. Ein Projekt mit viel Bass und echten Momenten.",
        "title": "Bongo Boulevard",
        "alias": "bongo-boulevard-807",
        "type": "format",
        "entityId": 807
      },
      {
        "creationDate": "2018-08-07T07:24:25.000+0000",
        "publicationDate": "2018-08-28T22:00:00.000+0000",
        "updateDate": "2018-12-03T18:04:27.000+0000",
        "importDate": "2018-12-11T12:01:43.365+0000",
        "imageUrlOrigin": "https://www.funk.net/api/v4.0/images/5c05702e42a6060001c0d54d",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c05702e42a6060001c0d548",
        "imageUrlSquare": "https://www.funk.net/api/v4.0/images/5c05702f42a6060001c0d55f",
        "imageUrlPortrait": "https://www.funk.net/api/v4.0/images/5c05702f42a6060001c0d55b",
        "shortDescription": "PlusPlusPlus Videos sind Schnittkunstwerke mit einer derben Ladung Ironie und Sarkasmus.",
        "description": "Direkt aus der großen Pause zeigt „PlusPlusPlus“ mit viel Sarkasmus und derben Schnitt-Skills, was in der Welt heute los ist. Modetrends, Brexit oder Antimaterie – alles betrachtet mit dem gewissen PLUS.\r\n„PlusPlusPlus“ beleuchtet Themen aus Gesellschaft, Politik und Naturwissenschaften aus seiner Weltansicht als Teenager in einer deutschen Kleinstadt. Er sucht im Netz, auf dem Schulhof und im Alltag nach Erklärungen für das legendäre Bermuda-Dreieck, die Antimaterie, schwarze Löcher, Klimaerwärmung oder Ufo-Sichtungen.",
        "title": "PlusPlusPlus",
        "alias": "plusplusplus-11961",
        "type": "format",
        "entityId": 11961
      },
      {
        "creationDate": "2018-11-12T09:21:46.000+0000",
        "publicationDate": "2018-11-22T17:00:00.000+0000",
        "updateDate": "2018-12-03T14:59:08.000+0000",
        "importDate": "2018-12-11T12:01:43.365+0000",
        "imageUrlOrigin": "https://www.funk.net/api/v4.0/images/5c068a3542a6060001c0d754",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c068a3542a6060001c0d751",
        "imageUrlSquare": "https://www.funk.net/api/v4.0/images/5c068a3542a6060001c0d75b",
        "imageUrlPortrait": "https://www.funk.net/api/v4.0/images/5c068a3542a6060001c0d758",
        "entityGroup": 3,
        "shortDescription": "Queerfeminismus für alle! softie dreht die Lautstärke queerfeministischer Stimmen auf und setzt einen geilen Beat darunter.",
        "description": "Queerfeminismus ist für alle da! softie ist das Zuhause der queerfeministischen Community im Internet. softie vernetzt, inspiriert und schafft Allianzen.\r\n\r\nsoftie ist ein Lifestyle-, Orientierungs- und Infoformat. softie kennt die neuesten Trends, lässt ihre größten Modecrushes zu Wort kommen. Gleichzeitig bringt softie Diskursbegriffe in den Mainstream, sodass endlich alle mitreden können!\r\n\r\nQueerfeminismus prägt den Puls der Zeit. Daher erzählt softie immer aus dieser Perspektive. So holt das Format alle ab, die sich schon längst mit Feminismus beschäftigen, sowie diejenigen, die das bislang noch nicht tun – sich aber dafür interessieren, was bei queeren und feministischen Trendsetter*innen und darüber hinaus in unserer Gesellschaft abgeht. Softie schließt Wissenslücken und spricht Themen an, die ansonsten im Mainstream unterrepräsentiert sind. \r\n\r\nsoftie begibt sich in die Tiefen feministischer und gesellschaftlicher Diskurse und schlüsselt sie auf, denn – Feminismus soll für alle sein! softie bringt Queerfeminismus, Vielfalt und Offenheit in den Mainstream.",
        "title": "Softie",
        "alias": "softie-11990",
        "type": "format",
        "entityId": 11990
      },
      {
        "creationDate": "2018-07-25T09:41:51.000+0000",
        "linkModels": [
          {
            "link": "https://www.youtube.com/channel/UC28vN_rPD_FOS3Wf7qwHyLw",
            "linkType": "youtubeLink",
            "entityId": 59823
          },
          {
            "link": "https://www.instagram.com/carolafray",
            "linkType": "instagramLink",
            "entityId": 60124
          }
        ],
        "publicationDate": "2018-08-18T22:00:00.000+0000",
        "updateDate": "2018-11-23T15:46:43.000+0000",
        "importDate": "2018-12-11T12:01:43.365+0000",
        "imageUrlOrigin": "https://www.funk.net/api/v4.0/images/5bf820e5c345d30001efc87d",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5bf820e5c345d30001efc879",
        "imageUrlSquare": "https://www.funk.net/api/v4.0/images/5bf820e6c345d30001efc886",
        "imageUrlPortrait": "https://www.funk.net/api/v4.0/images/5bf820e6c345d30001efc881",
        "shortDescription": "Lern- oder Serienmarathon? Beides! Studentin Caro zeigt, wie Selbstdisziplin und Unterhaltungspausen zum Lernen motivieren. Der Mix macht‘s.",
        "description": "Lasst sich Zielstrebigkeit und Erfolg mit dem ein oder anderen Serienmarathon vereinbaren? Klar! Das beweist Caro auf ihrem Kanal „alwaysxcaro“. Sie zeigt den Alltag einer jungen Studentin: Einerseits wird für die Uni und das Leben gelernt und andererseits bei einem Erdbeer-Bananen-Smoothie entspannt. Caro macht die stetige Weiterentwicklung Spaß- sei es in der Uni, im Alltag oder Beruf. In ihren Vlogs zeigt sie, wie man den Spagat zwischen Lern- und Serienmarathon schafft: Sie bietet ihrer Community sowohl Einblicke in ihre Lieblingsserien, als auch einen gewaltigen Motivationsboost durch ihre „Study with me“ Videos. Denn Caro ist sich sicher: Es gibt nichts, was man sich nicht selbst beibringen kann, man muss nur wissen, wie man sich selbst motiviert.",
        "title": "alwaysxcaro",
        "alias": "alwaysxcaro-11956",
        "type": "format",
        "entityId": 11956
      },
      {
        "creationDate": "2018-11-12T15:34:49.000+0000",
        "linkModels": [
          {
            "link": "https://www.youtube.com/channel/UCngQwWQ0OpiAjvSFU7bk1xw",
            "linkType": "youtubeLink",
            "entityId": 60074
          },
          {
            "link": "https://www.instagram.com/rebeccagubitzer/?hl=de",
            "linkType": "instagramLink",
            "entityId": 60075
          },
          {
            "link": "https://www.facebook.com/rebeccagubitzer",
            "linkType": "facebookLink",
            "entityId": 60105
          }
        ],
        "publicationDate": "2018-11-25T11:00:00.000+0000",
        "updateDate": "2018-11-23T14:04:33.000+0000",
        "importDate": "2018-12-11T12:01:43.365+0000",
        "imageUrlOrigin": "https://www.funk.net/api/v4.0/images/5c0f9c4e54cd0c000170f12c",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5c0f9c4e54cd0c000170f12a",
        "imageUrlSquare": "https://www.funk.net/api/v4.0/images/5c0f9c4f54cd0c000170f132",
        "imageUrlPortrait": "https://www.funk.net/api/v4.0/images/5c0f9c4f54cd0c000170f12e",
        "entityGroup": 2,
        "shortDescription": "Sarkastischer Humor, persönliche Stories und Katzen! Bei Becci fühlst du dich direkt wie zuhause bei deiner besten Freundin.",
        "description": "Mit dem Video „Let&#39;s make YouTube great again!“ fiel der Startschuss für den Kanal „Rebecca Gubitzer“. Seitdem möchte die gebürtige Österreicherin mit ihrer ironisch-offenen und sarkastischen Art die Community aus dem Alltag holen.\r\n\r\nAus lustigen, aber auch stressigen Alltagssituationen schöpft die Münchner YouTuberin Inspiration für ihre Videos und lässt dabei selten ein Fettnäpfchen aus, welches prompt in einem Storytime-Video verewigt wird.\r\n\r\nAußerdem kommt auch die Community zu Wort, wenn Rebecca das Feedback ihrer Zuschauer*innen in einem „Feedbecci“ Video kommentiert.\r\n\r\nIhre Videos sprechen alle an, die auf der “Suche nach sich selbst” abseits des Mainstreams sind. Mit ihrem übertrieben spitzen Humor, den besten Stories und Challenges holt sie ihre Zuschauer aus der Ernsthaftigkeit des Alltags und bringt sie direkt in die Sphären des Becciversums. Sie ist authentisch, nah und vor allem komisch! Dabei bleibt dem Zuschauer nichts anderes übrig, als sie und ihre Miezen direkt ins Herz zu schließen.",
        "title": "Rebecca Gubitzer",
        "alias": "rebecca-gubitzer-11992",
        "type": "format",
        "entityId": 11992
      },
      {
        "creationDate": "2017-05-23T14:02:20.000+0000",
        "linkModels": [
          {
            "link": "https://www.youtube.com/channel/UC6Nh0xrtXJfNGucGtVrqjHw",
            "linkType": "youtubeLink",
            "entityId": 51466
          }
        ],
        "publicationDate": "2017-05-19T22:00:00.000+0000",
        "updateDate": "2018-11-22T09:05:21.000+0000",
        "importDate": "2018-12-11T12:01:43.365+0000",
        "imageUrlOrigin": "https://www.funk.net/api/v4.0/images/5bf67155b79fcd00011e2db5",
        "imageUrlLandscape": "https://www.funk.net/api/v4.0/images/5bf67154b79fcd00011e2db3",
        "imageUrlSquare": "https://www.funk.net/api/v4.0/images/5bf67155b79fcd00011e2dba",
        "imageUrlPortrait": "https://www.funk.net/api/v4.0/images/5bf67155b79fcd00011e2db8",
        "shortDescription": "Fiesling Marc stellt den Hosts Ari und Meini absurde Aufgaben. Scheitern wird bestraft, Gewinner dürfen sich rächen. Drehbuch und Fakes sind tabu.",
        "description": "„Das schaffst du nie!“ ist Challenge pur! Redakteur Marc stellt die zwei Hosts Ariane und Sebastian immer abwechselnd vor eine fiese Aufgabe. Ein Flugzeug landen, ohne Pilot zu sein. Eine Nadel im Heuhaufen finden. Jemandem ein Tattoo stechen – obwohl sie das noch nie gemacht haben. Oder einen Bullen absamen. Schaffen es die Hosts, dürfen sie Marc bestrafen. Schaffen sie es nicht, müssen sie neben der Schmach der Niederlage auch noch eine Bestrafung ertragen.",
        "title": "Das schaffst du nie!",
        "alias": "das-schaffst-du-nie-1423",
        "type": "format",
        "entityId": 1423
      }
    ]
  },
  "_links": {
    "next": {
      "href": "https://www.funk.net/api/v4.0/channels/?size=10&sort=updateDate,desc&page=1"
    },
    "self": {
      "href": "https://www.funk.net/api/v4.0/channels/?size=10&sort=updateDate,desc&page=0"
    }
  },
  "page": {
    "size": 10,
    "totalElements": 87,
    "totalPages": 7,
    "number": 0
  }
}
```
