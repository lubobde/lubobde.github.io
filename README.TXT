Um eine neue Seite zu kompilieren:

0. in jedem subfolder von theme/ gibt es ein verzeichnis lubobde-site oder so ähnlich. 

1. Den Inhalt dieses folders ins Hauptverzeichnis kopieren, also noch eine ebene über dem themes/ folder

2. dann den Befehl "hugo server" um es anzuschauen

3. um die seite zu veröffentlichen den befehl
"hugo -b https://lubob.net"
das erzeugt ein verzeichnis public/

4. den inhalt von /public ins hauptverzeichnis

5. mit git push auf github publishen
