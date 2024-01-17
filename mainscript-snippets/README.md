# Mainscript Snippets

This folder contains "mainscript snippets", which are lines of code that can be inserted
into the global *mainscript*, in order to have them executed automatically when the
device starts up. Such snippets can do simple things like just calling a scene, but can
also start ongoing sequences using `concurrent`, or set up event handlers with
`on (...) { ... }`.

See [The main context](https://plan44.ch/p44-techdocs/en/scripting/#maincontext) for
information about the *mainscript* and how to edit it.

**Please do not forget:** mainscript must end returning true, otherwise the device
assumes unsuccessful mainscript execution and will re-start the mainscript again.
So make sure you put a `return true` at the end of your mainscript.

# Mainscript Snippets

Dieser Ordner enthält "mainscript snippets", d.h. Codezeilen, die in das globale
*mainscript* eingefügt werden können, um sie beim Start des Geräts automatisch ausführen
zu lassen. Solche Snippets können einfache Dinge wie das Aufrufen einer Szene tun,
aber auch fortlaufende Sequenzen mit `concurrent` starten, oder Event-Handler mit
`on (...) { ... }` einrichten.

Siehe [Der Maincontext](https://plan44.ch/p44-techdocs/de/scripting/#maincontext) für
Informationen über das *mainscript* und wie man es bearbeitet.

**Bitte nicht vergessen:** Das mainscript muss mit der Rückgabe von true enden, sonst
geht das Gerät von einer erfolglosen Ausführung des mainscript aus und startet das
mainscript erneut. Stellen Sie also sicher, dass Sie am Ende Ihres mainscripts
ein `return true` einfügen.
