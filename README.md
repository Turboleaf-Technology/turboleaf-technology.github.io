# Website - Turboleaf Technology

https://turboleaf-technology.github.io/

## Aktualisieren der Website 

1. Installation von Hugo: https://gohugo.io/installation/windows/#prebuilt-binaries\
Es wird nur die Extended-Version (ohne Deploy) benötigt.
2. Das Repository auf den Computer klonen:
    - HTTPS: `git clone https://github.com/Turboleaf-Technology/turboleaf-technology.github.io.git`
    - SSH: `git clone git@github.com:Turboleaf-Technology/turboleaf-technology.github.io.git `
3. Vornehmen der Änderungen:
    - Im Verzeichnis `/content` werden die Seiten verwaltet.
    - Im Verzeichnis `/static/documents` werden die Dokumente abgelegt.
    - In `/config/_default/menus.yaml` ist das Menü auf der linken Seite definiert.
    - In `/static/css/hyde.css` können Änderungen am Stylesheet vorgenommen werden.
    - In `/layout` befinden sich die verschiedenen Teile der Website. 
4. Vorschau auf dem eigenen Computer kann mit `hugo serve` angezeigt werden. Die Vorschau kann mit http://localhost:1313/ im Browser geöffnet werden.
5. Änderungen commiten und bei Bedarf pushen.
6. Eine GitHub-Action erzeugt die notwendigen Daten und die Website sollte nach ca. einer Minute aktualisiert sein.