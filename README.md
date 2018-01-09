
# LaTeX Template
Verbesserte Vorlage für Denkweisen, welche das anonymisierte erstellen eines PDFs erleichtert.

Weiters müssen noch die Dateien ``Second.tex,Third.tex,...`` erstellt werden wie ``First.tex`` für die einzelnen Arbeiten der Verfassenden.

## Anonymes PDF automatisch erzeugen
Um das Anonymus PDF (``BUG-Anonymous.pdf``) direkt zu erzeugen kann das ``anonymous.tco`` Profil in TexNicCenter importiert werden oder der Befehl

    pdflatex --jobname=BUG-Anonymous "\def\anonymus{1} \input{%tm}"

ausgeführt werden. (Das ``.tco`` Profil beinhaltet die Referenz für Adobe Acrobat Pro DC 2018 für andere Versionen muss Server:``acroviewA18`` angepasst werden)

Mit diesem Command in TeXnicCenter im "Ausgabeprofil" im Tab "Viewer" unter "Projektausgabe betrachten" und "Suche in Ausgabe" *zusätzlich* wird auch das Anonyme PDF in Acrobat geöffnet.

    [DocOpen("%dm\BUG-Anonymous.pdf")][FileOpen("%dm\BUG-Anonymous.pdf")]

	
# Disclaimer
*Es wird keine Garantie von mir übernommen, dass alle Metadaten hiermit entfernt werden!*
