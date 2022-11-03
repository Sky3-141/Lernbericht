# Lern-Bericht
Frei Simon

## Einleitung

Wir erhielten in der Schule eine Aufgabe, bei welcher wir eine Konsolenapplikation mit C# machen mussten, dabei erhielt ich speziell wegen des Jahres, welches ich wiederholte, einen anderen Auftrag, nämlich eine Applikation zu programmieren, bei dem das Ziel war im Sekundentakt einen Timer von 60 Sekunden herunterzählen zu lassen und auf Knopfdruck den Timer neu startet.

## Was habe ich gelernt?

Ich habe einiges über **"timespan"** und das stoppen und starten gelernt, was unter anderem ich auch mein Ziel wär, mit diesem Bericht ein wenig genauer zu erklären.
Ich habe auch gelernt, wie man die Zeit in Einheiten definieren kann per **"string"**.

## Beschreibung

Mit **"timespan"**, auf welches sich mein Code hauptsächlich auswirkte, wie beispielsweise eine Subtraktion, die im Sekundentakt Zeit abzog,  kann man einen Abstand angeben zwischen Zeiten und beliebig angegebenen Nummern, wie Tage, Stunden, Minuten, Sekunden und sogar Millisekunden.

Hier einen Codeausschnitt des Programmes:

   **timeLeft = new TimeSpan(0, 1, 0);**  
           **label1.Text = timeLeft.ToString(@"hh\:mm\:ss");**  
           **countdowntimer.Start();**  
            
**"timeleft"** ist hierbei nur eine Variable für die gesamte Zeit des Timers, welche ich mit wie oben erwähnt TimeSpan definiert habe.
Die Zeit wird in (0, 1, 0) angegeben und gleich darunter wird ein Textlabel mit dieser Zeit definiert. Im Textlabel wird ausserdem die Zeit heruntergezählt. **"@hh\:mm\:ss"**  definiert, dass die ersten Zahlen in der Klammer Stunden darstellen, die zweiten Minuten und die dritten Sekunden, man könnte jedoch noch Tage oder Millisekunden definieren, falls gewünscht. Dann am Schluss des Codeausschnitts muss dieser dann noch gestartet werden. Es gäbe auch noch das Stoppen des Timers, jedoch ist dazu nicht allzu viel zu sagen ausser, dass man das **"Start"** vom **countdowntimer** mit **"Stop"** ersetzt.

Ausserdem war etwas vom wichtigsten die Benutzereingabe, bei welcher ein Benutzer per Entertaste das Programm stoppen konnte oder auch wenn der Timer ablief. Dafür war es sehr wichtig eine **"if"** Überprüfung zu machen und zu prüfen, ob der Timer schon 0 erreicht hat und das nach jeder Sekunde oder ob der Benutzer die Entertaste gedrückt hat, bei welchem der Timer erneut auf 1 Minute gestellt wird.


## Verifikation

Der Codeauschnitt zeigt wie die Zeit definiert wird und wie der Countdown gestartet wird. Im dazugehörigen Text finden man genauere erklärungen was im Codeasuchnitt passiert und was man noch machen könnte. Beispielsweise könnte man noch Tage oder Millisekunden angeben.
Auch beschreibt der Text ganz kurz eigentlich wie mein Programm funktioniert und wie man ein solches programmieren könnte.

# Reflexion zum Arbeitsprozess

Ich hatte keine Probleme mit der Zeit und das Arbeiten fiel mir an sich leicht.
Jedoch gab es Probleme eine gut aussagende und aktuelle Quelle dazu zu finden, da die Auswahl der Quellen im Internet zu einem solchen Projekt sonst schon beschränkt war.
Auch hatte ich Probleme mit dem Formdesigner, weshalb dieser Lernbericht auch kein Bild enthaltet, da das Programm plötzlich beim neu öffnen des Programmes Probleme bekam, ich vermute, es liegt daran, dass ich einmal ein Objekt gelöscht habe, diese aber im Code irgendwo noch vorhanden ist. Ausserdem war es zu anstrengend alle Objekte nochmals nach ausgedachtem Design nochmals einzufügen und das Programm somit zu rekonstruieren.
Ich hätte definitiv öfters Fragen stellen sollen, vor allem wegen der begrenzten Anzahl der zuverlässigen Quellen und auch hätte ich mich beim Problem direkt an die Lehrperson wenden sollen.
