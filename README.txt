In der aesthetics.config.json können URLs zu .mlmodel Dateien eingetragen werden.
Die angegebenen .mlmodel Dateien werden von der iOS App Aesthetics genutzt.

Die URLs sind einzutragen wie im folgenden Beispiel zu sehen:

[
  {
    "title": "test1",
    "url": "https://example.com/hallo.mlmodel"
  },
  {
    "title": "test2",
    "url": "https://hello.com/world.mlmodel"
  }
]

Der Titel erscheint in der App als Name für das Modell.

Um ein Modell aus der App zu entfernen, kann einfach das entsprechende Element in dem Array gelöscht werden.
