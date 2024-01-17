# Scripted Devices

This folder contains pairs of `.js` and `.p44s` files which together (usually with some
parameters that need to be adapted before use, see comments in the files) comprise a
"scripted device", which is a device that is implemented as a p44script which for example
uses http APIs to control a physical device from a third party vendor, or obtains weather
data from a service in the internet.

For each example:

- the `.js` file contains the so-called *init-message* inn JSON, which defines the basic
  structure and behaviour of the device.

- the `.p44s` file is the *implementation* script which is the code that makes the device
  actually work.

Also see the [techdocs](https://plan44.ch/p44-techdocs/en/custdevexamples/) for more
information about scripted devices and examples with more guidance.


# Scripted Devices

Dieser Ordner enthält Paare von `.js`- und `.p44s`-Dateien, die zusammen (in der Regel
mit einigen Parametern, die vor der Verwendung angepasst werden müssen, siehe Kommentare
in den Dateien) ein "skriptgesteuertes Gerät" bilden. Dabei handelt es sich um ein Gerät,
das als p44-Skript implementiert ist und z. B. http-APIs verwendet, um ein physisches
Gerät eines Drittanbieters zu steuern, oder Wetterdaten von einem Dienst im Internet
bezieht.

Für jedes Beispiel:

- enthält die `.js`-Datei die sogenannte *init-message* in JSON, die die grundlegende
  Struktur und das Verhalten des Geräts definiert.

- ist die `.p44s`- Datei das *Implementierungs*-Skript, also der Code, der das Gerät
  tatsächlich zum Laufen bringt.

Siehe auch die [techdocs](https://plan44.ch/p44-techdocs/de/custdevexamples/) für weitere
Informationen über skriptgesteuerte Geräte und Beispiele mit weiteren Anleitungen.
