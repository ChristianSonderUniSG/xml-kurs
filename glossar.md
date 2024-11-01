|Eintrag|Definition|
|-------|----------|
|Attribut|Attributname + = + "Attributwert" oder Attributname + = + 'Attributwert'|
|CDATA|Character Data = nicht geparster Inhalt eines XML-Dokuments|
|CDATA-Section|Bereich in dem Character Data vorkommt. Innerhalb einer CDATA-Section gibt es kein Markup, daher ist auch Escapen nicht nötig|
|Content|Inhalt eines Elements, kann aus Elementen, Text oder beidem zugleich bestehen (Mixed Content)|
|CSS|Cascading Styles Sheets, Sprache zur Formulierung von Stylesheets für HTML oder XML|
|DTD|Dokumenttypdefinition: Satz von Regeln, die die Inhalt eines XML-Dokuments beschreiben|
|Element|Entweder Emptytag oder Starttag + Content + Endtag|
|Emptytag|< + Elementname + Attribute + />|
|Endtag|</ + Elementname + >|
|Entity|                  Definiertes Kürzel für ein oder mehrere Zeichen. Vordefinierte Entites in XML sind: lt, gt, amp, quot und apos für die Steuerzeichen|
|Entity Reference|        Referenz auf eine Entity in der Form & + Name der Entity + ; Z. B. &lt; für das Zeichen "<"|
|Escapen|                 Umschreiben von Steuerzeichen, die für das Markup unerlässlich sind, mithilfe von Entity References|
|Kommentar|               Kommentare in der Form <!-- + Inhalt + --> gehören nicht um Inhalt des XML-Dokuments und dienen der (internen) Kommentierung, sie müssen von XML-Prozessoren nicht zwingend verarbeitet werden|
|Mixed Content|		        s. Content|
|Namespaces|              Mechanismus zur Präfigierung von Element- und Attributnamen, damit verschiedene XML-Dialekte in einem Dokument nebeneinander stehen können|
|Processing Instruction|  Anweisung in der Form <? + Name + Attribute + ?> für XML-Prozessoren, wie ein Dokument zu verarbeiten ist. Die wichtigsten Processing Instructions sind Verknüpfungen mit Stylesheets (<?xml-stylesheet href="..."?>) und Schemata (<?xml-model href="..."?>)|
|Prolog|		            Vor dem Wurzelelement stehender Abschnitt, der eine XML-Deklaration und eine DTD enthalten kann|
|Starttag|		            < + Elementname + Attribute + >|
|Steuerzeichen|           Besonderes Zeichen, welches neben seiner wörtlichen Bedeutung auch eine Funktion für eine Sprache übernimmt, z. B. <> "' &|
|Stylesheet|              In der Regel in CSS oder XSL formuliertes Dokument, welches Verarbeitungs- oder Darstellungsregeln für Elemente und Attribute definiert|
|TEI|                     Text Encoding Initiative, Organsiation, welche mit TEI-XML einen XMl-Dialekt zur Kodierung von Texten vorschlägt. https://tei-c.org/|
|Unicode|                 Wichtigster Zeichensatz der Welt mit ca. 150.000 verschiedenen Zeichen aus nahezu allen Sprachen und Schriftssystemen der Welt|
|UTF-8|                   Technise Umsetzung des Unicode-Zeichensatzes mit variabler Bytelänge, d. h. ein Unicode-Zeichen kann zwischen 1 und 4 Bytes lang sein|
|valide|			            Einem XML-Schema oder einer DTD entsprechend|
|Verschachtelung|         Elemente müssen hierarchisch ineinander geschachtelt werden und dürfen sich nicht überlappen|
|Weissraum|               Leerzeichen, Tabs und Zeilenumbrüche, kurz Weissraum gehören zum Teil zum Inhalt des XML-Dokuments zum Teil dienen sie nur zur optischen Absetzung des Markups|
|wohlgeformt|		          Den XML-Syntax-Regeln entsprechend|
|Wurzelelement|		        Das einzige äusserste Element, welches alle anderen Elemente eines XML-Dokuments umfasst|
|W3C|                     World Wide Web Consortium, Organisation, welche die Spezifikationen von XML und X-Technologien herausgibt, https://www.w3.org/|
|XIncluce|                Mechanismus zum Einbinden von Inhalten in XML-Dokumente|
|XML|			                Extensible Markup Language, dt. erweiterbare Auszeichnungssprache|
|XML-Deklaration|         In der Form &lt;?xml version="1.0" encoding="..." standalone="yes&#124;no"?> kann deklariert werden, um welche XML-Version es sich handelt, welcher Zeichensatz vorliegt und ob weitere Dateien zum Parsen des Dokuments notwendig sind|
|XML-Dokument|	        Ein wohlgeformtes Datenobjekt, bestehend aus einem Prolog, einem Wurzelelement und ggfs. sonstigen Inhalten|
|XML-Dokumentklasse|    Abstraktes Muster für beliebig viele XML-Dokumente|
|XML-Editor|	          Software, mit der XML-Dokumente erstellt oder bearbeitet werden können|
|XML-Refaktorierung|Umwandlung bzw. Verarbeitung von XML-Bestandteilen mit einem XML-Prozessor|
|XML-Prozessor|		        Software, die XML-Dokumente automatisiert verarbeitet|
|XML-Schema|		          Sprache zur Beschreibung von XML-Dokumentklassen; einzelnes Dokument zur Beschreibung einer XML-Dokumentklasse|
|XPath|                   Sprache zur Navigation in XML-Dokumenten|
|XQuery|                  Sprache zum Abfragen von XMl-Dokumenten|
|XSL|                     Extensible Stylesheet Language, Sprache zur Formulierung von Stylesheets für XML|
|XSLT|                    Extensible Stylesheet Language Transformations, Sprache zur Transformation von XML in XML oder zur Konvertierung in andere Sprachen|
|Zeichensatz|             Menge von Zuordnungen von Zeichen zu Codepunkten, zentral für die Kodierung von Sonderzeichen|
