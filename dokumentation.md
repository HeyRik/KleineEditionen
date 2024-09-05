# Dokumentation


## Allgemein


Folgende XML-Grundstruktur sollte jedes Dokument enthalten:

``` xml
<text>
  <front>[...]</front>
  <body>
    <pb/>
    [...]
  </body>
  <back>
    <pb/>
    [...]
  </back>
</text>
```


## Gattungen

### Neue Gattung

### Briefe


Briefe erfordern keine große Untergliederung. Der Text steht in einem DIV mit type=letter. Die Ebene des Briefes wird mit n=1 markiert. Bei den Telota-Briefen wirdLediglich die abgrenzbare "writing session" wird untergliedert. Bei einem Brief, der an einem Stück geschrieben ist, steht der gesamte Text in einem DIV-Element.

``` xml
<TEI xmlns="http://www.tei-c.org/ns/1.0" xml:id="H0016462">
 <teiHeader>...</teiHeader>
 <text>
  <body>
   <div type="letter" n="1">...</div>
  </body>
 </text>
</TEI>
```


### Drama


Hier beginnt der Text
