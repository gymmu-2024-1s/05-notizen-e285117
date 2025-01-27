# Einführung

20.01

Hier sind meine Notizen zur Einführung in Daten.

- Was sind Daten? Videos, Dokumente, Webseiten, etc

- Wie werden die gespeichert? Aktiviert, deaktiviert, speicher zellen. 1 0 1 0 0
  1 1 1 0 1 und so.

- Wo werden die Daten gespeichert? In die SD-Karten, Festplatte.

- Wie werden die Daten von einen Computer zu einen andere Cumputer geteilt? Als
  1 0 1 0 0 1. Man braucht eine verbindung, eine frequenz, eine sekunde 1000
  byts. Ein byt ist 8 binär nummer lang. Morse code = Computer ist wie strom
  oder kein strom. Strom = 1 kein strom = 0

Beispiel: 0 1 1 0 -> 65 -> A (el ejemplo esta malo pero asi se hace) Se supone
que daria cuatro pero para el ejemplo se uso 65.

`JSON` Mit das kann man Code beschreiben

```JSON
Buch:
{
  "Titel": "Percy Jackson and the Lightning Thief",
  "Seiten": "375 Seiten",
  "Erscheinungsdatum": "28.06.2005",
  "Schriftsteller/-in": "Rick Riordan",
}

{
    "name": "Brot",
    "preis": 1.5,
    "aktion" 0.05
}

Was ist redudanz? Wieso ist das schlecht?
Redundant ist wenn man unnötige informationen in eine page oder dokument, wenn zwei sachen sich indirekt wiederholen.

Daten speicherung und daten ansicht, unterschied

Berechnete attribute und was haben die mit redundanz zu tun.

Geben sie ein beispiel über ein objekt mit und ohne redundanz, erklären Sie welche eigenschaften redudanz sind. Würde es trotzdem sinn machen dieses objekt zu verwenden.

Erklären Sie in 31 sätzen wie daten gespeichert und wie werden dann von gerät zu gerät übertragen werden.

27.01

Die daten werden als 0 und 1 gespeichert.

Redundanz: Wenn wir etwas mehrfach haben von eine information.
Warum schlecht: Unnötig (zu viele daten wegen der übersicht), speicherplatz, für das Datenmanegement (z.b wenn man die Jahre ein eine page schreibt dann muss man alle tage checken ob die person ein jahr mehr geworden ist.)
Warum gut: sehr wichtige daten, doppelgeprüft werden.

Objekte: Dinge die in code vorkommen die verschiedene eingenschaften zusammenpacken.

Pregunta de prueba: Puede ser que nos pregunte acerca de programar como la pelota se mueve, que haya una pelota paralela y de otro color, etc.

Die person hat 3 eigenschaften (vorname, nachname, adresse) und adresse hat komplexe daten.

Verschachtlung: Wenn ein objekt innerhalb von ein anderen objekt. Wenn man nicht an die adresse interessiert ist, dann muss man diese daten nicht anschauen.

JSON

{
  "vorname": "Peter",
  "nachname": "Muster",
  "Eigenschaften": {
    "Gewicht": "70 kg",
    "Höhe": "1,75 m",
  }
}

Listen: Wenn man eine listen einfügen möchte dann muss man die "[]" klammern.

z.b:

JSON

{
  "vorname": "Peter",
  "nachname": "Muster",
  "haustiere": ["Carlo", "Memphis", "Spot", "Daisy"]
}

Liste: Bevor einzelne objekte bracuhen wir keine schlüssel.

Was ist eine Klasse: Baupläne für objekte. Die klasse beschreibt welche eingenschaften in einen objekt vorhanden sind aber es hat keine werte.

Objekt: Eine representation von einen daten. Instanz von unsere Klasse.

Spielbeispiel:

Spielfigur, braucht position und so.

Alle npc haben gleiche bauplan, position in der welt, schaden (klasse), npc in der welt wir erstellen eine instanz von die Klasse. Wir nehmene die klasse und fügen da die werte ein.

Klasse: Name, Vorname, Adresse
Se sabe que tiene nomnbre y un apellido pero no se sabe especificamente cual.

Objekte: Genaue name (Also Peter)
Es algo especifico.

JSON

class fleischfressend {
  name
  tierart
  geschlecht
  höche (durschnittlich)
  länge (durschnittlich)

}

{
  "name": "Tiger",
  "tierart": "Säugetier",
  "geschlecht": "Weiblich",
  "grösse (durschnittlich)": "95 cm",
  "länge (durschnittlich)": "2,4 m"
}

Was ist Vererbung: Eingenschaften von einen anderen objekt übernehmen. Erweiterung von einen objekt.

class Haustier {
  name,
  art,
  alter
}

class Fisch extends Haustier {
  salzwasser,
  flossenAnzahl
}

La clase haustier existe por defecto y tiene las caracteristicas (o informaciones) nombre, especie y edad. Luego si colocamos "extends" significa que podemos crear una nueva clase que se conecte a la clase que soliamos tener ya creada (si se especifica). Por ejemplo, en la nueva clase de "Fisch" podemos agregar mas informacion que es especifica para los peces (como si es de agua salada o dulce, o cuantas aletas tiene), cuando le agregamos extends podemos decir que toda la informacion que tenias en "Haustier" se conecta a "Fisch" aunque no se vea.

Pregunta: Porque Vererbung es practica.

```
