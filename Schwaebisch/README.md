# Ålôetong Audio Transkriptio

> [!IMPORTANT]
> **Wichtige Vorabinfo:** des Ganze wird bloß funkioniera, wann Ihr Rechner **mindestens 8GB Arbaetsspeicher** håt. Wann Se an Rechner mit bloß 4Gb Arbaetsspeicher hent, nå wôeß e ao net.


Dåhanna send vier Notebooks aglegt, mô mr MP3-Dateia (od andere Dateiformate ao, oefach ausprobiera) transkribiera, also als Text-Datei speichera kå. Sotte Notebooks send gleichzeitig Code ond a Erklärong. Mr kå also interaktiv drmit schaffa, em Prinzip braucht mr koene Vorkenntniss em Progammiera.

*Hinweis:* dia Ålôetong ischd em Wesentlicha für Windows beschrieba, se funktioniert aber ao für Linux oder MacOSX.

> [!NOTE]
> Mr könnt sich jetzt fråga, wårom mr des net oefach mit ara KI macht. Dia Antwort ischd: mr kå net ällas oefach so en dia Dienste naeschiaba. Des håt en dr Regel mit am Dataschutz (DSGVO) zom doa. Deswega kå s sennvoll sae, des ganze lokal zom laofa lao.

## Schritt 0: Installatio vo Jupyter-Notebook 

a) De aktuell Versio vo Miniforge ralada, Link: https://conda-forge.org/miniforge/
![](https://github.com/christofschroth/Audio-Transkription/blob/main/Images/Miniforge-1-Download.png)


b) De entsprechende Datei installiera. Bei dem oena Punkt `Add Miniforge 3 to my PATH environment variable` obedengt a Häkle naemacha (då leuchtat zwår a rote Warnong auf, dia kå mr aber ignoriera, wann mr s erst Mål drmit schafft).
![](https://github.com/christofschroth/Audio-Transkription/blob/main/Images/Miniforge-2-Hinweis-Path.png)


c) Dr Miniforge Prompt öffna. Drzua oefach *Miniforge* ens Windows-Suachfenster aegeba.
![](https://github.com/christofschroth/Audio-Transkription/blob/main/Images/Miniforge-3-StartConsole.png)


d) Jetzt en dia Konsole vo eba aetippa: 

`conda install jupyter`

Mit de `Enter-Taste` bestätiga.
![](https://github.com/christofschroth/Audio-Transkription/blob/main/Images/Miniforge-4-CondaInstall.png)


e) Nômål mit `y-Enter` d Installatio bestätiga.

*Hinweis:* Mr muaß drauf achta, dass dr Rechner mit am Internet verbonda ischd.
![](https://github.com/christofschroth/Audio-Transkription/blob/main/Images/Miniforge-5-Install_y.png)


f) Jetzt beginnt de aegentliche Installatio. Conda ziaht a Beig Pakete aus am Internet ond führt d Installatio aus (sell kå a paar Minut gao, je nåch Internetvrbindong).
![](https://github.com/christofschroth/Audio-Transkription/blob/main/Images/Miniforge-Install-6-Pakete.png)

## Schritt 1: Pakete lada

a) Jetzt vo Håd dia Notebooks (des send dia ipynb-Dateia) ralada.

b) Jupyter-Notebook öffna, ab jetzt müaßt ällas standardmäßig em Browser laofa (der, mô entsprechend standardmäßig aegstellt ischd)

c) En *1_Install_Packages* naesprenga. Dort send de nächste Åweisonga.

*Hinweis*: Schritt 1 muaß mr bloß oemål ausführa.

## Schritt 2: Whisper Modelle lada

Mr muaß no oemalig de aegentliche Modelle ralada. Dådrzua *2_Load_Whisper_Models* öffna ond durchlaufa lao.

## Schritt 3: Transkriptio für Dummies

Sell Notebook (3_Transkription_Fuer_Dummies) ischd gschrieba für Leut, mô Null Programmiererfahrong hent. S ischd interaktiv ond braucht koe Vorerfahrong em Programmiera. 

## Schritt 4: Transkriptio für Fortgeschrittene (optional)

Selligs Notebook (4_Transkription_fuer_Fortgeschrittene) kå vo Leut gnutzt wera, mô schao a weng Programmiererfahrong (Code åpassa) hent. 
Mit dem Notebook kå mr sich s Leba a wenga oefacher macha ond a paar Schritt übersprenga.