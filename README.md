# 📝 ToDo-Applikation – Anleitung für Benutzer

Dieses README erklärt, wie du die **ToDo-Applikation** ganz einfach starten und nutzen kannst.  
Die Applikation läuft in einem **Docker-Container**, du brauchst **Node.js oder npm nicht** auf deinem Rechner.

---

## 💻 Voraussetzungen

Stelle sicher, dass folgende Programme auf deinem Rechner installiert sind:

- Docker Desktop
- Git (nur zum Klonen des Repositories)

---

## 📃 Schritte für Benutzer

1. **Repository klonen**

   Öffne dein Terminal oder PowerShell und klone das Repository:

   1. Gehe auf GitHub zu dem Repository: [Link](https://github.com/esseymulugieta/docker-nodejs-sample)
   2. Klicke auf **Fork**, um eine Kopie in deinem Account zu erstellen.
   3. Klone deinen Fork auf den lokalen Rechner und wechsle in das Projektverzeichnis.

2. **Docker vorbereiten**

   1. Stelle sicher, dass Docker Desktop gestartet ist.
   2. Prüfe, ob Docker korrekt installiert ist.

3. **Docker-Image bauen**

   1. Erstelle ein Docker-Image aus dem Projekt.
   2. Das Image enthält alle notwendigen Abhängigkeiten der ToDo-Applikation.

4. **Docker-Container starten**

   1. Starte einen Container aus dem Docker-Image.
   2. Der Container läuft im Hintergrund und stellt die App bereit.
   3. Der Port 3000 auf deinem Rechner wird auf den Container weitergeleitet.

5. **ToDo-Applikation im Browser öffnen**

   1. Öffne einen Webbrowser.
   2. Gib die URL http://localhost:3000 ein.
   3. Die ToDo-Applikation sollte angezeigt werden.
   4. Du kannst nun Aufgaben hinzufügen, ansehen und löschen.

6. **Container stoppen und entfernen (optional)**

   1. Beende den laufenden Container, wenn du die App nicht mehr nutzen willst.
   2. Entferne den Container, um Speicherplatz freizugeben.

## ✅ Tipps

- Die Anwendung läuft vollständig in Docker, daher brauchst du **keine Installation von Node.js oder npm**.
- Jederzeit kannst du den Container stoppen oder neu starten.
- Die URL http://localhost:3000 öffnet die ToDo-Applikation im Browser.
- Folge den Schritten in dieser Anleitung genau, um die App erfolgreich zu starten.

---

## 🧑‍💻 Autor

Erstellt von **<Essey>**  
