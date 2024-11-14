# Anleitung Audio Transkription

Hier finden Sie einen Code, um Audio Dateien (insbesondere MP3) zu transkribieren. Der Code kann mit interaktiven Jupyter-Notebooks angesteuert werden. Es sind keine Programmierkenntnisse notwendig.

*Hinweis:* die Anleitung wird für Windows beschrieben, funktioniert aber auch alles für Linux oder MacOSX.

## Schritt 0: Installation von Jupyter-Notebook

a) Laden Sie die aktuelle Version von Miniforge herunter: https://conda-forge.org/miniforge/
![](https://github.com/christofschroth/Audio-Transkription/blob/main/Images/Miniforge-1-Download.png)


b) Installieren Sie die Datei. Achten Sie darauf, bei Add Miniforge 3 to my PATH environment variable ein **Häckchen** zu setzen (ignorieren Sie die Warnung in roten Buchstaben).

![](https://github.com/christofschroth/Audio-Transkription/blob/main/Images/Miniforge-2-Hinweis-Path.png)


c) Öffnen Sie nun den Miniforge Prompt. Dazu einfach Miniforge ins Windows-Suchfenster eingeben.
![](https://github.com/christofschroth/Audio-Transkription/blob/main/Images/Miniforge-3-StartConsole.png)


d) Tippen Sie nun in die Konsole: 

conda install jupyter

Bestätigen Sie anschließend mit der Enter-Taste.
![](https://github.com/christofschroth/Audio-Transkription/blob/main/Images/Miniforge-4-CondaInstall.png)


e) Bestätigen Sie die Installation mit der Eingabe von y-Enter.

*Hinweis:* Achten Sie darauf, dass der Rechner mit dem Interner verbunden ist.
![](https://github.com/christofschroth/Audio-Transkription/blob/main/Images/Miniforge-5-Install_y.png)


f) Die Installation beginnt. Conda zieht nun einige Pakete aus dem Internet und führt die Installation aus (dies kann einige Minuten dauern).
![](https://github.com/christofschroth/Audio-Transkription/blob/main/Images/Miniforge-Install-6-Pakete.png)

## Schritt 1: Pakete laden

a) Laden Sie die Notebooks (die ipynb-Dateien) herunter.

b) Öffnen Sie nun Jupyter-Notebook und öffnen Sie *1_Install_Packages*. Dort finden Sie die nächsten Anweisungen.

Schritt 1 müssen Sie nur einmalig durchführen.

## Schritt 2: Whisper Modelle laden

Öffnen Sie *2_Load_Whisper_Models*, um die Modelle auf Ihren Rechner herunterzuladen. Auch diesen Schritt müssen Sie nur einmalig durchführen.

## Schritt 3: Transkription für Dummies

Dieses Notebook (3_Transkription_Fuer_Dummies) richtet sich an Menschen, die keinerlei Programmiererfahrung haben. Das Notebook ist interaktiv und erfordert keine Programmierkenntnisse.

## Schritt 4: Transkription für Fortgeschrittene (optional)

Das Notebook *4_Transkription_fuer_Fortgeschrittene* kann von Leuten benutzt werden, die etwas Programmiererfahrung (Code anpassen) haben. Man kann mit diesem ein paar Schritte überpringen.
