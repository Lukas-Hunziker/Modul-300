# Modul-300

```
$  cd Pfad/zu/meinem/Repository    # Zum lokalen GitHub-Repository wechseln

$  git status                      # Geänderte Datei(en) werden rot aufgelistet
$  git add -A                      # Fügt alle Dateien zum "Upload" hinzu
$  git status                      # Der Status ist nun grün > Dateien sind Upload-bereit (Optional) 
$  git commit -m "Mein Kommentar"  # Upload wird "commited" > Kommentar zu Dokumentationszwecken ist dafür notwendig
$  git status                      # Dateien werden nun als "zum Pushen bereit" angezeigt
$  git push                        #Upload bzw. Push wird durchgeführt
```

Unter **[Cloud Computing](https://de.wikipedia.org/wiki/Cloud_Computing)** (deutsch Rechnerwolke) versteht man die Ausführung von Programmen, die nicht auf dem lokalen Rechner installiert sind, sondern auf einem anderen Rechner, der aus der Ferne aufgerufen wird (bspw. über das Internet).

Eine **dynamische Infrastruktur-Plattform** ist ein System, das Rechen-Ressourcen bereitstellt (Virtualisiert), insbesondere Server (compute), Speicher (storage) und Netzwerke (networks), und diese Programmgesteuert zuweist und verwaltet, sogenannte Virtuelle Maschinen (VM).
Damit "Infrastructure as Code" auf "Dynamic Infrastructure Platforms" genutzt werden können, müssen sie die folgenden Anforderungen erfüllen:
•	Programmierbar - Ein Userinterface ist zwar angenehm und viele Cloud Anbieter haben eines, aber für "Infrastructure as Code" muss die Plattform via Programmierschnittstelle (API) ansprechbar sein.
•	On-demand - Ressourcen (Server, Speicher, Netzwerke) schnell erstellen und vernichtet.
•	Self-Service - Ressourcen anpassen und auf eigene Bedürfnisse zuschneiden.
•	Portabel - Anbieter von Ressourcen müssen austauschbar sein.
•	Sicherheit, Zertifizierungen (z.B. ISO 27001), ...

Tools
Um Konfigurationsdateien mit dem "Infrastruktur als Code" Ansatz zu bearbeiten, eigen sich u.a. folgende Tools:
sed
sed (von stream editor) ist ein nicht-interaktiver Texteditor für die Verwendung auf der Kommandozeile oder in Skripten. sed zählt zu den "Urgesteinen" in der Unix- / Linux-Welt und ist quasi in jeder Linux-Installation (auch Minimalinstallationen) enthalten.
