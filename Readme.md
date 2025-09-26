# How to Use 

> Ich persönlich Empfehle [LFH LaTeX template](https://github.com/SpezialK-dev/LFH-LaTeX-Text) mehr, da LaTeX an ein paar Stellen reifer ist, als Typst. 
> Dieses Template is relativ ähnlich mit dem LaTeX template also das umswitchen ist nicht sonderlich komplex


Um das Dokument zu Compilieren muss man lediglich denn folgenden Befehl ausführen
```shell
typst watch src/main.typ

```

## Die verschiedenen Datein 

### Packages.typ 

sollte in jeder Datei, wo man Text hat eingebunden werden wie gezeigt in Main_part.typ 
Hier sollten packaete eingebunden eingefügt werden, welche überall im Text verwendet werden wie bsps das Package für Abkürzungen. 

### abkürzung.typ

Hier sollten alle Abkürzungen reingeschrieben werden welche verwendet werden, damit dies zentrall passiert man muss diese datei aber nicht verwenden, theoretisch könnte man sie auch in denn Text packen.:


### Information.typ 

Enthllt alle Informationen, welche Eingetragen werden müssen für die Arbeit, sowie ob ein Sperrvermerk verwendet werden soll, sowie ob es eine Bachlorthesis ist
